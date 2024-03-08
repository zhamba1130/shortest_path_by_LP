# shortest_path_by_LP
Solve shortest path problems using PuLP, a python library used to model linear programming problems


## Consider a shortest path problem as a linear programming problem
identify the objective function, costs and constraints
![image](https://github.com/zhamba1130/shortest_path_by_PuLP/assets/58042279/facd6655-9742-4d18-98dd-df5f1ed56f8d)


## Constraints
Any complete path must follow the constraints:
![image](https://github.com/zhamba1130/shortest_path_by_PuLP/assets/58042279/ae9523ca-37d4-410f-9809-449f462228f7)

For instance, a complete path A->B->E->F
![image](https://github.com/zhamba1130/shortest_path_by_PuLP/assets/58042279/21ac3f5d-a1e9-45e8-a6dc-5a87d201b905)

It can be represented as a matrix shown below
![image](https://github.com/zhamba1130/shortest_path_by_PuLP/assets/58042279/bac72a1c-ede2-4dfa-b100-e57578ead9ee)

Pic below explains that the path follows the constraints
![image](https://github.com/zhamba1130/shortest_path_by_PuLP/assets/58042279/5c3cf0c2-fc71-441c-bc9c-488691d4ccec)
