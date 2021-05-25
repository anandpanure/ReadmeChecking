![App Logo](Images/KatalonSafalPlugin1.jpg)


**TestCase generation tool for SAFAL**

As we know about Keyword Driven Testing is a scripting technique that uses data files to contain the keywords related to the application being tested. These keywords describe the set of actions that is required to perform a specific step. Here, every testing action like opening or closing of browser, mouse click, keystrokes, etc. is described by a keyword such as openbrowser, click, Typtext etc. To form a Test case or a scenario, Tester used to write all the test steps manually. But from now, A Tester just need to record the scenario by  using our recording tool and export it into json format. Whatever the steps tool has recorded will be converted into Safal Test scripts.

**In this project we will be aiming to address the following:-**

 - Recording the user's action on the browser.
 - Generating  SAFAl Test Script.
 - Running the recorded steps by using SAFAL.

****A platform to convert the MAPL to High Level Language** 

## Problem solved

 - Provide automation to reduce manual efforts of writing test cases in SAFAL
 - Automatically find the element in DOM by using xPath or CSS
 - No need of technical skills.
 - Saving a lot of time by writing test steps automatically in Excel.
 - Fast and Simple
  

## How it works

* User record test scenario using Katlon recorder and export it in a json format
* A mapper is used to map the recorder actions to Safal actions

* Tool will take the exported json file and converted into Safal Test Scripts


### Architecture

![Architecture](Images\architecture.png)

## Technologies Used

Auto-generation programming Tool uses a number of technologies to work properly:

* [Safal Client](https://safal.fis.dev/SAFALClient/) -In-house automation offering
* [Katalon Recorder](https://www.katalon.com/katalon-recorder-ide/) - Selenium IDE based Katalon Recorder Plugin.
* [.Net Framework](https://docs.microsoft.com/en-us/dotnet/fundamentals/) - .Net Framework for Plugin and Windows Service.
* [Closed XML](https://github.com/ClosedXML/ClosedXML) -Open Source Library for Excel Operations.
* [JSON](https://en.wikipedia.org/wiki/JSON)-an open standard file format, and data interchange format, that uses human-readable text to store and transmit data objects consisting of attribute–value pairs and array data types

## WoW factor

Currently we spend too much effort writing the test cases for Safal. Our solution will reduce manual efforts of writing test cases for SAFAL. It revolutionizes the efforts put in by teams using the in-house Safal Automation tool for their workflows and will impower Business Analysts and Clients to record their test case Scenario.Utlimately reduces the overall time and efforts consumed by manual intervention.

