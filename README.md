# dirasa
The word “dirasa” is derived from Arabic word “دراسة” which means “study” in English language. There are many websites out there providing study material, video, applications for students but they all lack the sense of community. Our website was developed with a notion to address this problem and provide a sense of community thus the slogan “For the students, of the students, by the students”. The website was conceived considering all the options from the users. We created the website with the basic idea of file uploading in the first revision. Requirements analysis was done using appropriate elicitation techniques such as dialogue and questionnaire. The first basic prototype of website was presented amongst our friends and acquaintances and valuable feedbacks were noted down.

**NOTE**
The project was done for the  Object Oriented Software Development Course in 3rd year of CSE branch. A simple credit system was implemented around which the whole idea/business revolved.

The website was created with Object Oriented Modelling in mind and put into practice the theory learnt during the whole semester in this course. THe website has been built from scratch using core HTML, Javascript and PHP to learn the OOP concepts from the grassroots level. Utmost focus was given to Functional requirements and they were implemented first. Non-functional requirements were slowly added. Some of the unapplied non-functional requirements will be mentioned in the below list with a cross-mark across them. Functional requirements marked as unimplemented can be added in the next increment. This was done purposefully to show that in the next increment version of the website it is easy to add new functional features without affecting the other modules of the website.


**Functional Requirements:**
o	File uploading and downloading
o	Registeration
o	Login
o	Software uploading and downloading
o	Q&A section (x)
o	Community Portal (x)
o	Merchandising Portal (x)
o	Subjects Portal
o	Plagiarism Checking of Notes

**Non-Functional Requirements:**
o	Securing password in md5  and then sha256 encryption security layers
o	Credit based system implementation analytics
o	Accuracy and Efficiency of the Plagiarism Checker 
o	2-Step Verification to ensure more security (x)
o	Load balancing between the site servers on three separate servers (x)
o	Redundant database for reliable data access (x)

### Prerequisites

* You need to install **[Apache](https://httpd.apache.org/download.cgi)**, **[PHP](http://php.net/downloads.php)** and **[MySQL](https://dev.mysql.com/downloads/)** as three important functionalities in your servers to run this website. You can have any other database server as well but one which closely follows SQL format.
* Instead you can simply download **[XAMPP](https://www.apachefriends.org/download.html)** suite to get all three in one package on single server and run it without any configuration trouble

### Installing
* Create a MySQL or SQL database on your DB server which contains following tables

 ![Image1](img1.png)
 ![Image2](img2.png)
 ![Image3](img3.png)
 ![Image4](img4.png)
 ![Image5](img5.png)



### Build using
* HTM5 CSS JAVASCRIPT PHP7.2
* [Material Design Icons](https://github.com/google/material-design-icons)

### Conclusion
A fully functional credit system has been implemented as a rewarding scheme to engage users. To further engage users in future we are planning to provide the merchandise features. Users can also buy new courses with the credits they earn. To maintain the community nature of the website we will provide a community portal and a QnA section in the website. To check the plagiarism efficiently we will employ parallel computing techniques to check plagiarism check using Rabin Karp Algorithm to find the percentage of copied work. The current version of the website is 2.0 because we have changed the theme of the website entirely. Next time we will bring in a more display friendly template for website.
