# Communication-Efficient Federated Learning via Clipped Uniform Quantization

This repository contains the code and resources to replicate the simulations presented in the paper:  
**"Communication-Efficient Federated Learning via Clipped Uniform Quantization"**.  
The method integrates clipped uniform quantization with federated learning to enhance communication efficiency without sacrificing accuracy.

## Currently I am updating/completing the repo!
---
In Main function, you can specify the type of the algoithm that one would like besides the intended dataset! I am going to make all the other necessary details and posting them here!

## Links to the Paper
- Available at: [IEEE](https://ieeexplore.ieee.org/document/10944759)
- Available at: [arXiv](https://arxiv.org/abs/2405.13365)

 
---

## Abstract
This work presents a novel framework to reduce communication costs in federated learning using clipped uniform quantization. The key contributions include:
- **Optimal Clipping Thresholds**: Balances quantization and clipping noise to minimize information loss.
- **Stochastic Quantization**: Enhances robustness by introducing diversity in client model initialization.
- **Privacy Preservation**: Obviates the need for disclosing client-specific dataset sizes during aggregation.
- **Error-Averaging**: Averaging based on inverse of mean of quantization error, instead of FedAvg.

The proposed method achieves near-full-precision accuracy with significant communication savings, demonstrated through extensive simulations on the MNIST and CIFAR-10 datasets.

---

## Key Features
- **Enhanced Communication Efficiency**:
  - Optimal clipping of model weights before transmission.
  - Stochastic quantization for increased robustness.
- **Privacy-Aware Design**:
  - Avoids sharing dataset sizes with the server.
- **Versatile Aggregation Methods**:
  - Supports both FedAvg and error-weighted aggregation.

---

## Repository Contents
- **Code for MNIST and CIFAR-10 Simulations**:
  - Implements various quantization configurations (e.g., "4-2-2-4", "2-2-2-2").
  - Includes training scripts and evaluation metrics.
- **Clipping Threshold Optimization**:
  - Analytical method for optimal threshold selection.
- **Quantization Strategies**:
  - Deterministic and stochastic quantization.

---

## Highlights
- **Communication Savings**: Reduces communication costs.
- **Scalability**
- **Performance Metrics**

---

## Getting Started
### Prerequisites
- Python 3.7 or later
- Required libraries (see `requirements.txt`)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/username/ClippedQuantFL.git
   cd ClippedQuantFL
---

### Citation
If you find this repository helpful, please consider citing:

```bibtex
@inproceedings{bozorgasl2025communication,
  title={Communication-Efficient Federated Learning via Clipped Uniform Quantization},
  author={Bozorgasl, Zavareh and Chen, Hao},
  booktitle={2025 59th Annual Conference on Information Sciences and Systems (CISS)},
  pages={1--6},
  year={2025},
  organization={IEEE}
}

