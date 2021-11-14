<h1> AirBnB_clone </h1>

The goal of the project is to deploy on your server a simple copy of the AirBnB website.

The AirBnB website operates an online marketplace for travel information and booking services. The Company offers lodging, home-stay, and tourism services via websites and mobile applications. Airbnb serves clients worldwide.

<h2>Files and Directories</h2>

* <b>models</b> directory will contain all classes used for the entire project. A class, called “model” in a OOP project is the representation of an object/instance.

* <b>tests directory</b> will contain all unit tests.

* <b>console.py</b> file is the entry point of our command interpreter.

* <b>models/base_model.py</b> file is the base class of all our models. It contains common elements:

* <b>attributes:</b> id, created_at and updated_at

* <b>methods:</b> save() and to_json()

* <b>models/engine</b> directory will contain all storage classes (using the same prototype). For the moment you will have only one: file_storage.py**
