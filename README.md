Python Git LFS Server
=====================
This is a Python implementation of a [Git LFS](1) Server. It is designed 
with flexibility in mind, to allow pluggable storage backends, transfer 
methods and authentication methods. 

The implementation is inspired by [node-git-lfs](2).

Installation & Quick Start
--------------------------

### Running using Docker
TBD

### Installing & Running from Source
TBD

### Configuration
TBD

Development
-----------
`py-git-lfs-server` is based on Flask, with the following additional libraries:

* [Flask Classful](http://flask-classful.teracy.org/) for simplifying API 
endpoint implementation with Flask
* [Marshmallow](https://marshmallow.readthedocs.io/en/stable/) for 
input / output serialization and validation
* [flask-jwt-simple](https://flask-jwt-simple.readthedocs.io/en/latest/) for 
handling JWT tokens
* [figcan](https://github.com/shoppimon/figcan) for configuration handling

### Running tests

### Building a Docker image

License
-------
TBD
 

 [1]: https://git-lfs.github.com/
 [2]: https://github.com/kzwang/node-git-lfs