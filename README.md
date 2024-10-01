# AWS-Projects
This Repo is for AWS-Project which i have performed

Project - 1: Deploying a Multi-Tier Website Using AWS EC2

Description:
Amazon Elastic Compute Cloud (Amazon EC2) provides scalable computing
capacity in the Amazon Web Services (AWS) cloud. Using Amazon EC2
eliminates your need to invest in hardware up front so you can develop and
deploy applications faster. You can use Amazon EC2 to launch as many or as
few virtual servers as you need, configure security and networking, and manage
storage. Amazon EC2 enables you to scale up or down to handle changes in
requirements or spikes in popularity, reducing your need to forecast traffic.
Problem Statement:
Company ABC wants to move their product to AWS. They have the following
things set up right now:
1. MySQL DB
2. Website (PHP)
The company wants high availability on this product, therefore wants Auto
Scaling to be enabled on this website


Steps To Solve:
1. Launch an EC2 Instance
2. Enable Auto Scaling on these instances (minimum 2)
3. Create an RDS Instance
4. Create Database & Table in RDS instance:
a. Database name: intel
b. Table name: data
c. Database password: intel123
5. Change hostname in website
6. Allow traffic from EC2 to RDS instance
7. Allow all-traffic to EC2 instance

   ![Screenshot 2024-10-01 105816](https://github.com/user-attachments/assets/9581c749-b5d5-4bc2-8c8c-b438f606e5a2)

 ## Commands used
1. sudo su (to convert into root user)
2. apt-get update  (to get latest packages which are installed in ubuntu)
3. apt install apache2 -y  (to install web server)
4. systemctl status apache2
5. cd /var/www/html
6. rm index.html
7. nano index.php
---> copy the contents of index.php into the terminal
---> ctl + s -> to save the file
---> ctl + x -> exit the editor
8. apt-add-repository -y PPa:ondrej/php 
----> to add the repository into ubuntu instance which enables us to install the requrired php version
9. apt install php5.6 mysql-client php5.6-mysqli -y
 ## Create MySQL Database
 Use below commands
 1. mysql -h <endpoint> -u <username> -p
 2. show databases;
 3.  use intel; --> Change Database
 4.  show tables; --> It will show empty table
 5.   create table data (firstname varchar(50),email varchar(50)); --> to create a table
 6.   insert into data(firstname, email) values ('shreyas','shreyasbhinge007@gmail.com');
 7.   select * from data;
    ![image](https://github.com/user-attachments/assets/fb546e06-0b9d-4542-80b6-c78862836968)

