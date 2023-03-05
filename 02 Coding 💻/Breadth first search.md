#algorithms
___
Find the shortest path between two nodes in an unweighted graph
## Videos
[Video|fullwidth](https://youtu.be/oDqjPvD54Ss)
[Video|fullwidth](https://www.youtube.com/watch?v=rbYxbIMOZkE&ab_channel=Miziziziz)

## Shortest path
Each node In the path has a pointer to the previous node (Linked list)

1. Add start node to the queue
2. Pop node from the queue and check if it's visited before using a map
3. Check if the node is the end node
4. If it's the end node return the path by backtracking to the first node and reversing
5. If not go to 2
## Multiple paths
Same steps but don't immediately return after arriving at the end node and checking if a node is visited or not is by backtracking the path using the previous node