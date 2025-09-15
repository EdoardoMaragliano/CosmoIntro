
# CosmicStructures


<img src="DALL·E_LSS.webp" alt="Large Scale Structure Visualization" width="600" />


Computational Notebooks for the Physics of Cosmic Structures

This repository contains all the Jupyter notebooks and resources for the course "Physics of Cosmic Structures" held at the University of Genova (Italy) by Prof. Marco Raveri.

Some material has never been checked thoroughly, so some revision may be necessary and/or typos be corrected.

## Features
- Step-by-step cosmological computations
- Matter power spectrum, CMB, inflation, supernovae, and more
- Ready-to-run Python notebooks with explanations

## Requirements
- Python 3.x
- [CAMB](https://camb.readthedocs.io/en/latest/)
- [Healpy](https://healpy.readthedocs.io/en/latest/)
- Numpy
- Scipy
- Matplotlib

You can install the required packages with:
```bash
pip install camb healpy numpy scipy matplotlib
```

## Structure
```
CosmoIntro/
├── Cosmo1_FRW/
│   └── Cosmo1Ex2.ipynb
├── Cosmo2_Supernovae/
│   ├── CosmoExWeek2.ipynb
│   ├── covariance.txt
│   └── data.txt
├── Cosmo5_Inflation/
│   ├── Cosmo5Ex1.ipynb
│   └── Cosmo5Ex4.ipynb
├── Cosmo6_CMB_Angular_Power_Spectrum/
│   ├── COM_CMB_IQU-commander_2048_R3.00_full.fits
│   └── Cosmo6Ex1.ipynb
├── Cosmo8_MatterPowerSpectrum/
│   └── Cosmo8Ex2.ipynb
├── Cosmo9_CMB/
│   ├── COM_PowerSpect_CMB-TT-full_R3.01.txt
│   ├── Cosmo9Ex1.ipynb
│   └── Cosmo9Ex2.ipynb
├── LICENSE
├── photo.jpg
└── README.md
```

## Usage
Clone the repository and open the notebooks with Jupyter:
```bash
git clone https://github.com/EdoardoMaragliano/CosmoIntro.git
cd CosmoIntro
jupyter notebook
```

## License
Distributed under the MIT License. See `LICENSE` for details.

## Acknowledgments
Course: Physics of Cosmic Structures @ University of Genova
Instructor: Prof. Marco Raveri

---
For questions or suggestions, feel free to open an issue!
