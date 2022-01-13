# AspireTest
1. Prerequiresuite
  - Coppy "\Drivers" from "\NgaAspire" to C:\
  - Visual Studio 2019
  - Project is imported and opened
  - Dependent libraries: xunit,Selenium.WebDriver are installed

2. Description of the included files/folder
	- \Drivers\chromedriver.exe. -> chrome web driver
	- \Aspire1\SeleniumMethods.cs -> Methods for web interactions, they are used and enhanced from functions in QA.Selenium library
	- \Aspire1\Global.cs -> Defined variables for portal URL, username/password and default timeout (in seconds) 
	- \Aspire1\AspireFunctions.cs -> Web elements and functions that could be used in test scripts
	- \AspisePracticeInit.cs -> Test method and test script to be executed
	- \Testcase1.cs > Test script for the test case mentioned in homework

3. Run test script
	- Open Test Explorer from Visual Studio 2019
	- Expend the test as below: Aspire1/AspisePracticeInit/Testcase1
	- Right Click to "Testcase1" and Select "Run"

4. Test result: The test case is passed on Chrome version 96
