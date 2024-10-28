**Cucumber Automation Testing Project for Movies App**

**Project Overview:**
This project aims to automate various core features of the QA Movies App, including the login functionality, home page navigation, popular movies page, movies listing, and accounts page using Cucumber, Selenium WebDriver, and TestNG.

**Table of Contents**
1. Project Overview

2. Key Functionalities Automated

3. Folder Structure

4. Installation & Prerequisites

5. Setup Instructions

6. Running the Tests

7. Test Reports & Results

8. Author Details

**1. Project Overview:**

The application, accessible at QA Movies App Login, allows users to log in and explore a collection of movies. Automation testing ensures that these functionalities are reliable and work as expected.

**2. Key Functionalities Automated:**

Login Functionality:
After a successful login, the user is redirected to the homepage where their movie list is displayed, validating the core login functionality.

Homepage Navigation:
The homepage shows movies related to the user's profile. Automation verifies that the correct movies are displayed upon login.

Movie Details Page:
By clicking on a movie, the user is taken to the specific movie's page. Automation checks that the title, description, and other critical information are displayed correctly.

Popular Movies Page:
This page lists all popular movies. Automation ensures that the popular movies section loads and displays the expected content.

Account Page:
The account page shows the user's account details and plan information. Automation tests that the correct user details are displayed and the page functions as intended.

**3. Folder Structure**

Here is the folder structure followed for the current project

<img width="401" alt="image" src="https://github.com/user-attachments/assets/3d7bd977-9600-46f3-9f10-5748faf30d37">

<img width="389" alt="image" src="https://github.com/user-attachments/assets/eb4022ae-e7f3-4a32-b41b-7bad0fe0d9de">

**4. Installation & Prerequisites**

JDK 1.8+ (Ensure that the Java class path is properly set)

Maven (Ensure that the .m2 class path is properly set)

IntelliJ IDEA

Browser's (Make sure that you are having Chrome,Firefox & Edge browsers installed in your system)

The following dependencies are added in the pom.xml file:

selenium-java (Version: 4.25.0)

webdriver-selenium (Version: 0.9.7376)

testng (Version: 7.10.0)

commons-io (Version: 2.15.0)

webdrivermanager (Version: 5.9.2)

cucumber-junit (Version: 7.4.1)

cucumber-java (Version: 7.4.1)

allure-cucumber7-jvm (Version: 2.19.0)

**5. Setup Instructions**

1. Clone the repository using the following command:
https://github.com/Krisha-Wadhwa/seleniumCucumber.git

**6. Running Tests**

1. Open the project in IntelliJ IDEA.

2. Navigate to utility package using the following path: "src/test/java/utility"

3. Right click on TestRunner.java class file and select the option: Run 'TestRunner' this will run our project.

**7. Test Reports & Results**

Report`s will be generated in the following path: "target/cucumber-reports"

Here are the different reports that are generated after running this project:

1. HTML report: "target/cucumber-reports/cucumber.html"

![Screenshot 2024-10-23 at 15 47 59](https://github.com/user-attachments/assets/30de7789-8456-4fc6-a3a6-959fefc61c0a)

2. JSON report: "target/cucumber-reports/cucumber.json"

3. XML report: "target/cucumber-reports/cucumber.xml"

4. Allure report inside allure folder: allure-results
<img width="1369" alt="image" src="https://github.com/user-attachments/assets/a18ae41c-0280-45bb-9d97-8a1beb164480">

**8. Author Details:**

**Name:** Krisha Wadhwa

**E-Mail:** bavisha.bhatia@gmail.com

**LinkedIn** https://www.linkedin.com/in/krisha-wadhwa-a39b6a209/






