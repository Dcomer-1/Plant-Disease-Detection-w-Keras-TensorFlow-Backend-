**Plant Disease Classification Using CNN**

  This project uses a Convolutional Neural Network (CNN) to classify plant diseases based on image data. The model uses advanced machine learning techniques to assist plant owners in identifying and addressing plant health issues, ultimately promoting sustainable agriculture.

Project Overview
  The primary objective of this project is to enable accurate and efficient identification of plant diseases using an image-based model. By analyzing images of plant leaves, the CNN predicts the disease category with high precision, empowering users to take timely action to mitigate crop losses.

Dataset
The dataset used for this project includes labeled images of healthy and diseased plant leaves. These images are categorized into various classes, such as specific plant diseases or healthy states. The Dataset Can be found on Kaggle: https://www.kaggle.com/datasets/emmarex/plantdisease

----------------------------

Project Structure
1. Preprocessing and Augmentation
Resizes images to a uniform shape (256, 256, 3) to ensure consistency.
Uses data augmentation (rotation, zoom, etc.) to enrich the dataset and prevent overfitting.
2. CNN Model Architecture
The CNN comprises:

Convolutional Layers: Extract spatial features from the images.
MaxPooling Layers: Reduce dimensionality while preserving essential features.
Fully Connected Dense Layers: Perform classification tasks using the extracted features.

3. Training and Evaluation
The model is trained on the processed dataset using backpropagation and the Adam optimizer.
Validation accuracy and loss are monitored to ensure generalization to unseen data.

4. Visualization
Loss and accuracy metrics are plotted to evaluate the model’s performance over training epochs.

-----------------------------

**Setup Instructions**

This project has a lot of dependencies so the easiest way to run it would probably be to clone my Kaggle notebook here: https://www.kaggle.com/code/dcamarolive/plant-disease-detection-w-keras and run it that way so it can compile with no issues

