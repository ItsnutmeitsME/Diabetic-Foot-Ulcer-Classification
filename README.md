# Diabetic-Foot-Ulcer-Classification

**Overview:**

This project involves the development and implementation of a Convolutional Neural Network (CNN) to classify thermal images of feet from individuals with and without diabetes. Diabetes can manifest in various ways, including changes in foot temperature, which can be captured through thermal imaging. The goal of this project is to automate the classification process to aid in early diagnosis and monitoring of diabetic foot conditions.


**Dataset:**

The dataset consists of thermal images of feet, categorized into two classes:

	•	Control Group
	•	DM Group

The dataset is divided into training and validation sets, with images resized to 64x64 pixels for the CNN model.


**Model Architecture:**

The CNN model used in this project comprises the following layers:

	1.	Convolutional Layers: Extract features from the input images.
	2.	Max-Pooling Layers: Down-sample the feature maps.
	3.	Flatten Layer: Convert the 2D feature maps to a 1D feature vector.
	4.	Dense Layers: Perform classification based on the extracted features.

The model was trained using the Adam optimizer and binary cross-entropy loss function.


**Evaluation:**

The model was evaluated using a confusion matrix, which provided insights into its performance:
![Confusion matrix](https://github.com/user-attachments/assets/3bff3adb-2683-466b-b4ae-a947387c87a5)

This shows that the model has a 91% accuracy.


**Conclusion:**

This project successfully demonstrates the use of a CNN for classifying thermal images of feet, achieving an accuracy of 91%. This automated approach can potentially aid in early detection and monitoring of diabetic foot conditions, providing valuable support in medical diagnostics.



**Dataset:**

The dataset used for the project: https://www.kaggle.com/datasets/vuppalaadithyasairam/thermography-images-of-diabetic-foot
