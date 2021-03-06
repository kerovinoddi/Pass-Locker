#  Pass-Locker

#### 28/06/2020

#### By **Kerovin Oddi(https://github.com/kerovinoddi)**

## Description

Pass-Locker is a python application that allows users to store password for all their accounts.It can generate a password for the account.

* cu - create Password Locker account
* lg - log into account
* du - display the names of the users
* gc - create a credential with a generated password
* cc - create a new credential
* dc - display credentials for a logged in user
* dl - delete a credential for a logged in use
* ex - exit the terminal app

## Behaviour Driven Development

  **Search for users**

    Since there is a code for search, when you type short code for search it will return for you app users.

   **Creating an Account**

    There is a short code for creating a new account
    When you type the short code
    You should see a field to enter your details
    When you are done you'll see your account details

   **Login**

   There is short code for log in. When you enter your registered details and they are confirmed to be true then you should logged in succesfully


   **Creating a new Credential**

    After you have successfully logged in, there is a short code to create a new credential
    You should see prompt fields to create a new credentials
    When you submit the details
    You should see a confirmation message


   **Displaying My Credentials**
    If you type the code for displaying credentials you should receive  save credential.



   **Generating Random Password**

    If you wanted an auto generated password for your credentials
    Then you should see a prompt to enter your credential name
    And a prompt to enter the password length
    When you submit your new credential
    Then you should see your created credential with the random password

   **Deleting a Saved Credential**

    Since there is a code to delete a credential
    When you type it
    Then you should be prompted to enter the credential name
    Then you should receive the credential back if it exists
    Then you should be asked to either delete or abort
    When you choose to delete
    Then you should receive a notification of deletion

   **Exiting The Application**

    Since there is a code to exit the app
    When you type it
    Then you should logged out of the account
    Then you should be returned to the main page
    When you type the short code again
    Then you app should close 


## Prerequisites

* Download and install Python3.6

## Setup/Installation

* Clone this repository(https://github.com/kerovinoddi/python-pass-locker) 
* Open a terminal window  navigate to the app folder and type {./run.py} to run the application
* Use the short codes provided to navigate in the application

## Technologies Used

* Python3.6

### License

Copyright (c) 2020  **Kerovin Oddi (https://github.com/kerovinoddi)**


