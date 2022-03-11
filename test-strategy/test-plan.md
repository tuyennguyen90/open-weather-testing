===============================================================
TEST PLAN

1. Scope and Overview:
1.1 Scope:
	- Search weather in your city
	
1.2 Cross platform/browser testing: 
	- Device: Desktop (priority 1)
		- Browsers:
			- Chrome (latest version)
			- Firefox (latest version)
			- Safari (latest version)
		
	- Device: Mobile (priority 2)
		- Mobile devices:
			- OS (Iphone 6 or higher version)
			- Android
	- Device: Tablet (priority 3)
		- Tablet devices:
			- OS
			- Android
			
1.3 Dependencies:
	- Code is deployed into test environment as per the schedule
	- Environment is stable
			
1.4 Assumptions:
	- No change design
	- Quality development, minimal bugs to be indentified during functional testing.
	
1.5 Risk and issues:
	- Delay in code availability and deployment
	- Environment instability causing deplays for testing
	- Requirement changes
	- Software/Hardware unavailability for testing.
	- Unplanned leaves for project team members may causes delays execution timelines.
	
2. Test Approach

2.1 Functional testing:
	- Functional testing will be performed to ensure that the changes are in line with business and functional requuiredments. It wlll be performed by QA team in QA environment.
		- On a high level, functional testing will be mainly focused on the below functionalities:
			- Load the weather maps successful
			- Search weather in your city and other cities.
		- Cross platform/browser testing: will be performed	for a subset of requirements to ensure that the changes does not impact the UI, functionality of the page.
		- All test cases will be executed in Testrail/Excel
		- All defects identified will be raised in Azure ticket.
	
2.2 UI Testing
   - GUI testing will be performed to ensure the functionalities of software website work as per specification by:
		- Checking screens
		- Hover on city/country/menu
		- Zoom in/out
		- check colors
	- GUI is what user see.

2.3 Non functional testing
	- Performace testing will be performed to ensure that loading all countries on the maps accurately and smoothly. (ex: load 100 countries or 200 coutries or all)
	- Usability testing (User Experience (UX) testing) will be measured how easy and user friendly the website Open Weather is.

2.4 Regression test:
		- A regression test has been created for QA team in QA or stagging or UAT environments which covers most common functionalities of the website. The objective of regression testing is to ensure that the changes will not impacted any other major functionalities in the OpenWeather website.
		
2.5 Entry and Exit Criteria.
	2.3.1 Entry Criteria - UAT
		- All changes are deployed into test enviroment.
		- All components which are required to perform end-to-end testing (Intergration testing) should be up and runing.
		- Environment is ready and set-up for the code to be deployed into UAT environment.
		- Sanity testing for Intergration should be successful.
		- Test case design has been completed.
	2.3.2 Exit Criteria
		- All test cases are designed and executed with 100% pass.
		- No blocker or major issues exist that impacts the released functionality.
2.6 Test cases
	- All testing activity will be recorded and tracking using TestRail.
	- Test Case with Objecttive will be created in TestRail by QA team base on the corresponding requirements detailed in the document.
	- Test case will include the test objective and the test steps and scope of each test case.
	- Reviewes will be carried out by the Test Manager/Test Lead to ensure test cases and results are recorded accurately.
	
2.7 Test Results
	- Test results will be recorded and tracked in TestRail. (give sreenshot if any)
	
2.8 Test Completion Report.
	- The reporting features developed in the QA report tool will be used to produce test execution summary.
	
3. Defects Management.
	- Defects will be logged with the following details:
		- Project: Open Weather
		- Component: Search
		- Type: Bug
		- Desctiption: A desciption of the problem encountered with reproduction steps, screenshots/attachments as required
		- Status: Status of the defect.
		- Priority: Minor/Low/Medium/High/Blocker
		- Assign to: DEV/BA/PM
		
4. Enviroments Requirements
	- Test environment used are:
		- Test main functions: QA environments
		- Integration and Regresstion test: Staging environments (UAT environments)
		- Browsers
		- Prepare test data for UAT environments
		- Database server
		
5. Tools:
	- Defects Management: Azure
	- Project Management: Wiki
	- Test Management: TestRail
	- Cross Browser Testing tool: https://www.crossbrowertesting.com
	- Postman for API testing
	
6. Appendix
7. Review and Approvals
	- By PM, QA manager, and DEV leader/manager
	- IT support (for devices)
	
8. Document Management.
=====================================================================

Defects example:
		- Project: Open Weather
		- Component: Search
		- Type: Bug
		- Desctiption: The search result not match with search criteria
		- Status: New
		- Priority: High
		- Assign to: DEV
		- Steps to reproduce:
			Pre-conditions:
				- The Open Weather website is shown
			Steps:
				- Input full english name (ex: Ho Chi Minh)
				- Press Enter button
				- Observe the result
			Actual Result:
				- Show all cities in the Viet Nam (Screenshots or attachments)
			Expected Result:
				- Verify the result should be shown correct city (Ho Chi Minh)