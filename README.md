# Lightweight Reimplementation of ViTTA: Video Test-Time Adaptation for Action Recognition

This repository is a lightweight reimplementation of the method described in the paper:

> **"Video Test-Time Adaptation for Action Recognition"**  
> Authors: Wei Lin, Muhammad Jehanzeb Mirza, Mateusz Kozinski, Horst Possegger, Hilde Kuehne, Horst Bischof  
> Published at CVPR 2023  
> [Link to the Paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Lin_Video_Test-Time_Adaptation_for_Action_Recognition_CVPR_2023_paper.pdf)  
> [Link to the original git repo](https://github.com/wlin-at/ViTTA)  

The goal of this project is to experiment with the ViTTA method on a smaller scale using the UCF101 dataset. This implementation is designed to approximate the key concepts and results of the ViTTA approach without requiring fully trained models or extensive computational resources.

The Pipeline:
<img src="https://wlin-at.github.io/media/vitta/pipeline.png">

## Features

- Implementation of a simplified version of ViTTA's test-time adaptation.
- Focus on the **UCF101 dataset** for action recognition tasks.
- Lightweight setup with a single Jupyter notebook for clarity and accessibility.
- Partial functionality: This reimplementation may not include all features from the original paper but aims to replicate its core ideas and achieve comparable results.

## Repository Contents

- **`ViTTA-light.ipynb`**: The main Jupyter notebook containing the implementation.
- **`data/`**: Directory for dataset storage (UCF101). Users must manually download the dataset.
- **`requirements.txt`**: Dependencies for the project.
- **`.gitignore`**: Specifies files and folders to ignore in the Git repository.
- **`README.md`**: This file.

## Getting Started

### Prerequisites

1. Clone this repository:
   ```bash
   git clone https://github.com/IsmailHatim/ViTTA-light.git
   cd ViTTA-light