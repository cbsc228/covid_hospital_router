Hospital Routing for Covid

----DESCRIPTION----
This program is intended to route an incoming stream of patients to the best suited
hospital for them based on a few criteria such as condition, location, and hospital
capacity. This is implemented using an OrientDB graph database in order to create
patients as nodes and link them to the appropiate hospital node such that there is
an electronic record of what patient is assigned where.

Using this graph record, the program provided an api output using api.py.

In order to run the program, simply use the command file runProject to start the
necessary programs and instantiate the database.

NOTE
The data stream that this program depends on is no longer active, the database
host is no longer configured, and thus the api output will also no longer function.