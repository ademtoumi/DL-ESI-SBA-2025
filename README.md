# Deep Learning — Practical Works (TPs)

> **ESI-SBA** · Higher School of Computer Science, Sidi Bel Abbès · 4th Year AI & Data Science · 2024/2025

## Overview

Practical lab work for the Deep Learning module at ESI-SBA. The labs progress from neural network foundations through advanced architectures — covering optimization strategies, recurrent networks, convolutional networks, and transfer learning. The final lab applies fine-tuned EfficientNet and ShuffleNet models to COVID-19 X-ray classification.

## Lab Contents

| Lab | Topics |
|-----|--------|
| TP-1 | DL Foundations — perceptrons, activation functions, backpropagation |
| TP-2 | Optimizing DNNs — regularization, dropout, batch normalization, optimizers |
| TP-3 | Recurrent Neural Networks — LSTM, GRU, sequence modeling (MNIST + CIFAR-10) |
| TP-4 | Convolutional Neural Networks — CNN architectures, pooling, data augmentation |
| TP-5 | Transfer Learning — EfficientNet & ShuffleNet fine-tuned for COVID-19 X-ray classification |

## Tech Stack

- **Language:** Python 3.x
- **DL Frameworks:** PyTorch, Keras (TensorFlow backend)
- **Vision / Metrics:** torchvision, torchmetrics
- **Data:** NumPy, Pandas
- **Visualization:** Matplotlib, Seaborn
- **Environment:** Jupyter Notebooks

## Repository Structure

```
.
├── TP-1/              # Foundations notebooks
├── TP-2/              # Optimization techniques
├── TP-3/              # RNNs (part-one, part-two with plots)
├── TP-4/              # CNNs
├── TP-5/              # Transfer learning
│   ├── trainer/       # Custom training module
│   │   ├── trainer.py
│   │   ├── history.py
│   │   └── batch_results.py
│   └── main.ipynb
├── requirements.txt
└── README.md
```

## Custom Trainer Module (TP-5)

The `TP-5/trainer/` package provides a reusable training framework with:
- Batch-level metrics tracking
- Training history visualization
- Checkpoint management
- Custom metric computation

## Setup

```bash
# 1. Clone the repository
git clone https://github.com/ademtoumi/DL-ESI-sba-2025.git
cd DL-ESI-sba-2025

# 2. Create and activate a virtual environment
python -m venv .venv
# Windows
.venv\Scripts\activate
# macOS / Linux
source .venv/bin/activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Launch Jupyter
jupyter notebook
```

## Author

**Adem Toumi** — ESI-SBA, 4th Year AI & Data Science  
📧 addz1606@gmail.com

## License

This project is licensed under the [MIT License](LICENSE).
