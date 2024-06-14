# Project manager

An program that manages projects tasks

all info are stored on ./data.json

first it checks for global tasks on /etc/projectManager/tasks.json 
and it checks for local tasks on ./tasks.json

can create, activate, inactivate, complete tasks

## Commands

``sh
projManager.py task add [name] [description]
projManager.py task remove [name]
projManager.py task complete [name]
projManager.py task list
``