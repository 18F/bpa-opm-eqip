PERFORMANCE WORK STATEMENT (PWS) 
=================================

Electronic Questionnaires for Investigations Processing (e-QIP) Prototype Development
=====================================================================================

### 

1.0 BACKGROUND
--------------

The Electronic Questionnaires for Investigations Processing (e-QIP) is a
secure website currently managed by the United States Office of
Personnel Management (OPM) designed to automate the common security
questionnaires used to process federal background investigations. e-QIP
is operated by OPM Federal Investigative Services (FIS), which is
transforming into the National Background Investigations Bureau (NBIB).
OPM currently provides background investigations (BI) for federal
employees and contractors, and NBIB will serve a similar role in the
coming year.

2.0 OBJECTIVES
--------------

OPM and NBIB are seeking the creation of a new front-end/user interface
prototype of the e-QIP system. The new e-QIP will maintain the existing
business functionality and meet evolving requirements while leveraging
best practices in software development. The target date for the new
e-QIP application is 2017. The prototype will be built in an agile way,
using open source code, human-centered design, and with an extensible
infrastructure and robust documentation.

3.0 SCOPE
---------

The scope of this call order is for the contractor to deliver the
front-end prototype of the new e-QIP system. This Performance Work
Statement (PWS) describes the technical and administrative components of
the requirement as follows:

-   Tasks that the contractor must successfully perform.

-   Operational requirements that must be met while the
    contractor performs.

-   Generalized administrative requirements and any other terms
    and conditions.

-   Invoicing Instructions for contractor to receive payment.

**4.0 ROLES & RESPONSIBILITIES**

Contracting Officer:
====================

The Contracting Officer (CO) is responsible for monitoring call order
contract compliance, contract administration, and cost control and for
resolving any differences between the observations documented by the
Government and the contractor. The CO will designate, at a minimum, one
(1) CO’s Representative (COR) and one (1) Alternate CO’s Representative
(ACOR) as the Government authority for performance management. The
number of additional representatives serving as technical inspectors
depends on the complexity of the services measured, as well as the
contractor’s performance, and must be identified and designated by the
CO.

### Contracting Officer’s Representative and Alternate Contracting Officer’s Representative:

The Contracting Officer’s Representative (COR) and the Alternate
Contracting Officer’s Representative (ACOR) are designated in writing by
the CO to act as his or her authorized representative to assist in
administering a contract. COR/ACOR limitations are contained in the
written appointment letter. The COR/ACOR are responsible for technical
administration of the project and ensures proper Government surveillance
of the contractor’s performance. The COR/ACOR are not empowered to make
any contractual commitments or to authorize any contractual changes on
the Government’s behalf. Any changes that the contractor deems may
affect contract price, terms, or conditions shall be referred to the CO
for action. The COR/ACOR will have the responsibility to document the
inspection and evaluation of the contractor’s work performance. The
COR/ACOR’s acceptance of the vendor product is dependant on the Product
Owner’s approval.

### Procurement Project Manager:

The Procurement Project Manager is the interface between the requiring
organization (GSA 18F) and contracting organization (GSA FAS AAS/NCR).
The Procurement PM coordinates technical aspects of the contract with
the COR/ACOR and CO, assists with contract administration, ensures
client acceptance of services, and reviews invoices for payment.

### 18F Product Lead:

The 18F Product Lead is responsible for coordination between the
contractor, the Product Owner, as well as the CO and COR/ACOR.

18F Technical Lead:

The 18F technical lead is responsible for coordination between the
contractor’s development team, the Product Owner and the key interagency
stakeholders.

### Product Owner (DOD, with assistance from OPM): 

The Product Owner is the project’s key stakeholder and is from the e-QIP
Prototype Team. They are responsible for having a vision of what he or
she wishes to build, and convey the vision to the 18F Product Lead and
the contractor’s scrum or development team. The Product Owner does this
in part through the product backlog, which will be a prioritized
features list for the product. The Product Owner is responsible for
advocating on behalf of the agency’s needs and responsible for
decision-making during sprint planning and implementation. The Product
Owner will work with the COR/ACOR to inspect vendor work.

5**.0** TASKS
-------------

The contractor will provide the following services:

-   Contractor shall coordinate with OPM and DOD stakeholders to conduct
    end-user research on the e-QIP applicant and agency-user
    experiences, and apply the research to inform application and
    content design and development.

-   Contractor shall build a front-end software application prototype of
    the e-QIP system using a modern technology stack, digitizing the OPM
    Standard Form 86 (SF-86) or its successor and associated questions.

-   Contractor shall use data validation features to verify applicant
    > data, such as addresses, by querying outside data sources.

-   Contractor shall work with OPM and DOD project teams to ensure that
    the system is compliant with interagency requirements and policies,
    to include security policies.

-   Contractor shall ensure that the prototype includes user
    authentication and authorization functionality that, at a minimum,
    includes two-factor authentication using open source
    encryption protocols.

-   Contractor shall post all code to a publicly-available code
    repository, with a Public Domain license.

-   Contractor shall ensure that the prototype provides the ability to
    import/pre-populate and export data by interacting with a file or an
    API, and that the architecture is extensible to allow for
    future development.

-   Contractor shall incorporate analytics, monitoring, continuous
    integration, and measurement tools into their code base.

-   Contractor shall use plain language in application design and
    development, wherever possible.

<!-- -->

-   Contractor shall adhere to [US Web Design
    Standards](https://playbook.cio.gov/designstandards/) or other
    development standards as developed by the 18F team.

### Additional requirement:

-   As part of this being purchased off of the Agile Blanket Purchase
    Agreement (aBPA), work will be conducted in two-week sprints and
    reviewed at the end of each sprint for acceptability before
    moving on. The contractor and government may mutually agree to alter
    sprint length as needed.

### The contractor will not be responsible to perform the following:

-   Provide hosting of the e-QIP prototype

6**.0 OPERATIONAL REQUIREMENTS**
--------------------------------

### 6.1 Personnel

#### 6.1.1. Skills and Knowledge

The contractor shall provide qualified personnel commensurate with this
task's performance work statement, in terms of necessary skills at the
requisite level of knowledge and experience.

Broadly, a team assigned to build the eQIP prototype is expected to have
experience with:

-   Creating form-based applications

-   Human-centered design practices, such as:

    -   User research, such as (but not limited to) contextual inquiry
        > and usability testing

    -   User experience design

    -   Visual design

    -   Content design

-   Highly scalable systems, meaning 100s or 1000s of Transactions per
    > Second

-   Building and testing public facing sites and tools

-   Importing and exporting data in machine-readable formats, such as
    > XML and JSON

-   Structuring a database based on an XML or JSON schema

-   Building applications that interact with web APIs

-   Open source software development

-   Cloud deployment

-   Open-source login/authentication services

-   Agile and scrum methodologies

#### 6.1.2 Key Personnel

Contractor’s Project Manager (PM) and Technical Lead for this project
must be listed as Key Personnel.

To ensure successful performance of the requirement, contractor shall
satisfy the following:

A.  The contractor shall assign a PM and a Technical Lead as Key
    > Personnel whose résumés are submitted with its quotation to
    > perform this call order.

B.  If any individual proposed as Key Personnel becomes unavailable
    > during the course of the solicitation and evaluation process, the
    > contractor shall notify the CO immediately and provide a
    > substitute person with résumé. Any Key Personnel proposed who are
    > not currently employed by the contractor shall be identified as
    > such and an additional letters of intent signed by the proposed
    > Key Personnel shall be provided that indicates that person's
    > intent to be employed by the contractor if awarded this
    > call order.

C.  The contractor agrees that through the duration of the base period
    > of performance of the call order, no Key Personnel substitutions
    > shall be made unless necessitated by an individual’s sudden
    > illness, death, or termination of employment for cause. In any of
    > such event, the contractor shall promptly notify the COR/ACOR and
    > the 18F Product Lead and provide the information required by
    > paragraphs below on the proposed replacement for
    > Government approval.

D.  All requests for substitutions/additions of Key Personnel must
    > include a detailed explanation of the circumstances necessitating
    > the proposed substitution or addition, a complete résumé for the
    > proposed substitute or addition including skills, experience,
    > education, training, and security level. As determined by the CO,
    > all proposed substitutes/additions must have qualifications that
    > meet or exceed the qualifications of the person to be replaced.

E.  The CO, or duly designated COR/ACOR and the 18F Product Lead, will
    > evaluate the request(s) for substitutions/additions of Key
    > Personnel and the CO will notify the contractor, in writing, of
    > approval or disapproval. Disapproval of the proposed individual(s)
    > shall not provide grounds for non-performance by the contractor or
    > form the basis of any claim for monies, delivery schedule
    > extension, or any other equitable adjustment.

F.  Key Personnel must have a full understanding of the technical
    > approach discussed in the Oral Presentations and delivered by the
    > contractor after award. NOTE - the labor category proposed is at
    > the contractor's discretion.

G.  Key Personnel will be a direct liaison to the COR/ACOR and the 18F
    > Product Lead. Key Personnel shall be responsible for the
    > supervision and management of the contractor’s personnel,
    > technical assistance, and interface. Desired skills and experience
    > include:

    -   Experience in technical leadership.

    -   Ability to rapidly prioritize competing requirements.

    -   Ability to understand and simplify customer requirements.

    -   Ability to communicate end user feedback to technical and
        > design leads.

    -   Strong communication skills.

    -   Proven knowledge of industry standards.

### 6.1.3 Project Management

The contractor shall provide a Project Manager (PM) as the primary point
of contact for the government’s program office to enable timely problem
resolution, reporting in accordance with Program Management
methodologies, and properly aligning staffing requirements. Sprint plans
will be developed collaboratively with the 18F Product Lead for this
aBPA buy as well as the Product Owner from the e-QIP Prototype Team.

Per agile development principles, the contractor will be expected to
work with the COR/ACOR, the 18F Product Lead and the Product Owner.

### 6.2 Post Award Orientation Conference

The Government's team, CO, COR/ACOR, the 18F Product Lead and the
Product Owner will hold a Kick-Off Meeting/Post-Award Conference with
the the contractor. Ideally, this will physically located in Washington,
DC, but may be done virtually with contractor’s team and other relevant
Government staff to review and clarify the project’s objectives,
expectations from the Government, and address any questions the
contractor may have. Discussion topics shall include, but not be limited
to:

-   Introduction of the contractor and Government Staff;

-   Understanding of the workflow;

-   Project management expectations;

-   Agreement on communication methods; and

-   Discussion of any other relevant specific concerns.

The Kick-Off Meeting/Post-Award Conference will take place within 10
calendar days from award. The contractor shall provide any finalized
contractor Teaming Arrangements (CTAs)/Subcontractor arrangements at
this time.

### 6.3 Daily Operations

Contractor’s Project Manager shall be responsible for daily operations
as well as coordinating and communicating with the 18F Product Lead.
Daily operations may include:

-   Daily standup via video

-   Chat operations via web-based chat software such as Slack

-   Manage and update user stories + workflow tasks in shared project
    > management system

### 6.4 GSA AAS Business Systems (AASBS) Web Portal

The GSA AASBS (Assisted Acquisition Services Business Systems also known
as IT Solutions Shop (ITSS)) web portal will be accessible to the
contractor during the performance of the call order and be used in the
administration of the call order. This web-based system at
<https://portal.fas.gsa.gov/web/guest> shall be used by the contractor
to upload status reports, deliverables, invoices, and to respond to
inquiries. The contractor shall maintain a current account on this
system.

### 6.5 Travel and Other Direct Costs (ODC)

Travel outside of the Baltimore-Washington region is anticipated for the
purposes of user research and stakeholder meetings. A separate line item
shall be included for travel for each period and the estimated travel
expenses are provided below for each period. Travel shall be billed and
reimbursed in accordance with the Federal Travel Regulation. All travel
must be pre-approved in writing by the COR/ACOR. Travel shall not to be
charged as other direct costs (ODC).

> Travel plug in figure \$20,000 limit - Base Period; \$20,000 limit -
> each Option Period; \$120,000 limit - life of the contract

A separate line item shall be included for ODC for each period. Included
in the ceiling price for each period shall be the estimated other direct
costs (ODCs) provided below. All ODCs must be pre-approved in writing by
COR/ACOR.

> ODC plug in figure \$500 limit - Base Period; \$500 limit - each
> Option Period; \$3,000 limit - life of the contract

### 6.6 Deliverables

### 6.6.1 Status Reports

In lieu of a typical status report, contractor's progress must be
documented and submitted to the the COR/ACOR, the 18F Product Lead and
the Product Owner for each sprint's period of performance with a mix of
the following deliverables:

-   Links to the Github issues/commits/branches

-   Screenshot, links, or other documentation from the shared project
    > management system reflecting completed features, including number
    > and percentage of completed sprint tasks (e.g. percentage of
    > tasks completed)

-   User research documentation

-   Summary slide decks or other collateral created for design,
    > development, system architecture, and stakeholder briefings

### 6.6.2 Impact Reports

The contractor shall be responsible for providing timely notification to
the COR/ACOR and the 18F Product Lead when activities or issues outside
of the contractor’s control may directly impact the contractor’s
performance. This notification shall be provided in writing or via email
within 24 hours of any anticipated or known impact.

#### 6.6.3 **List of Deliverables**

  **REQUIRED DELIVERABLES / REPORTS** | **DUE DATES** | **DESCRIPTION OF DELIVERABLE CONTENT**
  ------------ | --------------- | --------------------
  Status Reports  | 1 business day after each sprint | A report of progress throughout each sprint
  Code Repository of Product | End of call order | Version-controlled Open Source repository of code that comprises prototype
  User Research Findings |  End of second sprint, and every applicable sprint thereafter | A summary of research conducted and results found. If applicable, next steps or recommendations based on research.
  Design Deliverables | End of every applicable sprint|  Mock ups and/or design files if applicable, or design changes reflected in the Development Prototype
  Development Prototype| End of second sprint, and every sprint thereafter | In-progress development prototype, accessible on the web via staging server / development server
  Transition plan | 3 business days after the conclusion of the second-to-last sprint |  See Section 5.7.1 of the PWS

#### The contractor shall submit all deliverables to COR/ACOR, 18F Product Lead, and Product Owner.

#### 6**.6.**4 **Delivery Instructions**

Code deliverables shall be submitted via the Github repository. A copy
of any document deliverables shall be submitted to the COR/ACOR, the 18F
Product Lead and the Product Owner, and uploaded to the AASBS (Assisted
Acquisition Services Business System) web portal. Refer to Section 6.11
for additional information on the AASBS web portal.

#### 6**.6.**5 **Inspection and Acceptance of Services**

Within approximately 5 business days of each sprint's conclusion, the
Government will inspect, test, review and accept all periodic reports
and task deliverables, as applicable.

Only the COR/ACOR, 18F Product Lead, and their designated alternate, has
the authority to accept or reject all deliverables. The COR/ACOR and the
18F Product Lead will provide written final acceptance of all
deliverables to the contractor within approximately 30 days from the end
of the call order, via electronic means. The COR/ACOR’s acceptance of
all deliverables will be contingent on Product Owner approval.

Any contractor performance to correct defects found by the Government as
a result of quality assurance surveillance and by the contractor as a
result of quality control, shall be in accordance with FAR 52.246-6,
Inspection – Time-and-Materials and Labor-Hour. The COR/ACOR and the 18F
Product Lead will monitor compliance and report to the Procurement
Project Manager.

#### 6**.6.**6 **System Documentation**

The contractor shall consult with the 18F Product Lead to determine what
is appropriate, effective, and essential for system documentation. The
Government requires, at a minimum, that the contractor will generate
comprehensive and complete documentation, both within the code itself,
within the source code version control system (e.g., through proper use
of descriptive commit messages, issue tracking, pull requests, etc.),
and as appropriate, in separate documentation, provide artifacts, and
create new user stories based on each sprint.

#### 6**.6.**7 **Quality Assurance**

The Government will use the attached draft Quality Assurance
Surveillance Plan (QASP) to monitor the contractor’s performance. The
QASP will provide oversight help to ensure that service levels reach and
maintain the required levels for performance of this task. Further, the
QASP provides the Government with a proactive way to avoid unacceptable
or deficient performance, and provides verifiable input for the required
Past Performance Information Assessments. The QASP is a living document
and may be updated by the Government as necessary. Any updates to the
QASP will be provided to the contractor. If needed, the draft QASP will
be updated within 10 business days of contract kick off meeting by 18F
Product Lead and/or the COR/ACOR.

### 6.7 Transition

#### 6**.7.1 Transition Plan**

The contractor shall:

-   Ensure and agree that all deliverables, products, licenses, designs,
    > data, documentation, tests, user research notes, source code,
    > configuration settings and files, and materials developed
    > throughout this call order will be the property of the U.S.
    > Government and in the public domain.

-   Two weeks prior to call order conclusion, provide a brief Transition
    > Plan for all deliverables, products, and materials in coordination
    > with the COR/ACOR, 18F Product Lead and Product Owner.

-   Coordinate with the COR/ACOR and the 18F Product Lead and
    > potentially another vendor, and implement the Transition Plan
    > according to the COR/ACOR and the 18F Product Lead’s direction.

-   Provide assistance to the COR/ACOR, 18F Product Lead, and
    > potentially other Government staff to stand-up the application.

#### 6**.7.2 Transition Activities**

During the transition to the Government, or a new contractor, the
contractor shall perform all necessary transition activities. Expected
transition activities may include, but not be limited to, continuation
of full services to 18F and other customers; participation in meetings
with the Government or new contractor to effect a smooth transition and
provide detailed information on the operation of all deliverables, at
COR/ACOR and the 18F Product Lead's discretion; training of new
personnel, either Government or new contractor, during transition
period; and appropriate close-out of any outstanding technical and
related performance elements for this task.

Final report shall include a list of sprint tasks completed,
documentation, and link to code repository developed for 18F. Should the
contractor be terminated prior to the end of the period of performance,
the contractor shall transfer all project materials to the COR/ACOR and
the 18F Product Lead within two weeks of the COR/ACOR and the 18F
Product Lead’s request.

7.0 TERMS AND CONDITIONS
------------------------

### 7.1 Type of Contract

This is a labor-hour (LH) order under master Agile BPA (aBPA) terms and
conditions.

### 7.2 Period of Performance (POP)

The Period of Performance (POP) includes a base period of 3 months, with
5 additional option periods, each 3 months in duration. Further, a
contingency of up to 6 months may be exercised . The POP is expected to
begin within 10 calendar days after award.

### 7.3 Place and Hours of Performance

The primary place of performance will be at the contractor’s facility.
18F is a distributed team and some 18F staff involved in this contract
may not be located in Washington, DC. Staff may also be distributed or
work at their homes, per agreement with the Product Owner.

Business core hours shall be 0900 to 1800 EST, Monday – Friday on
Government scheduled work days. The contractor may set its own work
hours except that the contractor shall be available for technical
contact by the Government between the hours of 0900 and 1800 local time
on Government work days.

### 7.4 Administration Points of Contact

The following Points of Contact (POC) are applicable to this order:\
\
Contracting Officer (CO): Fred Thomas, Contracting Officer, Federal
Acquisition Service, GSA, frederick.thomas@gsa.gov

CO’s Representative (COR): Esther Kim, GSA, Technology Transformation
Services, esther.kim@gsa.gov

Alternate CO’s Representative (ACOR): Michelle McNellis, GSA, Technology
Transformation Services michelle.mcnellis@gsa.gov

### 7.5 Government Furnished Items

The Government will furnish the data and scripts needed at time of
award. No other hardware or software will be provided by the Government.

### 7.6 Non-Personal Services

This call order is not being used to procure personal services
prohibited by FAR 37.104, Personal services contract.

### 7.7 Privacy Act

Performance of this call order may require that personnel have access to
Privacy Information. contractor personnel shall adhere to the Privacy
Act, Title 5 of the U.S. Code, Section 552a and any other applicable
applicable rules and regulations.

### 7.8 Transparency Policy

Vendors are advised that 18F will publish on a publicly available
website documents associated with this requirement, including any
Requests for Quotation (including amendments), Question and Answer
exchanges with vendors (source-identifying information removed), and
other relevant information that is not confidential/proprietary in
nature or source selection sensitive information that would otherwise
implicate procurement integrity concerns.

Upon award, 18F will publish the total price of the selected proposal
and certain non-source-identifying data (e.g., the number of bids, the
mean price, median, and standard deviation of price). During the
performance of this call order, 18F will similarly publish source code,
data related to project management (e.g., user stories, milestones, and
performance metrics), and top-line spending data.

### 7.9 Data Rights and Ownership of Deliverables

18F intends that any data or deliverable created as a result of the work
performed under the call order be committed to the public domain.

Further, 18F intends to commit the following items, to the public
domain, at a minimum:

-   All data, documents, graphics and code created under this call order
    including but not limited to, plans, reports, schedules, schemas,
    metadata, architecture designs, and the like;

-   Any and all new open source software created by the contractor and
    forks or branches of current open source software where the
    contractor has made a modification; and,

-   Any and all new tooling, scripting configuration management,
    infrastructure as code, or any other final changes or edits to
    successfully deploy or operate the software.

The contractor shall use open source technologies wherever possible, in
support of the 18F Source Code Policy. All licenses must be expressly
listed in the deliverable. Regardless of license(s) used (e.g., MIT,
GPL, Creative Commons 0) the license(s) shall be clearly listed in the
documentation.

If the contractor needs to use work that does not have an open source
license, the contractor is required to request permission from 18F, in
writing, before utilizing that work in any way in connection with the
order. If approved, all licenses shall be clearly set forth in a
conspicuous place when work is delivered to 18F.

If an open source license provides implementation guidance, the
contractor shall ensure compliance with that guidance. If implementation
guidance is not available, the contractor shall attach or include the
license within the work itself. Examples of this include code comments
at the beginning of a file or contained in a license file within a
software repository.

### 7.10 Section 508 Compliance Requirement

The contractor shall support the Government in its conformance with
Section 508 throughout the development and implementation of the work to
be performed.

Section 508 of the Rehabilitation Act of 1973, as amended (29 U.S.C.
794d) requires that when Federal agencies develop, procure, maintain, or
use electronic information technology, Federal employees with
disabilities have access to and use of information and data that is
comparable to the access and use by Federal employees who do not have
disabilities, unless an undue burden would be imposed on the agency.
Section 508 also requires that individuals with disabilities, who are
members of the public seeking information or services from a Federal
agency, have access to and use of information and data that is
comparable to that provided to the public who are not individuals with
disabilities, unless an undue burden would be imposed on the agency.

The following standard is applicable for compliance:

1194.22 Web-based Intranet and Internet Information and Applications.

The contractor should review the following websites for additional 508
information:

-   http://www.section508.gov/index.cfm?FuseAction=Content&ID=12

-   http://www.access-board.gov/508.htm

-   http://www.w3.org/WAI/Resources

**7.11 Non-Disclosure Agreement**

All contractor key personnel, employees, agents, subcontractors and
subcontractor personnel who will have access to documents or data during
the performance of their duties under the contract shall execute the
attached Non-Disclosure Agreement and return it to the CO within 5
calendar days of award and before being given access to such information
or documents.

8.0 INVOICING/ PROCEDURES FOR PAYMENT
-------------------------------------

The period of performance for each invoice shall be for one calendar
month. The contractor shall submit only one invoice per month per
order/contract.

*The Government reserves the right to audit, thus; the contractor shall
keep on file all backup support documentation for travels as
applicable.*

### 8.1 Content of Invoice

The contractor’s invoice will be submitted monthly for work performed
the prior month. The contractor may invoice only for the hours, travel
and unique services used in direct support of the call order. The
invoice shall be submitted on official letterhead and shall include the
following information at a minimum.

-   Client Order ID Number

-   ACT Number

-   Prompt Payment Discount

-   Remittance Address

-   Period of Performance for Billing Period

-   Point of Contact and Phone Number

-   Invoice Amount

-   Skill Level Name and Associated Skill Level Number (for T&M or
    Labor Hour)

-   Actual Hours Worked During the Billing Period (for T&M or
    Labor Hour)

-   Clearly indicate both the current invoice’s monthly “burn rate” and
    the total average monthly “burn rate” (for T&M or Labor Hour)

-   Travel Itemized by Individual and Trip (if applicable)

-   Supporting documentation for travel including travel approval and
    receipts (if applicable)

### 8.2 Invoice Submission

All invoicing shall be done electronically. Password and electronic
invoice access may be obtained through the AASBS web portal.

The Invoice and the Status Reports for the applicable billing period
shall be entered into the AASBS portal within 5 to 10 calendar days
after the end of the month. The contractor shall submit invoices
electronically by logging into the AASBS portal
([https://portal.fas.gsa.gov](https://portal.fas.gsa.gov/)), navigating
to the appropriate order, and creating the invoice for that order and
attach a copy of invoice, status reports with all required back-up
documentation as applicable.

The contractor shall NOT submit any invoices directly to the GSA Finance
Center (neither by mail nor via electronic submission). If the invoices
are acceptable, then the Procurement Project Manager and COR/ACOR will
approve them for payment and complete the information in the AASBS
portal.

### 8.3 Final Invoice

Invoices for final payment must be so identified and submitted within 60
calendar days from task completion and no further charges are to be
billed. A copy of the written acceptance of task completion must be
attached to final invoices. The contractor shall request for an
extension from the COR/ACOR for final invoices that may exceed the
60-day time frame.

The Government reserves the right to require certification by a COR/ACOR
before payment is processed, if necessary.

### 8.4 Close-out Procedures

The contractor shall submit a final invoice within 60 calendar days
after the end of the performance period. After the final invoice has
been paid the contractor shall furnish a completed and signed Release of
Claims (GSA Form 1142) to the CO. This release of claims is due within
15 calendar days of final payment.

### Attachments:

1.  ### PWS - QASP

2.  Non-Disclosure Agreement


