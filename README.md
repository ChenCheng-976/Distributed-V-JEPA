# Distributed-V-JEPA: Enabling Intelligent Distributed Sensing through Self-Supervised Cross-Device Knowledge Sharing

![Demo Reconstruction](assets/reconstruction.gif)

## Overview

**V-JEPA** is a self-supervised learning framework designed for distributed sensing systems. By fusing latent embeddings from multiple sub-views, V-JEPA reconstructs global scenes with high semantic fidelity.

This repository provides:
- Pretrained models for the V-JEPA pipeline.
- Scripts for training, evaluation, and inference.
- A demo notebook showcasing the reconstruction of full-view videos.

## Features
- **Cross-Camera Masking**: Leverages overlapping camera views to enhance global reconstruction.
- **Composable Embeddings**: Latent representations from sub-views are fused seamlessly.
- **Self-Supervised Learning**: No labels required for pretraining.

## Demo

Run the demo with our pretrained models:
```bash
# Clone the repository
git clone https://github.com/YourUsername/V-JEPA.git
cd V-JEPA

# Install dependencies
pip install -r requirements.txt

# Run the demo
python scripts/demo_inference.py
