# PCD Assignment 02 - Image Enhancement

**Name:** Mazaya Nurina  
**NIM:** 25/554758/PA/23236

## Topic

**Image Enhancement Based on Pixel**

## Method

**Histogram Equalization**

## Description

This assignment implements image enhancement using Histogram Equalization. A low-contrast city image is used as the input image.

The purpose of this experiment is to improve the contrast of the image by changing the distribution of its pixel intensity values. The original image is first converted into grayscale and its histogram is analyzed. Histogram Equalization is then applied to the grayscale image, and the original and enhanced results are compared.

## Objectives

- Understand the concept of image enhancement.
- Analyze the histogram of a low-contrast image.
- Implement Histogram Equalization.
- Compare the original and enhanced images.
- Compare the pixel intensity distributions before and after enhancement.

## Tools and Libraries

- Google Colab
- Python
- OpenCV
- NumPy
- Matplotlib
- Google Drive

## Process

The experiment follows these steps:

1. Load the original `city.jpg` image from Google Drive.
2. Convert the image into grayscale.
3. Display the original grayscale image.
4. Analyze the original image histogram.
5. Apply Histogram Equalization using OpenCV.
6. Display the enhanced image.
7. Display the histogram after enhancement.
8. Compare the original and enhanced images.
9. Compare the original and enhanced histograms.
10. Save the processed images.

## Results

### Original Image

The original city image has relatively low contrast. The grayscale histogram shows that the pixel intensity values are concentrated within a limited range.

### Histogram Equalization

Histogram Equalization spreads the pixel intensity values over a wider range. As a result, the contrast of the image is increased and some details become easier to distinguish.

### Comparison

The original and enhanced images are compared visually, while their histograms are compared to observe the changes in pixel intensity distribution.

## Repository Structure

```text
PCD_Assignment02/
│
├── PCD_Assignment02.ipynb
├── README.md
│
├── images/
│   ├── city.jpg
│   ├── original_gray.jpg
│   └── histogram_equalized.jpg
│
└── report/
    └── analysis.pdf
