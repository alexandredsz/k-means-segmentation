# Project: Image Segmentation with K-means

This project focuses on developing an image segmentation solution by implementing the K-means clustering algorithm from scratch. The primary objective was to group the pixels of an image based on their colors, resulting in a simplified version of the original image that facilitates visual analysis.

---

## Project Details

### K-means Implementation (`kmeans`)
The `kmeans(data, k)` function was implemented in Python to perform clustering tasks. It processes a data matrix, where each row represents a pixel from an image, and distributes these pixels into `k` clusters based on color proximity.

### Image to Data Conversion (`imageToData`)
The `imageToData(I)` function converts an image into an `n x 3` matrix, where `n` is the total number of pixels. Each row in the matrix contains the RGB values of a pixel, allowing the image to be treated as numerical data by the K-means algorithm.

### Image Segmentation (`segmentImage`)
The `segmentImage(I, k)` function combines the previous functions and applies the K-means algorithm to the converted image. The result is a segmented image where pixels with similar colors are grouped into clusters, highlighting different regions of the image.

---

## Technologies Used
- **Python**: The core language used for implementing the algorithm and auxiliary functions.
- **OpenCV/PIL**: Used for image processing and manipulation.
- **Numpy**: Employed for mathematical operations and array handling.

---

## Applications
This project demonstrates how K-means can be applied to efficiently segment images. The technique is useful in various areas such as image compression, pattern detection, and visual analysis. Implementing K-means provides practical insights into how unsupervised learning algorithms can be utilized in image processing.

---

## Notebook
All the code for this project is contained within the Jupyter notebook: `segmentation-with-k-means.ipynb`.

## Project By
[Alexandre Diniz](https://github.com/alexandredsz), Computer Science student at UFMS