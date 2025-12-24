# 💡 Affine Transformation in OpenCV (Python Tutorial)
---
[![main branch](https://img.shields.io/badge/branch-main-red?style=flat&logo=git&logoColor=white)](https://github.com/RH-NAYM/OpenCV-Image-Thresholding/tree/main)
#

<p align="center">
  <a href="https://opencv.org/" target="_blank">
    <img src="https://img.shields.io/badge/OpenCV-Computer%20Vision-green?logo=opencv&logoColor=white">
  </a>
  <a href="https://www.python.org/" target="_blank">
    <img src="https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white">
  </a>
  <a href="https://jupyter.org/" target="_blank">
    <img src="https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter&logoColor=white">
  </a>
  <a href="https://numpy.org/" target="_blank">
    <img src="https://img.shields.io/badge/Numpy-Numerical-lightblue?logo=numpy&logoColor=white">
  </a>
  <a href="https://matplotlib.org/" target="_blank">
    <img src="https://img.shields.io/badge/Matplotlib-Visualization-orange?logo=matplotlib&logoColor=white">
  </a>
</p>

# 📌 Overview
This project provides a comprehensive guide to `Affine Transformation` using `OpenCV` in Python. Affine Transformation is a fundamental geometric operation used in computer vision to perform **translation, rotation, scaling, and shearing** while preserving straight lines and parallelism.

The notebook demonstrates both basic transformations and practical applications in image augmentation and preprocessing.
---

The `Jupyter Notebook` demonstrates:
- **Affine Transformation Basics:** Understanding the 2x3 matrix representation.
- **Applying Transformations:** Using `cv2.getAffineTransform` and `cv2.warpAffine`.
- **Visual Comparison:** Before and after transformations.
- **Geometric Intuition:** How points are mapped to new positions.

`Whether you are working on image augmentation, object alignment, or geometric preprocessing, this repository is a practical guide.`

# 📁 Project Structure
```bash
.
├── 📓 Opencv-Affine-Transformation.ipynb   # Comprehensive notebook on affine transformations
├── 📘 README.md                             # Project documentation
├── 📦 requirements.txt                      # Python dependencies
├── 🖼️ testImage.jpg                        # Sample image for demonstrations
└── 🛠️ tools                                # Utility module for image handling
    ├── __pycache__                          # Python cache directory (auto-generated)
    │   └── tools.cpython-312.pyc
    └── tools.py                             # Helper functions for loading & visualization

# 📋 Table of Contents (Notebook Sections)
---
```bash
1. Introduction to Affine Transformations
2. Mathematical Representation (2x3 Matrix)
3. Selecting Source and Destination Points
4. Using cv2.getAffineTransform
5. Applying Transformation with cv2.warpAffine
6. Visualizing Results: Original vs Transformed
7. Best Practices and Real-World Applications
```

# 🧠 What You’ll Learn
---
Affine Math: How the transformation matrix maps points linearly:
$$
\begin{bmatrix}
x' \\
y'
\end{bmatrix}
=
\begin{bmatrix}
a & b \\
c & d
\end{bmatrix}
\begin{bmatrix}
x \\
y
\end{bmatrix}
+
\begin{bmatrix}
t_x \\
t_y
\end{bmatrix}
$$

Image Augmentation: Apply translations, rotations, scaling, and shearing to datasets.

Preservation: Straight lines remain straight; parallel lines remain parallel.

Visualization: Compare original vs transformed images to understand geometric effects.

# 🛠️ Technologies Used
---
- `Python 3.x`
- `OpenCV` for morphological image processing
- `NumPy` for array operations
- `Matplotlib` for visualization
- `Jupyter Notebook` for interactive experimentation


# 📦 Installation
---
## 1️⃣ Create a virtual environment
```bash
python -m venv venv
source venv/bin/activate    # Linux / macOS
venv\Scripts\activate       # Windows
```
## 2️⃣ Install dependencies
```bash
pip install -r requirements.txt
```
# 🚀 How to Run
---
**Option 1: Jupyter Notebook (Local)**
- Install Jupyter if needed: `pip install notebook`.
- Launch Jupyter: `jupyter notebook`.
- Open `OpenCV-Affine-Transformation.ipynb` and run cells sequentially.
    - Notebook will automatically download a placeholder image if testImage.jpg is missing.


**Option 2: Google Colab**
- Upload `OpenCV-Affine-Transformation.ipynb` to Colab.
- Install dependencies: `!pip install -r requirements.txt`.
- Run all cells for interactive demonstrations.


# ✅ Summary
---
Affine Transformation preserves lines and parallelism while enabling flexible geometric modifications.

It's commonly used in image augmentation, object alignment, and preprocessing.

Selecting proper source and destination points is critical for predictable transformations.

Visual verification is essential to understand the geometric effect on images.


# 🍴 Real-World Applications
---
Machine Learning: Data augmentation to increase training dataset diversity.

Object Detection: Aligning objects to canonical positions.

Medical Imaging: Standardizing orientations of scans before analysis.

Satellite & Aerial Imagery: Correcting geometric distortions in images.

# 📝 Contribution
`Feel free to open an issue or submit a pull request to add more advanced contrast stretching techniques or multi-spectral image examples.`
