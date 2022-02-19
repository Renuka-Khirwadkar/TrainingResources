
### Training Requirement

**Tools Required For Training**   

**Java+Selenium**    
Java 1.8 (Minimum Version)      
Eclipse Latest version    

**API** 
SOAP UI-Community edition( 5.6.0)  
POSTMAN

**Appium**    
Android Studio   
Appium Server  
Appium Inspector  

**Git**   
Git Bash exe  

***********************************************************************

**Usefull Links**    
Selenium Demo Sites   
https://demo.guru99.com/test/newtours/    
https://rally1.rallydev.com/slm/login.op    
https://www.saucedemo.com/inventory.html    
https://demoqa.com/text-box   

**XPath Docs**      
http://www.cheat-sheets.org/saved-copy/Locators_table_1_0_2.pdf   

**WebDriver Manager**   
https://github.com/bonigarcia/webdrivermanager    

**TestNG**      
https://testng.org/doc/eclipse.html   
https://testng.org/testng-eclipse-update-site/    
https://testng.org/doc/documentation-main.html#introduction   

**URL: Postman**      
https://github.com/vdespa/quick-introduction-to-postman/blob/main/simple-tool-rental-api.md#Get-a-single-order    
https://learning.postman.com/docs/writing-scripts/script-references/test-examples/    

**SOA**  
https://www.youtube.com/watch?v=7s_S5Hkm7z0
https://medium.com/@SoftwareDevelopmentCommunity/what-is-service-oriented-architecture-fa894d11a7ec  
https://en.wikipedia.org/wiki/Service-oriented_architecture  
https://www.geeksforgeeks.org/service-oriented-architecture/  

**SOUPUI**      
https://www.soapui.org/docs/scripting-and-properties/tips-tricks/   
https://petstore.swagger.io/    
http://www.dneonline.com/calculator.asmx?WSDL   
https://jar-download.com/?search_box=jxl    

**Appium**
Download link for dummy app:    
https://github.com/appium/appium/blob/master/sample-code/apps/ApiDemos-debug.apk  

https://stackoverflow.com/questions/49005791/how-to-check-if-intel-virtualization-is-enabled-without-going-to-bios-in-windows#:~:text=2%20Answers&text=If%20you%20have%20Windows%2010,is%20currently%20enabled%20in%20BIOS.

https://github.com/appium/appium/blob/master/docs/en/writing-running-appium/caps.md

**Project Links**   
[Selenium API Learning](https://github.com/gsumit1/SeleniumDemo)  
[Cucumber Project](https://github.com/gsumit1/CucumberBDD)     
[Test NG Project](https://github.com/gsumit1/TestNGProject)  
[RestAssured Project](https://github.com/gsumit1/RestAssuredTrainingCode)  
[SOAPUI](https://github.com/gsumit1/SOAPUI_Projects)  
[Appium Learning API](https://github.com/gsumit1/AppiumLearning) 
[Appium Project+TestNG](https://github.com/gsumit1/AppiumProject)  


***Assignment-01***
~~~
For Sauce Lab Site: https://www.saucedemo.com   
 @scenario1   
  Scenario: To verify adding multiple options in cart and checkout    
    Given user is on saucedemo homepage   
    And user logged in using correct credential   
      | username      | password     |    
      | standard_user | secret_sauce |    
    And user adds required item to cart   
    And user proceeds to checkout   
    And user enters the following details for checkout    
      | FirstName | LastName | PostalCode |   
      | abc       | def      |     400087 |   
    When user confirm checkout    
    Then user verify final confirmation messagge    
      
  @scenario2    
  Scenario: To verify adding removing then adding and checkout      
    Given user is on saucedemo homepage   
    And user logged in using correct credential     
      | username      | password     |    
      | standard_user | secret_sauce |    
    And user adds one item and then remove that item to go back   
    And user adds required item to cart   
    And user proceeds to checkout   
    And user enters the following details for checkout    
      | FirstName | LastName | PostalCode |   
      | abc       | def      |     400087 |   
    When user confirm checkout    
    Then user verify final confirmation message   
      
  @scenario3    
  Scenario: To verify sort low to high    
    Given user is on saucedemo homepage   
    And user logged in using correct credential     
      | username      | password     |    
      | standard_user | secret_sauce |    
    And user sorts item low to high   
    And user adds required item to cart   
    And user proceeds to checkout   
    And user enters the following details for checkout    
      | FirstName | LastName | PostalCode |   
      | abc       | def      |     400087 |   
    When user confirm checkout    
    Then user verify final confirmation message   

**Assignment 2: Assured Rest**    

URL: https://simple-tool-rental-api.glitch.me   
Design E2E flow:      
1. Generate bearer token using /api-clients   
2. Create order using using end point /orders   
~~~        
**Assignment 3: SOAP UI**     

http://thetestingworldapi.com/Help      

  studentsDetails     
  API	Description     
  GET api/studentsDetails:	Read All Student Info     
  GET api/studentsDetails/{id}:	Read Specific Student info      
  PUT api/studentsDetails/{id}:	Update individual Student info      
  POST api/studentsDetails:	Create a record for new Student     
  DELETE api/studentsDetails/{id}:	Delete the created Student      

Design E2E flow:      

1. Using post create an student 
2. Read the newly created student info  
3. Update Student info using PUT  
4. Read again the updated info  
5. Delete the student  

**Assignment-04**
Appium+TestNG assignment.
Please automate the following scenarios using the sample Sauce Lab app.
https://github.com/saucelabs/sample-app-mobile/releases/download/2.7.1/Android.SauceLabs.Mobile.Sample.app.2.7.1.apk
~~~
For Sauce Lab Site: https://www.saucedemo.com   
 @scenario1   
  Scenario: To verify adding multiple options in cart and checkout    
    Given user is on saucedemo homepage   
    And user logged in using correct credential   
      | username      | password     |    
      | standard_user | secret_sauce |    
    And user adds required item to cart   
    And user proceeds to checkout   
    And user enters the following details for checkout    
      | FirstName | LastName | PostalCode |   
      | abc       | def      |     400087 |   
    When user confirm checkout    
    Then user verify final confirmation messagge    
      
  @scenario2    
  Scenario: To verify adding removing then adding and checkout      
    Given user is on saucedemo homepage   
    And user logged in using correct credential     
      | username      | password     |    
      | standard_user | secret_sauce |    
    And user adds one item and then remove that item to go back   
    And user adds required item to cart   
    And user proceeds to checkout   
    And user enters the following details for checkout    
      | FirstName | LastName | PostalCode |   
      | abc       | def      |     400087 |   
    When user confirm checkout    
    Then user verify final confirmation message  
