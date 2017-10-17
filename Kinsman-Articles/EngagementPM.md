---
title: Onboarding PM
description: a "Spec" to describe where I'm at in my learning
keywords: Spec
---
# Onboarding PM for Azure and Windows

## Summary

Change 1

This document captures my learning and questions as I onboard to the new process. I will flush out the job and identify questions that need answering in this document.  

### High Level Job Description

- maintain relationship with Azure team (Carol Zumault and Tyson)
    - Help Azure documentation team with process they want to enable to allow appropriate level of collaboration for the business
        - 200 internal contributors, thousands of pull requests.  Azure has a small team to manage lots of contributions and so they want particular functionality that helps them manage that workload, parsing out various specific authoring capabilites to their contributors along with some automation.   
    
- Help keep Windows documentation publishing going fowrard through vendor management.  weekly reporting and meetings with vendor to check in and review status, see where help is needed, etc.

- Become completely ingrained with documentation migration processes

#### In Scope

*What items are in scope for this role?*
- Maintaining the presence of docsets in the onboarding Area Path in mseng.visualstudio.com/CSI that are in Windows and Azure (https://mseng.visualstudio.com/CSI/_queries/query/3c45d380-9fe3-4fd3-90e9-6a994e1b703a/)  Currently assigned to Paulina and Sanketh.

- Helping reference documentation publishing automation, debugging problems with the automation.  
- working with authors to assist their publishing of updated docsets for Conceptual documentation
- working with Tyson to flesh out and understand features for Azure documentation contributors and reviewers
- making sure new documentation releases stay on the radar
- Making sure redirection is implemented appropriately for items migrated from older publishing systems to docs.microsoft.com

- other things Dan wants me to do, coming tomorrow

#### Out Of Scope

TBD

### Customers and Stakeholders

- Tyson and Carol Zumalt
    - Azure Documentation Folks.  largest Customer for Jennifer

- Tara
    - Vendor who will be assigned to WDG documentation

- PubDesk
    - Vendor that sanketh says we can use for large batch processing and ad hoc requests

- Beyondsoft
    - Development vendor, mostly for devs

- Aquaint
    - Tara works for them.
        - Run PubDesk & PRReview

*Identify the customers and stakeholders who will be impacted by this change.*

- China Team
    - They do the automation to support generating reference documentation from the languages.  Current languages are here: 

### Dependencies, Terms and Definitions

Two types of content:
- Reference and Conceptual.  
    Reference is automatically generated using scripts and automation that has been created by the engineering team.  There is a different process for each language, and our ability to support documentation in this language is dependant on a relatively heavy engineering lift to support the documentation.  
    Conceptual

Types of pages 
    - Hub page...?
    - others...?

**Automation**
 - DocFX - a docfx.json file lets us set metadata about a docset and specify which files in a repro are to be included or excluded from the build.  This is part of the automation that creates reference documentation

 - YAML - Yaml is a "data serialization language".... what it is is the output of our automation that builds reference documentation. 

**Tick Tock** 
- Refers to a standardized publishing plan.  THere are 3 different tick tocks depending on the need, 
    one if the docset is new to OPS (because it is new, is on MTPS, is on CAPS or SMS)
    (https://microsoft.sharepoint.com/teams/Visual_Studio_China/_layouts/OneNote.aspx?id=%2Fteams%2FVisual_Studio_China%2FShared%20Documents%2FDOCS.MSFT&wd=target%28Engagement.one%7CA67BF78E-8EB6-4951-98EA-8F854EA3B909%2FTick-Tock%20Checklist%20MTPS%2C%20CAPS%2C%20SMS%20or%20New%20Content%20to%7C377561E4-D94B-468B-8E09-F667BA8B2B2F%2F%29
onenote:https://microsoft.sharepoint.com/teams/Visual_Studio_China/Shared%20Documents/DOCS.MSFT/Engagement.one#Tick-Tock%20Checklist%20MTPS,%20CAPS,%20SMS%20or%20New%20Content%20to%20Docs%20(Template)&section-id={A67BF78E-8EB6-4951-98EA-8F854EA3B909}&page-id={377561E4-D94B-468B-8E09-F667BA8B2B2F}&end),

- one if it is currently on OPS (even if the end point is MSDN or TechNet) (https://microsoft.sharepoint.com/teams/Visual_Studio_China/_layouts/OneNote.aspx?id=%2Fteams%2FVisual_Studio_China%2FShared%20Documents%2FDOCS.MSFT&wd=target%28Engagement.one%7CA67BF78E-8EB6-4951-98EA-8F854EA3B909%2FTick-Tock%20Checklist%20%28Template%5C%29%20-%20From%20OPS%20MSDN%5C%2FTN%7C3A66C739-9897-4A03-A32D-214DA1D04C45%2F%29
onenote:https://microsoft.sharepoint.com/teams/Visual_Studio_China/Shared%20Documents/DOCS.MSFT/Engagement.one#Tick-Tock%20Checklist%20(Template)%20-%20From%20OPS%20MSDN/TN/VS.com%20to%20OPS%20Docs&section-id={A67BF78E-8EB6-4951-98EA-8F854EA3B909}&page-id={3A66C739-9897-4A03-A32D-214DA1D04C45}&end) , and 

- one for reference documentation (https://microsoft.sharepoint.com/teams/Visual_Studio_China/_layouts/OneNote.aspx?id=%2Fteams%2FVisual_Studio_China%2FShared%20Documents%2FDOCS.MSFT&wd=target%28Engagement.one%7CA67BF78E-8EB6-4951-98EA-8F854EA3B909%2FTic%20Tock%20Reference%7CE89164AA-519A-4DBB-B201-8EC968AF731B%2F%29
onenote:https://microsoft.sharepoint.com/teams/Visual_Studio_China/Shared%20Documents/DOCS.MSFT/Engagement.one#Tic%20Tock%20Reference&section-id={A67BF78E-8EB6-4951-98EA-8F854EA3B909}&page-id={E89164AA-519A-4DBB-B201-8EC968AF731B}&end) 

PubDesk
    - Vendor managed.  They merge changes from the master branch to the live branch when it is publishing time.  Azure does this at 10am and 3pm weekdays.


OPS vs MTPS
- OPS is a publishing system that provides several important values.  See https://opsdocs.azurewebsites.net/en-us/opsdocs/whyops?branch=master.  The 

## Business Impact

### Success Criteria

*What metrics identify the success of this change? Provide the baseline value against the identified metrics.*

Carol and Tyson stay Happy
More docs migrate to Docs.

### Competitive/Internal Product Landscape

*Outline how the problem is managed by our competitors or other products.* 

## Proposal

### User Stories

*Outline of the key user stories that cover this feature.*

### Options and Tradeoffs

*Provide the various options that are evaluated to meet the above objective and the tradeoffs between those solutions.*

### User Experience

*Detailed user workflows, UX mockups, design comps, ideas, etc.*

### Feature Design

*System design/backend requirements, interface definition, integration requirements, etc.*

> [!Note]
> This should not include specific implementation details.

### Telemetry

*Plan what data should be collected on feature use and what types of intelligence we want to gain from the process.*

### Communication and Training Plan

*Some features require alerting the leadership team and writers. This would prepare parties for upcoming features, announcements about shipped features, information on any breaking changes, deprecated features or features that require an explicit content rebuild step.*

## Contacts

*List of stakeholders that agree with the content of this proposal and believe that this Project is ready to start, such as:*

* APEX PM
* APEX dev
* Business SMEs/stakeholders

## Appendix

### References

*A list of related references that will aid in understanding the goals of this feature.*

## Signoff

### Exit Criteria

*A list of expected behaviors, or pass/fail conditions, for all the user stories.* 

* Front End (Docs)  
  *For any user stories impacting docs page template, UI, and UX.*

* Back End (OPS)  
  *For any user stories impacting OPS, build, and publishing.*

* Content Validation  
  *For any content publishing associated with the feature release. Provide docset name, or published URL, if possible.*



Me:
- Onboarding
- evanegelism of features of OPS for azure
- new features -> Gaps in the plratform


    All OPS features
        0 Rob is the guy for 


        Rob
        Den Delmach
            .net, typescript, node
        Yun - shanghai
            Reference - 
        Jessie - shanhai

        planning in redmond, then in shanghai, switches every quarter




Azure

Azure_Docs_PR          
    private repo
    PRReviewrTeam - Aquent

    Publihsing Team - BeyondSoft - Andy Pasic  4 Dudes

    Andy's team 

    Beyondsoft also has a dev team for jonoathan duncan



Azure_Docs

Duncan has
    - Operations
    publihsing - Ke
            Andy

            publishing Master to Live

Gauntlet

Repo    option 1                Repo
    Docset 1

    docset 2
