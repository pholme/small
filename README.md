# small
This repository catalogs the network used in the paper "Robustness of small networks" by Jiang, Zhuang, Holme, Mucha, Schwartze.

We divide the networks into 11 categories as follows:

|Category|Number of networks|Description|
|---|---|---|
|animal|639|Animal interaction networks based on observations in the wild or in lab experiments. Nodes are individual animals, and edges indicate that they have interacted or were close to each other during the observation period.|
|vocal|207|Transition networks in animal vocalizations. One node is one sound, and an edge links two sounds that have followed one another in the data.|
|social|197|These are networks of people linked by a number of different types of interaction (friendship, kinship, advice-seeking, etc.)|
|covert|184|Like "social" but uncovered in criminal investigations.|
|graph|162|Graphs mentioned in the combinatorial graph theory literature. Typically, they represent an extreme example, like the Petersen graph, which is the smallest hypohamiltonian graph.|
|transport|53|Nodes are locations connected by an uninterrupted transportation route.|
|abstract|52|Graphs used for benchmarking (of optimization algorithms, etc.) or debugging.|
|art|39|Derived from network-looking art.|
|eco|12|Ecological networks of either trophic or mutualistic interactions. Nodes are species.|
|other|9|Any kind of other graph data, all of unique kinds. A power grid, a molecule (atoms connected by chemical bonds), baseball teams and their matches, etc.|
|chem|8|Molecular species or atoms connected if one can be converted into the other by a chemical or nuclear reaction.|

In the file *small.csv*, you can find all graphs listed with their sizes, types, and references to the literature.

In the file *small.bib*, you can find the bibliographic information indexed in small.csv.
