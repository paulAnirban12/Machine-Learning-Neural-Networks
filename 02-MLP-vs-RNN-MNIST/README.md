
## 02. MLP vs RNN — MNIST Classification

### Overview
This project compares a Multilayer Perceptron (MLP) and a Recurrent Neural Network (RNN) for handwritten digit classification using MNIST.

The experiment investigates how flattened and sequential image representations affect classification performance.

### Implementation
- Dataset: MNIST (60,000 training and 10,000 test images)
- MLP: Dense layers with 128 and 64 hidden neurons
- RNN: SimpleRNN with 128 hidden units
- RNN input: 28 image rows treated as a sequence
- Framework: TensorFlow / Keras
- Training: 10 epochs, batch size 128
- Evaluation: Five random seeds

### Results (Mean ± Standard Deviation)

| Metric | MLP | RNN |
|---|---|---|
| Test Accuracy | 97.49% ± 0.17% | 97.16% ± 0.18% |
| Training Accuracy | 99.50% ± 0.05% | 97.49% ± 0.18% |
| Parameters | 109,386 | 21,386 |
| Training Time | 16.91 ± 0.44 s | 29.11 ± 1.19 s |

### Key Findings
The MLP achieved slightly higher accuracy and faster training. The RNN achieved comparable classification performance using approximately 80% fewer trainable parameters.

**Skills:** MLP, RNN, Sequential Processing, Reproducible Experiments, Statistical Evaluation
