# Personal Project - Employee Contact App





React UI and Java/MySQL backend API deployed separately on Heroku

## Competencies

### JF 1.1
+ Knows all stages of the software development life cycle (what each stage contains, including the inputs and outputs
### JF 1.6
+ Shows curiosity to the business context in which the solution will be used, displaying an inquisitive approach to solving the problem. This includes the curiosity to explore new opportunities, and techniques; the tenacity to improve methods and maximise performance of the solution; and creativity in their approach to solutions.
### JF 1.7
+ Demonstrates creativity and tenacity in their approach to solutions and the methods used to come to a solution for example, sees the task through to the end by devising new solutions and despite obstacles and problems along the way.
### JF 3.1	
+ Knows how to design software approaches and patterns, to identify reusable solutions to commonly occurring problems
### JF 3.2	
+ Knows relevant and up-to-date software designs and how to read and implement functional/technical specifications
### JF 3.3	
+ Understands how to develop effective user interfaces
### JF 3.4	
+ Able to create simple software designs to effectively communicate understanding of the program
### JF 3.5	
+ Understands how to follow software designs and functional/technical specifications
### JF 3.6	
+ Maintains a productive, professional and secure working environment
### JF 4.1	
+ Knows the principles of algorithms, logic and data structures relevant to software development (e.g., Arrays, Stacks, Queues, Linked Lists, Trees, Graphs, Hash Tables, Sorting Algorithms, Searching Algorithms, Critical sections and race conditions)
### JF 4.2	
+ Knows the principles and uses of relational and non-relational databases
### JF 4.3	
+ Understands and can link code to data sets
### JF 4.4	
+ Understands how to create a logical and maintainable codebase
### JF 4.5	
+ Is able to build, manage and deploy code into the relevant environment
### JF 4.6	
+ Understands how to apply an appropriate software development approach according to the relevant paradigm (for example object oriented, event driven or procedural)
### JF 4.7	
+ Understands how to apply algorithms, logic and data structures
### JF 4.8	
+ Is able to interpret and implement a given design whilst remaining compliant with security and maintainability requirements

## Table of contents

- [Introduction](#introduction)
- [Demo](#demo)
- [Technologies](#technologies)
- [Features](#features)


---

## Introduction

This is my first attempt at creating web applications using microservices. I created two separate projects that would interact with each other via HTTP calls. 

The first project is a Java/Springboot RESTful API that originated with a MySQL database. However for deployment purposes the database as migrated to ClearDB.  

The second project is a React UI with is deployed separately and calls on the first project for data population. I intitially started out using a tutorial online. However that ended when the code being presented wasn't working due to being outdated. I quickly found myself writing code from scratch after using constant research and discovery via Google and React documentation. I hope to create alternate Web apps with different themes that all access the same RESTful API in the future.
---

## Demo

### Deployed: https://emp-mgt-app.herokuapp.com 

### Front End UI 
+ [Deployed on Heroku](https://emp-mgt-app.herokuapp.com)

![Heroku FE Deployment][FEHero]

[FEHero]: https://github.com/CrystalMorris/MVPortfolio/blob/main/personal-projects/HerokuEmpFE-deployed.png "Screenshot of App UI Heroku Deployment"

![Heroku FE 2 Deployment][FEHero2]

[FEHero2]: https://github.com/CrystalMorris/MVPortfolio/blob/main/personal-projects/HerokuEmpFE-pg2-deployed.png "Screenshot of App UI Heroku Deployment"

![Heroku FE 3 Deployment][FEHero3]

[FEHero3]: https://github.com/CrystalMorris/MVPortfolio/blob/main/personal-projects/HerokuEmpFE-pg3-deployed.png "Screenshot of App UI Heroku Deployment"


+ Git: https://github.com/CrystalMorris/EmployeeDirectoryFE

### Back end API  
+ Hosted on Heroku using ClearDB 


![Heroku Deployment][BEHero]

[BEHero]: https://github.com/CrystalMorris/MVPortfolio/blob/main/personal-projects/HerokuEmpBE-deployed.png "Screenshot of API Heroku Deployment"
+ Git: https://github.com/CrystalMorris/EmployeeDirectoryBE 
---

## Technologies

### Front End UI
- JavaScript
- React 5.0.0
- Node.js - version 12.11.1
- Bootstrap - version 5.1.3
- Axios - version 0.25.0
- Heroku
### Back End API
- Java
- Springboot
- MySQL
- Heroku/ClearDB



---


## Features

- A persistant database
- User friendly interface
- Full CRUD functionality

To-do:

- Implement Authentication and Authorization
- Add bio, image, salary, position fields
- Customize it to a particular company or organizational brand



