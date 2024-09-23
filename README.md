# Graph Neural Networks Coursework
Project Overview

This repository contains a coursework project completed for the Deep Graph-Based Learning course at Imperial College London. The coursework focuses on implementing and experimenting with various machine learning algorithms and techniques related to graph neural networks (GNNs). Throughout the project, several key concepts were explored, including centrality-based graph classification, GraphSAGE, attention-based aggregation, and propagation rules integrating edge features.
Key Concepts and Algorithms

The coursework is divided into multiple parts, each focusing on a different aspect of graph neural networks:

    Centrality-Based Graph Classification:
        In this part, centrality measures were used to classify nodes within a graph. Centrality metrics such as degree centrality, closeness centrality, and betweenness centrality were applied to perform graph classification tasks.

    GraphSAGE with Node Sampling:
        Implemented the GraphSAGE algorithm, a popular framework for learning node embeddings in large graphs. The algorithm incorporates node sampling to efficiently handle large graphs by aggregating information from a subset of neighboring nodes.

    Attention-Based Aggregation in Node Classification:
        Built a Graph Attention Network (GAT) to perform node classification. This method uses an attention mechanism to weigh the importance of neighboring nodes during the aggregation process, enhancing the model's ability to capture more informative features.

    Propagation Rule with Edge Features/Embeddings:
        Extended the graph convolutional network (GCN) propagation rule by incorporating edge features/embeddings. This allows the model to consider both node and edge attributes, improving its expressiveness and ability to model more complex relationships within the graph.

Methodology

Throughout the coursework, I explored different ways of representing graph-based data and experimented with various architectures and techniques:

    Graph Representation: Converted raw graph data into formats suitable for GNNs, including adjacency matrices and node feature matrices.
    Node Sampling (GraphSAGE): Applied node sampling strategies to efficiently handle large-scale graphs by only aggregating information from sampled neighbors, reducing computation time.
    Attention Mechanism (GAT): Implemented an attention-based aggregation function that assigns different weights to neighboring nodes, allowing the model to focus on the most relevant neighbors.
    Edge Feature Integration: Extended GCN models by incorporating edge features/embeddings into the propagation rule to capture both node and edge information for more accurate predictions.

Hyperparameter Tuning and Experiments

To improve the performance of the models, I conducted experiments with different hyperparameters, including:

    Learning rates
    Number of layers
    Hidden dimensions
    Batch sizes
    Sampling rates in GraphSAGE
    Number of attention heads in GAT

The experiments aimed to find the optimal model configurations for each task, with performance evaluated using metrics such as accuracy, F1-score, and loss.
Project Structure

    Part 1: Centrality-Based Graph Classification
    Part 2: GraphSAGE with Node Sampling
    Part 3: Attention-Based Aggregation (Graph Attention Networks)
    Part 4: Propagation Rule with Edge Features/Embeddings
    README.md: This file, providing an overview of the project and instructions on how to run the code.

Learning Outcomes

Through this coursework, I gained hands-on experience with graph neural networks and the challenges of applying machine learning to graph-structured data. The project provided insights into:

    How different graph-based algorithms perform in various node and graph classification tasks.
    The power of GNNs in learning representations from complex, structured data.
    How edge features can enhance model performance and the importance of attention mechanisms in improving feature aggregation.
