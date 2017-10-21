# TSP-implementation
Travelling Salesman Problem solution using Randomized hill climbing and Simulated Annealing
This program implements two search strategies for N cities Travelling Salesman Problem with cities being numbered from 0 to N-1. 
This program uses three different cost functions to calculate the cost of the tour.
The program takes the following inputs from the command line :
  1. Number of cities
  2. MEB (The Maximum number of states to be searched by the algorithm)
  3. Enter the cost function either c1 c2 or c3. *Note Please enter c1 for cost function c1 and so on 
  4. Enter the seed
  5. Enter the search strategy. Enter 1 for simple search(randomized hill climbing) and enter 2 for sophisticated search (Simulated Annealing)


Example:
Enter number of cities 
30

Enter MEB 
200000

Enter the cost function 
 Enter either c1 or c2 or c3  
c2

Enter the seed 
26

Enter the search strategy 
 1 for simple 
 2 for SOPH 
2
The cost of best solution 360
The Path of best solution [21, 19, 17, 15, 13, 11, 9, 0, 1, 2, 5, 4, 3, 6, 7, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 29, 27, 25, 23]
The Value of MEB count 200000
