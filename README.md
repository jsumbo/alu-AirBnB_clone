
## Description

This project is the first step in building an AirBnB clone web application. We're creating a command interpreter to manage AirBnB objects. This interpreter lets us perform actions like creating, retrieving, updating, and deleting objects. We're also making classes for AirBnB objects, like Users, States, Cities, and Places, and creating a storage engine for file storage. We'll write tests to make sure everything works.

## Usage

1. Clone the project repository.
2. Go to the project directory.
3. Run the command interpreter with `python3 console.py`.

Now you can use the command interpreter to manage AirBnB objects.
How to use
In interactive mode
$ ./console.py
(hbnb) help
Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb)
(hbnb)
(hbnb) quit
$
In non-interactive mode
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
Functions of the consonle
quit: Quit command to exit the program

EOF: method to EOF to exit with (CTRL + D)

empyline: an empty line + ENTER shouldn’t execute anything

create: Create a new object (ex: a new User or a new Place)

show: Prints the string representation of an instance based on the class name and id.

destroy: Deletes an instance based on the class name and id

all: Prints all string representation of all instances based or not on the class name.

update: Update attributes of an object
## Contributors

- [Jallah Sumbo ](https://github.com/jsumbo) 
- [Abubakar Ahmed] (https://github.com/abubakar-ahmed) 
