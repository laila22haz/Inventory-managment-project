# Inventory-managment-project

Inventory-managment-project is a user-friendly web application that Inventory Manager is an application to help you manage your supply chain. Our application allows access to a robust database system capable of fulfilling all of your business needs. in a seamless digital environment.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Author](#Author)
- [License](#license)

## Overview

The Inventory Manager application suite is suitable for any business, though we target scalable retail endeavors primarily. Our application allows for the tracking of a variety of information, which can be found in the data categories tab in the navigation bar at the top of the screen.


## Features

List of Key Features:
- **User-Friendly Interface:** Simplified for users.
- **tracking of a variety of information:** Engage in dynamic experience.

## Installation and usage 

### 1. First:
```bash
    Make sure to run the following commands locally to have
    the correct packages installed

```
### 2.Install Dependencies:
Run the following commands to set up the database:

```bash
-   pip install django
-   pip install django-cors-headers
-   pip install djangorestframework
-   pip install mysqlclient
-   pip install wheel
```
### 3. Run Application:
To install the node modules necessary to run the application, make sure to cd to inventory_manager/frontend/,
then run the command  
```bash
npm install
```
To run the development environment, follow the steps here:
- In the first terminal run:

``` cd /inventory_manager/
    python manage.py makemigrations
    python manage.py migrate
    python manage.py runserver
```
- In the second terminal run:
```
    cd /inventory_manager/frontend
    npm run dev
```
Alternatively, you can vist [Run](http://localhost:8000)


## License

This project is licensed under the GNU GPLv3 - see the [LICENSE](https://choosealicense.com/licenses/gpl-3.0/) file for details.

## Author
Laila hazmir <[Laila](https://github.com/laila22haz)>
