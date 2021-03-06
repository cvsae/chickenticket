# Chicken Ticket
[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)

Chicken Ticket is a Python powered blockchain solution. Users are encouraged to meander about the codebase, learn the nitty gritty details of what makes a coin tick, fork and design your own coin, or use as your every day cryptocurrency.

### Tech
Chicken Ticket uses a number of technologies:
* [Python 3] - A powerful object oriented programming language, we love it!
* [SQLite] - An ACID-compliant database solution for storing information in a single file, locally.
* [SQLAlchemy] - An ORM for SQL databases in Python.
* [PyCryptodomex] - Low-level cryptographic primitives for making the coin secure
* [ECDSA] - Elliptic Curve Digital Signature Algorithm. Used for generating keys fast and securely.

### Installing from source
Chicken Ticket requires [Python](https://python.org/) 3.5+ to run.

Clone this repository after installing [Git](https://git-scm.com):
```sh
$ git clone https://github.com/Aareon/chickenticket
```

Install the dependencies after cloning:
#### Unix
```sh
$ cd chickenticket
$ python3 -m pip install -r requirements.txt
```
#### Windows
```sh
$ cd chickenticket
$ py -3 -m pip install -r requirements.txt
```

### Development
Want to contribute? We ❤️ pull requests!
Please test code extensively before creating a pull request.
Keep in mind, we are strong supporters of idiomatic and beautiful Python code.

### Todos
 - MOAR TESTS
 - ~~Probably need to generate the genesis block, just saying.~~ Done!
 - ~~Release to the public~~ Done!
 - Peers and Nodes (including websocket handling, etc. Should be fun 😅)
 - Sending and receiving transactions
 - Mining (see: [Allium](https://github.com/JayDDee/cpuminer-opt/blob/master/algo/lyra2/allium.c))
 - Clean up!
 - Graphical Wallet


License
----
GPL
