## Software Test Automation - Amazon

## Project Description -

#### This project automates the manual testing process by validating various test cases such as login functionality of [Amazon](https://amazon.com) search input functionality and so on. The project begins with first preparing the test cases with their expected functionalities and then the test cases are converted to test scripts with the help of [Katalon Studio Web Recorder and Playback](https://katalon.com/). The same test cases are then run against different data formats such as csv or xls to perform data-driven testing. For the build delivery Katalon Studio is integrated with Git and Jenkins. For testing cross-browser interoperability of the test cases Katalon TestCloud is used. And finally, test report is generated.

## Tech stacks used -
* Katalon Studio 
* Git 
* Jenkins
* Katalon TestCloud 

## Test cases automated - 
* Valid Amazon Login 
* Invalid Amazon Login
* Amazon logo on home page
* Footer link 
* Hyperlinks present
* List of countries available

## Data-driven testing
#### To check whether what forms of data is parsed and executed by the application, data-driven testing can be performed. In this project I have used MS Excel data and CSV data to perform automated testing on Amazon login test case. The data files used for login test cases can be found [here](https://github.com/smartinternz02/SI-GuidedProject-705495-1706965358/tree/main/Data%20Files) and the corresponding test suite collection for CSV and xls data format can be found [here](https://github.com/smartinternz02/SI-GuidedProject-705495-1706965358/tree/main/Test%20Suites)

## Cross-Browser Testing
#### For testing interoperability with different Operating Systems and Browsers, Katalon Studio provides Katalon TestCloud that can be used to execute the same test cases across different environments. The test suite for cross-browser testing is available [here](https://github.com/smartinternz02/SI-GuidedProject-705495-1706965358/tree/main/Test%20Suites)

## Jenkins Integration with Katalon
#### Jenkins is used to automate build schedules with the help of Katalon Runtime Engine(KRE). The command script can be generated for any test suite in the Katalon Studio which then can be used to execute from Jenkins using the option of running Windows batch commands to start the build process. After the build process is executed via Jenkins, the test report is sent to Katalon TestOps. Here is the output of the console generated during the build process from [Jenkins](https://github.com/smartinternz02/SI-GuidedProject-705495-1706965358/tree/main/Jenkins_Katalon_Integration)

## Test Reports
#### The test report is generated from running different test suite in this project. Here the test reports generated in this [project](https://github.com/smartinternz02/SI-GuidedProject-705495-1706965358/tree/main/Reports)