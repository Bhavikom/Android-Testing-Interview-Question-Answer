# Android-Testing-Interview-Question-Answer

**1. Types of Software Testing ?**


  In this section, we are going to understand the various types of software testing, which can be used at the time 
  of the Software Development Life Cycle.
  As we know, software testing is a process of analyzing an application's functionality as per the customer prerequisite.
  
  If we want to ensure that our software is bug-free or stable, we must perform the various types of software testing because 
  testing is the only method that makes our application bug-free.
  
  ![types-of-software-testing](https://user-images.githubusercontent.com/35212651/219291961-f5019584-6bc9-4c59-8b14-b39ea3d73489.png)

  There are mainly two types of testing.
  
  1.Manual Testing
  2.Automation Testing
  
  *1. Manual Testing
  
  Testing any software or an application according to the client's needs without using any automation 
  tool is known as manual testing.
  In other words, we can say that it is a procedure of verification and validation. Manual testing is used 
  to verify the behavior of an application or software in contradiction of requirements specification.
 
  Classification of Manual Testing:
  
    1.White Box Testing
    2.Black Box Testing
    3.Grey Box Testing
    
    1.White Box Testing : 
    
    In white-box testing, the developer will inspect every line of code before handing it over to the testing team or the concerned test engineers.
    
    2.Black Box Testing :
    
    Another type of manual testing is black-box testing. In this testing, the test engineer will analyze the software against requirements, 
    identify the defects or bug, and sends it back to the development team.
    
        Types of Black Box Testing
        Black box testing further categorizes into two parts, which are as discussed below:
        
        1.Functional Testing
        2.Non-function Testing
        
        1.Functional Testing : 
        The test engineer will check all the components systematically against requirement specifications is known as functional testing. 
        Functional testing is also known as Component testing.
        
        In functional testing, all the components are tested by giving the value, defining the output, and validating the actual 
        output with the expected value.
        
        Functional testing is a part of black-box testing as its emphases on application requirement rather than actual code. 
        The test engineer has to test only the program instead of the system.
        
            Types of Functional Testing
            The diverse types of Functional Testing contain the following:

            Unit Testing
            Integration Testing
            System Testing
            
        2.Non-function Testing :
        
            Non-functional testing will help us minimize the risk of production and related costs of the software.
            Non-functional testing is a combination of performance, load, stress, usability and, compatibility testing.
            
            Types of Non-functional Testing
            Non-functional testing categorized into different parts of testing, which we are going to discuss further:

            1.Performance Testing
            2.Usability Testing
            3.Compatibility Testing
    
    3. Grey Box Testing : 
    
    Another part of manual testing is Grey box testing. It is a collaboration of black box and white box testing.

    Since, the grey box testing includes access to internal coding for designing test cases. Grey box testing is 
    performed by a person who knows coding as well as testing.

    Types of Software Testing
    In other words, we can say that if a single-person team done both white box and black-box testing, it is considered grey box testing.
    
  *2. Automated Testing
  
  The most significant part of Software testing is Automation testing. It uses specific tools to automate manual design 
  test cases without any human interference.

  Automation testing is the best way to enhance the efficiency, productivity, and coverage of Software testing.

  It is used to re-run the test scenarios, which were executed manually, quickly, and repeatedly.

 
**1. What is Manual and Automated Testing ?**


  *manual Testing*

    Manual testing is the process in which QA analysts execute tests one-by-one in an individual manner. 
    The purpose of manual testing is to catch bugs and feature issues before a software application goes live.
    When manually testing, the tester validates the key features of a software application. 
    Analysts execute test cases and develop summary error reports without specialized automation tools. 

    How Manual Testing Works
    Manual testing is very hands-on. It requires analysts and QA engineers to be highly involved in everything from test 
    case creation to actual test execution. 
  
  *Automated Testing*

    Automation testing is the process in which testers utilize tools and scripts to automate testing efforts.
    Automation testing helps testers execute more test cases and improve test coverage. 
    When comparing manual vs. automation testing, manual takes longer. Automated testing is more efficient.
  
    How Automated Testing Works
    Automation testing involves testers writing test scripts that automate test execution. (A test script is a set of instructions 
    to be performed on target platforms to validate a feature or expected outcome.)
  
**2. Top Android App Automation Testing Tools & Frameworks ?**


    1. Appium
    2. Selendroid
    3. Calabash
    4. Espresso
    5. Detox
    6. UI Automator


**3. Types of Software Testing ?**


  *1. Unit Testing*
 
    Unit testing is a method of testing individual units or components of a software application. It is typically done by developers 
    and is used to ensure that the individual units of the software are working as intended. Unit tests are usually automated and are 
    designed to test specific parts of the code, such as a particular function or method. Unit testing is done at the lowest level of 
    the software development process, where individual units of code are tested in isolation.
  
  *2. Integration Testing
  
    Integration testing is a method of testing how different units or components of a software application interact with each other. 
    It is used to identify and resolve any issues that may arise when different units of the software are combined. Integration testing 
    is typically done after unit testing and before functional testing, and is used to verify that the different units of the 
    software work together as intended.
  
  *3. Regression Testing
  
    Regression testing is a method of testing that is used to ensure that changes made to the software do not introduce new bugs or 
    cause existing functionality to break. It is typically done after changes have been made to the code, such as bug fixes or new 
    features, and is used to verify that the software still works as intended.
  
  *4. Smoke Testing
  
    This test is done to make sure that the software under testing is ready or stable for further testing 
    It is called a smoke test as the testing of an initial pass is done to check if it did not catch the fire or smoke in the initial switch on. 
  
  *5. Alpha Testing
  
    This is a type of validation testing. It is a type of acceptance testing which is done before the product is released to customers. 
    It is typically done by QA people. 
  
  *6. Beta Testing
  
    The beta test is conducted at one or more customer sites by the end-user of the software. This version is released for a limited 
    number of users for testing in a real-time environment 
  
  *7. System Testing
  
    This software is tested such that it works fine for the different operating systems. It is covered under the black box testing technique. 
    In this, we just focus on the required input and output without focusing on internal working. 
    In this, we have security testing, recovery testing, stress testing, and performance testing 
  
  *8. Stress Testing
  
    In this, we give unfavorable conditions to the system and check how they perform in those conditions. 
  
  *9. Performance Testing
  
    It is designed to test the run-time performance of software within the context of an integrated system. 
    It is used to test the speed and effectiveness of the program. It is also called load testing. 
    In it we check, what is the performance of the system in the given load.
    
  *10. Sanity Testing
  
    It is used to ensure that all the bugs have been fixed and no added issues come into existence due to these changes. 
    Sanity testing is unscripted, which means we cannot documented it. It checks the correctness of the newly added features and components.
  
  
**4. Differences between Black Box Testing vs White Box Testing ?**

    Software Testing can be majorly classified into two categories: 
 
    Black Box Testing is a software testing method in which the internal structure/design/implementation of the item being 
    tested is not known to the tester. Only the external design and structure are tested.
 
    White Box Testing is a software testing method in which the internal structure/design/implementation of the item being 
    tested is known to the tester. Implementation and impact of the code are tested.

