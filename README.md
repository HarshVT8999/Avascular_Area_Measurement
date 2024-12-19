# Image Sharpening and Avascularity Analysis

This Jupyter Notebook demonstrates image processing techniques to enhance and analyze grayscale images, particularly for computing avascularity percentages in biological samples.

## Overview
The notebook applies sharpening filters to medical images using the `unsharp_mask` method, enhances image quality, and calculates avascularity based on pixel intensities. It is suitable for researchers working on image analysis, especially in the healthcare and biological fields.

## Features
- **Image Selection**: Load images using a file dialog.
- **Preprocessing**: Convert the image to grayscale.
- **Enhancement**: Apply sharpening filters for better visualization using `unsharp_mask`.
- **Binarization**: Convert the enhanced image to binary based on intensity thresholds.
- **Avascularity Calculation**: Compute the avascularity percentage of a given sample.

## Requirements
The following Python libraries are used:
- `cv2` (OpenCV)
- `numpy`
- `matplotlib`
- `skimage` (Scikit-image)
- `tkinter`

Install them via pip if not already installed:
```bash
pip install opencv-python-headless matplotlib numpy scikit-image
