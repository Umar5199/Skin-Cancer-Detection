# Skin Cancer Detection Project

## Project Overview
This project is a **Skin Cancer Detection system** using a **multimodal deep learning approach**. The model combines **image data** of skin lesions with **patient metadata** (age, sex, lesion location) to predict 7 types of skin conditions:

- Melanocytic nevi (nv)
- Melanoma (mel)
- Benign keratosis-like lesions (bkl)
- Basal cell carcinoma (bcc)
- Actinic keratoses (akiec)
- Vascular lesions (vasc)
- Dermatofibroma (df)

The dataset is based on the **HAM10000 dataset**, a publicly available collection of dermatoscopic images with metadata.

---

## Project Objectives
- Load and preprocess image and tabular metadata.
- Perform Exploratory Data Analysis (EDA) on the dataset.
- Train a multimodal deep learning model (image + tabular data).
- Evaluate the model and display predictions with confidence scores.
- Generate charts and visualizations for insights.

---

## Dataset
The HAM10000 dataset contains:
- **Images**: Dermatoscopic images of skin lesions.
- **Metadata**: Age, sex, lesion location, and lesion type (dx).

> **Note**: Images and metadata are included in the project repository under `HAM10000_images_part_1`, `HAM10000_images_part_2`, and `HAM10000_metadata.csv`.

---

## Installation & Requirements
1. Clone the repository:
```bash
git clone https://github.com/Umar5199/Skin-Cancer-Detection.git
