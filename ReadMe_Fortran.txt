This folder contains the FORTRAN code:

TestBenford_public.for

that can be used for replicating the simulation results presented in the article:
"Who is Afraid of Benford-Savvy Data Manipulations?".

The input files required by the FORTRAN code are archived in file: 

TestBenford_input.zip

Each input file also includes a brief description of the parameters that the file contains.

The Fortran program makes use of some IMSL functions and routines. 
A compatible version (i.e., a version without IMSL routines) can be run from Matlab using 
a wrapper to the source file compiled using the mex function.