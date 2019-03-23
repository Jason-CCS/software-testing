# Different Testing

Mostly, test is the last phase in SDLC, and commonly called as QA(quality assurance) in company.
Test is not special but only for the purpose to validate functions or to check feasibility of system.

There are different types of testing:
* functional testing:
 test a function of a system, eg. login function.
* ui testing:
 test the ui elements, commonly use Selenium, Cypress, or others.
* acceptance testing:
 customers or product owner accept the function or not, also called UAT (User Acceptance Test).
* accessibility testing:
 the function is accessible for deaf or dumb, etc.
* ad-hoc testing:
 some crazy crazy special no logic tests to system in order to break down the system. Test the robustness of system.
* black box testing:
 no internal information testing. mostly seen in ui testing scenario.
* white box testing:
 information provided testing, eg. Unit testing for internal structure.
* smoke testing:
 test major function of system if you have no enough time, which is smoke testing.
* regression testing:
 test previous iteration(sprint) together when this iteration is ready to test, also called integration testing.
* stress testing:
 find the limit of a system, and think of improvement or not. For example, doing a big amount of requests to a service, 
 and gradually increase the number of requests. Before the system crashed, record every parameter of the 
 performance of the system so that we can understand the system condition when system is out of its capability.
* load testing:
 to see the performance of a system which is under the limited environment or resources.
* end-to-end testing:
 is a methodology used to test whether the flow of an application is performing as designed from start to finish.
 The purpose of carrying out end-to-end tests is to identify system dependencies and to ensure that the right 
 information is passed between various system components and systems.