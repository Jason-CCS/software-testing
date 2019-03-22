# Test Plan

Before testing, we should prepare a test plan and some common rules to define the scope of testing in accordance with
the requirement document.
The example below shows a demo plan which includes many important points.

> ### Objectives
> The aim of the testing, what functions should be tested. For example:
>
> *According to our company website: www.our-company.com.
> We should test all the ui functions of company website and build an automation system to test the correctness when
> a new update is integrated with current version.*
>
> ### Scope/Out of scope
> * In scope: the modules should be implemented and tested according to requirements.
> * Out of scope: the modules that are decided not to test. For some circumstances, we may not want to test some
> functions which are restricted by company policies.
>
> ### Assumptions
> In order to test, some materials or codes should be provided by manager or dev beforehand. 
> 
> ### Entry/Exit Criteria
> * Entry:
>   - approval of this test plan by the management.
>   - all databases, developers, and business teams should be notified about system test dates.
> * Exit:
>   - test cases for mentioned modules should be created 
>   - all the modules should be tested
>   - test case evidence will be provided to the manager.
>   - all the mentioned deliverable should be completed and signed off.
>
> ### Environment
> * System Test Platform: the platform where the tests occur.
> * Access authority to requirement documents.
> * If doing automation, you also need test management tool.
>
> ### Risks
> Examples:
> - Tight deadlines can affect the accuracy of system test execution.
> - Limited access to test system, test platform or test management tool can delay the execution.
>
> ### Key Dates and Deliverable
> Module Name     | Completion Time of Test Execution
> ----------------|----------------------------------
> Sign up          | 2019/8/15
> Sign in          | 2019/8/25
> Search function | 2019/8/30
>
> ### Scripts and Files
> The directory or file path which indicate where are test cases and test results.
>
> ### Roles and responsibilities
> Name     | Roles and Responsibilities
> ----------------|----------------------------------
> Me      | (QA Tester) Analyze requirements and create test cases
> Sign in | (QA Tester) Execute test cases         
> Search function | (QA Tester) Execute test cases
> Craig Thomson | (Project Manager) Approving the test plan
> Srinivas | (QA Manager) Monitoring the test plan and execution progress
>
> ### Closure
> Handle all the test cases and files to management.