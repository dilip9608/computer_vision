# computer_vision
learning computer vision with the examples (observation).
# Image Geometric Transformations using OpenCV (Python)

## Overview
This project demonstrates fundamental **geometric image transformations** using **OpenCV and Python**.  
The implementation is compatible with **Jupyter Notebook** and focuses on both **full-image transformations** and **Region of Interest (ROI)–based transformations**, which are core topics in **Digital Image Processing (DIP)**.

---

## Objectives
- Implement basic geometric transformations in images
- Apply transformations to a selected Region of Interest (ROI)
- Visualize results using Matplotlib
- Understand the practical use of OpenCV transformation functions

---

## Technologies Used
- Python 3.x
- OpenCV (cv2)
- NumPy
- Matplotlib
- Jupyter Notebook

---

## Project Structure
├── input.jpg # Input image
├── image_transformations.ipynb
├── README.md


---

## Transformations Implemented

### 1. Translation
Moves the image along the x and y directions using a translation matrix.

### 2. Rotation
Rotates the image around its center by a specified angle using an affine transformation.

### 3. Scaling
Resizes the image by applying scaling factors along width and height.

### 4. Shearing
Introduces a slanting effect by shifting one axis proportionally to the other.

### 5. Affine Transformation
Uses three reference points to transform the image while preserving straight lines and parallelism.

### 6. Perspective Transformation
Applies a projective transformation to simulate a change in viewpoint.

---

## ROI-Based Transformations
A selected **Region of Interest (ROI)** is extracted from the image, and transformations are applied only to that region.  
This approach is commonly used in object-based image processing, tracking, and segmentation tasks.

---

## How to Run the Project

1. Install required dependencies:
```bash
        pip install opencv-python numpy matplotlib
2.Place the input image in the        project folder and name it:

    input.jpg
3. Launch Jupyter Notebook:

    jupyter notebook
4. Open and run:

    image_transformations.ipynb


Output
        The notebook displays:

        Original image

        Selected ROI

        Transformed images for:

        Translation

        Rotation

        Scaling

        Shearing

        Affine transformation

        Perspective transformation

        All outputs are visualized using Matplotlib.

Applications
        Digital Image Processing laboratory experiments

        Computer vision preprocessing

        Image augmentation for machine learning

        Academic and internship project demonstrations

Notes
        ROI coordinates may need adjustment depending on the input image.

        Scaling may change the output image size.

        All transformations use optimized OpenCV functions.

Conclusion
    This project provides a clear and structured implementation of geometric image transformations using OpenCV.