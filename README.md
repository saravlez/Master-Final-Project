# Spatial Structure and Plankton Dynamics: A Multi-Patch and PDE Study
## The Role of Diffusion and Advection in a Multi-Patch Marine Environment
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://python.org)
[![SciPy](https://img.shields.io/badge/SciPy-1.7+-purple)](https://scipy.org)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)](https://jupyter.org)

#### Overview

This repository contains the Jupyter Notebooks and Python code supporting my Master of Science in Applied Mathematics thesis at TU Delft. The project explores the role of diffusion and advection in a multi-patch marine environment, building a hierarchy of models from a zero-dimensional Nutrient-Phytoplankton-Zooplankton (NPZ) baseline up to a two-dimensional multi-column grid. It also includes a continuous reaction-diffusion PDE benchmark based on the framework of Cowall et al. (2021).

An electronic version of the full thesis is available at the [TU Delft Repository](http://repository.tudelft.nl/).

#### Repository Structure
- **reference_papers**: Local copies of foundational NPZ literature.
- **notebooks_main**: Core project notebooks, progressing from initial data analysis through 1D and 2D spatial models.
- **notebooks_literature**: Reproductions of foundational NPZ literature.

The complete file tree for the project is organized as follows:
```text
Master-Final-Project/
├── reference_papers/               # Local copies of the original publications
├── figures/                        # Saved plots for the main project
│   ├── Chapter 3/
│   ├── Chapter 4/
│   ├── Chapter 5/
│   └── Chapter 6/
├── notebooks_main/
│   ├── 01_Data_Analysis.ipynb      # NASA and HYCOM satellite data preprocessing (Chapter 5.2)
│   ├── 02_2Patches.ipynb           # Minimal surface/deep vertical box model (Chapter 3)
│   ├── 03_OneColumn.ipynb          # 1D multi-layer vertical water column (Chapter 4.1)
│   ├── 04_MultiColumn.ipynb        # 2D horizontal grid with lateral exchange (Chapter 4.2)
│   └── 05_DataOceanGrid.ipynb      # Full model with internal waves and data forcing (Chapter 6)
└── notebooks_literature/
    ├── figures/                    # Saved plots from literature reproductions
    ├── Franks1986.ipynb            # 0D Ivlev vs. Mayzaud-Poulet grazing comparison
    ├── Busenberg1990.ipynb         # 0D stability thresholds
    ├── Cowall2019.ipynb            # Continuous reaction-diffusion equilibrium profiles
    └── Cowall2021.ipynb            # Continuous PDE seasonal bloom baseline (Chapter 5)
```

#### Prerequisites

To run the code, you will need a standard scientific Python environment. Key libraries include:
- `numpy`
- `scipy`
- `matplotlib`
- `jupyter`

#### Main References

- Franks et al. (1986) - [PDF Document](reference_papers/Franks1986.pdf)
- Busenberg et al. (1990) - [PDF Document](reference_papers/Busenberg1990.pdf)
- Cowall et al. (2019) - [PDF Document](reference_papers/Cowall2019.pdf)
- Cowall et al. (2021) - [PDF Document](reference_papers/Cowall2021.pdf)

#### Data Access

The seasonal forcing data used in this project (NASA MODIS-Aqua surface light and chlorophyll-a, and HYCOM mixed layer depth for the North Atlantic) are excluded from this repository due to GitHub's file size limits. All notebooks have been pre-run and saved, so you can view the complete outputs and figures directly in your browser.

If you would like the raw data files to reproduce the runs locally, please contact me via email.

---

#### Contact 
This project is for academic and research purposes. Please feel free to email me at  [saravlezfue@gmail.com](mailto:saravlezfue@gmail.com) if you have any questions or need access to the raw data files.
