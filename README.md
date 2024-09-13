# alu-AirBnB_clone

![AirBnB Logo](https://s3.amazonaws.com/alu-intranet.hbtn.io/uploads/medias/2018/6/65f4a1dd9c51265f49d0.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUZTW2RLVB%2F20240913%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240913T121534Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=822c6056cac864b39f922f96d7970dec8e98b5398f9972a1e809a1891053af1b)

### Description of the project

This project is a simple clone of the AirBnB website. The first stage implements a backend interface or console to manage program data(like shell). Console commands allow users to create, update, destroy objects, and manage file storage.

### Description of the command interpreter:

The command interpreter is the same as the shell but limited to a specific use-case of managing the objects of our project:

- Create a new object (ex: a new User or a new Place)
- Retrieve an object from a file, a database etc…
- Do operations on objects (count, compute stats, etc…)
- Update attributes of an object
- Destroy an object

### Tasks Involved:

- put in place a parent class (called `BaseModel`) to take care of the initialization, serialization and deserialization of your future instances
- create a simple flow of serialization/deserialization: Instance <-> Dictionary <-> JSON string <-> file
- create all classes used for AirBnB (`User`, `State`, `City`, `Place`…) that inherit from `BaseModel`
- create the first abstracted storage engine of the project: File storage.
- create all unittests to validate all our classes and storage engine

## How To Start the interpreter

```
./console.py
(hbnb) help

Documented commands (type help <topic>):
========================================
EOF  all  create  delete  destroy  exit  help  q  quit  show  update

(hbnb)
(hbnb)
(hbnb) quit
```

## How to use the interpreter

```
(hbnb) help
```

## Tests

To run all the tests execute the following command:

```
$ python3 -m unittest discover tests
```

You can also run a single test by specifying the test file:

```
$ python3 -m unittest tests/test_models/test_city.py
```

## Authors

- [Irakoze Loraine](https://github.com/IrakozeLoraine) - (l.irakoze2@alustudent.com)
