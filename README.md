# Facial Expression Recognition (FER)

A deep dive into the *process* of building and optimizing a deep learning model to classify human emotions. This repository documents the **learning journey** and **experimental process** of tackling the FER-2013 dataset.

The primary achievement of this project is not a single accuracy score, but the hands-on experience gained through systematic experimentation, optimization, and overcoming challenges like overfitting.

### Project Focus & Learning

* **Independent Experimentation:** The core of this project. Systematically experimented with data augmentation (rotation, flipping), batch normalization, and dropout to build an intuitive understanding of how to address overfitting and underfitting.

* **Model Optimization Process:** Demonstrates a strong grasp of the *entire* performance tuning workflow—from building a custom CNN from scratch to leveraging and fine-tuning a pre-trained ResNet-18.

* **Deep Learning Fundamentals:** Implemented and trained a custom Convolutional Neural Network (CNN) from the ground up to understand its architecture.

* **Transfer Learning:** Leveraged a pre-trained ResNet-18 model, freezing the majority of the network and only unfreezing the final layer for efficient training.

### Model Development Journey

The goal was to gain hands-on experience by starting from a baseline and iteratively improving it. The final accuracy (67%) was simply the result of this learning process.

1.  **Experiment 1: Custom CNN**
    * A custom CNN was designed and built from the ground up to establish a baseline.
    * This provided a deep understanding of model architecture and highlighted the challenges of the FER-2013 dataset.
    * Techniques like data augmentation and dropout were applied to improve robustness.

2.  **Experiment 2: Transfer Learning (ResNet-18)**
    * To improve performance, a pre-trained ResNet-18 model was used.
    * This experiment focused on efficient fine-tuning by only unfreezing the final classification layer.
    * This iterative approach led to the final, optimized model.

### Tech Stack

* **Core:** Python
* **Deep Learning:** PyTorch 
* **Data Science:** Pandas, NumPy, Scikit-learn (for metrics)
* **Data Visualization:** Matplotlib, Seaborn
* **Environment:** Google Colab
