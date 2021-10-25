
# CREATE-MPLS

  

## Description

**Create MPLS is a non-profit dedicated to preparing students in underserved communities for rewarding careers by providing accessible STEM learning programs at no cost to students or families**

**Duration:** 2 week sprint

This application allows Create MPLS to manage students, teachers, volunteers, and programs between locations. 

Goodbye spreadsheets! This application effortlessly generates graphic materials and data needed for current and future grant applications. 

There are two components to the application. 

 1. The mobile oriented side (for teachers) allows teachers to easily take attendance for their classes
 2. The desktop oriented side (for admins) allows admins to manage programs, students, and staff and view all data. 


## Flow Diagram
![Project Flowchart Diagram](https://raw.githubusercontent.com/gold-alex/create-mpls-gifs/main/creatempls_diagram.png)

  

### Prerequisites
-  [Node.js](https://nodejs.org/en/)

-  [PostgreSQL](https://www.postgresql.org/)

-  [Nodemon](https://nodemon.io/)
-  [React-Chartjs-2](https://www.npmjs.com/package/react-chartjs-2/) 
 -  [React-Select-Search](https://www.npmjs.com/package/react-select-search) 
-  [Passport](http://www.passportjs.org/) 
-  [Date-Fns](https://www.npmjs.com/package/date-fns?activeTab=versions)
-  [Material-UI](https://mui.com/)

## Installation
1. Head to database.sql and follow the instructions to setup the PostgreSQL database

2. Open your IDE's console and run `npm install` (Installs all program dependencies)

4. To initialize the server, run `npm run server` in your terminal

5. To initialize the client and view in browser, run `npm run client` in your terminal

## Teacher Usage
![](https://raw.githubusercontent.com/gold-alex/create-mpls-gifs/main/Teacher.gif)

1. Register to make a new account and input the given teacher registration code

2. Log in and you will be taken to a screen displaying all of the classes assigned to you

3. Click on the class you'd like to take attendance for

4. Configure class date, length, and volunteer count

5. Click a student's name to mark them present

6. Press submit to submit attendance data to the database

(Optional) If needed, edit attendance by scrolling down on the home screen. A list of dates of previously submitted attendance will be available. Simply tap the date you want to change and update students present.

  
## Admin Usage

1. Register to make a new account and input the given admin registration code

2. Log in and you will be taken to the Dashboard containing graphs and charts on student breakdown and data grids below displaying all student, teacher, and attendance data. To change registration codes for administrators and teachers, head to the bottom of the page to find the update fields.
![](https://raw.githubusercontent.com/gold-alex/create-mpls-gifs/main/Dashboard-Charts.gif)

3. On the "Students" page, admins can add students, edit existing students, and view and filter existing students 
![](https://raw.githubusercontent.com/gold-alex/create-mpls-gifs/main/Student-Page.gif)

5. On the "Programs" page admins can create new programs and assign teachers and students to existing programs. (Note: Only  teachers can be added to programs, admins DO NOT show up.) On the bottom of the page, admins can view and filter existing programs. 

6. On the "Staff" page admins can edit the names of existing Create MPLS staff and deactivate staff

## Built With
 - PostgreSQL
 - Express
 - React 
 - Node
 - CSS3
 - HTML5
 - Redux
 - Passport
 - Restful API

  

## Directory Structure
-  `src/` react source directory
-  `components/` contains react components 
-  `public/` contains static assets for the client-side
-  `server/` express server and authentication middleware
-  `server.js/` contains server files
-  `routes/` REST endpoints 
-  `database.sql/` contains the database tables and info needed to create db

  