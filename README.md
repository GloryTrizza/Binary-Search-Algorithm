# Binary-Search-Algorithm

## Introduction
This program is designed to demonstrate the difference between linear and binary search algorithms by simulating an agent searching for a file in a directory. The program evaluates the average number of steps it takes for the agent to find the file using a binary search algorithm.

## Components
The program consists of two main components: the environment and the agent.

### Environment
The environment is represented by the Environment class and it is responsible for generating a list of files in a directory and selecting one file randomly to be searched for by the agent.

### Agent
The agent is represented by the Agent class and it extends the Environment class. The agent is responsible for finding the selected file using a binary search algorithm. The algorithm is implemented as a static method called binsearch and takes in a list and the target item to be searched for. The method returns the number of steps taken to find the target item.

## Execution
The program is executed by running 20 instances of the simulation where each instance creates an environment and an agent. The agent then uses the binary search algorithm to find the selected file and the number of steps taken is recorded in the performance list. Finally, the average number of steps taken to find the file is calculated and plotted as a graph.

## Conclusion
The program demonstrates that the binary search algorithm takes fewer steps to find the target item compared to a linear search algorithm. This makes binary search a more efficient algorithm for searching large datasets.



