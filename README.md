# AirBnB clone - The console

![Airbnb_logo](https://user-images.githubusercontent.com/111001850/218263253-43c8fff1-720f-4b5f-9f62-e2fdee781765.png)

## Description
The goal of the project is to deploy on my server a simple copy of the AirBnB website.

## Execution
Your shell should work like this in interactive mode:
```
$ ./console.py
(hbnb) help

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb) 
(hbnb) 
(hbnb) quit
$
But also in non-interactive mode: (like the Shell project in C)

$ echo "help" | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb) 
$
$ cat test_help
help
$
$ cat test_help | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb)
$
```
## Parts
### I. The Console
- Create my data model.
- Manage (create, update, destroy, etc) objects via a console / command interpreter.
- Store and persist objects to a file (JSON file).
