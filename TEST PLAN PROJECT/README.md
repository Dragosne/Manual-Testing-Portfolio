<h1>TESTING PROJECT</h1>

<h1>for IT Factory Manual Testing Course</h1>

The scope of the final project for ITFactory Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application

Application under test: [Guru99 Banking WebApp](https://demo.guru99.com/V4/index.php)

Tools used: Jira, Zephyr Squad.

<h2 align="center">TABLE OF CONTENT:</h2>
   
1. [Introduction](#introduction)
   - [Functional Specifications of Project](#functional-specifications-of-project)
   - [Complete Documentation](#complete-guru99-banking-software-requirements-specifications)
   - [Project Release](#functionalities-and-tests-out-of-scope)
3. [Test Process](#.)
   - [Test Planning](#test-planning)
     - [Roles asigned to the project and persons allocated](#Roles-asigned-to-the-project-and-persons-allocated)
     - [Test Criteria](#test-criteria)
       - [Entry Criteria](#entry-criteria)
       - [Exit Criteria](#exit-criteria)
       - [Suspension Criteria](#suspension-criteria)
     - [Test Scope](#test-scope)
       - [Test IN Scope](#test-in-scope)
       - [Test NOT IN Scope](#test-not-in-scope)
     - [Risks](#risks-detected)   

*******************
   - [Test Analysis](#test-analysis)
   - [Test Design](#test-design)
   - [Test Implementation](#test-implementation)
   - [Test Execution](#test-execution)
   - [Test Closure](#test-closure)
   - [Test Monitoring and Control](#test-monitoring-and-control)
5. [Test Deliverables](#test-deliverables)
   - [Test Conditions](#test-conditions)
   - [Test Cases](#test-cases)
   - [Daily Test Summary Reports](#daily-test-summary-reports)
   - [Traceability Matrix](#traceability-matrix)
   - [Test Case Results](#test-case-results)
   - [Bugs Report](#bugs-report)
   - [Test Completion Report](#test-completion-report)
   - [Schedule](#schedule)

<h1 align="center">INTRODUCTION</h1>

This test plan describes the methods and procedures that will be used in the testing procedures of the project.
The objective of the testing activities is to check functions and features provided by the guru99 net banking facilities offered to its customers in order to raise the trust in the quality of the product as high is possible before the application release. 

The purpose of this testing plan is to be used and followed during the testing process and to identify which items and feature will be tested, the types of testing would be performed, the resources and the personnel required for testing process, the risks associated and the schedule to complete the testing process.

## FUNCTIONAL SPECIFICATIONS OF PROJECT

The below story was created in Jira and describes the functional specifications of the "**New Customer, Edit Customer and Delete Customer**" modules, for which the final project is performed upon.

![image](https://github.com/Dragosne/Manual-Testing-Portfolio/blob/main/TEST%20PLAN%20PROJECT/ProjectImages/Jira%20specificattions.jpg)
![image](https://github.com/Dragosne/Manual-Testing-Portfolio/blob/main/TEST%20PLAN%20PROJECT/ProjectImages/story%20edit%20customer.png)
![image](https://github.com/Dragosne/Manual-Testing-Portfolio/blob/main/TEST%20PLAN%20PROJECT/ProjectImages/story%20delete%20customer.png)

### COMPLETE GURU99 BANKING SOFTWARE REQUIREMENTS SPECIFICATIONS

For complete "**Documentation**" please, click here: [**Guru99-SRS_v1.3**](https://github.com/Dragosne/Manual-Testing-Portfolio/blob/main/TEST%20PROJECT/Guru99%20Banking%20SRS_v1.pdf)

## PROJECT RELEASE

Here you can find the release that was created for this project:

**(inserati aici o poza cu release-ul pe care l-ati creat in jira. Atentie, release-ul nu va contine si teste, ci doar epic-uri, story-uri, task-uri, subtaskuri si bug-uri)**

###### .

<h1 align="center">TESTING PROCESS</h1>

The test process was performed based on the standard test process as described below.

## TEST PLANNING

The Test Plan is designed to describe all details of testing for "New Customer" module of Guru99 Banking WebApp

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan. The test plan that was created for this project can be found here: [**COMPLETE TEST PLAN**](https://github.com/Dragosne/Manual-Testing-Portfolio/blob/main/TEST%20PROJECT/!PROIECT%20ITFACTORY%20TEST%20PLAN.pdf)

### ROLES ASIGNED TO THE PROJECT AND PERSONS ALOCATED

<ul>
  <li>Project manager: John Smith </li> 
  <li>Product manager: Krishna Rungta</li>
  <li>Software developer: Tom Patrick</li>
  <li>QA Engineer: Dragos Nechifor</li>
</ul>

### TEST CRITERIA

#### TEHNIQUES 

Execute each use case, use-case flow, or function, using valid and invalid data, to verify the following: 
- The expected results occur when valid data is used.
- The appropriate error or warning messages are displayed when invalid data is used
- Each rule is properly applied. 

#### ENTRY CRITERIA 

-	The application construction is completed. 
-	The guru99 server is functional and the web banking app is available for testing. 
-	Necessary devices, instruments, and other equipment are acquired. 
-	Test environment is prepared, and the application is released to the test environment.
-	Test specification is created

#### EXIT CRITERIA

- all the test have been executed
- 90% of test are passed
- all reported bugs have been fixed and retested
- no critical issues have Open status.

#### SUSPENSION CRITERIA 

- the web server is unstable
- 40% of test cases failed suspend testing util the development team fixes all the failed cases

### TEST SCOPE

#### TESTS IN SCOPE

- All the features of New Customer, Edit Customer, and Delete Customer module defined in Guru99 business requirements will be tested using functional testing and GUI testing.
- A manager can add a new customer
- To check if the same Email Id exist in the system, system shows an error
- To ensure that new customers can successfully register and access the Guru99 Bank services
- The banking site it is compatible with Chrome version 27 and above

#### TESTS NOT IN SCOPE

- Non-functional testing like stress, performance is beyond the scope of this project.
- Automation testing is beyond scope.
- No QA support for mobile applications developed. Only web applications will be tested.

### RISKS DETECTED

#### PROJECT RISKS:

- Limited number of persons in the team
- The project schedule is too tight; it's hard to complete this project on time
- A lack of cooperation negatively affects your employees' productivity
  
#### PRODUCT RISKS:

- Server Stability risks (crashes, disconnects, etc)
- The Guru99 Bank App is not intuitive and easy to understand.
- Some of the Guru99 Bank users may not have adequate computer knowledge to use the site.
- Validation constraints on the fields might be too restrictive to the end-user
- Data validation errors
- New browser might not be supported

#### EVALUATING ENTRY CRITERIA

The entry criteria defined in the Test Planning phase have been achieved and the test process can continue.

*********************

<h3>1.2 Test Monitoring and Control<h3>

**(inserati aici motivul pentru care a fost facuta etapa de monitorizare si control si respectiv cum s-a facut aceasta etapa. Aici veti insera de asemenea si raportul de status (test status report) din zephyr - test metrics - primul din lista care sa reflecte activitatea si evolutia testarii. Recomand aici sa executati teste aproape in fiecare zi ca sa vada angajatorul implicarea voastra in testare)**

<h3> 1.3 Test Analysis </h3>

The testing process will be executed based on the application requirements.

The following test conditions were found: <br>

For each field of New Cutomer Menu:
- Tehnical requirements for each field are met
- Fields functions with valid and invalid data (characters, special characters, blank, space)
- The error messages are displayed correctly
- The inserted data (valid or invalid) will be validated
- Fields lenght

For the New Customer module:
- UI test
- The functional validation is met
- The functional validation is met
- A new customer can be created and saved in database
- Tehnical requirements for the module are met

![image](https://github.com/Dragosne/Manual-Testing-Portfolio/blob/main/TEST%20PLAN%20PROJECT/ProjectImages/testCasesTitles.png)

<h3>1.4 Test Design</h3>

Functional test cases were created in Zephyr Squad based on the analysis of the specifications. 
The test cases can be accessed here:<br> 
[**TEST CASES .csv**](https://github.com/Dragosne/Manual-Testing-Portfolio/blob/main/TEST%20PLAN%20PROJECT/ProjectImages/ZFJ-Cycles-02-27-2024.csv); 

<h3>1.5 Test Implementation</h3>

The following elements are needed to be ready before the test execution phase begins:

- The test cases are written for the application module to be tested
- The environment is ready to start the testing process:
   - Internet connection (good and stable; at list 5mbs specified, 15mbs at a minimum recommended),
   - Desktop or laptop computer, minimum requirements: windows 7 or MacOS Sierra or above; 4GB RAM; CPU 3.4Ghz,
   - Google Chrome ver27 or above installed,
- The Guru99 web app server and database server are intalled, available and online,
- The credentials for app login are provided.

<h3>1.6. Test Execution </h3>

Test cases are executed on the created test Cycle summary: **Release 3.0/Guru99 Bank Web App Testing**

Bugs have been created based on the failed tests. The complete bug reports can be found here: [**BUG REPORTS .csv**](https://github.com/Dragosne/Manual-Testing-Portfolio/blob/main/TEST%20PLAN%20PROJECT/ProjectImages/BugsDetails.csv)

The following is a summary of the bugs that have been found
![**Jira Bug List**](https://github.com/Dragosne/Manual-Testing-Portfolio/blob/main/TEST%20PLAN%20PROJECT/ProjectImages/bugList.png)

Full regression testing is needed on the impacted areas after the bugs are fixed and retesting will be done for every functionality that was previously failed.

1.7 Test Completion
As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team

The traceability matrix was generated and can be found here: **(inserati aici fie o poza cu matricea de trasabilitate din jira, fie linkul catre fiserul excel exportat din jira cu matricea de trasabilitate. Nu uitati sa faceti filtrare dupa type = story)**

Test execution chart was generated and can be found below. 

**(inserati aici raportul de executie generat din jira din sectiunea de dashboards)**

The final report shows that a number **(inserati numarul de teste)** tests have failed of a total of **(inserati numarul de teste)**

A number of **(inserati numarul de bug-uri)** total bugs were found, from which the priority is: **(inserati numarul de bug-uri)** are high and **(inserati numarul de bug-uri)** are medium.

**(inserati aici o concluzie generala a testarii care sa cuprinda cate teste au fost create si executate, ce procentaj aproximativ din cerintele in scop au fost acoperite, daca exista vreo functionalitate pe care nu ai apucat sa o testezi, daca bug-urile gasite impacteaza lansarea produsului in productie sau se pot fixa si ulterior, daca ai identificat riscuri de produs care trebuie mitigate, daca e vreo reecomandare pe care vrei sa o faci pentru lansare, daca sunt ceva lessons learned de care trebuie sa se tina cont la proiectele viitoare etc.)**
