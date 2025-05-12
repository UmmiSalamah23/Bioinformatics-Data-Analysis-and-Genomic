
# Phylogenetic Analysis with MEGA

## Description

This project compares four phylogenetic tree-building methods to evaluate their effectiveness in determining evolutionary relationships among bacterial 16S rRNA sequences: Neighbor-Joining (NJ), Maximum Likelihood (ML), Maximum Parsimony (MP), and UPGMA.
Methods Overview:
- Neighbor-Joining (NJ): A distance-based method that groups taxa by minimizing branch lengths. Fast and simple but less statistically robust than ML.
- Maximum Likelihood (ML): Estimates the tree topology that is most likely based on the data and evolutionary model. It’s statistically robust, especially for complex datasets.
- Maximum Parsimony (MP): Seeks the tree with the fewest evolutionary changes. Effective for simpler data but less reliable for more complex relationships.
- UPGMA: Assumes a constant rate of evolution and constructs a hierarchical tree based on pairwise distances. Less reliable if the molecular clock assumption is violated.

## Tools
- MEGA X
- ClustalW (built-in)
- Bootstrap Analysis

## Output
### Maximum Likelihood Tree
![Maximum Likelihood](https://github.com/user-attachments/assets/a6642d5a-14f6-4176-8725-1293a5891279)

### Maximum Parsimony Tree
![Maximum Parsimony](https://github.com/user-attachments/assets/6cfde645-5903-46a2-b0a2-7db84b4d197b)

### Neighbor Joining Tree
![Neighbor Joining Trees](https://github.com/user-attachments/assets/67b9cacb-4b0e-4691-a900-9a8cbefffb0e)

### UPGMA Tree
![UPGMA](https://github.com/user-attachments/assets/18377e54-d89e-4c78-a133-de0fd2b6f3d6)

## Steps
1. **Import sequences into MEGA**: Import bacterial 16S rRNA sequences into MEGA X.
2. **Align using ClustalW**: Perform multiple sequence alignment using ClustalW.
3. **Build NJ, ML, MP, UPGMA tree with bootstrap**: Construct the phylogenetic tree using the Neighbor-Joining method with 1000 bootstrap replications.
4. **Export and upload the tree**: Export the resulting tree and upload it to the GitHub repository.



