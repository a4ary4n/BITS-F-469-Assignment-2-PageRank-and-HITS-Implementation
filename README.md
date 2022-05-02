# IR-Assignment-2-2022
This is the repository for IR assignment of CS F469 made by

Petlozu Sujith (2018AAPS0365H)

P Sree Vishnusai Karthik (2018A3PS0526H)

Aryan Surana (2018B4A70937H)	

# BITS-F-469-Assignment-2-PageRank-and-HITS-Implementation

## Using algebra packages
MX=X implementation using numpy.linalg wheere M is the transition matrix and X is the eigen vector containing page ranks
###### Procedure
Made a lin_alg() function to calculate effective transition matrix using damping factor and solved for pageranks

## Using power iteration on transition matrix
(M)^k x V implementation using poweriteration function
###### Procedure
Implemented function power_iter() Matrix M is multiplied with itself for given input number of iterations and further multiplied with the initial equal probability vector

## convergence in power iteration
No of iterations until pageranks will have no change in their order of ranks
###### Procedure
Implemented function conv_pi() that performs iterations until convergence.

## example
i/p:

no of vertices <space> no of edges \n

give all the directed connections between the nodes.
  
Test case:11 20
1 2
2 1
2 3
3 2
3 4
4 3
4 5
5 4
5 6
6 5
6 7
7 6
7 8
8 7
8 9
9 8
9 10
10 9
10 11
11 10

O/p:
  
[8.65697288 9.50309398 9.11157012 9.09194474 9.09096113 9.0909143
 9.09096113 9.09194474 9.11157012 9.50309398 8.65697288]
[8.65697288 9.50309398 9.11157012 9.09194474 9.09096113 9.0909143
 9.09096113 9.09194474 9.11157012 9.50309398 8.65697288]
2 iterations until convergence
[8.65681818 9.50340909 9.11136364 9.09204545 9.09090909 9.09090909
 9.09090909 9.09204545 9.11136364 9.50340909 8.65681818]
time :0.00015860899975450593
  

  

  
  
  


