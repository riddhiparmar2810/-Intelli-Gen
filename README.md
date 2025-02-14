

# INTELLI-GEN

Welcome to **INTELLI-GEN**! This project aims to generate bulk image data from 4-5 input images, addressing the problem of dataset scarcity by automating the generation of new, realistic images based on a limited set of input data. This tool is particularly useful for training machine learning models in image-based tasks, such as computer vision applications, where a large dataset is needed.

## Project Structure

This repository contains the following key elements:

### 1. **fast-DreamBooth.ipynb**
   - This notebook is based on the DreamBooth technique and is used to fine-tune a model using a small set of input images, generating new images that reflect the features of the input data.
   - [Open fast-DreamBooth Notebook on GitHub](https://github.com/Kandarp-joshi-007/Intelli-Gen/blob/main/fast-DreamBooth.ipynb)

### 2. **Model Training Notebook**
   - This notebook provides the workflow to train the model on your own dataset. It guides you through the setup of the environment and data preparation before training.
   - [Open Model Training Notebook on GitHub](https://github.com/Kandarp-joshi-007/Intelli-Gen/blob/main/model-training.ipynb)

### 3. **Image Generation Pipeline**
   - This notebook outlines the steps involved in generating images based on the trained model. It shows how to generate high-quality synthetic images for dataset expansion.
   - [Open Image Generation Notebook on GitHub](https://github.com/Kandarp-joshi-007/Intelli-Gen/blob/main/image-generation.ipynb)

## **UI Mockup**

### 🚀 **Explore the INTELLI-GEN Mockup UI**  
You can check out the project’s UI mockup here:  
[**INTELLI-GEN Mockup**](https://intelligen-mockup.vercel.app/)

This mockup provides a user-friendly interface for interacting with the project, demonstrating how the user can easily input their images and generate new data.

## Features

- **Bulk Image Generation:** Generate large quantities of images using a minimal set of input images.
- **Ease of Use:** Intuitive notebooks that guide you through every step from training to generation.
- **Customizable:** Fine-tune the model based on your specific dataset and needs.

## How to Use

1. Clone the repository.
2. Open the notebooks directly from GitHub.
3. Follow the instructions in each notebook to train and generate images.
4. Use the generated images for further training or dataset expansion.

## Requirements

- Python 3.8
- Google Colab for running the notebooks
- GPU enabled (for faster training)
