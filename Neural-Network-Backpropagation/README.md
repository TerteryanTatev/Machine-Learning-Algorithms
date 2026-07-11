# Neural Network with Backpropagati
This folder contains a custom Python implementation of a Multi-Layer Perceptron (MLP) Neural Network, focusing on manual gradient tracking and mathematical backpropagation logic without relying on high-level DL libraries (like TensorFlow or PyTorch).

##  Implemented Methodology
* **Forward Propagation:** Computing linear vector dot-products followed by Sigmoid activation mappings to transition from the input array through hidden node vectors up to the final output predictions.
* **Analytical Error Gradients:** Structuring partial derivatives via the mathematical Chain Rule to compute exact error metrics for both hidden and output weight nodes.
* **Stochastic Weight Optimization:** Dynamically updating synaptic weights ($W, V$) and biases across iterative training epochs based on explicit learning rate factors.

##  Technologies Used
* **Python 3**
* **NumPy:** For managing dense layer matrix alignments and mathematical execution tracks.
