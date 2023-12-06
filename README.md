# Databse3130 Group Project for the University of Ottawa
CSI3130 Group project

# Team:
Nicolas Bérubé - 300239551

Joseph Peters - 300024207

Joshua Zan - 300242310

# Changes Made
All changes can be found by doing CTRL-F and searching for "//"
The files in the Project folder are the versions in Postgres 8.0, We could not get it to run because we did not have a linux so we converted it to 16.1. 
WARNING the postgres 8.0 version has issues which were solved in 16.1 so it will not work
In the end we got from 520 errors to the build succesfuly compiling and working

# Objective:
new symmetric hash join query operator to replace currnet hash join

# What is a symmetric hashjoin
2 hash tables with two hash functions

# Files to be updated (project folder):

postgreql-160/src/executor/nodeHashJoin. (processing of hash join operator)

postgreql-160/src/executor/nodeHash. (Creating and maintaining hashtable)

postgreql-160/src/optimizer/plan/createplan.c (creates hash join node in queryplan)

postgreql-160/src/include/nodes/execnodes.h (structure of HashJoinState that maintain state of hash join during execution)
