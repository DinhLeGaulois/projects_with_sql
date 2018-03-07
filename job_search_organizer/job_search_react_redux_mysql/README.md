# Job Search Organizer - Version 2

## Aim

To build an entire application using 3-tier architecture using **React/Redux** as **UI**, **Sequlize** as ORM (**O**bject-**R**elational **M**apping) and **MySQL** to manage the database. Beside the main features, there are **validations** from the **UI** to the **database**.

## Technologies

> 1. **UI** -->  **React/Redux**
> 2. **UI - Server** --> **axios - ExpressJS**
> 3. **Server** --> **Express/NodeJS**
> 4. **Server - Database** --> **Sequelize - MySQL**
> 5. **Database** --> **MySQL**

## Changes Comparing to [**version 1**](https://github.com/DinhLeGaulois/job_search_react_redux_mysql)

![alt text](https://github.com/DinhLeGaulois/job_search_react_redux_mysql_v2/blob/master/assets/img/objectInstead.jpg)

## Problem (maybe?)
The "**bundle.js**" could be heavier in ***version 2** if **webpack** takes **objects** (for constants, for example) as a whole or just "**key**": "**value**" (the latter could be a ***function***, ***object***, ***variable***, etc.) 

But in the worst case, even with a big project, the weight added wouldn't be more than some hundred kilo-bytes.
 

---------------

## Author
* Dinh HUYNH - All Rights Reserved!
* dinh.hu19@yahoo.com