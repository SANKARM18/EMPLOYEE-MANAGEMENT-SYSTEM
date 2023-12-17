# EMPLOYEE-MANAGEMENT-SYSTEM
USERNAME : admin
password : 12345

THIS PROJECT IS BASED ON JAVA 
WE HAVE USED MANY MODULES TO CREATE THIS PROJECT
THIS IS A WEB PAGE BASED PROJET
THE STEPS TO CRAETE THIS PROJECT ARE:
  1.DOWNLOAD APACHCE NETBEANS
  2.DOWNLOAD MYSQL WORKBENCH
DOWNLOAD THE ABOVE TWO APPS USING YOUTUBE VIDEOS BECAUSE AFTER DOWNLOADING WE HAVE TO SET PATH FOR THESE TWO APPS TO RUN PROPERLY.

NOW OPEN MYSQL MARKBENCH,NOW JUST COPY THE BELOW CODE AND PASTE IT IN THE MYSQL MARKBENCH
NOTE: U SHOLUD CODE ONE ONE LINE AND COPY IN THE MYSQL AND JUST PRESS THE THUNDER ⚡LIKE SYMBOL TO RUN.
create database employeemanagementsystem;

show databases;
use employeemanagementsystem;
create table login(username varchar(20), password varchar(20));
insert into login values('admin','12345');
select * from login;
create table employee( name varchar(20),fname varchar(20),dob varchar(30),salary varchar(20),address varchar(100),phone varchar(20),email varchar(40),education varchar(20),designation varchar(30),aadhar varchar(25),empId varchar(15));
select * from employee;



THEN DOWNLOAD THE LIBRARIES jcalendar,rs2xml,mysql connector and jdk 21 by refering youtube videos
Then import them into libararies.

