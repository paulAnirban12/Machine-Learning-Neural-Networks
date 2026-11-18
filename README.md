
## 01. MLP vs CNN — Fashion-MNIST Classification

### Overview
This project compares a Multilayer Perceptron (MLP) and a Convolutional Neural Network (CNN) for image classification using the Fashion-MNIST dataset.

### Implementation
- Dataset: Fashion-MNIST (60,000 training and 10,000 test images)
- MLP: Two hidden Dense layers (128 and 64 neurons)
- CNN: Two convolutional layers (32 and 64 filters), followed by max-pooling
- Framework: TensorFlow / Keras
- Training: 10 epochs with Adam optimizer

### Results

| Metric | MLP | CNN |
|---|---|---|
| Test Accuracy | 88.30% | 90.84% |
| Training Accuracy | 90.97% | 95.06% |
| Parameters | 109,386 | 121,930 |
| Training Time | 39.69 s | 348.39 s |

### Key Findings
The CNN achieved higher classification accuracy by learning spatial features from images, while the MLP trained considerably faster.

**Skills:** Neural Networks, CNNs, Image Classification, Model Evaluation.
