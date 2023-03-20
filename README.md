# 安徽财经大学宿舍管理系统 

宿舍管理系统采用**IntelliJ IDEA**和**WebStorm**两款开发工具进行开发 
本系统采用B/S(浏览器/服务器)结构，系统支持Windows、Unix、Linux操作系统。 

本系统数据库采用 **MySQL**。MySQL 为关系型数据库，它的运行机制为开发者提供了可靠的保障，其体积小、速度快、总体拥有成本低、性能卓越，因此使用MySQL 作为数据库比较合适。 

本系统采用Tomcat作为后台服务器。Tomcat 配置简便，并且是一个轻量级的开源的Web服务器。系统将Tomcat当作一个管理者，管理客户端的请求，对数据库进行管理，就像一个管家，所有事物都集中在Tomcat服务器，体现了软件开发的高内聚低耦合。 

后端程序使用IntelliJ IDEA开发工具进行开发，利用Java 语言进行程序开发，利用Spring Boot框架整合MyBatis Plus、Redis等完成业务功能的实现，其内包含内嵌的Tomcat服务器，通过Navicat Premium工具连接到MySQL数据库对数据进行操作。 

前端程序使用Web Storm开发工具进行开发，利用html、javascript语言进行程序开发，利用VUE3框架整合Axios、Vue Router、Vue Store等完成页面展示功能的实现，其中UI框架选择的是Element Plus框架。


**该系统包括缴费模块、维修登记模块、卫生情况模块等功能。**  
通过该系统，宿舍管理员可以对学生信息进行增删改查。  
## 缴费模块
学生可以通过该系统查看自己宿舍的电费适用情况并进行缴费。  
## 维修模块
当学生宿舍东西需要维修时可以登录该系统进行登记。
## 卫生情况模块  
学生可以登录该系统查看自己宿舍的卫生评比情况

# Implementation of dormitory management system  

The dormitory management system was developed using two development tools, IntelliJ IDEA and WebStorm 
The system adopts B/S (browser/server) structure, and the system supports Windows, Unix, Linux operating systems. 
The database of this system uses MySQL. MySQL is a relational database, its operation mechanism provides developers with a reliable guarantee, its small size, fast speed, low total cost of ownership, excellent performance, so it is more suitable to use MySQL as a database. 
This system uses Tomcat as the background server. Tomcat is easy to configure and is a lightweight, open-source web server. The system treats Tomcat as a manager, manages client requests, manages the database, like a housekeeper, everything is concentrated in the Tomcat server, reflecting the high cohesion and low coupling of software development. 
The back-end program is developed using IntelliJ IDEA development tools, the Java language is used for program development, and the Spring Boot framework is used to integrate MyBatis Plus, Redis and other business functions to complete the implementation, including the embedded Tomcat server, which connects to the MySQL database through the Navicat Premium tool to operate on the data.
The front-end program is developed using Web Storm development tools, using html and javascript languages for program development, and using the VUE3 framework to integrate Axios, Vue Router, Vue Store and other implementation of page display functions, of which the UI framework is selected as the Element Plus framework.


The system includes functions such as payment module, maintenance registration module, and hygiene module.  
Through this system, dormitory administrators can add, delete, modify, and check student information.  
## Payment module
Through this system, students can check the availability of electricity bills in their dormitories and pay for them.  
## Repair module
When something needs to be repaired in the student dormitory, you can register by logging into the system.
## Hygiene module  
Students can log in to the system to check the hygiene rating of their dormitory
