# Amnesic-Flooding
This is a research project in amnesic flooding in a small world network.
### Definitions

### WATTS-STROGATZ MODEL: 
_The formal study of random graphs dates back to the work of Paul Erdős and Alfréd Rényi.[2] The graphs they considered, now known as the classical or Erdős–Rényi (ER) graphs, offer a simple and powerful model with many applications._

**However the ER graphs do not have two important properties observed in many real-world networks:**

* They do not generate local clustering and triadic closures. Instead, because they have a constant, random, and independent probability of two nodes being connected, ER graphs have a low clustering coefficient.
* They do not account for the formation of hubs. Formally, the degree distribution of ER graphs converges to a Poisson distribution, rather than a power law observed in many real-world, scale-free networks.
* The Watts and Strogatz model was designed as the simplest possible model that addresses the first of the two limitations. It accounts for clustering while retaining the short average path lengths of the ER model. It does so by interpolating between a randomized structure close to ER graphs and a regular ring lattice. Consequently, the model is able to at least partially explain the "small-world" phenomena in a variety of networks, such as the power grid, neural network of C.

### Vertex (Each individual)
**Property of each individual vertex:**
* Index: Index is a unique number given to a node for easy identification of each vertices. Each vertex represents a unique individual.
* Connected Neighbours: Each vertex is surrounded by a number of other vertices called the neighbouring vertices. The neighbouring vertices which are connected with the vertex through a medium are called connected neighbours.
* Memory: Each vertex has a specific amount of memory . This memory is exploited to store unique messages which it receives from its connected neighbouring individuals. 
* Generator: Few of the individuals are generators of messages. The generator generates a unique message and distributes it among its connected neighbouring individuals. 


## Results

### Average Hops per Iteration VS Iteration
#### Memory
![](https://github.com/thecrazyphysicist369/Amnesic-Flooding/blob/main/Results/Average%20Hops%20per%20iteration%20vs%20Iteration/Memory/memory_avghopvsiteration.gif)

#### Nearest Neighbor
![](https://github.com/thecrazyphysicist369/Amnesic-Flooding/blob/main/Results/Average%20Hops%20per%20iteration%20vs%20Iteration/Nearest%20Neighbour/nearest%20neighbour.gif)

#### Shareability
![](https://github.com/thecrazyphysicist369/Amnesic-Flooding/blob/main/Results/Average%20Hops%20per%20iteration%20vs%20Iteration/Shareability/shareability.gif)



### Memory VS Total Hops per Iteration
#### Shareability = 1; Population = 100
![](https://github.com/thecrazyphysicist369/Amnesic-Flooding/blob/main/Results/Memory%20vs%20Total%20Hops%20per%20Iteration/Shareability%201%3B%20Nodes%20100/s1n100.gif)

#### Shareability = 2; Population = 200
![](https://github.com/thecrazyphysicist369/Amnesic-Flooding/blob/main/Results/Memory%20vs%20Total%20Hops%20per%20Iteration/Shareability%202%3B%20Nodes%20200/s2n200.gif)

### Total hops VS per Message
#### Memory
![](https://github.com/thecrazyphysicist369/Amnesic-Flooding/blob/main/Results/Per%20Message%20total%20Hops/Memory/memory.gif)

#### Nearest Neighbor
![](https://github.com/thecrazyphysicist369/Amnesic-Flooding/blob/main/Results/Per%20Message%20total%20Hops/Nearest%20Neighbour/nearest%20neighbors.gif)

#### Shareability
![](https://github.com/thecrazyphysicist369/Amnesic-Flooding/blob/main/Results/Per%20Message%20total%20Hops/Shareability/shreability.gif)

### Total hops per Iteration VS Iteration
#### Nearest Neigbors
![](https://github.com/thecrazyphysicist369/Amnesic-Flooding/blob/main/Results/Total%20hops%20per%20Iteration%20vs%20Iteration/Nearest%20Neighbors/nearest_neighbour.gif)

#### Shareability
![](https://github.com/thecrazyphysicist369/Amnesic-Flooding/blob/main/Results/Total%20hops%20per%20Iteration%20vs%20Iteration/Shareability/shareability.gif)

### Total hops VS Nearest Neighbors
#### Memory
![]()

#### Shareability
![]()

### Total hops VS Shareability
#### Memory=1; Iteration=100
![]()


#### Memory=1; Iteration=100
![]()


#### Nearest Neighbors
![]()


#### Probability
![]()
