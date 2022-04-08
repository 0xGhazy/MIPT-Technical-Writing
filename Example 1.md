# Documentation Description
My #2 issue description on PyPass project

Link: https://github.com/0xGhazy/PyPass/issues/2

Audience: newcomer contributors

Purpose: Describe the required changes/features to be added a new layer of privacy that protect users accounts.

Type: N/A

# Documentation Content
Hey our dear contributors, I'm happy to see you here :)

In this easy/medium issue that aims to improve privacy for user accounts. I suppose to solve this problem the contributor should know the basics of `Python3`, `SQLite3`, and `QtDesigner` and write documentation of the code or contribution he made to help others understand what he has done.

## Problem statement:
at the current time, if the user tries to open the PyPass application the application will open without any authentication layer or process. which threatens the privacy of the user's accounts.

## Suggested solutions:
    Design a login window that appears when the user tries to open the application that asked him to 
    provide a valid username and password that he provides at the setup stage.


### To achieve the previous solution you need to do the following {

- create a new table in the application database `.cores/PyPassdb.sqlite3` to hold the username and password

- ask the user to provide a username and password when he tries to run the application. this step must be in the setup stage `setup.py`

- Design the login window using `QtDesigneer` which uses the `PyQt5` library.

- Implement the authentication function that checks if the provided username and password in the `users` table in the application database

- Implement the method of checking if that is the first time to run the application after turning on the computer. if not the application will run directly without asking him to log in again.

- Creating the documentation that describes the changes made and mentions the technology he uses.
### }

---

- If anything isn't clear to you please inform me, and if you have any other ideas you can describe them below :).

- If you wanna contribute to this issue and don't know how to implement specific steps you can ask me to assign it to you and then help you in finishing your contribution.

All kinds of contributions are accepted even if was a small one. fill it's your place, stay calm and start your coding journey ❤.
