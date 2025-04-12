# CD-FTCN: Federated Crop Disease Detection via Spectra-Driven Temporal Convolutional Networks

## Overview
This repository contains the implementation code for a novel federated learning approach to crop disease detection, as presented in my research manuscript. The proposed methodology leverages temporal convolutional networks and hyperspectral imaging data while preserving data privacy through federated learning architecture.

**Note:** I implement centralized deep learning models from literature with both federated and centralized variants (not included). For appendix brevity, centralized models are identical to their federated counterpart, with just removed distributed learning components.

## Repository Structure

### Core Implementation
- `JSHS CD-FTCN.ipynb`: Primary implementation of the CD-FTCN architecture
- `JSHS Data Preparation.ipynb`: Data preprocessing and feature extraction protocols

### Baseline Models
- `JSHS 1D-CNN.ipynb`: One-dimensional convolutional neural network baseline
- `JSHS MLP.ipynb`: Multi-layer perceptron implementation
- `JSHS KNN.ipynb`: K-nearest neighbors classifier
- `JSHS LR.ipynb`: Logistic regression implementation
- `JSHS SVM.ipynb`: Support vector machine classifier

### Documentation
- `LICENSE`: Distribution and usage terms

## Contact Information
**Researcher:** Michael Gao  
**Institution:** DISIDE Lab, UF  
**Email:** michaeljgao07@gmail.com 
| If you use code from this repository, please cite!
