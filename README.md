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

The user execution envelope (binary, arguments, input files, output files, …) are defined through a simple “key=value” configuration file (Py4Grid.cfg) read by the application.

3. Instalation
