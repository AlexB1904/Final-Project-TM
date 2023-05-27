# Guru99 Project
## ***Test Plan***
### **Revision History**

| Date | Description | Author | Comments |
|---|---|---|---|
| 27.04.2023 | v1.0 | Alexandru Bud |  |
| 14.05.2023 | v1.1 | Ema Bud | More details added on "Test Implementation" |
| 19.06.2023 | v1.2 | Alexandru Bud | Test completion report added |

    1. Introduction
        1. Project objective
        2. Functionalities in scope
        3. Functionalities and tests out of scope
    2. Test process
        1. Test planning
        2. Test analysis
        3. Test design
        4. Test implementation
        5. Test execution
        6. Test closure
        7. Test monitoring and control
    3. Test deliverables
        1. Test plan
        2. Test conditions
        3. Test cases
        4. Daily test summary reports
        5. Traceability matrix
        6. Test case results
        7. Bugs report
        8. Test completion report

### **1. Introduction**

* This test plan document describes the strategies, process, workflows and methodologies used to plan, organize, execute and manage testing process for Guru99 Bank.

#### ***1.1 Project Objective***

* The scope of the final project for ITF Manual Testing Course is to use all gained knowledge through the course and apply them in practice, using a live application.

Application under test:
[Guru99 Bank](https://demo.guru99.com/V4/index.php) - The focus will be only on "Manager module"

Application [documentation.](https://docs.google.com/document/d/1rPW5DV82VJT6vtA1VDSrfxaCBuAduxW0zb1yfTh_VMk/edit)

Tools: Jira, Postman, MySQL

#### ***1.2 Functionalities in scope***

* All the features of "Manager module" which were defined in business requirements need to be tested: functional testing, GUI testing and API testing
* The below user story was created in Jira and describes functional specifications of the "Manager module"

#### ***1.3 Functionalities and tests out of scope***

* Non-functional testing like stress, performance is beyond scope of this project
* No QA support for mobile application developed. Only web application will be tested.
* Automation testing is beyond scope

### **2. Test process**

#### ***2.1 Test planning***

#### **Roles and responsibilities**

| Role | Name |
|---|---|
| Product Owner | Mihai Toma |
| Software Developer | Lisa Diaconescu |
| Tester | Alexandru Bud |

#### **Entry criteria:**

* Business specifications are defined
* Roles needed for the project are allocated
* Initial project risks were detected and mitigated 

#### **Exit criteria:**

* All test cases have been executed
* The unresolved bugs/defects have low priority
* No detected major risks remained un-mitigated
* All resolved bugs have been retested and approved by the testers
* Regression testing have been ran and no major bugs detected 
* All business requirements have been covered by test cases 
* All business requirements have been met

#### **Risks:**

* *Project risks:* lack of experience of QA team, lack of tools, short deadline for Jira and Zephyr Squad, unavailability of OrangeHRM demo environment
* *Product risks:* Validation constraints on the fields might be too restrictive to the end user

#### ***2.2 Test analysis***

* Analyze the business requirements to make sure that we have all the details to create the test conditions 
* Write test conditions that will be tested in out test process

#### ***2.3 Test design***

* Functional test cases will be created in Jira
* GUI test cases will be created in Jira
* API test case will be created in Postman
* Queries in DB will be done in MySQL

#### ***2.4 Test implementation***
