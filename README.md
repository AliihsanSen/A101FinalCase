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

1-) Projenin çalıştırılacağı bilgisayarda Java SDK ve Apache Maven kurulu olmalıdır. Ayrıca raporlamaların stabil çalışabilmesi için log4j2 ile ilgili gerekli kütüphaneler oluşturulmalıdır. 

2-) Bu bir Maven projesidir. Projenin ilk başta çalışmaması halinde, tek yapılması gereken pom.xml dosyasını açarak gerekli kütüphaneleri yüklemek olacaktır. İlgili klasöre gerekli kütüphaneleri yükledikten sonra Intellij için sağ tarafta bulunan maven sekmesi açılarak aşağıda kırmızı kutu içersinde gösterilen uptade simgesine tıklamak yeterli olacaktır.

![image](https://user-images.githubusercontent.com/111094912/199597222-c023fb87-b2bd-412e-9a30-0057293641df.png)

3-) Proje, src/test/java/tests/HepsiBuradaLoginTest01.java ve src/test/java/tests/HepsiBuradaTest02.java dosyalarından ayrı ayrı çalıştırılabilmektedir.

![image](https://user-images.githubusercontent.com/111094912/199600150-45da611b-05ad-4cfa-978d-0104e6eb690e.png)

### III- Reporting:

Our test steps given within the framework of the application were written within the framework of clean code principles and all of them were completed successfully. In order for the user to test the codes we have written manually, two reporting methods have been used and all of these reports have been saved to the target folder. The reporting methods we use are log4j2 and the screenshot taking method.

1-) Reporting using the log4j2 method

![image](https://user-images.githubusercontent.com/111094912/199611639-167649a0-d83d-4991-9b95-6eb34510afe9.png)

2-) Reporting using the screenshot taking method

![image](https://user-images.githubusercontent.com/111094912/199612204-02b83fb3-617b-4651-9bae-6eb59f4ffb20.png)

### IV- Tools and Technologies Used in the Project:

•	Java

•	Selenium

•	TestNG

•	Maven

•	POM (Page Object Model)

•	OOP (Object Oriented Programming)
