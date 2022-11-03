## A101FinalCase ABOUT PROJECT

This project is the Path.dev & A101 New Merchandising A.S. Practicum was developed as a graduation project.

### I- Test Scenario:

https://www.hepsiburada.com / any product has been searched from the address, with and without login. The product requested by the user was added to the cart from two different sellers separately within each 2 tests and the steps of adding to the cart were tested.

#### Parametrik olarak alınacak veriler:
It is set from the Configuration.properties file.
Configuration.properties dosyasından ayarlanmaktadır. In addition, the selection of the scanner where the test will be performed can be made here (The project supports Chrome, Firefox and Edge browsers.).

![image](https://user-images.githubusercontent.com/111094912/199613664-a5be1557-7c9e-4f3f-a943-86aeec095975.png)

•	browser           : The browser where the test will be performed.

•	hepsiburadaUrl    : Link to the web page where the test will be performed.

•	userMail          : The email address that will be used in the login test.

•	userPassword      : The password that will be used in the login test.

•	productToSearch1  : The product to be searched for in the login test.

•	productToSearch2  : The product to be searched for without login.

### II- Projenin Çalıştırılması:

1-) The Java SDK and Apache Maven must be installed on the computer where the project will be run. In addition, the necessary libraries related to log4j2 should be created in order for the reporting to work stably. 

2-) This is a project Maven. If the project doesn't work at first, all that needs to be done is to open the pom.xml file and install the necessary libraries. After uploading the necessary libraries to the corresponding folder, the maven tab for Intellij, located on the right, will open and it will be enough to click on the update icon shown in the red box below.

![image](https://user-images.githubusercontent.com/111094912/199597222-c023fb87-b2bd-412e-9a30-0057293641df.png)

3-) The project can be run separately from src/test/java/tests/HepsiBuradaLoginTest01.java and src/test/java/tests/HepsiBuradaTest02.java files.

![image](https://user-images.githubusercontent.com/111094912/199766065-f60a1e2c-c413-4cff-8b3a-2802dca21621.png)

### III- Reporting:

Our test steps given within the framework of the application were written within the framework of clean code principles and all of them were completed successfully. In order for the user to test the codes we have written manually, two reporting methods have been used and all of these reports have been saved to the target folder. The reporting methods we use are log4j2 and the screenshot taking method.

#### 1-) Reporting using the log4j2 method

![image](https://user-images.githubusercontent.com/111094912/199611639-167649a0-d83d-4991-9b95-6eb34510afe9.png)

#### 2-) Reporting using the screenshot taking method

![image](https://user-images.githubusercontent.com/111094912/199612204-02b83fb3-617b-4651-9bae-6eb59f4ffb20.png)

### IV- Tools and Technologies Used in the Project:

•	Java

•	Selenium

•	TestNG

•	Maven

•	POM (Page Object Model)

•	OOP (Object Oriented Programming)

### V- Running the Test:

The test steps described above were recorded on video by running them as an example.

https://drive.google.com/file/d/1ymOBLXjyUeIOwPvM_gt89eQX0pSni36A/view?usp=sharing
