# 160122771059 | Sasi Vakul Rithwik | AI&DS - 1 Sem VI | Batch 2
# IVA Assignment-1

## 1. Color Detection
- Loaded an image and determined its dominant color using K-Means clustering.
- Mapped the dominant color to predefined color names based on the closest match.

## 2. T-Pyramid (Gaussian Pyramid) Computation
- Generated a multi-level Gaussian pyramid by downsampling an image.
- Displayed different pyramid levels to analyze image resolution at various scales.

## 3. Image Smoothing
- Applied different image blurring techniques to reduce noise:
  - **Averaging Blur**: Computes the mean of the neighboring pixels.
  - **Gaussian Blur**: Uses a Gaussian kernel for smooth blurring.
  - **Median Blur**: Takes the median value of neighboring pixels (useful for salt-and-pepper noise).
  - **Bilateral Filter**: Preserves edges while reducing noise.

## 4. Edge Detection
- Converted the image to grayscale for better edge detection.
- Applied **Sobel Edge Detection** in both X and Y directions to extract gradients.
- Used **Canny Edge Detection**, which applies gradient-based thresholding to detect edges efficiently.

## 5. Object Detection (Face Detection with Haar Cascades)
- Used a **Haar cascade classifier** to detect faces in an image.
- Converted the image to grayscale and applied histogram equalization for better detection.
- Drew bounding boxes around detected faces using OpenCV.

