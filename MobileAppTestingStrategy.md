**Mobile app testing strategy**

***Strategy no: 1 Cross-Platform Testing***
There are different types of mobile OS available in the market. The main being android and iOS.
It is essential to plan to test the mobile application on all platforms to ensure the application works as expected on all platforms.
Most applications will have a separate code set for android and iOS, hence it is important to test the application cross-platform to find any issues.


***Strategy no: 2 Functionality Testing*** 
The main testing has to be related to the functionality of the application that we are developing.
The USP for any application is how well it performs the task it is intended to. So, it is very important to test to complete functionality in and out.
Every flow in the application needs to be tested to ensure there are no broken functionalities or flows.


***Strategy no: 3 Type of application***
There are mainly 3 types of mobile applications   
 		Native application – the ones developed specifically for the Android or iOS platform    
    Mobile Web application – browser-based applications on the mobile phone and   
 		Hybrid – a mix of the above two   
While planning for testing, good coverage is needed for all three types of applications to ensure stability and performance.

***Strategy no: 4 UI and UX testing*** 
The user interface (UI) and user experience (UX) are the next things that need to be planned well without fail.
The user interface is what the users see and how they interact with your mobile application.
The UI should be designed in a way that it is to understand and navigate through the app for all categories of users.
Similarly, for UX also the navigation between the pages and the time taken to generate the reports of output as per the application 
should be well within the pre-defined SLA.With the numerous mobile apps available in the market today, your app may not get a second chance
if the consumer or end-user does not like it.

***Strategy no: 5 Backend Testing***
Backend testing is done to ensure the data is getting stored in the right places and in the right format.
During the testing, we need to ensure that the data entered by the user is saved correctly, against the right profile, and also it should be easily retrievable.
Backend testing also involves checking the different places where the data is saved and reflected in the application and that it is done correctly.
Saving and retrieving the correct user profile would be another major use case for backend testing.

***Strategy no: 6 Network compatibility Testing***
Mobiel applications behave according to the variances in internet strength
In this case, network compatibility testing needs to be included in your test strategy as well.
This will include testing the application in different network configurations like with data and wifi.
Different signal strength, bandwidth, and then measuring the TPS (transactions per second) to see if is within the planned SLA.


***Strategy no: 7 Storage Testing***
Storage testing has become an important part of the mobile app testing strategy very recently.
With the growing number of apps being used and limited space available for use.
People tend to avoid apps that need too much space to download or more data to use.
Thus it is important to check and rectify these parameters for better acceptance from the end-users.

***Strategy no: 8 Data flow testing***
Most mobile applications are not stand-alone and need one or the other input from systems and servers outside the app.
It thus becomes an important part of the strategy to include the testing of the data flow from one system to the other.


***Strategy no: 9 Localization Testing***
While this may not be needed for all apps, if needed it would be good to have in your strategy.
Localization testing involves testing the application for location-based parameters like language, maps, and any other things related to the locations. These are sometimes legal requirements also for some locations.

***Strategy no: 10 Device Testing:*** 
There are a plethora of devices in existence now. To make sure that your app is working fine on all of them you need to check the app’s performance, functionality, and UI on real devices.It’s a challenging as well as a daunting task. And there are thousands of devices with varied screen size out there. So in this situation depending on emulators has been seen as a common practice.But it’s true that emulators are not an absolute solution. So the perfect solution here would be to test the app in screen size that’s commonly used and then for other options use emulators.

-----------------------------------------------------------------------------------------
**Mobile APP Test Pyramid

<img src="https://marvel-b1-cdn.bc0a.com/f00000000131077/www.perfecto.io/sites/default/files/image/2021-05/image-testing-pyramid-purple_0.jpg" width="800" height="600">

~~~
The testing pyramid is a concept that groups software tests into three different categories. 
This helps developers and QA professionals ensure higher quality, reduce the time it takes to find the root cause of bugs,  
and build a more reliable test suite. 

The testing pyramid is a concept that strategically groups software tests into different categories.From top to bottom, the main layers include: 

UI/exploratory tests  
Integration tests  
Unit tests  

~~~
The following image shows how in the world of mobile testing, the pyramid also lends insights into the types of devices your team should use for each testing layer.

The lower portion of the pyramid is more automated, making those tests faster. The top of the pyramid is for slower and more manual test scenarios. The higher you go on the pyramid, the fewer the tests. In other words, teams should have many unit tests, which are small and isolated, and not so many end-to-end exploratory tests, which are time-consuming and manual. Frontloading tests at the unit level makes fixing bugs quicker and easier, as opposed to defects that are discovered much later in the process.

**The Testing Pyramid Base: Unit Testing**
The base of the pyramid is unit testing. The scope of unit tests is small — and they ensure that isolated units of code work as they should. Unit tests should test one variable and not rely on any external dependencies. In this layer of the pyramid, tests are executed pre and post-commit. Tests are dev triggered. 

***Which Devices To Use*** For these tests, it is recommended to use virtual devices — simulators and emulators. Executing these tests on virtual devices is sufficient and provides the necessary feedback and debugging/log information. Plus, virtual devices offer the benefits of being faster and more cost-efficient for testing.

**The Middle Stage: Integration Testing**
In the middle of the pyramid, you test across integrations of more than one system. Unlike unit tests, these tests are CI-triggered. In this stage, you have more features to cover and more testing types to conduct.

***Which Devices To Use***
With integration testing, it is critical to get the right balance of real and virtual devices.Some types of testing, such as acceptance testing, can be done on virtual devices. However, other types of tests, such as performance testing, security testing, and certain accessibility features, cannot be done on virtual devices, so it is best to use a mix of real and virtual devices at this stage.You will also want to add additional real device/OS configurations that match the client usage analytics and market trends. You can get device/OS usage data in our Test Coverage Index. Using both real and virtual devices in your testing strategy is a best practice. Real and virtual devices complement each other and support your goal of achieving high-quality builds for nightly regressions.

**The Top of the Test Automation Pyramid: UI & Exploratory Tests**
The top layer of the pyramid is for UI and exploratory tests. These tests generally are more complicated, and have more dependencies than unit and integration tests. While teams can speed up UI testing with automation, exploratory testing is typically done manually and takes longer.

*Keeping in mind the shape of the pyramid, the tests in this section should be far fewer than those at the base.*

***Which Devices To Use***
Once you get to production monitoring at the top of the pyramid, testing must be done on real devices.

*Why? End-to-end testing, as well as exploratory testing, requires real devices to more closely mimic the app on a user’s device — because real users report defects on real devices, not on virtual ones.

It is also critical to apply real user simulation to your tests. Testing with conditions such as conflicting apps, call/text interruptions, network throttling, network latency, and more enable you to see how your app will hold up out in the world under varying circumstances.
