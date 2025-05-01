# 🎨 Image-to-Equation: Mathematical Art Generator

<h1 align="center">
  <img src="docs/images/logo.png" width="300" alt="Image-to-Equation Logo">
</h1>

<p align="center">
  <strong>Transform any image into a mathematical equation that recreates it pixel-perfectly</strong>
</p>

<p align="center">
  <a href="https://opensource.org/licenses/MIT">
    <img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-blue.svg">
  </a>
  <a href="https://pypi.org/project/tensorflow">
    <img alt="TensorFlow 2.x" src="https://img.shields.io/badge/TensorFlow-2.x-FF6F00?logo=tensorflow">
  </a>
  <a href="https://github.com/psf/black">
    <img alt="Code style: black" src="https://img.shields.io/badge/code%20style-black-000000.svg">
  </a>
</p>

## 🌟 Key Features

- **Image to Mathematical Representation**: Convert any image into a set of equations
- **Two-Step Process**:
  - **Pre-training**: Uses DIV2K dataset (high-quality images) to learn general patterns
  - **Fine-tuning**: Adapts to your specific image for precise reproduction
- **Framework-Free Output**: Generates pure NumPy code with no external dependencies
- **Multiple Output Formats**:
  - Standalone Python script
  - Mathematical expression (LaTeX format)
  - Interactive visualizations
- **GPU Acceleration**: Optional GPU support for faster processing

## 🚀 Quick Start

### Prerequisites

- Python 3.8+
- NVIDIA GPU (optional but recommended)

### Installation

```bash
# Clone the repository
git clone https://github.com/your-username/image-to-equation.git
cd image-to-equation

# Create and activate virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
