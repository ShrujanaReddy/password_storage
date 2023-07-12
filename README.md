# Password Vault

This is a simple password vault application implemented in Python. It provides a graphical user interface (GUI) using the Tkinter library and uses SQLite for data storage. The application allows users to securely store their website credentials (website, username, and password) and retrieve them when needed.

## Prerequisites

- Python 3.x
- SQLite
- Tkinter (Python GUI library)

## Installation

1. Clone the repository or download the code files.
2. Install the required dependencies: `pip install tkinter`.
3. Run the script: `python password_vault.py`.

## Features

- Securely stores website credentials (website, username, and password).
- Uses strong encryption to protect stored passwords.
- Supports a master password for accessing the password vault.
- Provides a recovery key for resetting the master password if forgotten.

## Usage

1. Upon first run, the application will prompt you to choose a master password. Enter your desired password twice, and it will be securely hashed and saved in the database.
2. A recovery key will be displayed, which you should save in a secure location. This key can be used to reset the master password if you forget it.
3. After setting up the master password, you will be prompted to enter it every time you launch the application.
4. Once logged in, you can add new website credentials by clicking the "+" button. Enter the website, username, and password, and click "Save" to store them securely.
5. Existing credentials will be displayed in a table, showing the website, username, and an option to delete the entry.
6. To delete an entry, click the "Delete" button corresponding to that entry.
7. To reset the master password, click the "Reset Password" button on the login screen. You will be prompted to enter the recovery key, and if it matches, you can set a new master password.


![image](https://github.com/ShrujanaReddy/password_storage/assets/130744023/7211d511-cef4-4628-a2b6-7932d2336fee)

![image](https://github.com/ShrujanaReddy/password_storage/assets/130744023/bd5262a9-60c6-4598-955e-fd3ceaa71042)

![image](https://github.com/ShrujanaReddy/password_storage/assets/130744023/ec72bef0-72cf-44e4-bf0e-44d5b804afcc)

![image](https://github.com/ShrujanaReddy/password_storage/assets/130744023/d92cc10d-95a0-4808-b9a0-d7431c56b190)

![image](https://github.com/ShrujanaReddy/password_storage/assets/130744023/44146bcd-afaf-43d2-a3c6-bf00dec2ad5b)

![image](https://github.com/ShrujanaReddy/password_storage/assets/130744023/1cd2f333-733b-41ac-8dcd-07e049af7e1c)
