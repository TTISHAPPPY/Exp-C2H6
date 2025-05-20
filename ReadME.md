

# Metal-Organic Framework Discovery for Ethane/Ethylene Separation

This repository contains data and scripts supporting the research paper:
**"Accelerating the Discovery of Stable Metal–Organic Frameworks for Ethane/Ethylene Separation Using Data Mining and Multitarget Screening"**

## 🛠️ Requirements

The code has been tested with the following package versions:

Python == 3.10.14
scikit-learn == 1.3.2
imbalanced-learn == 0.12.4
rdkit == 2023.9.6
mendeleev == 0.17.0

## 📊 Data Preparation

Descriptor sets were computed separately using `descriptors.ipynb`:

| Descriptor Type          | Description                                 |
| ------------------------ | ------------------------------------------- |
| **Organic Ligand** | Molecular features of linker components     |
| **Metal**          | Physical/chemical properties of metal nodes |
| **Structural**     | Geometric properties calculated by zeo++    |
| **Experimental**   | Gas species and temperature conditions      |

## 🚀 Implementation

The predictive modeling workflow consists of two main stages:

1. **Feature Engineering** (`descriptors.ipynb`):

   - Computes comprehensive MOF descriptors
2. **Predictive Modeling** (`Script/` directory):

   - Supports both classification and regression tasks

## 📝 Usage

To reproduce the results:

1. Run `descriptors.ipynb` to generate feature sets
2. Execute modeling scripts in the `Script/` directory

## 📑 Citation Request

If you use this code or data in your research, please cite our work
