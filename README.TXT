Big Data in Finance final exam, Part B1, calculating PI using MPI
=================================================================

The MPI program has several bugs. These bugs can be in the C code,
the makefile, or the PBS job file. Your task is to find these bugs,
fix them, compile and run the program, then share your results.

In this file, write any thoughts or comments that might help
improve your grade.

A hint to help you on your way. Remember that make uses tabs to indent
the commands below targets.

And, remember, to use Git you must first load Git:

  module load git
  
These may also be useful commands:

  module list
  
  module avail
There are 2 mistake
1. The fomular error in mpi.c
    correct fomular should be 4/(1+x*x)
2. makefile error
the source is mpi.c not mpi.cpp
output is mpi.exe not mpi
