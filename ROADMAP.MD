## simple-lang roadmap

The to dos are executed without order, mostly the most needed or simplest issue is taken up first. 
For any type of addition or subtraction to the simple-lang the **request for comment (rfc)** should be use, you can check 
out how to make  a **rfc** in the [rfc](https://github.com/simple-lang/rfcs) repository by reading the 
[readme file](https://github.com/simple-lang/rfcs/blob/master/README.md)

The roadmap is divided into sections
- [General](#general)
- [Modules](#modules)
- [Environments](#environments)

### General

These are features which apply to the general construction of the core of the language which includes the compiler, interpreter
build, installation, features e.t.c 

- [x] create the simple-lang interpreter 
- [x] create a working installer script to enable installation with curl and bash or shell script [working issue](https://github.com/simple-lang/simple/issues/24)
- [ ] build a compiler to allow faster program execution - simplify
- [x] make vm search for **call** files in 5 folder. 
	- [x] 1 absolute to path
	- [x] 1 relative to modules folder in working directory
	- [x] 2 in relative to environment SIMPLE_PATH
	- [x] 1 in relative to installation folder per os 
- [x] write build script for building simple-lang core, environment and modules for windows os
- [x] write build script for building simple-lang core, environment and modules for linux os
- [ ] write build script for building simple-lang core, environment and modules for mac os
- [ ] write build script for building simple-lang core, environment and modules for haiku os
- [x] make linux build script generate .deb and .zip package
- [ ] presence of simple-lang codes and snippets on rosetta codes [working issue](https://github.com/simple-lang/simple/issues/20)
- [x] IRC or gitter channel for simple-lang [working issue](https://github.com/simple-lang/simple/issues/25)
- [ ] write documentation to get started with developing with simple lang
- [ ] build the language website
- [ ] write a comprehensive book on developing with simple-lang
- [ ] re write the simple-lang interpreter with lot of optimization and split into in dependable parts
- [x] load shared library in linux [working issue](https://github.com/simple-lang/simple/issues/8)
- [ ] load shared library on MAC
- [x] load shared library on windows
- [ ] load shared library on haiku os
- [x] writing a vscode extension [working issue](https://github.com/simple-lang/simple/issues/13)
- [ ] add the simple-lang to the github language repository - linguistic 
- [ ] create simple-lang tag in stack overflow and simlar forums
- [ ] a suitable, befitting and upto date README on github repository
- [x] build script should build .lib for windows os
- [x] build script should create a .a archive for statically linking simple-lang runtime on windows os
- [ ] build script should create a .a archive for statically linking simple-lang runtime on linux os
- [ ] build script should create a .a archive for statically linking simple-lang runtime on mac os
- [ ] build script should create a .a archive for statically linking simple-lang runtime on haiku os

### Modules

To dos and features relative to the simple-lang standard modules which includes new modules addition, module modification or any other
issue related to the module

- [ ] create the input output (io) module which include File, Path, Directory, PathAttribute, PathType, FileStream
- [ ] create all high level data types [working issue](https://github.com/simple-lang/simple/issues/15)
- [ ] init functional console module to simplify working with command line and terminal 
- [x] building a better debugging module [working issue](https://github.com/simple-lang/simple/issues/17)
- [ ] develop the complete functional GUI module (fulltick) using the fltk c++ library
- [ ] port qt library to simple-lang for a higher GUI module 
- [ ] create database module for simple-lang which includes mysql, sqlite, odbc and access
	- [ ] build the mysql database module
	- [ ] build the sqlite database module
	- [ ] build the odbc database module
	- [ ] build the access database module
	- [ ] build the postgresql database module
- [ ] build the internet module using curl as the back bone
	- [ ] make curl request and accept both http and https protocols
- [ ] build a web module for cgi and template base development
- [x] Math module to treat any form of basic math operation
- [x] date and time module 
- [ ] conversion module to convert between objects and types 
- [ ] system, simplex and runtime module
- [x] create the hash module 
- [x] a basic encrypt and decrypt module that uses keys and IV
- [ ] port murmur hash C library to simple-lang

### Environments

- [ ] build a semi-intelligent small simple-lang editor - simplepad [working issue](https://github.com/simple-lang/simple/issues/18)
- [ ] build package installer - modular [working issue](https://github.com/simple-lang/simple/issues/18)
	- [x] modular install and upgrade new module, doc and dynamic module added to the package index
	- [ ] modular clone and install module from github repository
	- [x] upgrade simple-lang distro on the system from either dev or stable version
	- [ ] test full operation on windows os
	- [ ] test full operation on linux os
	- [ ] test full operation on mac os
	- [ ] test full operation on haiku os
- [x] create the language repl - simplerepl 
- [x] Build the minifier environment that reduces module size by compressing code upon installation.
- [ ] create the distribution program - bake
	- [ ] package simple source file (.sim) or compiled file (.complex) to system executable
	- [ ] package simple source file (.sim) or compiled file (.complex) to system library or simple-lang specific library
	- [ ] create directory for generated output
	- [ ] allow static or dynamic linking of simple-lang runtime
	- [ ] minify and build a distributable modules and dynamic modules for distribution
	- [ ] test full operation on windows os
	- [ ] test full operation on linux os
	- [ ] test full operation on mac os
	- [ ] test full operation on haiku os




