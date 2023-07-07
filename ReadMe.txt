This Project is for "Find travel insurance plan for students"

There are Three Packages in src/main/java:
1) Package: PageClasses- contains all the page classes(BaseClass.java, HomePage.java, TravelInsurance.java, TravelInsurancePOM.java, CarInsurance.java, CarInsurancePOM.java, HealthInsurance.java)
2) Package: TestCases- contains the test classes(TravelInsuranceTest.java)
3) Package: Utilities- contains utilities classes(DateUtil.java, ExtentReportManager.java)

There are two folders in src/test/resources:
1) drivers- contains all the three drivers(chromedriver.exe, geckodriver.exe, msedgedriver.exe)
2) ObjectRepository- contains properties file(config.property)

Input: config.property, TestData folder(CarInsuranceInput.xlsx,TravelInsurance.xlsx)

Output: test-output folder(Travel Insurance.xlsx, Car Insurance.xlsx, Health Insurance.xlsx)

-->Screenshots will be in Screenshots folder
-->Html reports,output excel files,xml files will be in test-output folder

Classes:
1)BaseClass.java- Contains all the common functions along with invoking browsers and opening url
2)HomePage.java- contains all the webelements to be located in homepage and its respective methods
3)TravelInsurancePOM.java- contains all the webelements to be located in travel insurance page and some common functions 
4)TravelInsurance.java- contains methods to fill forms and to retrieve travel insurance plans using the webelements from TravelInsurancePOM.java
5)CarInsurancePOM.java- contains all the webelements to be located in car insurance page and some common functions
6)CarInsurance.java- contains methods to fill forms and to retrieve Car insurance plans using the webelements from CarInsurancePOM.java
7)HealthInsurance.java- contains webelements and methods to retrieve health insurance menu items
8)TravelInsuranceTest.java- contains smoke and regression tests
9)DateUtil.java- it is used to retrieve current date along with time. so that it will be used to store reports with that time and date.
10)ExtentReportManager.java- it is used to create report and store some properties.