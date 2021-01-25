# Foundations of PyTorch

## Course Overview
- Internals of neurons and neural networks
- How such a model is trained
- Gradient descent optimization
- PyTorch constructs
- Build dynamic computation graphs

## Getting Started with PyTorch for Machine Learning

### Module Overview 
- Deep learning using neutral network
- Neurons and activation functions
- Introducing Pytorch to build neural networks
- Understanding the differences between PyTorch and TensorFlow

### Prerequisites and Course Outline

### Presentation Learning Using Neural Network
- Introducing Neural Networks
  - Neural Network: 
    - Deep Learning: Algorithms that learn what featrues matter
    - Neural Networks: Corpus -> Layers (Visible/Hidden) -> ML-based Classifier
    - Neurons: simple building blocks that 'learn' 
  - ML-based:
    - Traditional: rely on experts 
    - Representation: rely on the system itself (Neural Networks?)
## Neuron as a Mathematical Functions
- **The heart of the neural network is a neuron** 
- Neuron:
  - is the active learning unit
  - is just a mathematical function that is applied to the inputs that are fed into a neuron 
    - x -> Mathematical function -> y
    - The outputs of neurons feed into the neurons from the next layer
    - W: weight, measure, how important
    - b: bias
    - tensor
  - Operation of a Single Neuron
    - Affine Transformation: can only learn **linear** when **alone**
    - Activation Function: ?
### Activation Functions
  - combine with The Affine Transformation can **learn any arbitrary relationship**
  - Common Activation Functions: 
    - reLU (rectified linear unit): reLU(x) = max(0,x)
    - logit
    - tanh 
    - step 
  - ** w and b of individual neurons are determined during the training process **
