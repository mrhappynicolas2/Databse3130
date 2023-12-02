# Databse3130 Group Project for the University of Ottawa
CSI3130 Group project

# Team:
Nicolas Bérubé - 300239551

Joseph Peters - 300024207

Joshua Zan - 300242310


# Objective:
new symmetric hash join query operator to replace currnet hash join

# What is a symmetric hashjoin
2 hash tables with two hash functions

# Files to be updated (project folder):

postgreql-160/src/executor/nodeHashJoin. (processing of hash join operator)

postgreql-160/src/executor/nodeHash. (Creating and maintaining hashtable)

postgreql-160/src/optimizer/plan/createplan.c (creates hash join node in queryplan)

postgreql-160/src/include/nodes/execnodes.h (structure of HashJoinState that maintain state of hash join during execution)
