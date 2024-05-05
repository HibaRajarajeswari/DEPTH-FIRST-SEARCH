# Lab Experiment 2: Depth First Search
## DATE: 17/2/2024
## REGISTER NUMBER:212221040056
# AIM:
## Write a program to implement depth-first search. 
```
graph = {
    '2': ['3', '4'],
    '3': ['5'],
    '4': ['6', '7'],
    '6': [],
    '5': ['6'],
    '7': ['8'],
    '8': []
}

visited = set()  

def dfs(graph, node):  
    if node not in visited:
        print(node, end=" ")
        visited.add(node)
        for neighbour in graph[node]:
            dfs(graph, neighbour)

# Driver Code
print("DFS order is")
dfs(graph, '2')
```
## OUTPUT:
![image](https://github.com/HibaRajarajeswari/DEPTH-FIRST-SEARCH/assets/129970809/0983b8aa-da4b-47e5-aa36-b7c01137d723)
## RESULT:
 A program to implement depth first search is executed successfully.
