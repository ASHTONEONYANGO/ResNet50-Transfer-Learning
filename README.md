# ResNet50-Transfer-Learning

Image Classification using Transfer Learning by Retraining Residual Networks

Data (https://www.kaggle.com/birajsth/cats-and-dogs-filtered)
Colab Notebooks – open in copy
(https://colab.research.google.com/drive/1a88xF5742rnFuB2vVfopcA97sNmKM0sa?usp=sharing )

Analysis Objective
The objective of the project is to retrain a Residual Network (ResNet50) model that can perform Image Classification on an image dataset of cats and dogs.

Theoritical Background
The human brain by design, can easily recognize and distinguish between objects in an image, or images. As an example, given the image of a cat or a dog, a human brain can distinguish between the two within nanoseconds of each other, and our brain perceives the difference.
If a machine could mimic this behavior, Artificial Intelligence is as close as it gets. The field of Computer Vision aims to achieve this milestone, mimicking the human vision system, and there have been strides towards achieving this. 
Rapid developments in Computer Vision, and by extension – Image Classification, has been further accelerated by the advent of Transfer Learning. in this regard, Transfer Learning enables us to use a pre-existing and pre-trained Deep Learning Model, that has been trained on huge datasets, for our applied tasks.
One of the top pre-trained models for Image Classification, that is state of the art and is also widely used in the industry, is the Residual Network (ResNet50).

Experimental Design
The process of Image Classification using pre-trained ResNet50 model involves:
•	Setting up the System
•	Loading and Preparing the Dataset
•	Image Preprocessing
•	Model Building (Retraining)
o	ResNet50
Data Relevance
The images dataset used in this project have been accessed form and are publicly available on Kaggle. 
(https://www.kaggle.com/birajsth/cats-and-dogs-filtered)
The data has been split into the training set and test set. 
•	Training set
o	Cats
	1000 images
o	Dogs
	1000 images
•	Validation Set
o	Cats 
	500 images
o	Dogs
	500 images
