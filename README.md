# 13 Object-Relational Mapping (ORM): E-Commerce Back End

## Description

Internet retail, also known as **e-commerce**, is the largest sector of the electronics industry, generating an estimated $29 trillion in 2019. E-commerce platforms like Shopify and WooCommerce provide a suite of services to businesses of all sizes. Due to their prevalence, understanding the fundamental architecture of these platforms will benefit you as a full-stack web developer.

This project, primarily focuses on the back end of an e-commerce site and is configured using Express.js, Sequelize and MySQL.

Because this application won’t be deployed, you’ll also need to provide a link to a walkthrough video that demonstrates its functionality and all of the acceptance criteria being met. You’ll need to submit a link to the video and add it to the readme of your project.

## User Story

```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Installation

To install this application locally, you must; 

```
  git clone git@github.com:DavidSzamek/ecommerce-orm.git
```

Then, install dependencies; 

```
  npm install express
  npm install sequelize
  npm install mysql2
```

## Getting started

To run this application; 

Open MySQL;

``` 
  mysql -u root -p
``` 

Then,

```
  SOURCE db/schema.sql;

  USE ecommerce_db;

  EXIT

```

Then, run; 

```
  npm run seed
```

Lastly, to initaite the server run;

```
  node server.js
```

## Functionality

