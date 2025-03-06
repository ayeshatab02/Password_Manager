# Password_Manager
This is a simple Password Manager application built using Python and the Tkinter library for the graphical user interface (GUI). The application allows users to securely store and retrieve passwords for different websites. It uses SHA-256 hashing to securely store passwords, and the data is saved in a JSON file (passwords.json)

##Features
Password Generation: Automatically generate random passwords with letters, digits, and symbols.
Password Storage: Save passwords securely (hashed) along with website names and usernames.
Password Retrieval: Retrieve saved passwords by searching for the website name.

##How to Use
Run the Python Script:  Open the password_manager.py file in your preferred Python environment or run it from the command line.

Generate a Password:
Click on the Generate Password button to generate a random password for any website.

Save a Password:
Enter the Website Name, Username, and Password in the corresponding fields and click Save Password.
The password will be saved securely with a hashed password in the passwords.json file.

Retrieve a Password:
Enter the Website Name and click Retrieve Password to display the saved username and password hash.

The passwords are hashed using SHA-256 for security

##file Location
The passwords.json file will be created in the same directory as the Python script or Jupyter notebook. This file stores all the saved passwords.
