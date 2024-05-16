# PEOPLE API

The people api project was created to simulate real life API. This project was created as an Application Under Test for the API testing with python project [here](https://github.com/victoriaajuwon/tau-api-testing-in-python/blob/main/README.md).

## Table of Contents
- [SetUp](#Setup)
- [IMPORTANT NOTE](#NOTE)
- [Purpose](#Purpose)


### Setup

1. Clone the repository.
   ```sh
    git clone https://github.com/victoriaajuwon/python-people-api
    ```
2. On another terminal, navigate to the root directory in your terminal
    ```sh
    cd python-people-api
    ```
3. You need to ensure you have virtual environment set up for the project
4. You can pip.  To install pip, follow this [link](https://pip.pypa.io/en/stable/installation/)
5. Install dependencies using pip
    ```sh
    # Create virtualenv, inside the root directory, use the code below
    python -m venv venv
    # Activate virtualenv for windows
    .\venv\Scripts\activate
    # Activate virtualenv for Linux/MacOS
    source venv/bin/activate
    # Install dependencies
    python -m pip install
    ```
6. List of the dependecies used are
   - Flask version 2.2.2
   - "connexion[swagger-ui]==2.14.1" (Ensure to include the double quotes when installing)
   - "flask-marshmallow[sqlalchemy]==0.14.0"
   - You can check the PipFile for the dependencies as well
7. To build the database later in the code, run in your virtual environment
   ```sh
   python build_database.py
   ```
### NOTE

- #### Follow tutorial
  - I followed a tutorial by Philipp Acsany on [RealPython](https://realpython.com/) website to create this project
  - The tutorial is a three-part tutorial
  - The first part can be gotten [here](https://realpython.com/flask-connexion-rest-api/#getting-started)
  - The second part can be gotten [here](https://realpython.com/flask-connexion-rest-api-part-2/)
  - The third part can be gotten [here](https://realpython.com/flask-connexion-rest-api-part-3/)


### Purpose
The purpose of this project is to create AUT for learning and understanding how to use python to automate API testing.
