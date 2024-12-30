# -Brain-Tumor-Segmentation-using-3D-U-Net
# Brain Tumor Segmentation using 3D U-Net

This repository contains the implementation of a **3D U-Net** model for brain tumor segmentation using the **BraTS2020 dataset**. The project involves data preprocessing, custom data loading, model implementation, and training the model to achieve accurate segmentation results.

---

## Table of Contents
1. [Project Overview](#project-overview)
2. [File Descriptions](#file-descriptions)
3. [Setup Instructions](#setup-instructions)
4. [Usage](#usage)
5. [Results](#results)
6. [Acknowledgements](#acknowledgements)
7. [License](#license)

---

## Project Overview

Brain tumor segmentation is a critical step in medical image analysis, aiding in diagnosis, treatment planning, and monitoring. This project utilizes a **3D U-Net** architecture to segment brain tumors from MRI scans. The model is optimized to handle 3D volumetric data, ensuring high accuracy in delineating tumor boundaries.

---

## File Descriptions

- **`data_preprocessing.py`**:  
  Handles the preprocessing of the BraTS2020 dataset, including resizing, normalization, and data augmentation.

- **`custom_data_generator.py`**:  
  Implements a custom data generator for efficient loading and processing of 3D NIfTI files during training.

- **`unet3d_model.py`**:  
  Contains the implementation of the 3D U-Net architecture, featuring an encoder-decoder structure with skip connections.

- **`training.py`**:  
  Script for training the 3D U-Net model, including GPU optimization, saving model checkpoints, and evaluating performance metrics.

---

## Setup Instructions

1. **Clone the repository**:  
   ```bash
   git clone https://github.com/<your-username>/brain-tumor-segmentation-3d-unet.git
   cd brain-tumor-segmentation-3d-unet
