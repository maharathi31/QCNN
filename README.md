# Quantum Convolutional Neural Networks Experimentation

## Overview
This repository contains code for experimenting with quantum convolutional neural networks using PennyLane, TensorFlow, and Qiskit. The experiments involve applying quantum convolutions to the Fashion MNIST dataset and comparing the performance with classical convolutional neural networks.

## File: Quanvolutional Neural Networks Experimentation (1).py

### Instructions

To run the code and obtain results for different kernel sizes, follow these steps:

### For 2x2 Kernel Size:
1. **Importing Modules**
   - Run the section titled "importing modules".

2. **Initialization of Parameters**
   - Run the section titled "initialisation of parameters".

3. **Dataset Loading**
   - Run the section titled "dataset loading".

4. **Circuit Creation (2x2 Kernel)**
   - Run the section titled "2*2 kernel size".

5. **Quantum Convolution (2x2 Kernel)**
   - Run the section titled "2*2 kernel".

6. **Quantum Pre-processing**
   - Run the section titled "quantum pre-processing".

7. **Neural Network with Quantum Convolution**
   - Run the section titled "neural network with quantum convolution".
   - Store the results in `vaq2` and `valq2`.

### For 3x3 Kernel Size:
1. **Importing Modules**
   - Run the section titled "importing modules".

2. **Initialization of Parameters**
   - Run the section titled "initialisation of parameters".

3. **Dataset Loading**
   - Run the section titled "dataset loading".

4. **Circuit Creation (3x3 Kernel)**
   - Run the section titled "3*3 kernel size".

5. **Quantum Convolution (3x3 Kernel)**
   - Run the section titled "3*3 kernel".

6. **Quantum Pre-processing**
   - Run the section titled "quantum pre-processing".

7. **Neural Network with Quantum Convolution**
   - Run the section titled "neural network with quantum convolution".
   - Store the results in `vaq3` and `valq3`.

### For 4x4 Kernel Size:
1. **Importing Modules**
   - Run the section titled "importing modules".

2. **Initialization of Parameters**
   - Run the section titled "initialisation of parameters".

3. **Dataset Loading**
   - Run the section titled "dataset loading".

4. **Circuit Creation (4x4 Kernel)**
   - Run the section titled "4*4 kernel size".

5. **Quantum Convolution (4x4 Kernel)**
   - Run the section titled "4*4 kernel".

6. **Quantum Pre-processing**
   - Run the section titled "quantum pre-processing".

7. **Neural Network with Quantum Convolution**
   - Run the section titled "neural network with quantum convolution".
   - Store the results in `vaq4` and `valq4`.


### Plotting Results:
1. **Run the Section**
   - Run this section after storing the values in the above respective variables.
   - Run the section titled "Plotting code for all the three kernels + CNN with quantum convolution" to visualize the results.

## File: Quanvolutional Neural Networks Experimentation (2).py

### Instructions

To run the code and obtain results for quantum convolution using a real IBM quantum device, follow these steps:

1. **Importing Modules**
   - Ensure all necessary modules are imported at the beginning of the script.

2. **Initialization of Parameters**
   - Run the section titled "Set up parameters".

3. **Dataset Loading**
   - Run the section titled "Load dataset".

4. **IBM Quantum Account Authentication**
   - Authenticate your IBM Quantum account by running the provided commands.

5. **Listing and Selecting Backend**
   - Run the sections to list available backends and select the desired backend.

6. **Defining Quantum Circuit**
   - Run the section titled "Define quantum circuit".

7. **Executing Quantum Circuit**
   - Ensure the function for executing the quantum circuit on the selected backend is defined.

8. **Calculating Expectation Values**
   - Define the function for calculating expectation values from the measurement counts.

9. **Quantum Node with PennyLane**
   - Define the quantum node using PennyLane and Qiskit.

10. **Quantum Convolution Function**
    - Define the function to apply quantum convolution to an input image.

11. **Pre-processing Data Using Quantum Convolution**
    - Run the section to pre-process the training and testing images using the quantum convolution function.

12. **Training and Evaluating Neural Network**
    - Define and train a simple neural network model on the quantum-processed images.

13. **Plotting Results**
    - Plot the accuracy and loss of the neural network trained with quantum convolution.
