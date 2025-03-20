# XRD Data Comparison
# Automated, fast and simple

## Overview

This repository contains a Python-based standalone executable for comparing multiple powder X-ray Diffraction (XRD) data. The program focuses on easy and fast visualization of the experimental data.

### Table of Contents
1. [Overview](#overview)
2. [Functionality](#functionality)
3. [Main Outputs](#Outputs)
4. [How to Use](#how-to-use)
5. [Technical Details](#technical-details)
6. [License](#license)


---
## 2. Functionality
1. **Plots multiple XRD data in the same plot**: Plots experimental data, must be in .xy format.


## 3. Main Outputs
The code is meant to be a quick and easy way to plot and visualize experimental XRD data. The main outputs of the program is:

<div align="center">
   <img src="plots/XRD_comparison_example.png" alt="XRD_comparison_example" width="500">
</div>


## 4. How to Use
Follow these steps to use the software:
1. **Clone the repository to your own machine**
2. **Make sure the following foler structure is followed**:
```
XRD Compare 1.0.1/
├── reference_patterns/  
│   └── reference_patterns.xlsx   # Stores the crystallographic information of the reference patterns             
│
├── plots/                        # Stores the generated plots
|
├── raw_xy_data/
│   └── your_data.xy       # XRD data to be analyzed
|
├── README.txt             # Documentation for the project.
├── LICENSE     
└── Powder_XRD_VA.exe      # Standalone .exe file
```

3. **Run the .exe file**
4. **Select all the files you want to compare**
4. **Open the plots in the plots folder**


## 5. Technical Details

### Adding more reference patterns
- 

## 6. License

This project is licensed under the MIT License — see the `LICENSE` file for details.

