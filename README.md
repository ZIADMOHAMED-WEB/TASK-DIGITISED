# TASK-DIGITISED
This repository contains a scalable image classification system using ResNet-18, implemented in PyTorch. The project demonstrates efficient training and inference on image datasets with comprehensive scalability features for both computational resources and dataset sizes.
# Scalable Image Classification with ResNet-18

![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![CUDA](https://img.shields.io/badge/CUDA-%230175C2.svg?style=for-the-badge&logo=nvidia&logoColor=white)

A production-ready image classification system using ResNet-18 in PyTorch, optimized for scalability across hardware configurations.

## 🚀 Features
- **Adaptable Architecture**: ResNet-18 with residual connections
- **Hardware Optimization**: Automatic GPU detection & multi-GPU support
- **End-to-End Pipeline**: Data loading → Training → Validation → Inference
- **Edge Deployment**: Post-training quantization support
- **Performance Tracking**: Loss, accuracy, and timing metrics

## 📊 Performance (CIFAR-10)
| Epoch | Train Loss | Val Loss | Accuracy | Time/Epoch |
|-------|------------|----------|----------|------------|
| 1     | 1.4321     | 1.2104   | 62.34%   | 23.15s     |
| 5     | 0.6438     | 0.7010   | 81.05%   | 23.22s     |
**Inference Speed**: 3.2ms/image (GPU)

## 🛠️ Installation
```bash
pip install torch torchvision matplotlib
