PERFORMANCE BASED QUALITY ASSURANCE SURVEILLANCE PLAN (QASP)
=============================================================

Electronic Questionnaires for Investigations Processing (e-QIP) Prototype Development
=====================================================================================

INTRODUCTION
------------

This Quality Assurance Surveillance Plan (QASP) has been developed to
evaluate contractor actions while implementing the Performance Work
Statement (PWS). It is designed to provide an effective surveillance
method of monitoring contractor performance for each listed objective on
the Performance Requirements Matrix in the call order. It also provides
a systematic method to evaluate the services the contractor is required
to furnish.

STANDARD
========

The contractor is responsible for management and quality control actions
to meet the terms of the call order. The role of the COR/ACOR is quality
assurance to ensure call order standards are achieved. The contractor
shall perform all work required in a satisfactory manner in accordance
with the requirements of the PWS. The COR/ACOR shall notify the CO for
appropriate action if it is likely that the contractor will not achieve
successful final delivery of the software code in accordance with the
performance objectives and acceptable quality levels (AQLs) identified
below.

PERFORMANCE REQUIREMENTS MATRIX
===============================

The COR/ACOR will evaluate the performance objectives through
surveillance as reflected below by reviews and acceptance of work
products and services. As indicated, the COR/ACOR will assess progress
towards the final delivered software code. Note that the performance
requirements listed below are required for the final deliverable.
However, the sprints and incremental delivery of code will be assessed
by the Government to ensure that the contractor is on a path to
successful final delivery.

Deliverable or Required Services Performance Standard(s):

  **Deliverable or Required Services** | **Performance Standard(s)** | **Acceptable Quality Level (AQL)** | **Method of Surveillance**
   ----------- | ---------------- | -------------- | ---------------
   Tested Code | Code delivered under the order must have substantial test code coverage and a clean code base. | Minimum of 90% test coverage and Code Climate GPA of 3.0 | https://codeclimate.com
   Accessible | Client-side rendering must conform with section 508 standards. | Meets 508 Standards |  http://squizlabs.github.io/HTML_CodeSniffer/
   Deployed | Code must successfully build and deploy into staging environment. | Successful build with a single command | Combination of manual review and automatic testing
   Documented | All dependencies (and licenses for dependencies) are listed and all major functions are documented. | All dependencies are listed and the licenses are documented. Software/source code is documented. System diagram is provided. | Combination of manual review and automatic testing
   Available | Code must be stored in a version-controlled open-source repository. | All of the code needed to run the front end of the prototype must be available. | 18F will assess code availability.
   User research | Usability testing and other user research methods must be conducted at regular intervals throughout the development process (not just at the beginning or end). |  Artifacts from usability testing and/or other research methods with end-users are available at the end of every applicable sprint, in accordance with the vendor’s research plan. | 18F will evaluate the artifacts based on a research plan provided by the vendor at the end of the second sprint.
   Secure | Code must be free of medium- and high-level static and dynamic security vulnerabilities | Clean tests from a static testing SaaS, such as Gemnasium, and from OWASP ZAP, and/or documentation explaining any false positives. |  https://pages.18f.gov/before-you-ship/

PROCEDURES
==========

The COR/ACOR, along with the 18F Product Lead and the product owner,
will inspect all tasks required by the call order to ensure contractor
compliance with the call order requirements at the conclusion of each
sprint, which shall have a length of two weeks or less. Delivery will
occur by pull request from the contractor’s repository to the 18F
repository. If inspection results are satisfactory, the pull request
will be merged; otherwise, deficiencies will be noted in the pull
request or through issues as described below. The COR/ACOR may find the
delivery satisfactory even though further work is required, provided
that the specific requirements of the sprint are met.

At the conclusion of each sprint, the COR/ACOR, along with the 18F
Product Lead and the product owner, will review the completed user
stories and related functionality. Incomplete or inadequate code and
user stories will be noted in a mutually agreed-upon issue tracker, such
as Trello or GitHub Issues, and links to each issue shared with the CO.
The contractor may respond in that tracker as appropriate, addressing
the accuracy and validity of the defect as well as any planned
corrective action (if not already noted). The contractor team will
discuss and document actions to prevent recurrence in their sprint
retrospectives.

At the conclusion of the period of performance, a similar procedure will
be followed to document discrepancies and to assess overall performance.

If any of the services do not conform to the call order requirements,
the COR/ACOR may require the contractor to perform the services again in
conformity with call order requirements. Any user stories that are not
accepted must be completed in the next sprint, unless the product owner
and 18F product manager agree to move it to a later sprint. The COR/ACOR
shall not certify satisfactory performance for the call order until all
defects have been corrected. When the defects in services cannot be
corrected by re-performance, the Government may:

1)  Require the contractor to take necessary action to ensure that
    future performance conforms to call order requirements; and,

2)  Reduce the call order price to reflect the reduced value of the
    services performed. The COR/ACOR shall, in addition to providing
    documentation to the CO, maintain a complete quality assurance file.
    The file will contain copies of all reports, evaluations,
    recommendations, and any actions relating to the Government’s
    performance of the quality assurance function, including originals
    of all surveillance activity checklists. All such records will be
    retained for the life of the call order. The COR/ACOR shall forward
    these records to theCO at completion or termination of the
    call order.

ACCEPTANCE OF SERVICES
======================

Acceptance of services shall be based upon compliance with performance
standards described in the PWS and surveillance procedures described in
this QASP. Before approving/certifying any contractor invoices, the
COR/ACOR will verify that all invoiced services have been performed in
compliance with call order requirements. The COR/ACOR shall not certify
satisfactory performance for the call order until all defects have been
corrected.
