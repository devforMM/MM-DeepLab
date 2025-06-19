# 🧠 Custom Weight Initializers in PyTorch
This repository contains my personal implementation of weight initialization methods for neural networks with PyTorch.  


## 📚 What’s Inside

I implemented four popular initialization methods:

- **Xavier Normal Initialization**
- **Xavier Uniform Initialization**
- **He Normal Initialization**
- **He Uniform Initialization**

These methods are widely used to stabilize the variance of outputs across layers and improve training convergence.

## 📌 Functions

Each function takes the size of the weight matrix to initialize, and the number of inputs/outputs to the layer.  

### Xavier Normal
    """
    Xavier initialization (normal distribution)
    Args:
        w_matrice_size (tuple): size of the weight matrix
        n_in (int): number of inputs to the layer
        n_out (int): number of neurons in the layer
    Returns:
        torch.Tensor: initialized weight matrix
    """
### Xavier Uniform
    """
    Xavier initialization (uniform distribution)
    Args:
        w_matrice_size (tuple): size of the weight matrix
        n_in (int): number of inputs to the layer
        n_out (int): number of neurons in the layer
    Returns:
        torch.Tensor: initialized weight matrix
    """
### He Normal
    """
    He initialization (normal distribution)
    Args:
        w_matrice_size (tuple): size of the weight matrix
        n_in (int): number of inputs to the layer
    Returns:
        torch.Tensor: initialized weight matrix
    """
### He Uniform7
        """
    He initialization (uniform distribution)
    Args:
        w_matrice_size (tuple): size of the weight matrix
        n_in (int): number of inputs to the layer
    Returns:
        torch.Tensor: initialized weight matrix
    """

