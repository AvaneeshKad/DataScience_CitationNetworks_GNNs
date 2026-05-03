# Citation Network analysis with GNN algorithm

<p>
  This repository implements Graph Neural Network (GNN) architectures to perform node classification and link prediction on citation networks. By representing academic papers as nodes and citations as edges, the project explores how structural relationships and node features (abstracts/keywords) can be leveraged to predict a paper's field or the likelihood of future citations.
</p>

### Project Overview
Citation networks are inherently graph-structured data where the directionality and connectivity provide critical context beyond text alone. This project utilizes frameworks like PyTorch Geometric to implement and compare several state-of-the-art GNN models.

## Key Objectives

- Node Classification: Predict the research category of a paper based on its citation context and features
- Link Prediction: Predict missing or future citations between papers.
- Graph Visualization: Project high-dimensional node embeddings into 2D space using t-SNE to visualize community clustering.
