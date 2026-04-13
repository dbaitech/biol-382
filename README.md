# A Scalable Framework for Hodgkin–Huxley Neuronal Networks with Feedback and Synaptic Scaling

[Giannari et al.](https://doi.org/10.1016/j.neucom.2022.04.115) created a scalable, adaptable and modular framework to accurately simulate the action potentials of neurons in networks with distinct firing patterns and different types of coupling. It is based on the original Hodgkin-Huxley differential equation, augmented to include extra ion channels to model 3 different neuron types: FS, RSA and IB. 

More importantly, in the original HH model, the injected current is supplied into the neuron from an abstract environmental source and constitutes the only exogenous driver of changes in membrane potential. However, pre-synaptic neurons contribute to the injected current received by a post-synaptic neuron so that the individual neuronal dynamics are controlled not only by external input but also by the structure of the network. The model uses graph theory to  incorporate this feedback arising from the underlying network structure.

This repository contains the following files:
1. reimplementation.ipynb: Reimplements a selection of the original paper's model validations (see Section 5 of Giannari et al.)
2. synaptic_scaling_extension.ipynb: Implements and demonstrates the synaptic scaling novel extension

## Citations
Giannari, A. G., & Astolfi, A. (2022). Model design for networks of heterogeneous Hodgkin–Huxley neurons. Neurocomputing, 496, 147–157.
https://doi.org/10.1016/j.neucom.2022.04.115
