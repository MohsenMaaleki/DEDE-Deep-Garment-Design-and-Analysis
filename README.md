# DEDE: Deep Garment Design and Analysis

A deep learning framework for 3D garment analysis, generation, and manipulation using point cloud-based Variational Autoencoders (VAE).

## Overview

DEDE (Deep Cloth Simulation for Garment Design) is a deep learning project that focuses on:
- 3D garment segmentation and reconstruction from real scans
- Garment generation and interpolation
- Point cloud-based garment representation and manipulation

Built using PyTorch, Kaolin, and Streamlit, this project provides both a training pipeline and an interactive web interface for garment manipulation.

## Features

- 🧠 Point Cloud VAE for garment encoding and generation
- 🔄 Garment interpolation between different styles
- 👕 Support for various garment types
- 🎨 Interactive 3D visualization
- 📊 Web-based interface for garment manipulation

## Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/DEDE.git
cd DEDE

# Install dependencies
pip install -r requirements.txt
```

## Quick Start

1. Train the model:
```bash
python src/train.py --data_path path/to/dataset
```

2. Run the web interface:
```bash
streamlit run app/streamlit_app.py
```

## Dataset

This project uses the Multi-Garment Network dataset:
- 712 digital garments in correspondence
- Different clothing types and styles
- Real 3D scans of people in different clothing and poses

## References

Based on research work in 3D garment analysis and deep learning:
- [Multi-Garment Net: Learning to Dress 3D People from Images](https://arxiv.org/abs/1908.06903)
- PRIN 2022 Project: "Physical simulation of deformable bodies from real object observation"

## License

MIT License

## Citation

If you use this code in your research, please cite:
```bibtex
@misc{DEDE2024,
    title={DEDE: Deep Garment Design and Analysis},
    author={Your Name},
    year={2024},
    publisher={GitHub},
    journal={GitHub repository},
    howpublished={\url{https://github.com/yourusername/DEDE}}
}
```
