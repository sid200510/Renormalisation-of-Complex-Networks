# Renormalisation-of-Complex-Networks
The flow of complex networks should be consistent with its governing mechanism. We propose an algorithm for renormalisation of complex networks incorporating its underlying governing mechanism.
The algorithm uses probabilistic embedding of nodes of a network into a low dimensional space using variational encoders. The likeliness of a graph in reconstruction is estimated through a variational decoder. The model is trained to maximize ELBO. With the Battacharyya distance as a metric is the latent space, nearby nodes are grouped together. The probabilistic embedding of the supernode endows a hierarchical embedding across scales. The relavant decoder specific to a scale is trained in accordance to the RG condition.

'RG_complex_networks.pdf' contains a detailed presentation of the scheme. 'RG_VAE_gpu.ipynb' contains the implimentation tailored for performance through GPUs.  
