# Applicability Domain for Small Molecules (Machine Learning & Deep Learning)

## Introduction

The concept of Applicability Domain (AD) is crucial in the field of cheminformatics, particularly when using machine learning (ML) and deep learning (DL) models for small molecule prediction. AD refers to the chemical space covered by a model within which predictions are considered reliable. It's a way to assess whether a new compound is similar enough to those in the training set, and thus if the model's predictions for that compound are likely to be accurate.

## Approaches to AD

1. **Distance-Based Methods**: These involve measuring the distance or similarity of a new compound to those in the training set. Methods like Euclidean or Manhattan distance are common.

2. **Descriptor-Based Methods**: In this approach, various molecular descriptors (like molecular weight, logP, etc.) are used. The AD is defined based on the range of these descriptors in the training set.

3. **Model-Based Methods**: These involve using the model itself to determine AD, like using the output of a neural network's hidden layer to assess similarity.

4. **Probabilistic & Statistical Methods**: Using statistical measures (e.g., standard deviation, confidence intervals) to define the boundaries of the AD.

5. **Hybrid Approaches**: Combining various methods to create a more robust AD definition.

## Getting Started

### Prerequisites

- Python 3.x
- Libraries: numpy, pandas, scikit-learn, tensorflow/keras (for deep learning models)

### Installation

1. Clone the repo:
   ```bash
   git clone https://github.com/[your-username]/Applicability-Domain-for-Small-Molecules.git

**Usage**
Provide examples of how to use your code, including data preparation, model training, and applying the AD methods.

**Contributing**
Encourage other developers to contribute to your project. Provide guidelines on how they can do so.

**License**
State the license under which your project is released.

**Authors and Acknowledgment**
Credit to those who have contributed to the project.

**FAQs**
Address common questions and issues related to the AD for small molecules.
