# Gastrointestinal Diseases Classification using Deep Learning

This repository contains Python Jupyter notebook files for a research project focused on the classification of gastrointestinal diseases using deep learning techniques. The code was developed using the free hardware resources provided by [Google Colab](https://colab.research.google.com/?hl=en-GB). The project is organized into three main directories, which can be used independently of each other.

## Directory Structure

1. **Separating 10% Data for Testing**
2. **Model Training and Testing**
3. **Plotting Results**

### 1. Separating 10% Data for Testing

This code is used to create a separate directory from the source dataset, containing 10% of the images. This separate directory is used exclusively for making predictions and testing our trained models. It includes two files, one for the [Kvasir Dataset](https://datasets.simula.no/kvasir/) and another for the [Hyper Kvasir Dataset](https://datasets.simula.no/hyper-kvasir/).

**Data Partitioning:**
- 70% of the source dataset is used for **training**.
- 20% of the source dataset is used for **validation**.
- 10% of the source dataset is used for **testing**.

### 2. Model Training and Testing

This directory contains 20 notebook files. The file naming convention used is: `ConfigurationSerialNo_ConfigurationName_using_ModelName_on_DatasetName`. These notebooks are used to:
- Ingest the datasets.
- Create training and validation splits.
- Visualize the images.
- Create model architectures.
- Train and fine-tune (only for pretrained models) the models.
- Use the model checkpoints with the highest validation accuracy.
- Test the models on the 10% of unseen images.

### 3. Plotting Results

This code is used to plot the accuracy scores across epochs during the training and fine-tuning (for pretrained models only) processes.

## Usage

The directories and notebooks can be executed independently of each other. It is not mandatory to follow the order listed above.

1. **Separating 10% Data for Testing**:
   - Run the notebooks in this directory to partition your dataset appropriately.
   
2. **Model Training and Testing**:
   - Use the notebooks in this directory to train and validate your models. Follow the naming convention to understand the configurations and datasets used.
   
3. **Plotting Results**:
   - Run the notebooks in this directory to visualize the training and validation accuracy over epochs.

## Acknowledgements

- [Kvasir Dataset](https://datasets.simula.no/kvasir/)
- [Hyper Kvasir Dataset](https://datasets.simula.no/hyper-kvasir/)
