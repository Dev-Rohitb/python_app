# Python App Repository

This repository contains a Python application that performs a certain task, as well as a folder for tests. This Readme.md file provides instructions for running the application, testing it, and Dockerizing it.

#Prerequisites
To run this application, you need to have Python 3 installed on your machine. You can download it from the official website: https://www.python.org/downloads/
Additionally, 
if you want to Dockerize the application, you need to have Docker installed on your machine. You can download it from the official website: https://www.docker.com/get-started

# Running the Application
1.	Navigate to the python_app/task folder in the terminal/command prompt.
2.	Inside this folder, you will find another folder named task. This folder contains the Python script that performs the task. To run the script, enter the following command:
bashCopy code
python python_app.py 

This will execute the Python script and output the result of the task.


# Testing the Application
1.	Navigate to the python_app/test folder in the terminal/command prompt.
2.	Inside this folder, you will find another folder named tests. This folder contains the Python script that performs the tests. To run the tests, enter the following command:
bashCopy code
python -m unittest test_order_data_analysis.py 

This will execute the test script and output the results of the tests.


# Dockerizing the Application
1.	Navigate to the python_app folder (in Respective Test and Task Folder) in the terminal/command prompt.
2.	Create a Docker image by running the following command:

bashCopy code
docker build -t python_app . 

This will create a Docker image with the tag python_app based on the Dockerfile in the python_app folder.
3.	Run the Docker container by executing the following command:
bashCopy code
docker run python_app 

This will start the Docker container and execute the Python script inside it. The output of the script will be printed to the terminal.


