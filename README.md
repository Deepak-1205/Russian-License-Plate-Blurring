# License Plate Detection and Blurring using OpenCV & Haar Cascade

## Overview

This project implements a **License Plate Detection and Blurring System** using **OpenCV** and a **Haar Cascade Classifier**. The system automatically detects vehicle license plates, applies a blur effect to the detected region, and displays the privacy-protected output image.

The project demonstrates the use of classical computer vision techniques for object detection and image processing applications such as traffic monitoring, automated toll collection, smart parking systems, and privacy protection.

---

##  Aim

To implement a License Plate Detection system using OpenCV and Haar Cascade Classifier, draw bounding boxes, crop the detected region, and blur the license plate to improve privacy. Detection performance is enhanced through parameter tuning of the Haar Cascade classifier.

---
## Author

**Name**: Deepak S

**Register Number**: 212224230053

---
## Software Requirements

* Python 3.7 or above
* OpenCV (`opencv-python`)
* NumPy
* Matplotlib
* Jupyter Notebook / Anaconda
* `haarcascade_russian_plate_number.xml`

---

## Algorithm

### Step 1

Import the required libraries such as OpenCV and Matplotlib.

### Step 2

Load the input vehicle image.

### Step 3

Convert the image into grayscale format for faster processing.

### Step 4

Load the Haar Cascade XML classifier.

### Step 5

Detect license plate regions using the `detectMultiScale()` method.

### Step 6

Extract the detected license plate region using the coordinates returned by the classifier.

### Step 7

Apply Median Blur to the detected plate region.

### Step 8

Replace the original plate area with the blurred version.

### Step 9

Display the final output image.

---

## Output

### Original Image

Input vehicle image containing the license plate.

### Detected License Plate

License plate region detected using Haar Cascade.

### Blurred License Plate

Detected license plate region blurred using Median Filtering for privacy protection.

---

## Result

The License Plate Detection and Blurring system was successfully implemented using OpenCV and Haar Cascade Classifier. The detected license plate region was blurred using Median Filtering, effectively protecting sensitive vehicle information while maintaining image quality.

---

## Conclusion

This project demonstrates the practical application of classical computer vision techniques for license plate detection and privacy protection. By combining Haar Cascade classifiers with image filtering methods, an efficient and lightweight solution for real-time license plate anonymization can be achieved. Proper preprocessing and parameter tuning significantly enhance detection performance and reliability.

---
