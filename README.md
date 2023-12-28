# Metro-Hub of Kolkata

## Introduction
This is a simple Java program that will take information (name) of the source station and the destination station, of Delhi Metro, 
from the user and display the fare and shortest metro route to reach the destination. It will also be having a metro map for commuter’s better navigation.

## Implementation Details

Main.java cointains all the major code and Heap.java contains heap implementation.

* Graph and Heap Data Structures:
The implementation leverages the Graph data structure to model metro stations, where each station is represented as a node.
Nodes contain essential information such as the station's name, metro corridor, and the lines it connects.

* Edges and Distances:
Edges in the graph represent the connections between two metro stations.
The distance between two stations is utilized as the cost of each edge in the graph.

* Algorithmic Approach:
Various algorithms like Dijkstra, breadth-first search, depth-first search, etc., are employed to find the shortest path between a source station and a destination station.

* Path Calculation:
The chosen algorithms are used to determine the shortest path between the source and destination stations in the metro system.

* Fare Calculation:
The total fare for the metro route is calculated based on the total distance between the source and destination stations.

* Code Organization:
The core implementation is housed in the Main.java file, where the major logic for graph operations and path finding resides.
The heap data structure, crucial for certain algorithms, is implemented in the Heap.java file.

User Interface:
The application provides a user-friendly interface for users to input source and destination stations and receive information about the metro route and total fare.

Dynamic Metro Information:
The system dynamically handles and displays information about each metro station, including its name, metro corridor, and the lines it connects.

Route Visualization:
The determined metro route between the source and destination stations is visualized and presented to the user.
Output Display:

The application displays the metro route information and the total fare to the user after the algorithmic calculations.
By implementing these features, the Metro Hub App provides a robust solution for navigating and calculating fares within a metro system.
