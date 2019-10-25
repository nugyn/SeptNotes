#Week 12 Software Engineering Process & Tools

Table of Contents:

[TOC]

This course aims to develop your knowledge of **the processes and associated tools** required to service the software development life-cycle to:

- Manage **complexity**

- Reduce **risk**

- Maximise **quality** of product. 

##Process and Tools

What are some of the characterists of modern software construction: 



How does Process help:

- It manages complexity, reduces risk and improves quality.

How do Tools help:

- Git:Teamwork
- Automation: reduces human error

What else do we need: 



### Week 1: SE Process, Agile

####Why is good SE Process so critical? 

It is critical to, 

- Reduce risk of failure
- Failure is quick
- Feedback is recieved quickly, and solutions based on changing requirements and needs of the clients

Tools help with 

- Automation reduce human error
- Collaboration

####What does good process manage, reduce, maximise? 

Manage risk

Reduce human error

Maximise error free code



####Explain the Quality Triangle. 

####What are the main parts of the SE life cycle? 

Requirement Gathering: 

> What the user wants

System Analysis and Requirements Engineering

> Understanding/documenting requirements

Design

> Planning a solution

Implementation

> Building a solution

Testing

> Ensuring it meets requirements

Deployment

> Making it available for use

Maintenance

> Updating to add functionaility or resolve issues

Other: Project Scoping

- Dealing with imposed limits on how much you want to create/clearly specifying what you want to achieve
  - You may decide to leave network play out of a game

####What are the main activities in SE? 



####What are the main SE Processes? Their advantages and disadvantages? 

<u>Waterfall</u>

It is a robust process, which adheres strictly to the 'plan' when the requirements are well understood. 

Problems: 

> Difficult to accomodate change after the process us underway
>
> Inflexible partitioning makes it difficult to respond to changing customer requirement
>
> Model is only appropriate when the requirements are well understood and changes are limited during the design process
>
> Mostly used for large system engineering project where a system is developed at several site. 

<u>Incremental Programming</u>

- Cost of accomodating changing customer requirements is reduced. 
- It is easier to get customer feedback on the development on the development work that has been done
- More rapid delivery and development of useful software to the customer is possible.

<u>Extreme Programming</u>

- New versions built several time per day

- Deliveries to customers every 2 weeks 

- All tests must be run for every build and the build is only accepted if tests run successfully. 

<u>Agile Method</u>

Great for small teams, but hard to scale for a large system. 

Customer involvement, Incremental Delivery, People not process, Embrace change, maintain simplicity.

####What are the characteristics of Incremental and Agile methods? How does Agile address the problems of the traditional Waterfall approach? What are its strengths? 

The issue with Waterfall is how inflexible, and incapable the process is to respond to change. Morever, it is slow, and requires more documentation to make sure that the requirements are solid enough to proceed. However, if changes happen, you can get the end have to scrap the project because it does not meet requirements. 

Agile and incremental methods, allow for a team to backtrack and make rapid changes on the fly in respone to the clients whims. Its strengths lie in taking advantage of a how a small team can work, quickly, efficient, keeping the customer involved to embrace change and maintain the simplicity of the software. 

####How does Scrum work? What are its benefits? How do the task-tracking tools like Trello and JIRA support it? How would you organise a Trello/JIRA board to manage Scrum? 

Scrum is one framework under a Agile methodology. It involves, sprints (which represent a development cycle), which last 2 - 3 weeks, user stories to represent the requirements and a responsive methodology to change and problems faced through a development lifecycle. The process a cycle of assess, select, develop, review and assess.

People act as Scrum Master, a Product Owner, or Developer. The idea is that each member share resposiblity, and no one is 'in charge'. Tasks begin on a high level as User Stories. The stories represent the features/requirements of the project. 

Scrum will have Sprint Planning, the actual sprint, stand-up meetings often to check in on progress and to free up roadblocks, and then a sprint retrospective to reflect on what went well in a sprint vs not so well such that the next sprint planning accounts for this. The idea is that each sprint will improve the next sprint.

Trello can be used to manage the tasks, and there are ways to organise it such that it facilitates Scrum. 

One way of organising it, is maintaing a product backlog (which contain the user stories), Sprint Backlog (which are tasks/features planned to be implemented), an in progress tab to see who is doing what at a given time, and a complete section for each sprint. The cards are labelled according to the User Story, and sub divisions of the labels are used to organise 'sub-tasks' of bigger overall tasks. 

####How are the Scrum team roles and what do they do? Who fills them? .

Product Owner: a teammember who interfaces with the client and keeps external influence from interfering with the developers work.

Scrum Master: a teammember who facilitates stand-up meetings, and ensures organisation runs smoothly.

Developer: a teammember who develops. However, all members in a team will contribute to the code, and the roles only entail side 'responsiblities' but ultimately responsibility lies with all teammembers.

####What are the different Scrum meetings and their purpose?

Sprint Planning: typically 7 to 30 days long. The planning involves planning out what needs to be done, the length of sprints, how many sprints are required, the product backlog (requirements), estimation of story points.

Sprint Retrospective: After each sprint, the meeting is conducted to reflect on what went well and not so well. It is designed to learn your mistakes and improve the next sprint. 

Stand-up Meeting: Meetings that happen intermittently throughout sprints, to check in progress and identify and remedy roadblocks.

### Week 2: User Stories and Backlogs

####User Stories: how are they different to Use Cases? How do they fit with agile development? How do they reduce risk associated with requirements change? 

User stories are different to Use Cases because it involves a user interacting with the functionality of the system and in steps. 

It fits with Agile Development, because in Agile, 'Customer Involvement'. Requirements are drawn from these stories, and keeps development customer focused. 

It reduces risk, because requirement changes are always centered the customers needs and wants. Changing the requirements, involves the customer immediately, and there is always the closest 

####What are the main parts of a User Story? What does a User Story look like? How are User Stories used? What are characteristics of a good User Story? 

The title of the User Story, the priority, and estimate

| Title | Priority | Estimate |
| ----- | -------- | -------- |
|       |          |          |

As a <type of user>

I want to <perform some task>

so that I can <achieve some goal>

**Acceptance Critera**

Given <some context>

When <some action is carried out>

Then <a set of observable outcomes should occur>

####How are task times/sizes estimated? What is the relationship between User Stories and Backlogs? 

The tasks times/sizes are estimated by story points. Backlogs contain a log of User Stories . When User Stories and the associated tasks are completed, these can be ticked off the backlog as complete. The purpose of the backlog is too keep and maintain a record of the progression of the User Stories. 

####What is a Definition of Done? What are different possible definitions?

Definition of Done

> 1. Unit tests passed
> 2. Code reviewed
> 3. Acceptance criteria met
> 4. Functional Tests passed
> 5. Non-Functional requirements met
> 6. Product Owner accepts the User Story

Alternatives:

> - Non-Functional requirements met
> - End-to-end integration completed
> - Regression tests pass
> - Promoted to production environment
> - Meets defined market expectations

### Week 3: Version Control, Git, Gitflow

####Why is version control critical (multiple reasons!)? What is version control’s role in modern SE process? 

Version control is critical in SE, 

1) It allows back tracking incase a current version of the project breaks or is unviable due to not matching requirements. 

2) Backing up each version of the project is a game saver when things go wrong

3) You can different versions for deployment, testing, and etc.

Its role in SE process is to facilitate concurrent development of the project for different features of the project. Keep the development rolling, and reduce human error. 

####What is the difference between centralized and distributed Version Systems? What are some advantages of the Distributed model?

A central distributed systems have one repo, and all developers will check in (commit), and checkout (update) into one single repository.

A distributed one, means each developer has their own local copy, and then can pull and push their local into the central repository. 

DVCS provides a powerful and detailed change tracking, which means fewer conflicts at the time of merge.

DVCS gives an ability that developers can share changes with one or two other members of team at a time if they want to get some feedback before showing the changes to everyone.

####What are the main operations in Git and how do they work, esp. clone, commit, merge, push/pull, tag, but also rebase. roll-back? 

Git clone: it clones the repo into a local copy

Git commit: commit the current changes

Git merge: gets two branches and merges the code into one. 

Git push/pull: push changes into the central repository, or pull into your own local version

git rebase: is way to change the commit branch, basically changingt he history itself to represent a different sequence of commits. 

git roll back: is used to revert the head of a branch to a certain commit. 

####You should understand how to perform these and some basic “good practice” 

rebase is bad practice

####You should understand some issues that might arise and how to resolve them (e.g., conflicts) 

Conflicts arise when, pushing changes, or merging them, there is a line in code that have differing changes and git does not know which one is the one that should be changed. 

####When/how often should you commit/merge/push etc? 

Commit, merge and push often. If you practice seperate feature branches, this will not be a problem. Because the branch is your own, issues won't arise. When it comes time for merging, this can be dealt with, but working on your own branch means you can freely commit often, and push often. 

This willr educe the chances of losing work. 

####What are good practice workflows, e.g., branch-per-feature, Gitflow? What are their benefits? How do they support CI/CD

Master branch: which contains final releases.

Dev_branch: is the development branch which keeps up with master. All feature branches will stem from here

Feature_branches: branches that are specific for features being implemented

Hot fix and bug branches: these branches are used to implement quick fixes, seperates from the main code just in case the fix causes more issues. 





### Week 4: Unit Testing, Logging

####What is Test Driven Development? What are its benefits? 

Rules:

- Develop in **small increments**
- Cycle should be in minutes, not hours.
- All tests should fail initially
- Tests are created from concrete requirements

Benefits:

- Increase your confidence in the code's quality
- Better understanding of the requirements
- Bugs are found earlier 
- Code maintenance
- Unit test makes better design since programmar has to understand the features. 
- Low-level regression test unit
- Unit tests demonstrate concrete progress

####What are Mock Objects and what are they used for (multiple reasons)? 

####What are Java Assertions and what are they used for? 

> Mock objects to test functionality, when there exists no real example of the object, it is too difficut to create at that given time, the real object may be actually slow to test and may return non-deterministic values.
>
> e.g. Testing a Loan/Library class the actual time of borrow/return operation can be done by using a mock object (instead of system clock)

####Be prepared to design and write JUnit tests for a simple short program, using @BeforeClass, @Before, etc, testing for Exceptions, etc 

> @Before: on a method to have it run before each test method
>
> @After: on a method to have it run after each method
>
> @BeforeClass: to run it ONCE
>
> @AfterClass: Similar?

####What is Logging useful for? What sort of information should be logged? What are the basics for using the Java Loggger? In particular, how are Levels used?

> The logger contains more features to log specific information, and can timestamp the progression of the tests. This will allow for useful information to be extracted from each test run. 
>
> The logger can filter by 'severity' by:
>
> - Severe
>
> - Warning
>
> - Info
>
> - Fine
>
> - Finer
>
> - Finest
>
>   

###Week 5: Testing and Test/Issue Management

####What is testing for? How is early testing important? 

> Purpose: 
>
> - Demo that the code meets the requirements
> - Discover parts that do not
>
> "Test cannot prove that we have removed bugs, only prove that there EXISTS bugs"

> Early testing is essential, to minimise the cost of fixing errors
>
> Level of cost (low to high)
>
> 1. Design: 1x
> 2. Implementation: 6.5x
> 3. Testing: 15x
> 4. Maintenance: 100x
>
> The cost of fixing errors increases with each shift in the development stage

####What are the different stages of testing and what are the inputs to them? –What is Regression testing and why is it important? 

> Must specify a pass or fail, and define the acceptance criteria
>
> - Start from a known state / configuration
> - Clearly specifiy steps to perform test
> - Specify the expected result which means test "passed"

> Regression Testing: 
>
> is full or partial selection of already executed test cases which are re-done to ensure existing functionalities work fine. This is usually performed once some code changes are implemented. It is very important, it ensures that the old code still works, and that the new changes should not have side effects on the existing functionalities

####What goes into a Test Case description? How/when are users engaged in testing? What are good features of a test case? You should be prepared to design some small number of test cases for a simple application. 


Designed to test 1 aspect of the system. 

| *Test Case ID*        | Unique Test Case Identification Number                       |
| ----------------------- | ------------------------------------------------------------ |
| *Module to be tested* | Module name or Requirement ID, generally used to prepare requirement traceability matrix between test cases and requirement. |
| *Assumptions*         | If any                                                       |
| *Test Data*           | Test data required for executing the test case.              |
| *Test Steps*          | Detailed steps for test case execution.                      |
| *Expected results*    | How application should behave after executing the above testing steps. |
| *Result*              | Pass or Fail                                                 |
| *Comments*            | Add Additional information like screenshot, login credentials, for developer to get the exact information for developer. |

- Use use-cases or stories to design test case at the system level
- Functional requirements may be used to identify different data values
- Must be reproducible - the setup and the steps to perform the test must be precise.

> Designed to test 1 aspect of the system. 
>
> - Use use-cases or stories to design test case at the system level
> - Functional requirements may be used to identify different data values
> - Must be reproducible - the setup and the steps to perform the test must be precise. 

####Why is issue tracking important? What are the different uses for a good bug report? What are the characteristics of a good bug report? You may be required to critique a bug report. 

> It is basically a TO-DO list of known bugs discovered in a the code. It will detail the bug itself, and steps to reproduce the bug. 
>
> This is communicated from the QA team to the Developer team. 
>
> and or User to Developer. 
>
> A report will consist of
>
> - ***Open***
>   - **New**: it has been reported by User, not looked at by the Developer
>   - **Accepted**: accepted to be a valid issue
>   - **In progress**: being worked on by a developer
>   - **Need more info (NMI)**: waiting for more info from user

> - **Closed:**
>   
>   - Fixed;
>   
>   - Verfied Fixed
>    
>     - QA or user has verified that the fix worked
>    
>   - Invalid 
>   
>   - Duplicate 
>   
>   - Will not fix / known shippable 
>   
>     

Severity 

- Scope of the problem, does it crash, block progress, is there workaround or is it annoying

Priority

- 1 Highest - 5 Lowest
- Classfied by User or Developer

####What are the different states/stages a bug goes through? How are bugs ranked? How are Severity and Priority measured?

| SEVERITY: EFFECT OF FAILURE ON THE SYSTEM          | PRIORITY: EFFECT OF FAILURE ON CUSTOMER/ USER |
| :------------------------------------------------- | :-------------------------------------------- |
| 1. Loss of data, hardware damage or a safety issue | 1. Complete loss of value                     |
| 2. Loss of functionality with no work around       | 2. Unacceptable loss of value                 |
| 3. Loss of functionality with a work around        | 3. Possibly acceptable reduction in value     |
| 4. Partial loss of functionality                   | 4. Acceptable reduction in value              |
| 5. Cosmetic or trivial                             | 5. Negligible reduction in value              |

NB: Easier to assign severity, but harder to assign priority. Priority can be adjusted during bug triage. 

### Week 6: Builds

####Why is semi/automating the build process important? Where are the complexities in build processes? What risks are involved with manual builds? 

It is important to semi/automate the build process because it reduces human error. Manual building introduces human error into the process, and slows down development even further. 

####What are the steps in a standard build process? How do build files help us manage dependencies? 

Maven builds as Project Object Model (POM), defined as XML, pom.xml.

It has two components

- a long running process which can execute a simple workflow at regular intervals
- provide a view of the results of the process that have been run
- notifies you of the success or failure of your build and test runs, and provides access to test reports, installers, ...



####What is Maven – not details? What are the extra features of Maven over, say, Ant (in general terms)? In particular, how does Maven manage library dependencies and using up-to-date versions? How are lists of dependencies encoded –You do not need to write Maven code but you should know “how it works” at an appropriate (abstract) level

Maven is better for managing dependencies. Main benefit is its lifecycle. You can just add specific actions on correct phase, which seems pretty logical: just launch yu integrations tests on intergrtion-test phase, which seems pretty logical: just launch the integration test on the IT phase.  Morever, there exists many plugins whicah could do alomst everything. 



| command     | Lifecycle Phases                        | Plugins             |
| ----------- | --------------------------------------- | ------------------- |
| mvn compile | generate-sources, compile, test-compile | Archetype, compiler |
| mvn test    | test, package, integration-test         | Surefire            |

mvn install		 install, deploy											jar install

### Week 7: Continuous Intergration and Delivery 

####What is Continuous Integration (CI)? How does it tie in with Agile process? What problems does it solve / what risks does it reduce? 

CI is a developmental practice that requires developers to integrate code into a shared repository. 

It involves check-ins that then verified by an automated build, allowing teams to detect problems early.

CI ensures that all the time, the product is ready to deploy. In an agile process, it means that it keeps the team in sync by removing integration delays. No gap between operation and developments, automated tests mean its a reliable product, and there is a quicker repsonse to changes without error. 

####Does CI require an automation framework like Travis or Jenkins? How are Git, Maven, and other tools involved? 

CI requires an automation framework, so you can automate the running of code, test and or builds on a 'It  machine'. 

You can utilise TravisCI, to automatically build, and test (based on a configuration) to automate and ensure the current commit is correctly building and passing tests on a consistent environment. 

If your project has NPM and Maven Dependencies, TravisCI will run the Maven and NPM commands in your specified order, to build your project and test if it runs correctly. 

Travis can also, run your pre-defined tests , and will only pass if your current commit has passed all builds with error, and passed all tests. 

####How does a CI process integrate with the code repository? What role does the branch-per-feature/Gitflow model play in Continuous Delivery? 

Everytime a developer commits to a shared repo, it will be passed through a CI configuration that will test the code, and see if it can build with a pre-defined set configuration. This will ensure that, the code that developer has commited adheres to consistent standard and configuration.

CI is integrated within a code repository by running through each check-in through automated build process, and tests. 

The branch-per-feature/Gitflow model can play in CD because a developer can ensure that feature branch is sync with their teammates other work. Or different automation builds can be set up, for different purposes such as one specifically designed for testing. 

For example, perhaps my branch has a overall broken build. Committing to my branch will not affect the deployment branch or the final release branch, as I can experiment with different configurations.

####What are some of the essentials rules for practicing CI / CD? – e.g., why can you never go home on a broken build? 

- Don't check in on a broken build
- Always run all commit tests locally before commiting, or get your CI server to do for you.
- Wait for commit tests to pass before moving on
- Always be prepared to revert to the previous version.
- Time-box fixing before reverting
- Do not comment out failing tests
- Take responsiblity
- Test-Driven Development

####You will not need to know how to write detailed Travis scripts, but you should know generally what it does and how it works, and generally how it encodes workflow (i.e,. via yaml file)

Travis yaml

``` yaml
matrix:
  include:
    - language: java
      jdk: oraclejdk8
      dist: trusty
      before_install: cd restful-web-services/
      install: mvn install
      script: mvn test -B

    - language: node_js
      node_js:
        - 10.16.3
      sudo: required
      services:
          - xvfb
      addons:
        chrome: stable
      before_install:
        # starting a GUI to run tests, per https://docs.travis-ci.com/user/gui-and-headless-browsers/#Using-xvfb-to-Run-Tests-That-Require-a-GUI
        - sudo apt-get install g++ build-essential
        - "export DISPLAY=:99.0"
        - "npm config set spin false"
      before_script:
        - "cd frontend/app"
        - "rm -rf node_modules"
        - sudo apt-get update
        - sudo apt-get install -y libappindicator1 fonts-liberation
        - wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
        - sudo dpkg -i google-chrome*.deb
        - "yarn install"
        - "cd .. && cd .. && ls"
        - "cd restful-web-services"
        - travis_wait 30 nohup mvn spring-boot:run &
      script: 
        - "cd .."
        - "cd frontend/app"
        - "npm rebuild node-sass"
        - "nohup npm start &"
        - sleep 5
        - "npm run test"
        - "npm run wdio"

notifications:
  slack: tomyumsept:PvqV1oTyYrS9OKT0hp2kH4TA
  email: false

```



### Week 8: Deployment via containers / Docker

####Docker and containerization: what is it for, how is it used? 

Docker is a tool designed to make it easier to create, deploy, and run applications by using containers. Containers allow a developer to package up an application with all of the parts it needs. 

####Comparison between Docker containers and standard virtualisation: containerisation is more “lightweight” … why? 

The difference is that Docker container will use the same Linux Kernel as the system that they'r running on and only requires application to be shipped with things not already running on the host computer, rather create a whole virtual operating system. 

####What is the process for creating a Docker container, in the abstract? (You do not have to remember all Docker commands, although you should remember the main operations; knowing the main commands may help to be precise in describing operations.)

docker build --tag=tagname

docker pull 

docker run

docker run -p 4000:80 friendlyhello

> Process of the creating a docker file, 
> 1) Create a docker file (the configuration of the build)
>
> 3) Docker run --name my_first_apache_instance -i -t clever ()
>
> Abstract:
>
> 1) Configuration file is build,
>
> 2) The commands talk the daemon to build the project. If specified, it will talk to the registry and pull 
>
> Scalability:
>
> State-less: no storage is external the container
>
> Vertical: CPUS n Rams (increases the processing power of single container or system to meet increasing demand)
>
> Horizontal: State-less containers (For example App-Engine, when resources are peaked, spin another container) Horizontal Scaling. De-coupling the storage. Kurbernetes facilitates horizontal scaling, handles the networking. 

###Week 9: Design characteristics, patterns, refactoring

####What are some of the important design characteristics and what do they mean, esp coherence and coupling? What are the implications? You should be able to recognise these properties in specific designs and be able to suggest how to achieve them in designs (to a simple degree). 

Coherence refers to how much one class is doing at time. If the class has too many methods, then another class should be created to take those methods as their own. 

Coupling, that refers to the degree of interdepedence between software modules; a measure of how closely connected two routines or modules are. 

####What are some of the “design smells”, the blocks to reusability, extensibility, modifiability --- don’t memorise them all but know how to describe them and why they are a problem. 

Rigidity:

> The system is hard to change because changes in one part will lead to change in other parts (high coupling)

Fragility: 

> System may break in many places due to one change

Immobility: 

>  Parts could useful in other systems, but seperating has high risk

Viscosity: "Doing things right is harder than doing things wrong"

> Development environment is slow and inefficient
>
> Design-preserving methods are moe difficult to use than the hack.

Needless Complexity 

> contains elements that aren't currently useful

Needless repetition

> System has lots of repeated code elements

Opacity 

> System or parts is hard to read and understand

####What are the SOLID principles for? Be prepared to identify why some code violates a SOLID principle and describe a fix. 

SRP: a class has one responsbility. Therefore, when the class begins to grow and increases its responsiblities, its time to make another class to take up that responsibility. 

Open-Closed Principle (OCP): Software Entities (classes, modules, functions, etc) should be open fo extensions but closed for modification.

- Open for extension = behaviour can be extended
- Closed for modification = extending behaviour does not result in changes to the code
- Rely on abstractions: abstract classes, interfaces

Interface Segregation Principle (ISP):



Dependency Inversion Principle (DIP): High-level modules should not depend on low-level modules; both should depend on abstractions. 

Abstractions should not depend in details, details should depend ob abstractions



####What is Refactoring, why is it important/critical in Agile. You do not have to memorise the catalog of Refactoring operations, but you should be able to recognise an opportunity for application of a simple Refactoring operation. 

It is important for applications because within an Agile paradigm, code is constantly developed to a 'working level', and output is constant and fast. Because the level of completion is done to the point in which a feature is 'good enough' refactoring is important to make the code perfect. 



####What are Design Patterns and what is their benefit? What are the motivations for some of them --- i.e., what problems do they solve? You should be able to provide some design, even some simple code to demonstrate understanding (Observer, Factory Method, Facade, Visitor)

Design Patterns Benefits:

- Support reuse
- Communicate successful designs
- Narrow design space
- Focus on design what have been proven to work
- Promote good practice
- Leverage and build on best practice and expertise



### Week 10: NFRs Perfomance Testing

####What are Non-Functional Requirements? How do they relate to System Quality? What are the important System Qualities to design for? 

Constraint of operation of the system. Not what it does but HOW it does.

Example: efficiency, reliability, security and learnability...

####What do we write NFRs? Why is it critical to be specific and precise?? Be prepared to critique and potentially write NFRs for some of the System Qualities (e.g., Performance/Speed, Reliability, Usability) 

We write NFR's to specify how, not just the what. It is critical to be specific because it will greatly effect System qualities such performance, reliability and usability)

####What is Performance Testing? Why is it critical to success of products? What are the risks of not doing it? What aspects of requirements cover it? 

It is to evaluate the system against required performance criteria, comparing between different systems/architectures to find which one performs best, find the source of performance problem.

Using performance test we can find the throughput levels

- Baselines: compare the performance improvements against with your initial performance metric data
- Benchmarks: comparing your system against industry standards

Why: end-users satisfaction, meets desired performance, behaviour of app with various load levels, identify bottle necks, capacity of the app and future resources needed for adequate performance, different configurations to determine which works the best for the app and business. 

Risk-mitigation (reduce) strategies

- Ensure that performance requirements represents needs of real user
- Design workloads representing both normail and peak usage. 
- Use performance tests to inform business and architecture decisions
- Include time-critical transactions in performance test
- **Conduct** some **performance** **test** **under real condition** (while other apps are running…)
- **Measure speeds under various conditions** / loads / scenarios.

Scalabilty-related risks

- Does the application have consistent and acceptable repsonse for all users
- Does it hold the all the data over the life of the app
- Will the app be secure over heavy usage.
- Can it. handle unexpected loads?
- Can the app respond to DoS attack?

####What are the aims of performance testing? What are the different sorts of performance testing? What does each one hope to discover/explore? 

Capacity planning: provide actal data to capacity planners, and determines the current usaefe and capacity.

Component testing: provides information to tune the component-leve performance

Endurance testing: detects slow memory leaks / insufficient storage capacity,..

Investigative Testing: Collects useful information at various development stages
Load testing	Determines throughput at expected loads.
Also used to gather statistics at various loads
Smoke testing	Quick assessment of current performance
Quickly finds obvious performance issues
Spike testing	Detects memory leaks / disk I/O problems
Identifies problems with returning to steady state
Stress testing	Determines behaviour at overstressed levels
Estimates extremes of system capabilities

####What are some of the steps of doing performance testing? Why does the data used need to be carefully designed? What do we risk if we do not vary the data? 

1. Identify testing environment
2. Performance Acceptance Criteria
3. Plan and Design Tests
4. Execute the Tests
5. Analyze result and report

####Why do we use automated tools to do performance testing? Why is it important to test different Loads? How do we do this?

It is important to automate the the testing, to keep the testing consistent 



### Other Expectations

You are expected to know about anything that you may have been expected to do in any of your assessment work, e.g., knowledge of some task-planning / version control / bug-management tool

You will NOT be asked details about programming frameworks you used in your assignment (i.e., Springboot, React). Any programming will be short and focused on lecture concepts (e.g., unit tests, design patterns) 

Some sample exam-style questions (i.e., from old exams) are available on Blackboard. Do the questions BEFORE checking the solutions---this makes for MUCH BETTER learning than just reading solutions!!
