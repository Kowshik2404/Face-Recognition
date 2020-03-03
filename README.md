# Face-Recognition

Overview
In this problem, we use a pre-trained model trained on Face recognition to recognize similar
faces.
Here, we are particularly interested in recognizing whether two given faces are of the same
person or not. Below are the steps involved in the project.

Data link : 
https://drive.google.com/file/d/1AuJ7yQlq3FhRFZy3MK2DwvtxtFgTDP2h/view?usp=sharing

1. Load the dataset and create the metadata.
2. Check some samples of metadata.
3. Load the pre-trained model and weights.
4. Generate Embedding vectors for each face in the dataset.
5. Build distance metrics for identifying the distance between two given images.
6. Use PCA for dimensionality reduction.
7. Build SVM classifier to map each image to its right person.
8. Predict using the SVM model.
