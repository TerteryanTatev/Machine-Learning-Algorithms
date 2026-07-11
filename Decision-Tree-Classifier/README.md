# Decision Tree Classifier 
This folder contains a custom Python implementation of a Decision Tree classification algorithm, focusing on manual recursive tree traversal and structural mapping without high-level ML framework dependencies.

## Implemented Methodology
* **Logical Condition Splitting:** Structuring binary and categorical feature conditions ($X_1, X_2, X_3, X_4$) to segment rows into granular target subsets.
* **Recursive Tree Invariant:** Implementing a recursive traversal function (`g(tree, n)`) that dynamically parses parent-child nested dictionaries to isolate operational leaf nodes.
* **Visual Graph Rendering:** Leveraging the `graphviz` library to plot and export the hierarchical `Digraph` node architectures for transparent decision-path analysis.

## Technologies Used
* **Python 3**
* **Pandas & NumPy:** For managing logical data matrices and multi-feature evaluations.
* **Graphviz:** For algorithmic visualization and structural rendering of the generated decision tree nodes.
