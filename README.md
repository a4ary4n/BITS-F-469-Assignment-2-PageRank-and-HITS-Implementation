# IR-Assignment-2-2022
This is the repository for IR assignment of CS F469 made by

Petlozu Sujith (2018AAPS0365H)

P Sree Vishnusai Karthik (2018A3PS0526H)

Aryan Surana (2018B4A70937H)	

# BITS-F-469-Assignment-2B-HITS-Implementation
Implementing HITS algorithm in python.
Given a query, we can obtain hub scores and authority scores for web pages.

###### procedure
from a given .gpickle file we read the graph and create a list of all page contents using networkx library. We then create base set nd root set, using them we create an adjacency matrix. Using the adjacency matrix we find hub and authority scores in the form of python lists, namely 'u'  and 'v' by multiplying within a loop until steady-state values are reached.

## Example
i/p: query word

![7d3e9177-523e-40ff-b61e-d9bb9dbf9320](https://user-images.githubusercontent.com/74662983/166210203-9138ac6e-7699-4662-858c-959429919e66.jpg)

![7690afe2-a909-4389-86cb-993b7b456212](https://user-images.githubusercontent.com/74662983/166210217-0f5bf71a-2285-4215-abca-9f7b09d1efde.jpg)

# BITS-F-469-Assignment-2A-PageRank-Implementation
implementing PageRank algorithm in python.
## Using algebra packages
MX=X implementation using numpy.linalg where M is the transition matrix and X is the eigen vector containing page ranks.
###### Procedure
Made a lin_alg() function to calculate effective transition matrix using damping factor and solved for pageranks.

## Using power iteration on transition matrix
(M)^k x V implementation using poweriteration function.
###### Procedure
Implemented function power_iter() Matrix M is multiplied with itself for given input number of iterations and further multiplied with the initial equal probability vector.

Added a conv_pi() function to iterate until convergence.

## example
i/p:

no of vertices <space> no of edges \n

give all the directed connections between the nodes.
  
![31b36278-6f47-4fa1-ad6b-dbbff399b434](https://user-images.githubusercontent.com/74662983/166210356-1b0c4e90-8c5c-4a0b-96be-2d1555735363.jpg)

  

  
  
  


