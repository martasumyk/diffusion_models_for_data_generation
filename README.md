#  Diffusion models for dataset generation in case of limited data

This project explores the use of diffusion models to generate synthetic datasets in scenarios where real-world data is scarce. Specifically, we focus on augmenting a dataset of satellite images of Ukrainian agricultural fields affected by bombing during the war.

## Overview

Training robust computer vision models typically requires large amounts of annotated data. In real-world scenarios — especially conflict zones — obtaining such datasets can be extremely challenging.
This project leverages diffusion models to generate synthetic satellite images of bombed and not bombed fields, expanding the limited real-world dataset.
We aim to evaluate whether such synthetic data can help improve classification models' performance when real data is limited.

## Project structure 

```
.
├── diffusion_models/                # Pretrained or trained diffusion model checkpoints
├── Diffusion_models_training.ipynb # Notebook for training and generating images using diffusion models
├── GMM_testing.ipynb               # Testing classifier performance (e.g., GMM-based approach)
├── ViT_model_training.ipynb        # Vision Transformer training on original and synthetic datasets
├── requirements.txt                # Python dependencies
└── README.md                       # Project description and instructions
```
