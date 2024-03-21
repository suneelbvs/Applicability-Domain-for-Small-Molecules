# Applicability Domain for Small Molecules (Machine Learning & Deep Learning)

## Introduction

The concept of Applicability Domain (AD) is crucial in the field of cheminformatics, particularly when using machine learning (ML) and deep learning (DL) models for small molecule prediction. AD refers to the chemical space covered by a model within which predictions are considered reliable. It's a way to assess whether a new compound is similar enough to those in the training set, and thus if the model's predictions for that compound are likely to be accurate.

##🚧 Project Status: Getting Ready for Launch! 🚧

We are excited to announce that this GitHub repository is swiftly moving towards its launch! Currently, it's a hive of activity as we lay the groundwork for something truly special.

What to Expect:

Work in Progress: Our team is diligently preparing the repository, ensuring that everything is set for a smooth launch.
Coming Soon: Stay tuned for the deployment of our initial version. We're just as eager as you are to share our work with the community.
New Features and Improvements: Beyond the initial release, we have a roadmap packed with new features, enhancements, and updates. Our commitment is to continuously evolve and adapt, providing you with tools that meet and exceed your expectations.
Stay Updated: Keep an eye on this space! We'll share progress updates, sneak peeks, and launch announcements. Your feedback and suggestions are always welcome as they are invaluable in shaping the future of this project.

Thank you for your patience and support. We can't wait to unveil what we've been working on!


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
