# Flux 2 Lab

A specialized inference repository for **Flux 2**, optimized for performance and derived from the `musubi-tuner` ecosystem. This project provides a streamlined, standalone implementation of Flux 2 architectures for high-quality image generation.

## Features
* **Flux 2 Dev/Klein Support**: High-fidelity image generation.
* **Optimized Inference**: Cleanly extracted logic for efficient standalone use.
* **Modern Stack**: Integration support for CUDA 12.4

## Installation
1. **Clone and Setup**:
   ```bash
   git clone [https://github.com/taekim99/flux2-lab.git](https://github.com/taekim99/flux2-lab.git)
   cd flux2-lab
   python -m venv venv
   source venv/bin/activate

2. **Install with CUDA 12.4 support**:
   ```bash
   pip install -e ".[cuda124]"

## Usage
**To run the Flux 2 inference script**:
    ```bash
    python src/tti_flux_2/flux_2_inference.py --prompt "A futuristic city under water" --height 1024 --width 1024

## Credits and License
This repository is a derivative work and relies on the following open-source projects:
### 1. [kohya-ss/musubi-tuner](https://github.com/kohya-ss/musubi-tuner)
The core logic, structure, and training/inference scripts are heavily based on **musubi-tuner** by **kohya-ss**.
### 2. [Z-Image Team](https://github.com/Tongyi-MAI/Z-Image)
The Flux 2 architecture implementation includes code from the **Z-Image Project**.
* **License:** Apache License 2.0
* **Copyright:** Copyright (c) 2025 Z-Image Team
* **Note:** Original files have been modified for integration into this project.

---

## License
This project is licensed under the **Apache License 2.0**. See the `LICENSE` file for full details.
As required by the license:
* All original copyright notices have been preserved in the source files.
* Files modified from their original source contain headers indicating that changes have been made.
