# SimSiam-Self-supervised-Image-Classification

This notebook is part of the ECE763 final course project focusing on self-supervised learning (SSL). The primary objectives are to implement two self-supervised contrastive learning methods and compare the representations learned via SSL with those from a supervised baseline.

## Introduction
Self-supervised learning aims to learn useful data representations from unlabeled data, which can then be fine-tuned for specific tasks like classification. This approach is beneficial because it allows the use of large datasets without the need for manual labeling, making it cost-effective and efficient. 

## Libraries and Imports
The notebook uses Python 3, Following are several standard libraries necessary for data processing, visualization, and machine learning tasks:

- Standard Libraries: `os`, `copy`, `json`, `math`, `random`, `numpy`, `time`
- Plotting Libraries: `matplotlib`, `seaborn`
- Progress Bar: `tqdm`

## Implementation Details
The notebook contains detailed code cells implementing the SimSiam self-supervised learning method. Below is an overview of the key sections and their purposes:

**1. Data Preparation:**
- Loading datasets such as CIFAR-10.
- Preprocessing steps including normalization and augmentation.

**2. Model Architecture:**
- Defining the SimSiam architecture using PyTorch or a similar framework.
- Implementing the backbone network (e.g., ResNet) and the projection head.
  
**3. Training Loop:**
- Implementing the training loop with contrastive loss calculation.
- Using techniques such as learning rate scheduling, gradient clipping, and checkpointing.

**4. Evaluation:**
- Comparing the performance of the SSL method with supervised learning baselines.
- Visualization of learned representations using techniques like t-SNE.

**5. Results and Analysis:**
- Presenting quantitative results (accuracy, loss curves).
- Qualitative analysis of the learned representations.