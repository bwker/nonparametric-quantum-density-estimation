# KDE for Quantum Measurements: Almost Sure Uniform Consistency

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)

This repository contains the complete Python code for the research paper:

> **"Almost Sure Uniform Consistency of Kernel Density Estimation for Outcome Densities Induced by Quantum Measurements"**
> *Bouaker Imed, Babylonian Journal of Mathematics, 2026.*

## 📖 Overview

The code reproduces all numerical experiments and figures from the paper. It includes:
- Implementation of Kernel Density Estimation (KDE) with Epanechnikov kernel.
- Real data analysis from a Schrödinger cat state experiment (homodyne detection).
- Synthetic experiments for heterodyne and squeezed states.
- Robustness analysis against additive Gaussian noise.
- Fast bandwidth selection method (comparison with cross-validation).
- Statistical significance tests.
- Generation of all figures (`error_evolution.png`, `density_comparison.png`, etc.).

## 📁 Repository Structure

```
.
├── figures/                 # Generated figures
├── data/                    # Contains the HDF5 data file (downloaded automatically)
├── main_analysis.py         # Main script for the paper's numerical results
├── future_steps.py          # Extended analysis for robustness and computational efficiency
├── generate_figures.py      # Script to generate all figures
├── requirements.txt         # Python dependencies
└── README.md                # This file
```

## 🚀 Getting Started

### Prerequisites

- Python 3.8 or higher
- pip (Python package installer)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/KDE-Quantum-Consistency.git
   cd KDE-Quantum-Consistency
   ```

2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

### Running the Analysis

To reproduce the main results and generate all figures:
```bash
python main_analysis.py
```

To run the extended analysis (robustness, computational speed):
```bash
python future_steps.py
```

## 📊 Results

The figures will be saved in the `figures/` directory. The main results are:
- **Figure 1:** Evolution of L∞ error with sample size.
- **Figure 2:** Density estimates comparison.
- **Figure 3:** Distribution of KDE errors.
- **Figure 4:** KDE with 95% confidence intervals.
- **Figure 5:** Bar chart comparison of errors.
- **Figure 6:** Bandwidth evolution.

## 📝 Citation

If you use this code in your research, please cite the paper:

```bibtex
@article{Bouaker2026KDE,
  author = {Bouaker, Imed},
  title = {Almost Sure Uniform Consistency of Kernel Density Estimation for Outcome Densities Induced by Quantum Measurements},
  journal = {Babylonian Journal of Mathematics},
  year = {2026},
  volume = {2026},
  pages = {1--20},
  doi = {10.58496/BJM/2026/001}
}
```

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📧 Contact

Bouaker Imed - [imed.bouaker@univ-naama.dz](mailto:imed.bouaker@univ-naama.dz)
