Py4Grid
=======

Python for Grid (Py4Grid) is an easy and flexible python software for job and data management. 


Users interact with the grid middleware through 4 simple python commands: 
- Py4Grid-JobSubmit.py: job submission and transparent upload of big data input files)
- Py4Grid-JobState.py: retrieve job status)
- Py4Grid-JobGetOutput.py: retrieve job outputs and transparent transfer of big data output files back to the user 
- Py4Grid-JobDelete.py: job and file purging. 
The user definitions (the execution envelope, input files, output files, big data transfers, …) are defined through a simple “key=value” configuration file (Py4Grid.cfg) read by the application.
