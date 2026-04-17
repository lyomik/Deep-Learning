# 🧠 Deep-Learning

> A collection of deep learning concepts, implementations, and experiments — covering fundamental training techniques to advanced architectures and applications.

---

## 📁 Repository Structure

| Folder | Description |
|--------|-------------|
| `CNN原理` | Convolutional Neural Network fundamentals — convolution operations, pooling, feature map visualization |
| `GoogLeNet` | GoogLeNet (Inception v1) architecture implementation with Inception modules in PyTorch |
| `Pytorch+Backpropagation` | PyTorch basics and backpropagation mechanics — computational graphs, autograd, gradient flow |
| `YOLOv1` | You Only Look Once v1 — real-time object detection, grid-based prediction, loss function breakdown |
| `梯度消失x BN x ResNet` | Vanishing gradient problem, Batch Normalization, and ResNet skip connections — comparative experiments on CIFAR-10 |
| `過擬合&kernel運算量` | Overfitting strategies (dropout, regularization) and kernel computational cost analysis |

---

## 🔑 Key Topics Covered

- **CNN Fundamentals** — receptive field, parameter sharing, spatial hierarchy
- **Backpropagation** — chain rule, autograd in PyTorch, gradient visualization
- **Vanishing Gradients** — sigmoid saturation, deep network degradation
- **Batch Normalization** — internal covariate shift, γ/β learnable parameters, train vs. eval mode
- **ResNet** — skip connections, identity mapping, residual learning
- **GoogLeNet** — Inception modules, 1×1 convolutions, multi-scale feature extraction
- **YOLO v1** — unified detection framework, anchor-free grid prediction
- **Overfitting & Regularization** — dropout, L2 regularization, data augmentation
- **Kernel Computational Cost** — FLOPs analysis, depthwise separable convolutions

---

## 🛠️ Requirements

```bash
pip install torch torchvision matplotlib numpy
```

- Python 3.8+
- PyTorch 2.x
- CUDA (optional, for GPU acceleration)

---

## 🚀 Getting Started

```bash
git clone https://github.com/lyomik/Deep-Learning.git
cd Deep-Learning
```

Navigate to any subfolder and open the corresponding `.ipynb` or `.py` file to explore the topic.

---

## 📌 Notes

- Experiments are designed for educational purposes, with step-by-step explanations.
- CIFAR-10 is used as the primary benchmark dataset across most modules.
- Code style favors flat, readable Jupyter Notebook format over abstracted pipelines.

---

## 📄 License

This repository is for educational use. Feel free to reference or adapt the code with attribution.
