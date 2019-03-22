# Test Case
Test case usually is a spreadsheet to list all the single test according to the requirement documents.
See below. Here is a table to show some demo tests. The requirement is based on requirement documents.
Each requirement may be divided into several test cases, and each test cases may be divided into 
several detailed steps. Each step should clearly state how to test a higher-scope function or, comparatively,
how to test a lower-scope atomic operation on system. It depends on what type of testing you're proceeding on.


Requirement reference|Test Cases#|Pre-Condition|Objective|Test Step#|Detailed Test Step|Expected Results|Execution Result
---------------------|-----------|-------------|---------|----------|------------------|----------------|----------------
1.1|1| User should be given the system test environment of the www.my-company.com platform. | To test the login functionality of Homes.com with invalid credentials. |1| Launch the firefox browser and navigate to homes.com|The www.my-company.com home page should appear successfully. |Pass
1.1|1| | |2| Click on the sign-in Button from the top right hand side. | User should be navigated to the sign-in popup box of homes.com. | Pass
1.1|1| | |3| Enter invalid id and password. | User should be able to enter texts in the fields. | Pass
1.1|1| | |4| Click on login button. | User should see the 'Invalid Username/password' error message | Pass







