# Change Order 02 for ABCL - Milestone 5 onwards (1).docx

| Field | Value |
| --- | --- |
| Type | sow |
| Uploaded at | 2026-06-18T06:17:36.325352+00:00 |
| Chunks indexed | 5 |
| Artifact targets | user_story, epic, journey_map, sandbox_prototype, project_home, workshop_plan, wireframe, test_case |

## Content

```
Definitions

This Change Order, effective as of the last date beneath the parties’ signatures below ("Change Order Effective Date") applies to, and is subject to, the terms of Statement of Work between “SFDC” and “Customer” as defined below.   SFDC reserves the right to reject this Change Order if not signed by the Expiration Date provided below.  

Authorization of the changes set forth in this Change Order is necessary for SFDC to continue work on the project outlined in the original SOW, but does not guarantee that the Professional Services will be completed within these hours.  In the event that upon exhausting the Professional Services hours and/or dollars authorized under this Change Order, additional Professional Services are required to progress the project, the parties will execute an additional Change Order(s) to continue the Professional Services. 

Statement of Work Summary

Description of Changes under this Change Order

Impact to Scope

The primary objective of this Change Order is to modify/remove the original scope of work (SOW04098753 dated July 1st, 2025) and include additional scope items with reference to the Personal Loan Loan Originations System project.

Customer and SFDC agree that SFDC has already delivered the scope pertaining to Releases 1 and 2, and Milestones 1, 2

and 3 from the original scope of work (SOW04098753 dated July 1st, 2025.) Additionally modified Milestone 4 has also been delivered by SFDC via CO001, which was approved on 02 June 2026.

The Parties hereby agree that Releases 4 and 5 from the original scope of work are removed from scope in their entirety.

This Change Order will supersede and replace the original scope of work for Release 4, Release 5 and Milestones 5, 6 and

7 in its entirety.

The revised scope, as detailed below (section 3.1.1), accounts for work to be performed following the execution of this Change Order:

3.1.1 Scope Inclusion for PL Journey

Scope for PL LOS Journey

SFDC will use a combination of standard configuration tools and custom code to design, specify, develop and configure the following currently anticipated functionality as integrated modules within the Application: 

The Customer wants the implementation of a Lending solution – Loan Origination System (LOS) for the Personal Loans  line of businesses to be developed on the Salesforce Platform. SFDC Professional Services will build and deploy the Application in the existing Lead Management System/Questioned Data Entry (LMS+QDE) Salesforce Org which will cater to the Unsecured Personal Loan Line of Business.

Implementation will cover following Products, Channels, Journeys and Functionalities and will be done in a single release.

The high level scope is as follows:

Products

Unsecured Personal Loan

Product Offerings

Term Loan

Overdraft

Hybrid Term

Dropline Flexi

Channels

Branch

Direct Walk-in customer

Call Center

DSA

Aggregators

Website (DIY)

ABCD Mobile App (DIY)

Marketing

Digital Marketing Lead

Core Journeys

New Business

Top up

Balance Transfer (BT)

Top up + BT

Cross-Sell/Value Added Service

Do it Yourself (DIY)

STP

STP to Non STP

Constitutions

Salaried Individuals

Self Employed Professionals

Self Employed Non Professionals (Sole Proprietor)

Staff

Functional Modules

Loan Application (Questioned/Quick Data Entry (QDE)/Detailed Data Entry (DDE))

Credit/Underwriting

Pricing & Negotiation

Field Investigation

Personal; Discussion (Video/Tele/Dynamic)

Risk Control Unit

Post Sanction Ops

Reports & Dashboards (25 reports/10 dashboards)

TAT Management

Query Management

Alerts & Notifications

The detailed technical scope/solution to deliver the above high level scope are as follows:

SFDC - Data Services - Data Integrations 

SFDC will work with Customer to implement the following data integrations. Any additional integration touch points  needed will go through the Change Control Process (refer to section 7.1). The table below lists system names and high level approaches.  

Scope Assumptions:

Functional Scope

PL LOS Implementation will be a brownfield implementation on existing LMS/QDE Salesforce Org.

A total of sixty five (65) integration touch points across twenty six (26) systems are included in scope of this implementation. 

Customer will share the final list of integration touch-points, specification and system details prior to commencement of discovery/define phase of the project. 

Business requirements will have detailed fields to be captured at each screen and validations at screen and field level.

Customer BRE will pass the Green Channel/Amber/Red case prioritization flag for a loan application to Application, which will then be used to determine the loan application journey next steps

Loan applicants will be sent a link for uploading loan related documents and related comments as part of the loan journey. Applicants will be able to access the Salesforce guest community page to upload the same.

The link sent to customers for KFS and Sanction letter through SMS and Email will be enabled to expire after a certain duration (specific number of hours post generation). The actual expiry duration will be finalized during discovery. This functionality will be applicable only for links generated from Salesforce Application.

Testing

SFDC testing will be limited to dedicated browsers (Safari, Google Chrome) and devices (Mobile - iOS, Android - make to be confirmed during development phase, Desktop - Mac)

User Acceptance Testing (UAT) will be conducted by Customer. The development of a test plan document and test cases will be the responsibility of the Customer

Middleware

Customer has tools which can performs ESB and ETL functionality like process orchestration, protocol transformation, asymmetric encryption

Any encryption of payload (using Symmetric or Asymmetric algorithms) must be handed in middleware

Customer should do all response parsing on middleware

Asynchronous executions for interfaces will be via Platform Events. Customer must procure additional HVPE add-on licenses by estimating the number of events published per month. Customer middleware should subscribe for these platform events and push response back to Application.

Language

The application will support English language only. Localization or testing in any other language is not in scope.

All system-generated documents and notifications(Email) will be in English only. Multi-language support for documents or notification(Email) templates is not part of the scope.

PDF documents generated in Application will support only fonts and styles supported by the Salesforce PDF engine.

Bulk Upload Features 

Application will not support any data uploads using excel files, any data upload should be using pre-defined CSV  files using the Application standard import wizard 

Data load will be done through the standard import wizard. UI of import wizard is not customizable and should be  used as is. 

Other

SFDC will enable standard Salesforce mobile app for mobile usage for all internal personas/employees.

Scanning the file during upload etc. is out of scope and file security will only be limited to validating the file extensions.

All inbound lead or loan creation requests originating from external systems (such as PolicyBazaar, third-party APIs, or internal systems) must be orchestrated via middleware

To support bundled products (e.g., personal loan and insurance), the BRE API must return consolidated eligibility for all applicable products within a single response.

All callbacks must be initiated by the customer, which will invoke the relevant application endpoints.

For integrations involving large payloads, middleware must perform data transformation, optimize payload size, and directly push documents to the application.

SFDC Project team will employ AI-augmented engineering and productivity tools (including but not limited to Google Gemini, NotebookLM, Lucid AI, Jira, Story2Test, Figma, Claude Code and Cursor) sticking to the in-scope user stories delivery. All AI-generated outputs are subject to mandatory SFDC Project teams’ review and validation to ensure the final Application strictly meets all finalized functional specifications and quality standards.

Journey fallback/alternate flow options for all journeys/workflows - DIY, Assisted, Hybrid will be discussed and finalized during the define & design phase.

Scope Exclusions:

Any PL products other than included explicitly in scope including Secured PL product.

Any custom mobile app development/configuration including but not limited to any offline capabilities on any mobile app.

Data Migration - No transactional data migration has been included in the current scope for this implementation.

Any ETL development for master data loads.

Any data upload using an excel file.

Any development on Partner Community for partner portals in current scope of work. 

Any development on Customer Community for Self Help portals and customer self servicing in current scope of work.

BRE related requirements except for basic formulas and calculations, which can be supported on Application Out of the Box.

Loan Management System features and functionalities, specifically Loan Servicing, Pre-EMI, Repayment Schedule Variations, Payment Requisition and any other Disbursement, Post Disbursement activities not included in scope.

Document Management System (DMS) related workflows and functionalities.

Biometric Device integration with Application.

Co–Lending business and related functionalities.

Collections process and related functionalities

DIY Journey

Co-browsing/Screen mirroring and Chat functionality.

OTP delivery via call.

Call Center Integration/CTI integration for outbound/ inbound calling.

Any requirement requiring reading and parsing offline Aadhaar XML.

API development or testing of API’s on Customer systems.

File based integration with any systems.

Any reporting on data not residing in Application. Any analytical reporting involving significant calculations or external data like LMS data is out of scope.

Data extraction to and from any external data warehouse. 

Customer 360 views.

Collateral Management and valuation will be done outside Application. The details related to the same will be fetched and shown in Application for CAM processing and approval.

Any marketing or campaign related functionalities

IRR calculator

Incentive calculator

USB token based (dongle) authentication for E-sign

Business process reengineering, process redesign, or process transformation activities.

Standard REST API logging is out of scope

Application will support integration with only one LMS (Loan Management System) and not with multiple LMS systems..

Automation test scripts development and Automation Testing

Non-functional requirements including security compliance certifications, accessibility standards, or regulatory certifications.

Performance, security, scale and load testing.

Training of end users.

Change management - Customer will conduct all Change Management activities, including but not limited to:

stakeholder identification; 

end user training and preparation of any training materials (eg: manuals, deck) for end users;

end user communications; and 

adoption planning and execution.

Devops setup/implementation

Assumptions:

In addition to the assumptions set out above section, the General Scope Assumptions set out in Section 2.3.1 of SOW04098753 shall apply to the Professional Services set forth in this Change Order.

Scope Exclusions:

The scope exclusions set forth in Section 2.3.1 of the SOW04098753 and the following scope exclusions apply to the Professional Services set forth in this Change Order:

Warranty support for ABCL: 

An additional warranty support of four (4) weeks post production deployment of PL LOS application is considered as part of change order 02 in the professional services fees below

Dependencies

Impact to Professional Services Schedule:

The below is an indicative program timeline for PL LOS implementation based on our current understanding. Actual release date is subject to change due to the outcome of discovery & design activities. Material changes to this timeline will be handled through the Change Control process.

The original schedule of forty six (46) weeks will now increase to seventy four (74) weeks.

Impact to Professional Services Fees

To reflect the scope modifications detailed in Section 3.1, the Milestone Table in Section 4.1 of the original SOW04098753 is hereby amended. The original Milestones #5, #6 and #7 are superseded and replaced by the "Revised Milestone #5, Milestone #6, Milestone #7 and new Milestone #8, Milestone #9, Milestone #10 and Milestone #11" set out in the table below.

The requirements and timelines for original Milestone #5, Milestone #6, and Milestone #7 stand cancelled.

Payment Obligation

Is a Purchase Order (“PO”) required for the purchase or payment of the products on this SOW?  Please Select: 

No.  A PO is not required by the Customer to purchase or for payment of the Professional Services in this Change Order. 

Yes. Customer has fully approved PO                                  for the amount of                            .  

Signatures

This Change Order may be signed in counterparts, each of which shall be deemed an original.  IN WITNESS WHEREOF, the parties have caused this Change Order to be executed by their duly authorized representatives as identified below.
```

---
_Auto-generated from in-app state. Source field: `documents['Change Order 02 for ABCL - Milestone 5 onwards (1).docx']`. Last updated: 2026-06-29T12:32:32.230049+00:00._
