# buzzline-01-aaron

![Python 3.11](https://img.shields.io/badge/Python-3.11-blue?logo=python&logoColor=white)

## Overview: Addictions-Based Monitoring and Notifications

This project has a producer focused on money based addiction terms, dollar amounts, and feelings.  
There is a consumer which is monitoring for certain large dollar figures and alerts if found.
This is an example of how a system can alert for those with certain addictions.

## Task 1. Generate Streaming Data (Terminal 1)


In VS Code, open a terminal.
Use the commands below to activate .venv, and run the generator as a module. 
To learn more about why we run our Python file as a module, see [PYTHON-PKG-IMPORTS](docs/PYTHON-PKG-IMPORTS.md) 

Windows PowerShell:

```shell
.venv\Scripts\activate
py -m producers.basic_producer_aaron
```

## Task 2. Monitor an Active Log File (Terminal 2)

A common streaming task is monitoring a log file as it is being written. 
This project has a consumer that reads and processes our own log file as log messages arrive. 

In VS Code, open a NEW terminal in your root project folder. 
Use the commands below to activate .venv, and run the file as a module. 

Windows:
```shell
.venv\Scripts\activate
py -m consumers.basic_consumer_aaron
```


## Save Space
To save disk space, you can delete the .venv folder when not actively working on this project.
We can always recreate it, activate it, and reinstall the necessary packages later. 
Managing Python virtual environments is a necessary and valuable skill. 
We will get a good amount of practice. 

## License
This project is licensed under the MIT License as an example project. 
You are encouraged to fork, copy, explore, and modify the code as you like. 
See the [LICENSE](LICENSE.txt) file for more.
