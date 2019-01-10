# Restaurant Menu App
## Objective:
##### Restaurant Menu App is simple web application developed as part of learning CRUD functionalities in Udacity Full Stack Nano Degree Programming.  The objective of this app is to create, edit, delete and display list of many restaurants and their menus. This application is created using python,Flask, SQLite.
## Requirements:
1.  Display list of Restaurants and their menus.
2.  Add, Edit and Delete Restaurants
3.  Add, Edit and Delete Menu for a Particular Restaurant.
## System Requirements and Setup
1.  Download Vagrant from Download it from vagrantup.com. and install.
2.  Download the VM configuration frome FSND-Virtual-Machine.zip and install.
3.  Download and install sqlalchemy package from  https://www.sqlalchemy.org/
4.	To install flask, Use the following commands:
##    $ pip install flask==0.9
5.  To Start the vagrant virtual machine, run the following command on terminal: 
##      $vagrant up.
6.  To connect to the virtual machine, run the following command on terminal: 
##      $vagrant ssh 
7.  To change directory to this project, run the following command on terminal: 
##      $cd /vagrant/finalproject/
8.  To Initialize the database and fill data in the database, run the following command
##     $ python database_setup.py
##     $ python lotsofmenus.py
9.  Run the web app finalproject.py:
##     $ python finalproject.py

##  Result:
1.  The app runs on port 5000: http://localhost:5000/, we can view, add, delete, edit restaurants and their menus
2.  We can Also obtain JSON object from 
3.  List all restaurants: http://localhost:5000/restaurants/json
4.  List all menu items for a given RESTAURANT_ID: http://localhost:5000/restaurants/<RESTAURANT ID>/menu/json
5.  List a single menu item: http://localhost:5000/restaurants/<RESTAURANT ID>/menu/<MENU ID>/json
