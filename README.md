# Major-Project_SecuroHealth

# Secure Sharing of Health Records on Cloud Computing

# Introduction
Most of the time, when people go for a prescription, healthcare person ask them for previous records but people forget to take their past medical records or they have thrown the files unknowingly.  It creates some misleading approach for doctor to process the treatment.

To avoid this kind of misleading approaches, we have designed a secured platform where everyone can keep their medical records for free in a very convenient way. Also hospital can adopt this platform to keep track of admitted patient in their hospital and can also keep the expenses as bill generation in the platform.

# Features

1 Cryptography:
Security is the major issue in this system. To secure the user healthcare medical records, we have 
used private key encryption technique. We are using Advance Encryption Standard (AES128bit) to encrypt the data. The private/secret key for the encryption will be encoded in the QR 
Code. User and hospital has to scan the QR Code to access the data.
2 Payment Gateway Integration: 
We have integrated the payment gateway to collect the billing amount. It will help hospitals to 
receive all the charges of patient from admission to discharge.
3 QR Code Integration:
For each user the unique QR Code will be generated. It consists of Card Number and 
Private/Secret Key. Hospital Dashboard will be required to scan this QR Code to admit the 
patient.
4 Speech Recognition:
To save the time and energy of the physicians, we have implemented the speech recognition 
technique to make the data insertion fast.
5 Secure Socket Layer (SSL):
We will enable secure socket layer (SSL). It will provide secured access to all of the server 
requests.
6 Billing System:
To make the platform as a one stop solution, we are providing billing management facility. So
that all of charges can transparently visible to patient and hospital. Patient can also make the 
payment with the help of integrated payment gateway in this site.
7 Curo Card:
It is a physical card. It consists of public information like Name, Date of birth , Address, Card 
Number, Private/Secret Key, QR Code etc. It is required to use the platform. Without the 
availability of Curo Card, no one can use or retrieve the personal data.

# Programming Languages:

# Backend Development 
1 PHP (Version 7.2):
Used in majority is this project to handle users’ requests and database requests. PHP is capable 
to handle a lot of client and server requests and also it secures the database from outside
resources.
2 MySQL (Version 5.0.12):
MySQL is used to securely insert, update and retrieve the data from database.
3 AJAX (Version 3.5.1):
It is used to handle the user requests without refreshing the whole page. It gets data from user 
events and send them to different pages for execution with database.
4 jQuery (Version 3.5.1):
jQuery is used for grabbing data from DOM elements and pass it to through AJAX request.

# Frontend Development:
1 Bootstrap (Version 5.0.2):
For responsive layout design, we have used bootstrap. It has inbuilt classes for different 
usability.
2 JavaScript (ES2015):
For dynamic behavior of the project, we have used JavaScript in some places. It helps in capturing 
user events for any DOM element.
3 CSS(Version 3):
To change some properties of the HTML elements and display them differently, we have used 
CSS.
4 HTML(Version 5):
To render data in web page and display them with browser property, we have used HTML.

# Conclusion
We find that electronic health record will help physicians to make evidence based decisions and can predict right treatment process according to their medication history. The community level health status can also be tracked and required campaign can also commenced by the respected government departments. 

To solve the unauthorized access, we have encrypted all the data with latest encryption techniques. No one (except the persons whom the user has granted permission to access the data) can access the stored data of any person.

The hospital can also manage the billing of the individual patient and can collect charges from them through the payment gateways integrated with this site. 
