# Restaurant Menu App

# Objective:
Restaurant Menu App is a simple web application developed as part of learning CRUD functionalities in Udacity Full Stack Nano Degree Programming.  The objective of this app is to create, edit, delete and display restaurants list and their menus. This application is created using python,Flask, SQLite.

# Requirements:
Display list of Restaurants and their menus.
Add, Edit and Delete Restaurants
Add, Edit and Delete Menu for a Particular Restaurant.

# Setup
We use a virtual machine (VM) to run a web server and a web app that uses it. The VM is a Linux system that runs on top of your own machine. You can share files easily between your computer and the VM. We use the Vagrant software to configure and manage the VM. Here are the tools you'll need to install to get it running:

# Install Git
If you don't already have Git installed, download Git from git-scm.com. Install the version for your operating system. On Windows, Git will provide you with a Unix-style terminal and shell (Git Bash). (On Mac or Linux systems you can use the regular terminal program.) You will need Git to install the configuration for the VM.

# Install VirtualBox
VirtualBox is the software that actually runs the VM. You can download it from virtualbox.org, here.

Install the platform package for your operating system. You do not need the extension pack or the SDK. You do not need to launch VirtualBox after installing it.

**Ubuntu 14.04Note:** If you are running Ubuntu 14.04, install VirtualBox using the Ubuntu Software Center, not the virtualbox.org web site. Due to a reported bug, installing VirtualBox from the site may uninstall other software you need. Vagrant

# Install Vagrant
Vagrant is the software that configures the VM and lets you share files between your host computer and the VM's filesystem. You can download it from vagrantup.com. Install the version for your operating system.

**Windows Note:** The Installer may ask you to grant network permissions to Vagrant or make a firewall exception. Be sure to allow this.

# Terminals to use
Windows: Use the Git Bash program (installed with Git) to get a Unix-style terminal. Other systems: Use your favorite terminal program.

# Run the virtual machine!
Using the terminal, change directory to current working directory, then type **vagrant up** to launch your virtual machine.

Once it is up and running, type **vagrant ssh**. This will log your terminal into the virtual machine, and you'll get a Linux shell prompt.

When you want to log out, type exit at the shell prompt. To turn the virtual machine off (without deleting anything), type **vagrant halt**. If you do this, you'll need to run vagrant up again before you can log into it.

Now that you have Vagrant up and running type vagrant ssh to log into your VM. change to the /vagrant directory by typing cd /vagrant. This will take you to the shared folder between your virtual machine and host machine.

# Download the Project

Run the following command git clone https://github.com/ChandrakalaRatan/Restaurant-App.git

This will give you a directory named Restaurant-App complete with the source code for the flask application, a vagrantfile, and a pg_config.sh file for installing all of the necessary tools.

Now change the directory to Restaurant-App **cd Restaurant-App**

# Running the Restaurant App

Type ls to ensure that you are inside the directory that contains finalProject.py, database_setup.py, restaurantmenu.db,lotsofmenus.py, Vagrantfile, pg_config.sh and two directories named 'templates' and 'static'

Now type **python database_setup.py** to initialize the database.

Type python **lotsofmenus.py** to populate the database with restaurants and menu items. (Optional)

Type **python finalProject.py** to run the Flask web server. In your browser visit http://localhost:5000 to view the restaurant app. You should be able to view, add, edit, and delete menu items and restaurants.

We can Also obtain JSON object from   List all restaurants: http://localhost:5000/restaurants/json. List all menu items for a given RESTAURANT_ID: http://localhost:5000/restaurants/<RESTAURANT ID>/menu/json. List a single menu item: http://localhost:5000/restaurants/<RESTAURANT ID>/menu/<MENU ID>/json
