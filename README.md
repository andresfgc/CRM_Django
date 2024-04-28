
# <h1 align="center">CRM - Custom Relationship Managemenet System</h1>

![CRM](/crm_django.png)

CRM is intended to facilitate the tracking of potential customer during the purchasing process.

In this project it was possible to put into practice fundamental topics such as database creation, agile methodology and CRUD.

## Table of Contents

- [CRM Django](#crm-django)
  - [Table of Contents](#table-of-contents)
  - [Features](#features)
  - [Features left to implement](#features-left-to-implement)
    - [Customer Sales Journey](#for-customer-sales-journey)
    - [Responsiveness](#for-responsiveness)
  - [Case Requirements](#case-requirements)
  - [Technologies](#technologies-used)
  - [Libraries](#imported-libraries)
  - [Bugs](#bugs)
  - [Deployment](#deployment)
  - [Credits](#credits)
    - [FreeCodeCamp.irg](#freecodecamp.org)

## Features

Within CRM the user can:

1. register and login.
2. create, update and delete records.
3. change customer status between Record, Contact & Client.
4. visualize customer data according to their statuses.

The deployed application can be found at [CRM](https://crm-afgc-3efdf830ce47.herokuapp.com/)

## Features left to implement

### For Customer Sales Journey
* Create ticket-system:
  * I plan to add a ticket system where the user can document the interaction and next steps with every particular sale process of each customer.

### For Responsiveness
* Create great mobile experience:
  * I plan to add responsiveness for the most relevant mobile devices.

## Technologies Used

  * Python
    * Most of the program was written in python.
  * Django
    * It's libraries were used to create the application.
  * Github
    * It was used to store the project.
  * Git with VStudio
    * It was used to create, add, commit and push my code to Github.
  * Heroku
    * It was used to deploy the project.
  * Bootstrap
    * It was used to add css style.
  * gunicorn
    * It is used to run Django on Heroku.
  
 
## Imported libraries

  * mysql, dj_database_url & psycopg2 were used to work with PostgreSQL and locally with MySQL.


## Bugs

Solved Bugs
* Error H10 on Heroku was solved by using decouple to properly send the .ENV data to settings.py.
* Error 404 for staticfiles on Heroku was solved by using whitenoise to properly send the Style.css info in the txt/css type format.


## Deployment
This project was deployed on Heroku.

The deployed application can be found at [CRM](https://crm-afgc-3efdf830ce47.herokuapp.com/)

## Credits

### FreeCodeCamp.org
* Main conception of how to create a CRM from scratch [Video](https://www.youtube.com/watch?v=t10QcFx7d5k&t=712s).
