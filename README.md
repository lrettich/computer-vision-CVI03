# computer-vision-CVI03
Repository for handing in the code of the project for the module Computer Vision (CVI03)

**Project:** Histological Samples Tissue Classification Model

**Authors:** Eleonora Pedrini-Pedroli, Leo Rettich

**Date:** 30.03.2023

Note: All Jupyter Notebooks in this repository were developed using Google Colab and are meant to be executed as Google Colab Notebooks. 

**Notebooks (original version):** 
- **`data_preparation.ipynb`**: Download of the dataset, data preparation, storing the dataset as pickle file. 
- **`model_training.ipynb`**: Load the prepared dataset from the pickle file, train the model, store the model to google drive. 
- **`model_evaluation.ipynb`**: Load the trained model from a folder, perform model evaluation.
- **`model_application.ipynb`**: Load the trained model from a folder, show how the model can be applied by creating a classification map on a larger image.

**Notebooks (adapted version to include complex stroma):** 
- **`model_training_V2.ipynb`**: Copy of `model_training.ipynb`. Model is trained to predict additionaly the category COMPLEX.
- **`model_application_V2.ipynb`**: Copy of `model_application.ipynb`. Extended by category COMPLEX. 
