## Image Similarity Search with Multiple Approaches


This repository implements an alternative to Google Lens by performing image similarity search using various machine learning approaches. The project includes dataset fine-tuning, feature extraction, and evaluation metrics to compare the performance of different techniques.

Implemented Approaches

	1.	Hashing Method: Converts images into unique hexadecimal codes and performs linear search for matches.
	2.	CNN-Based Feature Extraction: Uses pre-trained convolutional neural networks for feature extraction and similarity search.
	3.	Siamese Network: Employs a pairwise learning approach to determine the similarity between image pairs.
	4.	Vision Transformer (ViT): Leverages the power of self-attention to process image patches for similarity search.
	5.	Autoencoder-Based Approach: Encodes and decodes images to extract meaningful representations for similarity comparison.

 Dataset Preparation

	•	The dataset is fine-tuned by applying the following techniques:
	•	Resizing: All images are resized to a consistent resolution.
	•	Normalization: Pixel values are normalized to a range of 0-1.
	•	Data Augmentation: Variations such as rotation, flipping, and zooming are applied to increase dataset diversity.
	•	Class Balancing: Ensures equal representation of all classes.

 
