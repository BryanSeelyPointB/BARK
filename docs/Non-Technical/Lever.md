# Lever

Lever is the Applicant Tracking System (ATS) and Candidate Relationship Management System (CRM) for Point B, EV, Point B Direct, and Parner Operations (e.g. Agencies and vendors)

## Access
#### Production
Lever can be accesed via Okta SSO or directly via this url https://hire.lever.co

#### Sandbox
https://hire.sandbox.lever.co

## Vendor Contacts
#### Success Manager
Elizabeth Fendyan

## Configurations

## Out of the Box Integrations

## Custom Integrations

## Training

## Newsletter Instructions
Instructons for creating an up to date mailing list for Recruitment Marketing as of 8/27/2019

#### Smashfly
> 1. Pull list of talent network leads in Smashfly (Recruiting)
> 2. In Excel, add report data to table
>3. Create a new Column for Full Name
    1. Formula: =A2&" "&B2
>4. Create a new column for Talent Network
    1. Enter "Talent Network" for all values
>5. Create a new column for Smashfly Opt-in
    1. Enter "Smashfly Opt-in" for all values
>6. Create a new column for Persona
    1. Change PTB - Years of Experience column to general data type
    2.Convert the Years of Experience data to tag values
        1.Example formula: =IF(G2="0-4","Student or Graduate",IF(G2=43592,"Emerging Leader",IF(G2=43687,"Experienced Professional",IF(G2="11+","Subject Matter Expert"," "))))
    3. Select all in Persona column
        1. Copy and paste values
        2. Select blanks
        3. Clear/delete blanks
>7. Create a new column for Tags
    1. Formula: =TEXTJOIN(",",TRUE,[@[Talent Network]],[@[Smashfly Opt-in]],[@Persona])
>8. *If blank sources in sheet
    1. Filter Source column to blanks
    2. Select all blanks
    3. Enter "Career Marketing Site"
    4. Ctrl + Enter
>9. *If there are duplicates that need grouping
    1. Create a new Query from table
    2. In the Query Builder, Group By
        1. Advanced
        2. Group by Primary Email
        3. Then Full Name
        4. Column Name: Email
        5. Operation: All Rows
>10. Copy each column into Lever bulk upload sheet and save as CSV
    1. Name
    2. Email
    3. Phone
    4. Link
    5. Sources
    6. Tags
>11. Save and submit to Lever
    1. https://help.lever.co/hc/en-us
    2. Submit a request
    Select "Question about Lever Product or feature"
    3. Add Subject
    4. Select "Task - I need Lever to Perform a Task"
    5. Add a description
    6. Attach CSV
    7. Submit`

#### Lever

  
>1. Download Candidates from Lever
    1. Filter Candidate report to Tag = "Talent Network"
    2. Export to Excel
>2. In Excel, filter Archive reasons
    + blanks
    + Prospect to watch 
    + Works at client
    + Withdrew - staying at current job
    + Withdrew - accepted another offer
    + timing misaligned
    + salary expectations
    + out of market
    + market conditions
    + lacks ability to travel
    + Commute inflexibility
    + candidate non-responsive
>3. Copy filtered list to new sheet
>4. Add data to table
>5. Create a new Query from table
    1. In the Query Builder, Group By
        1. Advanced
        2. Group by Email
        3. Then Candidate Name
        4. Column Name: Count
        5. Operation: All Rows
    2.Close and Load
>6. Select emails and copy to an empty location in the sheet
>7. Text to columns
    1. delimited
    2. comma
>8. Copy column with single emails and paste values in Column A
>9. Import to iContact

## Taleo Snapshot
Point B migrated most data from our previous ATS, Taleo, as part of initial launch. Taleo information, at time of migration is captured here for reference:

#### Location
https://tbe.taleo.net/MANAGER/dispatcher/login.jsp
#### Company Code: 
POINTB2

#### Final Version
TBE 19A
#### Subscription Details
|   |   |
|---|---:|
|Licensed to:   |Point B   |
| Company code: |	POINTB2|
| Service level: |	Premium
| Expiration date: |	12/30/25
| Search server URL: |	ch-m-search-2
| Size of database: |	58920 MB
| Size of file storage: |	11572 MB

#### Users
**373** Users w/ Access

**516** Users w/ No Access

**898** Users total

#### Candidates
Total: **86248**

Active: **5674** 

#### Requisitions

Total: **583**

Open - **176**

#### Custom Fields
| Object  |# of Custom Fields   |
|---|---:|
|Candidate Fields |	99
|Calendar Event Fields |	0
|Candidate Special Fields |	5
|Reference Checks Fields |	4
|Requisition Fields |	27
|Background Checks Fields |	0
|Requisition Candidate Fields |	0
|User Fields |	3
|Offer Fields |	18
|Contact Fields |	1
|Interview Fields |	1
|Account Fields |	0
|Feedback Fields |	19
|Task Fields |	0

#### Reports
| | |
|---|---:|
|Candidate Reports|	88
|Requisition Reports|	17
|Compliance|	10
|User Reports|	5
 
#### Career Centers
**7** Active Career Centers

#### Templates
System Email Templates

Social Media Templates

Feedback, Reference and Offer Templates

Invitations

Email Reminders

#### Forms

#### Customized Processes

#### System Limits
**250** custom candidate field limit

**250** custom candidate requisition limit

**250** custom contact field limit

**250** custom account field limit

**250** custom task field limit

Unlimited Custom Reports

Unlimited Careers Websites

#### Integrations
EDW - Tableau

#### Questions

**56** Total Custom Questions in Taleo

**39** Unique Questions on Open Reqs
 
**99** Reqs include at least 1 additional question

**15** Unique Question Bundles