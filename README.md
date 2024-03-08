# shortest_path_by_LP
Solve the shortest path problem using PuLP, a python library used to model linear programming problems  

## Consider a shortest path problem as a linear programming problem
In order to solve a shortest path problem by using PuLP, the problem should be transformed into a linear programming problem.  
  
First, identify the objective function, costs and constraints
<p align="center"><img src="https://github.com/zhamba1130/shortest_path_by_PuLP/assets/58042279/facd6655-9742-4d18-98dd-df5f1ed56f8d.jpg" width="800" height="450">

## Constraints
Any complete path must follow the constraints:  
<p align="center"><img src="https://github.com/zhamba1130/shortest_path_by_PuLP/assets/58042279/ae9523ca-37d4-410f-9809-449f462228f7.jpg" width="400" height="100">  
  
For instance, a complete path A->B->E->F  
<p align="center"><img src="https://github.com/zhamba1130/shortest_path_by_PuLP/assets/58042279/21ac3f5d-a1e9-45e8-a6dc-5a87d201b905.jpg" width="250" height="150">  
  
can be represented as a matrix shown below  
<p align="center"><img src="https://github.com/zhamba1130/shortest_path_by_PuLP/assets/58042279/bac72a1c-ede2-4dfa-b100-e57578ead9ee" width="170" height="150">  
  
Figure below explains how the path follows the constraints  
<p align="center"><img src="https://github.com/zhamba1130/shortest_path_by_PuLP/assets/58042279/5c3cf0c2-fc71-441c-bc9c-488691d4ccec" width="800" height="450">  

## PuLP
Tutoral: https://coin-or.github.io/pulp/  

## Find the shortest path between two points on a graph  
A graph with 250 randomly-generated points  
<p align="center"><img src="https://github.com/zhamba1130/shortest_path_by_PuLP/assets/58042279/36b5e4b6-9dac-4087-a199-112aa46d3448.jpg" width="400" height="300">  
  
Successfully find the shortest path between p1 to p2 
<p align="center"><img src="https://github.com/zhamba1130/shortest_path_by_PuLP/assets/58042279/b285a223-f1b6-4702-8b07-5f4c199685a2.jpg" width="400" height="300">  

Successfully find the shortest path between p89 to p250 
<p align="center"><img src="https://github.com/zhamba1130/shortest_path_by_PuLP/assets/58042279/a807eeb5-51e7-4f35-ba97-f65ac122da67.jpg" width="400" height="300">  
