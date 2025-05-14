<img width="712" alt="Screenshot 2025-05-14 at 2 05 44 PM" src="https://github.com/user-attachments/assets/6ee5fd0c-1a84-4f3c-9906-bc60bfb2742d" />
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
<img width="713" alt="Screenshot 2025-05-14 at 2 07 01 PM" src="https://github.com/user-attachments/assets/c02d907d-15b2-4620-9cc7-35dd9c7205b3" />
### Maximum Parsimony Tree
![Uploading Screenshot 2025-05-14 at 2.09.52 PM.png…]()

### Neighbor Joining Tree
![Uploading Screenshot 2025-05-14 at 2.05.44 PM.png…]()
### UPGMA Tree
<img width="710" alt="Screenshot 2025-05-14 at 2 08 58 PM" src="https://github.com/user-attachments/assets/810cb631-c3c3-41ac-b5a0-68f804f14a6a" />

## Steps
1. **Import sequences into MEGA**: Import bacterial 16S rRNA sequences into MEGA X.
2. **Align using ClustalW**: Perform multiple sequence alignment using ClustalW.
3. **Build NJ, ML, MP, UPGMA tree with bootstrap**: Construct the phylogenetic tree using the Neighbor-Joining method with 1000 bootstrap replications.
4. **Export and upload the tree**: Export the resulting tree and upload it to the GitHub repository.



