# DDP-Network-Inversion-Explainability
Dual Degree Project: Network Inversion, Explanation Generation and Sparse Circuit Discovery
# Network Inversion, Explanation Generation and Sparse Circuit Discovery

## Dual Degree Project

Author: Aditya Anand

Guide: Prof. Amit Sethi

Institution: IIT Bombay

---

## Overview

This repository contains the complete work carried out during my Dual Degree Project on neural network interpretability.

The project evolved from studying Network Inversion methods for understanding neural network representations to developing activation matching based explanation generation frameworks capable of producing sparse and faithful explanations.

The work spans:

* Explainable AI
* Network Inversion
* Sparse Autoencoders
* Activation Matching
* Circuit Discovery
* Medical Explainability

---

## Research Timeline

### Phase 1: Explainability Survey

Studied:

* LIME
* GradCAM
* GradCAM++
* Attention Maps
* Feature Inversion
* Guided Feature Inversion

### Phase 2: Network Inversion

Implemented generator-based inversion for:

* MNIST
* FashionMNIST
* CIFAR10

Investigated latent representations, diversity losses and sparse autoencoder based analysis.

### Phase 3: Activation Matching

Developed an activation matching framework where explanation images are optimized to preserve classifier activations while minimizing image content.

### Phase 4: CAM and EXP-CAM

Extended activation matching to generate minimal evidence explanations and discover sparse decision circuits.

### Phase 5: Med-CAM

Applied the framework to medical decision making and diagnostic explanation generation.

---

## Models Evaluated

* Custom MNIST Classifier
* ResNet18
* DenseNet121
* MobileNetV2
* EfficientNet
* ViT-B/16

---

## Datasets

* MNIST
* FashionMNIST
* CIFAR10
* ImageNet subset
* Medical Imaging datasets

---

## Publications

* Activation Matching for Explanation Generation and Circuit Discovery
* CAM: Classifier Activation Matching for Minimal Explanation Generation and Sparse Circuit Discovery
* EXP-CAM: Explanation Generation Using Classifier Activation Matching
* Med-CAM: Minimal Evidence for Explaining Medical Decision Making

---

## Main Contributions

* Generator-based Network Inversion
* Activation Matching Framework
* Sparse Explanation Generation
* Multi-Architecture Evaluation
* Sparse Circuit Discovery
* Medical Explainability Framework

---

## Future Work

* Quantitative faithfulness metrics
* Larger vision models
* Improved sparse circuit extraction
* Medical explainability benchmarks
