# Lab 32 — Setting Up and Using a Cloud-Based Jupyter Environment

This repository contains the materials for **Lab 32**, part of the **Data Science — Week 7** curriculum focusing on **Cloud Computing for Data Science**.

## 🎯 Overview
The goal of this lab is to familiarize students with using cloud-based Jupyter environments, specifically **Google Colab**. You will learn how to leverage remote hardware (including GPUs), manage persistent storage via Google Drive, and execute a complete machine learning workflow from data loading to model deployment in the cloud.

## 🚀 Key Learning Objectives
1. **Cloud Setup**: Launch a Jupyter Notebook on Google Colab without local installation.
2. **GPU Acceleration**: Switch to a free **T4 GPU** runtime to speed up model training.
3. **Storage Integration**: Mount Google Drive to save and load files permanently.
4. **Environment Management**: Install additional Python libraries (like `yellowbrick`) using `pip`.
5. **Machine Learning Workflow**:
   - Load and explore the **Iris flower dataset**.
   - Visualize data using `seaborn` pairplots.
   - Train a **Random Forest Classifier**.
   - Evaluate model performance (accuracy, precision, recall).
6. **Model Persistence**: Save a trained model using `joblib` and reload it for future predictions.

## 📋 Prerequisites
- A Google account.
- Access to [Google Colab](https://colab.research.google.com).

## 🛠️ Installation & Setup
To run this lab:
1. Open the `.ipynb` file in Google Colab.
2. Click **File → Save a copy in Drive** to create your own editable version.
3. To enable the GPU, go to **Runtime → Change runtime type** and select **T4 GPU**.

## 📂 Project Structure
- `Lab_Cloud_Jupyter_Setup.ipynb`: The main notebook containing all instructions, code cells, and explanations.

## 🤖 Model Details
The lab utilizes a **Random Forest Classifier** with the following workflow:
- **Data Split**: 80% training, 20% testing (stratified).
- **Features**: Sepal length, sepal width, petal length, petal width.
- **Target**: Iris species (Setosa, Versicolor, Virginica).
- **Persistence**: Models are saved as `.pkl` files in a dedicated Google Drive folder (`DS_Lab_Week7`).

## 🏆 Bonus Challenges
Included in the notebook are homework tasks to deepen your understanding:
- Swapping the model for `LogisticRegression`.
- Experimenting with different `test_size` parameters.
- Applying the workflow to the **Wine dataset**.
- Visualizing feature importance.
- Verifying GPU availability via TensorFlow.

## 🎉 Acknowledgments
This lab is designed for students to master the foundation of real-world data science workflows using cloud infrastructure.
