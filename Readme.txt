# Reinforcement Learning for Mineral Exploration

This repository contains the official implementation of the machine learning models used in the paper:

**"Using Reinforcement Learning in Mineral Exploration: Integrating ASTER, Landsat 9, and Geophysical Data while Comparing Machine Learning Techniques"**  
*Hassanreza Ghasemitabar, Abolghasem Kamkar Rouhani, Ali Reza Arab-Amiri, Mirhassan Moosavi*  
*Computers & Geosciences, 2026*

---

## 📋 Overview

This study implements and compares five machine learning approaches for copper exploration targeting using integrated multi-sensor data:

| Model | Type | Key Characteristic |
|-------|------|-------------------|
| **Deep Q-Learning (DQL)** | Reinforcement Learning | Precision-optimized policy with reward function design |
| **Monte Carlo Tree Search (MCTS)** | Reinforcement Learning | Model-based exploration strategy |
| **Random Forest (RF)** | Ensemble Learning | High interpretability with feature importance |
| **Convolutional Neural Network (CNN)** | Deep Learning | Spatial feature extraction |
| **Support Vector Machine (SVM)** | Kernel Method | Margin-based classification |

### Key Findings
- ✅ **DQL achieved 92.7% accuracy** in borehole validation
- ✅ **Only DQL maintained predictive capability** across diverse geological settings
- ✅ **CNN and SVM completely failed** to detect mineralization in validation boreholes
- ✅ **RF showed extreme false positive bias** (72 FP in BH-01)

---

## 🚀 Getting Started

### Prerequisites

- Python 3.8 or higher
- pip package manager
- (Optional) CUDA-compatible GPU for faster training

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/[YOUR-USERNAME]/RL-mineral-exploration.git
   cd RL-mineral-exploration