pathgrind
=========

Path based Dynamic Analysis

Requirements
------------
- bzip2
- autoconf
- make
- gcc
- python
- gawk

Installation
------------
$ ./install.sh

Configuration
-------------
Configuration file: fuzz/settings.cfg

Execution
---------
CLI: $ ./fuzz/fuzz.py

GUI: $ ./fuzz/gui.py

Example
-------
$ ./fuzz/fuzz.py test6
  
New input are created in testcase/input/

Crash files are be saved in testcase/crash/
