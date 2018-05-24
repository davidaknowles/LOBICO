# LOBICO

This is a fork of Theo Knijnenburg's LOBICO code to add some details on installation. 

You need to install IBM's CPLEX optimization library to use LOBICO. If you're an academic you can get a free version by signing up for an account and searching for `CPLEX optimization studio` here:
https://ibm.onthehub.com/

If you're not an academic I think there might be free community version? I'll let you work that out. 

Once you've downloaded and installed CPLEX find the matlab subdir (for me it's `/Applications/CPLEX_Studio128/cplex/matlab`) and edit Init.m to be something like
`addpath(genpath('/Applications/CPLEX_Studio128/cplex/matlab'))`

The examples should then run. 

