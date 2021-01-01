# Recon Rover

This repository hosts all the code for the project Recon Rover, original as it was in October, 2017. Here is a brief overview of the files, folders, and structure of the project. Please note that you will likely not be able to execute majority of the files without access to the exact robot with the myRIO.


## Overall structure
* The LabVIEW project `Recon Rover.lvproj` is the place to start if you want to access the files.
* The project consists of three systems: the computer where the user interacts, the myRIO real-time target, and the myRIO FPGA target.

## Important files and folders
* `Real Time` has files that run on the myRIO real-time, and the files that run on the computer.
* `FPGA` has the files that run on the myRIO FPGA target
* `Main myRIO.vi`, and `Main myRIO (WTSS).vi` run on the real-time target.