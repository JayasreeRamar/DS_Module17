# Ex23 Depth First Graph
## DATE:16/04/2025
## AIM:
To compose the code for the function createNode to traverse the graph below in the depth first fashion.

![image](https://github.com/user-attachments/assets/63552824-d0a3-49c6-a473-6db27d1f03e4)

## Algorithm
1. Allocate Memory: Use malloc to allocate memory for a new node of type struct node.
2. Initialize Vertex: Set the vertex field of the new node to the value v.
3. Initialize Next Pointer: Set the next pointer of the new node to NULL.
4. Return Node: Return the pointer to the newly created node.
5. End Function: Complete the function execution.  

## Program:
```
/*
Program to traverse the graph below in the depth first fashion
Developed by: JAYASREE R
RegisterNumber:  212223230087
*/

struct node* createNode(int v) {
  struct node* newNode = malloc(sizeof(struct node));
  newNode->vertex = v;
  newNode->next = NULL;
  return newNode;
}

```

## Output:

![alt text](image-2.png)

## Result:
Thus, the C code for the function createNode to traverse the graph below in the depth first fashion is implemented successfully
