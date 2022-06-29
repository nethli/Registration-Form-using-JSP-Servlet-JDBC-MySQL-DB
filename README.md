# Registration-Form-using-JSP-Servlet-JDBC-MySQL-DB

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

