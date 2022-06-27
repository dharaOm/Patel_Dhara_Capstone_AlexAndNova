# Patel_Dhara_Capstone_AlexAndNova
CAPSTONE PROJECT BY DHARA PATEL

About Project
This is a ecommerce website alexandnova which has four important elements.
1. Main Pages- Includes homepage, privacy page, about us,careers page etc
2. Product Pages- Includes different options for the product such as sixe, color, and other attributes such as sorting and filtering
3. Product Description Pages- Includes the title,description, images,the add-to-cart feature, 
4. Shopping Cart- Include payment options and option to remove a product form the shopping cart.

---------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------
Techincal Specifications:

I have created a maven project with intelliJ IDE. I have used selenium webdriver and testNG framework and have used POM (Page Object Design) pattern.
Locators I have used to find the elements are ID, xpath, linktext, css selector, and class name.

Below are the dependecies I have downloaded in pom.xml 

Dependency Name               Version
org.seleniumhq.selenium        4.0.0
org.testng                     6.14.3
commons-io                     2.11.0
com.aventstack                 3.1.5

Below are the plug-ins I have downloaded in pom.xml


Plugin Name                  Version
maven-clean-plugin             3.1.0
maven-resources-plugin         3.0.2
maven-compiler-plugin          3.8.0
maven-surefire-plugin          2.22.1
maven-jar-plugin               3.0.2
maven-install-plugin           2.5.2
maven-deploy-plugin            2.8.2
maven-site-plugin              3.7.1
maven-project-info-reports     3.0.0
org.apache.maven.plugins       3.5.1

---------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------

Challenges 
--> The webiste was not stable and requires to add wait scenarios at many places just to find the element while running the scripts.
--> Exceptions- I have encountered stale element and element click intercepted exceptions during the run time of the scripts.
--> Captcha-Another issue i have faced is to deal with the captcha, the only to handle this is solve manully and put a wait time.
My project can be found at https://github.com/dharaOm/DharaPatel_CapstoneProject_UI_Testing.git 

I would like to thank my instructor Igor Adulyan for his teaching and guidance during this entire course. 

