# alu-AirBnB_clone

![AirBnB Logo](https://s3.amazonaws.com/alu-intranet.hbtn.io/uploads/medias/2018/6/65f4a1dd9c51265f49d0.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUZTW2RLVB%2F20240913%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240913T121534Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=822c6056cac864b39f922f96d7970dec8e98b5398f9972a1e809a1891053af1b)

### Project description

In this project, we will implement the console component of the AirBnB clone project.

Our task involves developing a command interpreter to manage various AirBnB objects.

### Description of the command interpreter:

Do you remember the Shell? It’s exactly the same but limited to a specific use-case. In our case, we want to be able to manage the objects of our project:

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
