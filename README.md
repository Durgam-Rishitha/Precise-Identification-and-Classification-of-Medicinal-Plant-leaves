# Precise-Identification-and-Classification-of-Medicinal-Plant-leaves
...
## Project Overview

This project focuses on predicting medicinal plant species using leaf images through deep learning. It processes images to extract key features like shape, texture, and color for accurate classification.And it also provide the uses and location where these plants are grown.


...
## Project Structure

Medicinal_leaves_prediction/
├──Source_code/
|   ├──preprocessing.ipynb 
|   ├── Model_Training.ipynb
|   ├── Evaluation_Code.ipynb
|   ├── Deployment_Code.ipynb
|   ├── Main Code.ipynb
├──data/
|   ├──Alovera/
|   ├──Amla/
|   ├──Bamboo/
|   ├──Beans/
|   ├──Castor/
|   ├──Catharanthus/
|   ├──Coffee/
|   ├──Coriender/
|   ├──Globe Amarnath/
|   ├──Jackfruit/
|   ├──Kasambruga/
|   ├──Lemon/
|   ├──Mango/
|   ├──Marigold/
|   ├──Palak(spinach)

...     



## File Description
- **preprocessing.ipynb**This file uploads the dataset, organizes image files, applies data augmentation, and prepares the images for training a deep learning model.
-  **Model_Training.ipynb**The file loads and preprocesses the dataset, visualizes sample images, builds and trains an InceptionV3-based deep learning model for medicinal plant classification, and evaluates its accuracy.
-   **Evaluation_Code.ipynb**The code evaluates a pretrained InceptionV3 model on plant image classification by computing accuracy, loss, precision, recall, and F1-score, while also visualizing training performance with accuracy and loss plots.
-   **Deployment_Code.ipynb**It contains the user interface code and libraries.
...
## Features
- **Upload an Audio File:** Users can upload `.jpg`,`.png`,`.jpeg` format files.
- **Preprocessing:**The input image is cleaned and improved, important features are identified.
- **Deep Learning Model** A deep learning model learns patterns from images and uses them to correctly identify and classify the given plant.
- **Confidence Score:** The model provides a confidence score for classified prediction.
- **Interactive UI:** Built using Streamlit for a user-friendly experience.

## Tech Stack 
- **Python** 
- **TensorFlow** for deep learning
- **Streamlit** for web UI
- **InceptionV3** as Model
- **NumPy & Matplotlib** for data processing & visualization


