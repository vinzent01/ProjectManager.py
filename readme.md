# Project manager

An program that manages projects tasks

all info are stored on ./data.json

first it checks for global tasks on ~Documentos/tasks/tasks.json
you can change it by changing the **GLOBAL_TASKS_FOLDER** folder path

You can create, activate, deactivate, remove, complete tasks

## Commands

```bash
  Usage: /usr/bin/pManager action [parameters]

  Action : -h 
  Action : tasks add [name, description]
  Action : tasks remove [name]
  Action : tasks list 
  Action : tasks complete [name]
  Action : tasks activate [name]
  Action : tasks deactivate [name]
```

## Todo 

- [ ] Add per project local tasks
- [ ] add Pomodoro timer
