# Deep_Learning_Coursework
A collection of Deep Learning projects and explorations I have conducted at McGill.

## mlp.ipynb
A multilayer perceptron that uses stochastic gradient descent, and a sum of squared errors loss function. 

## classifier.ipynb
A Pytorch program designed to classify points in this manner:
<img width="350" alt="image" src="https://github.com/Saif-Shahin/Deep_Learning_Coursework/assets/90293080/06a6d8ff-f164-47dc-ada2-7459cd414c30">

## hw2_Group24.ipynb
- **Q1.1 to Q1.3: Data Augmentation and Transformation**
  - Exploration of three specific transformations applicable to digit matching tasks, including their variance introduction and potential benefits. Implementation involves `torchvision.transforms` for enhancing model generalization on the Twin neural network setup.
  - Development of a custom transformation for adding pixel-level noise to digit images, ensuring legibility while simulating real-world data imperfections.

- **Q2.1 & Q2.2: Dropout Implementation and Evaluation**
  - Implementation of dropout in neural network layers to investigate its effect on overfitting and network generalization.
  - Comparative analysis of models with and without dropout, evaluated based on Loss and AUC metrics.

- **Q3.1 & Q3.2: Theoretical Insights into Regularization Techniques**
  - Derivation and discussion on the equivalence conditions between early stopping and L2 regularization, leveraging quadratic approximation of cost functions and gradient descent iterations.
  - Detailed mathematical explanation on deriving gradients for backpropagation, focusing on the algorithmic steps and chain rule applications in the context of neural network layers.

## Conditional_VAEs_and_GCNs.ipynb
### Part 1 - Conditional Variational Autoencoders (CVAEs)
- **Introduction:** Explores CVAEs as an extension of VAEs, for generating specific images by adding conditions to both the encoder and decoder processes.
- **Assignment Tasks:**
  - **Q1.1 Implementing an MNIST CVAE:** Enhancements to the MNIST VAE for conditional image generation.
  - **Q1.2 Demonstrate Reconstruction:** Validation of CVAE's reconstruction capabilities.
  - **Q1.3 Demonstrate Conditional Reconstruction:** Testing CVAE's performance with varied conditions.
  - **Q1.4 Explore the Latent Space:** Analysis of latent variables' impact on image generation.

### Part 2 - Graph Convolution Networks (GCN)
- **Introduction:** Investigates the equivalence and application of GCNs compared to traditional 2D convolutional layers in deep learning.
- **Assignment Tasks:**
  - **Q2.1 Describe a graph equivalent to an image:** Conceptual translation of image data into graph format for GCNs.
  - **Q2.2 GCN and 2DConv equivalence:** Identifying conditions for output equivalence between GCN and 2DConv layers.
  - **Q2.3 GCN and 2DConv+2DPool equivalence:** Conditions for equivalence between GCN outputs and 2DConv layers with pooling.

## TimeSeriesForcastngExploration.ipynb
We developed, optimized, and evaluated three deep learning models for time-series forecasting using weather data from the Max Planck Institute for Biogeochemistry.  The models were:
- a baseline Multilayer Perceptron (MLP)
- a Long Short-Term Memory (LSTM) network for capturing temporal dependencies
- a custom model we proposed that combines 1D convolutional layers with fully connected layers

Pre-processing steps such as wind direction transformation, date-time extraction, data normalization, and the removal of negative values were implemented to clean and structure the dataset for optimal model training and evaluation.

The following is a snippet from the report we wrote, showcasing the performance of our model compared to the LSTM and MLP approaches: 

<img width="688" alt="Screen Shot 2024-03-14 at 9 38 25 PM" src="https://github.com/Saif-Shahin/Deep_Learning_Coursework/assets/90293080/5610e4bd-051a-4818-9058-1c0efca09082">
