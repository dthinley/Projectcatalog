## Project Overview
This project is a RESTful web application utilizing the Flask framework which accesses a SQL database that populates categories and their items. OAuth2 provides authentication for further CRUD functionality on the application. Currently OAuth2 is implemented for Google Accounts.

## Why This Project?
Modern web applications perform a variety of functions and provide amazing features and utilities to their users; but deep down, it’s really all just creating, reading, updating and deleting data. In this project, you’ll combine your knowledge of building dynamic websites with persistent data storage to create a web application that provides a compelling service to your users.

## What Will I Learn?
•	Develop a RESTful web application using the Python framework Flask
•	Implementing third-party OAuth authentication.
•	Implementing CRUD (create, read, update and delete) operations.

## How to Run?
PreRequisites
1.	Python ~2.7
2.	Vagrant
3.	VirtualBox

## Setup Project:
1.	Install Vagrant and VirtualBox
2. Download or Clone [fullstack-nanodegree-vm](https://github.com/udacity/fullstack-nanodegree-vm) repository.
3. Find the catalog folder and replace it with the content of this current repository, by either downloading or cloning it from
  [Here](https://github.com/dthinley/Projectcatalog).
  
## Launch Project
1.	Launch the Vagrant VM using command:
  Go to project folder:
  $ cd project folder
2. Run the server up by:
  $ vagrant up
3. Get into server:
  $ vagrant ssh
  cd /vagrant
4. run with python
  $ python project.py
4.	Access and test your application by visiting http://localhost:5000.
