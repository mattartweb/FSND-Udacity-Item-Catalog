# Catalog Project

> Matthew Weber

## About
This project was about setting up a backend database using SQLAlchemy and python calls, generating a website using Flask, and using third-party API to authenticate and authorize.

## To Run

### Requirements:
- Virtualbox VM Software
- Vagrant Software
- Vagrant File provided by Udacity
- Python3

### Setup
1. Install the Virtualbox and Vagrant programs.
2. Use the Vagrant File to generate the the VM.
3. SSH into the Vagrant environment and run the database_setup.py.

### To Run

Boot the Vagrant VM with command `vagrant up`, then connect with the command `vagrant ssh`.

Once you are in the SSH session, use command 'python application.py' to run the web server. Then visit localhost:8000 on your web browser.

You can log in via Google or Facebook, then create a catalog and add items based on the different types of Sports.

### Resources
- Portions of code provided by the Udacity classes Working With CRUD, Creating Google Sign in, and Adding Facebook and other providers. Additionally some code snippets were provided by Google and Facebook for their login setup walkthroughs.
- udacity.com
- console.developers.google.com
- developers.facebook.com
