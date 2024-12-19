# Image Sharpening and Avascularity Analysis

This Jupyter Notebook demonstrates image processing techniques to enhance and analyze grayscale images, particularly for computing avascularity percentages in biological samples.

Overview

The notebook applies sharpening filters to medical images using the unsharp_mask method, enhances image quality, and calculates avascularity based on pixel intensities. It is suitable for researchers working on image analysis, especially in the healthcare and biological fields.

Features
	1.	Load and preprocess images (convert to grayscale).
	2.	Apply sharpening filters for better visualization.
	3.	Binarize the enhanced image based on intensity thresholds.
	4.	Compute the avascularity percentage of a given sample.

Requirements

The following Python libraries are used in the notebook:
	•	cv2 (OpenCV)
	•	numpy
	•	matplotlib
	•	skimage (Scikit-image)
	•	tkinter

Steps
	1.	Image Selection:
	•	Use a file dialog to select an image for analysis.
	2.	Preprocessing:
	•	Convert the image to grayscale.
	3.	Enhancement:
	•	Apply the unsharp_mask method with configurable parameters (radius and amount).
	4.	Binarization:
	•	Convert the image to binary based on an intensity threshold.
	5.	Avascularity Computation:
	•	Calculate the avascularity percentage of the region of interest.

Usage

To run this notebook:
	1.	Clone or download the repository.
	2.	Install the required libraries:

 pip install opencv-python-headless matplotlib numpy scikit-image

 	3.	Open the notebook in Jupyter or any compatible environment.
	4.	Follow the prompts to select an image file and process it.

Output
	•	Visual comparison of the original and enhanced images.
	•	Binarized image.
	•	Avascularity percentage of the analyzed region.

Acknowledgments

This notebook is designed for applications in medical and biological research, especially for analyzing vascular properties in images
