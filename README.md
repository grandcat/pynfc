Pynfc - Python C bindings for libnfc
====================================

Requirements
------------
- libnfc >= 1.7.1
- python >= 3.0

Building and Setup
------------------
The bindings are constructed at runtime using ctypes.
Please ensure that libnfc is correctly installed in one of the system default
paths.

To install this library, just change to `src/` directory and run
`sudo python setup.py install`.

Documentation
-------------
pynfc3 offers basic ctype bindings for the API of libnfc. There is no proper
wrapper to facilitate the data exchange with Python right now.

Using this library needs some experience with ctypes. Nevertheless, it is not so
hard :)
