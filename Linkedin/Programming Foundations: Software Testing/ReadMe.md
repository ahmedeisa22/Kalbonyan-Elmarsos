#  Software Testing/QA

* Learning objectives
* How QA fits into the software
* development life cycle (SDLC)
* Setting expectations and goals
* Making a test plan
* Incorporating box testing into your process
* Executing manual testing
* Leveraging UI automation testing
* Identifying, reporting, and prioritizing bugs
---
**Quality Assurance** systematic process used to determine whether a product meets specifications.
 **titles** 
*  QA
*  QA engineer 
*  QA analyst
*  Software engineer in test,
*  Tester.

the cycle of project:
* It starts by having clear specifications.
* implemented in code
*  code tested
*  code is released
---------
## The Role of QA


**These skills should include**
* technical aptitude
  * manual testing
  * automated testing
  *  programming 
  *  scripting
* business knowledge
  * feature scoping
  *  test planning
  *  test case management and bug management
* DevOps principles
  * configure tooling
  * set up continuous integration
  * automate processes like running tests
  * deploying the application.
* process and release expertise.
  * defining and improving practices for testing 


**SDLC** 
1. plan
   1. identify risks
   2. identify use case
2. Define
   1. specifications or acceptance criteria
   2. ecide what's in scope and what's out of scope.
   3. write a test strategy
3. Design
   1. solidify test scenarios
   2. get feedback on them from the team.
   3. manually test the scenarios defined and script automated test
4. Build 
5. Test
   1.   1. manual and automated
6. Deploy
   1. validate the release build
   2. test production

teammate in company:
, there are developers, designer, a tester, and product manager or business analyst.
   

Template  A test strategy:

1 - introduction:
high-level summary of the project.

2 - references:
include any relevant links for their project, including their project's repository and tools used in the tech stack.
3 - QA deliverables:
The first deliverable is this quality strategy, the high-level guide of how quality will be maintained on our project.
4 - test management:
 section to describe what resources are needed to carry out testing
 5 - the scope of testing:
  This describes what types of tests exist for this project.

  ![Capture](https://user-images.githubusercontent.com/70604321/163689216-cd3ff790-664e-4700-9fc2-34cb2aa1fcc8.PNG)


**criteria or AC** for short are conditions that a software product must satisfy to be accepted by a stakeholder.

 Acceptance criteria follow a specific format. They always start with a **given**. This is a precondition or beginning state Next is the **when**. This describes the input or action of the scenario. The final part is the **then**. This describes the expected outcome of the scenario.

 ---

**black box** testing, which means that the box is completely concealed and it is not possible to see inside of it. Each test scenario here examines the product from the outside. It allows input to the box and gets output from the box.

**gray box** testing:
here examine the interaction between the outside and inside of the box. It requires QA engineers to have a deeper understanding of the application


**white box testing**:
ocuses on the internals of the application and what is happening at the code or system level

With the surface level of the application tested by manual and UI automation, a QA engineer might want to move on to test the application from another perspective. Integration testing focuses on the interaction between components at lower layers of the application. 

 **Performance testing** is done to benchmark how a system performs under load.

 **different types of performance testing**
 * load
checks the application's ability to perform under anticipated user loads. The objective is to identify the maximum operating capacity of an application by observing when bottlenecks occur


* endurance testing
the application can handle the expected load over a long period of time.

* stress testing:
 testing an application under extreme workloads, and seeing how it handles data processing. 


**common performance problems include**
* long load time
*  poor response time
*  limited scalability 
*  bottlenecking in the system.

 **Security testing** instead looks to expose problems in the application that can either cause it to behave

 **Denial of service:**
 This type of attack tries to take down making it inaccessible to users. In terms of flight search, it


 ![Capture](https://user-images.githubusercontent.com/70604321/163692261-621e7693-bc01-4529-b4fc-36158b04c5fe.PNG)

. **Severity** is based on how impactful the bug is to the business

**priority** is based on how fast the bug should be fixed.


 **priority:**

![Capture](https://user-images.githubusercontent.com/70604321/163692369-47658348-7457-43d4-bd8e-22d534cd69a8.PNG)

---
![165](https://user-images.githubusercontent.com/70604321/163693204-e38131be-2cb3-47c8-9c55-3777084aa68d.png)
