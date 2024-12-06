# Deep Learning Model: Image Classification

This repository contains a deep learning model implemented in PyTorch, designed for image classification. The model includes end-to-end functionality from data preparation to training and evaluation.

## Features
- **Frameworks and Libraries**: PyTorch, Torchvision, NumPy, Pandas, and OpenCV.
- **Model Architecture**: Utilizes pretrained models from `torchvision.models` with transfer learning.
- **Data Augmentation**: Implemented using `torchvision.transforms`.
- **Customizable Parameters**: Easily adjust batch size, number of samples, and other hyperparameters.

## Project Structure
- **Notebook**: `Part2_24586683_kai_to_mok.ipynb` - The main file containing the code for data processing, model definition, training, and evaluation.
- **Dataset**: Instructions to load or prepare your dataset.
- **Results**: Logs, metrics, and visualizations of model performance.

## Requirements
Install the required libraries with:
```bash
pip install -r requirements.txt
```
## How to Run
1.Clone the repository:
```bash
git clone https://github.com/TaylorMok0717/food101.git
```
2.Navigate to the project directory:
```bash
cd deep-learning-model
```
3.Open the notebook and execute the cells step by step:
```bash
jupyter notebook Part2_24586683_kai_to_mok.ipynb
````
## Customization
- **Modify parameters such as TrainSampleNo, SampleNo, and batch directly in the notebook.
- **Adjust data transformations in the torchvision.transforms section to suit your dataset.

