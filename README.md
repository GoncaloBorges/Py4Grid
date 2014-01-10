Py4Grid
=======

1. Introduction

Python for Grid (Py4Grid) is an easy and flexible python software for job and data management in EGI grid infrastructures. It abstracts users from the complexity of grid UMD middleware allowing individual researchers to transparently interact with grid resources without the need to understand major architecture and/or technical concepts.

2. Basic Functionality

Users can submit, copy, delete and retrieve grid jobs and input/output data through 4 simple python commands: 
- Py4Grid-JobSubmit.py: job submission and transparent upload of big data input files;
- Py4Grid-JobState.py: retrieve job status;
- Py4Grid-JobGetOutput.py: retrieve job outputs and transparent transfer of big data output files back to the user;
- Py4Grid-JobDelete.py: job and file purging. 

The user execution envelope (binary, arguments, input files, output files, …) are defined through a simple “key=value” configuration file (Py4Grid.cfg) read by the application. The Py4Grid application is responsible for building the JDLs and prolog and epilog scripts dealing with data transfers. 

3. Instalation

Execute the following instruction under your bash environment. Otherwise, adjust them to the proper shell environment you are working with.
- Download the py4grid-X.X.X.tgz
- tar xzvf py4grid-X.X.X.tgz
- export PYTHONPATH=$PWD/py4grid/X.X.X/include/Py4GridModules:$PYTHONPATH
- export PATH=$PWD/py4grid/X.X.X/bin:$PATH
- export PY4GRIDHOME=$PWD/py4grid/X.X.X
- cp $PY4GRIDHOME/templates/config/Py4Grid.cfg .
- vi Py4Grid.cfg (adjust your execution envelope)
