# NoWay

NoWay is a project designed to help users find the shortest path between two nodes. It provides an easy-to-use interface for calculating the shortest distance between a source and destination node. The project is useful for students and anyone interested in finding efficient paths in a network or graph.

## Demo
- [Demo Link 1](demoLink1)
- [Demo Link 2](demoLink2)

## Features
- Displays the shortest distance between a source and destination.
- Displays the shortest path one must take to reach the destination with minimum distance.

## API Reference

### Get shortest distance between node A and node B
```bash

Parameters:
Parameter	Type	Description
source	integer	Required. The source node.
destination	integer	Required. The destination node.
Example:
To get the shortest distance between node 1 and node 10, you would make a GET request to:

bash
Copy code
GET /shortd/1/10
The response will return the shortest distance between the two nodes.

Tech Stack
Client: React
Server: Flask, Python
Used By
This project is used by the following:

Students of IIT Guwahati
FAQ
How will I obtain my shortest path from source to destination?
Every possible source and destination is mapped with a number ranging from 1 to 64. The path in the application will display the nodes in order to reach the destination.

What do the node numbers represent?
The node numbers represent positions in a predefined map or network where each node corresponds to a point in the path. These numbers are mapped between 1 and 64 for simplicity.

Authors
@siddharthKashyap
