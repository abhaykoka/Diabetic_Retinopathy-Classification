# Deep_Learning-Diabetic_Retinopathy-Classification-Ongoing
Diabetic Retinopathy (DR) is a severe complication of diabetes that affects the retina, potentially leading to vision loss if untreated. Early detection and classification of DR stages are crucial for timely intervention. However, manual diagnosis by ophthalmologists is time-consuming and subjective, requiring expertise and consistency.

Challenges:
Large volume of retinal images to analyze.
Subtle differences between DR severity levels make classification difficult.
Variability in image quality due to lighting, focus, and artifacts.
Need for automated, accurate, and scalable solutions.

Our Objective is to develop a deep learning-based model that can classify DR images with high accuracy, leveraging Convolutional Neural Networks (CNNs) and Vision Transformers.

There are Basicall five classes that are involved :NO_DR,Proliferate,Mild,Moderate and Severe.
In our We leverage the use of CNN's and vision transformers to classify an image into 5 classes and as there are only very few images available of the minor class we have used Data Augmentation to generate, Augmented images of minority classes and made the No' of images equeal in all the classes.
We have employedK-fold Cross-validation method with 75 epochs each for 5 folds.
We have used light weight customised versions of multiple popular CNN architectures.
