# Disease_Identification_and_Progression_Monitoring-

This project aims to classify malaria cell images into two categories: "Parasitized" and "Uninfected". Malaria is a life-threatening disease caused by parasites that are transmitted to people through the bites of infected female Anopheles mosquitoes. Rapid and accurate diagnosis of malaria is crucial for effective disease management and control.

![image](https://github.com/JITESHMD/Disease_Identification_and_Progression_Monitoring-/assets/121152161/f9686755-e929-4094-a302-e1293e9e413d)


# Project Explanation
Malaria remains a significant public health issue in many parts of the world, particularly in tropical and subtropical regions. Early detection and treatment of malaria cases are essential for reducing mortality rates and preventing the spread of the disease.

This project utilizes deep learning techniques, specifically Convolutional Neural Networks (CNNs), to automatically classify microscopic images of blood cells as either infected (parasitized) or uninfected. By analyzing thousands of cell images, the model learns to recognize patterns and features indicative of malaria infection, enabling accurate classification of new images.

# The main objectives of this project are:

Automated Diagnosis: Develop a system capable of automatically diagnosing malaria from microscopic blood cell images with high accuracy.


Efficiency: Provide a fast and efficient method for malaria diagnosis, reducing the time and resources required for manual examination by healthcare professionals.


Scalability: Create a scalable solution that can be deployed in various healthcare settings, including resource-limited regions where access to trained medical personnel may be limited.

# Project Structure
data/: Contains the dataset for training and testing.
model.h5: Pre-trained model file saved after training.
main.py: Main Python script containing the code for data preprocessing, model training, evaluation, and prediction.
README.md: This README file providing an overview of the project.

# Setup Instructions
Clone the repository to your local machine.
Install the required dependencies by running pip install -r requirements.txt.
Ensure you have the necessary dataset available at the specified location in the code.
Run the main.py script to train the model and make predictions.


# Usage
To train the model: Run the main.py script. The trained model will be saved as model.h5.
To evaluate the model performance: View the accuracy and loss curves generated during training.
To make predictions: Use the saved model to predict classes for new images.


# Dependencies
Python 3.x
TensorFlow
NumPy
pandas
matplotlib
scikit-learn
keras


![image](https://github.com/JITESHMD/Disease_Identification_and_Progression_Monitoring-/assets/121152161/db98ba49-dde0-4993-bce5-76447608a425)


# Credits
This project was created by Jitesh.
