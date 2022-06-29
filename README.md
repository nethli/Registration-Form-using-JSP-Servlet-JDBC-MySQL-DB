# Registration-Form-using-JSP-Servlet-JDBC-MySQL-DB

![image](https://user-images.githubusercontent.com/87275026/176404147-32a09550-aaf2-4167-ae48-23c0b23a44bb.png)


CREATE DATABASE `employees`

CREATE TABLE `employee`(
	`id` INT(3) NOT NULL,
    `first_name` VARCHAR(20) DEFAULT NULL,
    `last_name` VARCHAR(20) DEFAULT NULL,
    `username` VARCHAR(250) DEFAULT NULL,
    `password` VARCHAR(20) DEFAULT NULL,
    `address` VARCHAR(45) DEFAULT NULL,
    `contact` VARCHAR(45) DEFAULT NULL,
     PRIMARY KEY(`id`)
);

