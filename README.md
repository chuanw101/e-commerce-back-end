# e-commerce-back-end

## Description
This is a backend program that maintains a e-commerce database.<br>
Can get all, get by id, create new item, update by id, delete by id for the category, product, and tag tables in the database.<br>
There is a one to many relationship between category and product and a many to many relationship between product and tag, the many to many relationship is done through product_tag table.<br>
When information is being sent through the get methods the related information is also shown, for example, you can see products in each category when viewing all category.<br>
See installation and usage for info on how to use.<br>

## Demo
[![Watch the video](https://img.youtube.com/vi/qgV1LPRdloQ/maxresdefault.jpg)](https://youtu.be/qgV1LPRdloQ)
![](./demo.mp4)

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Contribution](#contribution)
- [Test](#test)
- [License](#license)
- [GitHub](#github)
- [Contact](#contact)

## Installation
type "npm install" in terminal to install dependencies, required for this program to work.<br>
also requires mysql to be installed on computer.<br>
To intialize the database, need to log into mysql with "mysql -u root -p" in cmd with directory being in the same folder as the schema.sql. <br>
after getting into mysql shell, use command "SOURCE schema.sql" to create the database.<br>
create a .env file in the same directory as server.js.<br>
inside it should have:
- DB_USER=root
- DB_PW=what ever your password is for root user
- DB_NAME=ecommerce_db

## Usage
After all steps in installation, type "npm start" or "node server.js" to start the program.<br>

## Contribution
No need for contribution, solo project.

## Test
After starting the server use insomnia or similar program to test various api routes. <br>

## License
This project is licensed with MIT License.<br>
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## GitHub
https://github.com/chuanw101

## Contact
- Author: Chuan Wang
- Email: chuan.wang101@gmail.com