# NetworkHierarchy

graph_edge.txt:
Each line records one directed edge in the TF-TF network.
Column one is the id of the source node and column two is the id of the target node.

TF_id.txt:
Each line represents the name for one transcription factor (TF).
So in this TF-TF network, we have 101 nodes and 4819 edges.

We want to use some graph neural network methods to get the latent representation of each node (TF),
and then use some unsupervised clustering methods to explore the network hierarchy.
