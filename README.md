## Description

This application lets users reach all endpoints for an e-commerce app. It demonstrates the ability to read, update, create, delete products, tags, and categories with influence and relationships on each other from a relational database

## Table of Contents


- [Installation](#installation)

- [Usage](#usage)

- [Questions](#questions)

## Installation

This app requires Node and NPM to be installed to work.

You will also need a MySQL server to run the schema file on.


First you will need to clone or download this repository to your machine.

Then in your terminal, while on the repo folder, run the following command

```
npm install
```

Be sure to create a .env file in the repo and add the following, filling out the lines as needed per your database info.
The db name will be ecommerce_db

```
DB_USER=
DB_PW=
DB_NAME=
```

Log in to your MySQL server, and run the schema.sql file to create your DB.
Then, if you choose you may seed the DB with the seeds.sql file.

This can be done also with the following command
```
npm run seed
```




Your application and all its dependencies should now be installed

## Usage

This can be used by following these steps

While on the repo folder in your terminal, run the following command to start the application

```
npm start
```

Use Insomnia core to test each endpoint as this application has no functional front end currently.