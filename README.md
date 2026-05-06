**Author:** Nguyen Ngoc Canh  
**Institution:** University of Science, VNU-HCM  
**Course:** Applications of Natural Language Processing in Industry

## 📌 Overview
This repository contains the source code for fine-tuning a text classification model on a subset of the **BANKING77** dataset using **Unsloth**. The project includes scripts for data processing, training, and running standalone inference.

## ⚙️ Environment Setup
This project is designed to be executed directly on **Kaggle** without any complex local installations. 

To set up the environment:
1. Create a new Notebook on [Kaggle](https://www.kaggle.com/).
2. Upload the entire project directory (including `scripts/`, `configs/`, and `sample_data/`) to Kaggle workspace.
3. Navigate to **Notebook Options (three dots) > Accelerator** and select **GPU T4 x2**.

## 📂 Data Preparation
The model uses a sampled version of the BANKING77 dataset. Ensure your data files are correctly placed in the `sample_data/` directory before running the scripts:
* `sample_data/train.csv`
* `sample_data/test.csv`

Link video: https://drive.google.com/file/d/1Q8C3lLsTG-PZIBsExI0nrxmh82e4iqmJ/view?usp=sharing
