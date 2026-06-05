# Edge Detection Exploration

A computer vision project focused on understanding, implementing, and comparing classical and modern edge detection techniques.

---

## Project Overview

This project was developed as part of the **Artificial Intelligence in Image Processing** course.

The primary goal was not to build a production-ready application, but to explore the evolution of edge detection methods, understand their underlying principles, and evaluate their behavior on different types of images.

The notebook combines classical image processing techniques with modern deep learning approaches, providing both theoretical explanations and practical experiments.

---

## Learning Objectives

* Understand how edge detection works
* Explore classical image processing techniques
* Investigate the impact of image characteristics on edge detection quality
* Compare traditional algorithms with deep learning-based approaches
* Evaluate edge detectors on real datasets

---

## Methods Explored

### Classical Methods

* Sobel
* Prewitt
* Roberts Cross
* Laplacian of Gaussian (LoG)
* Difference of Gaussians (DoG)
* Canny Edge Detector

### Advanced Topics

* Scale-space analysis
* Real-time edge detection using webcam input
* Influence of illumination on edge detection
* Edge quality evaluation using image metrics

### Deep Learning Approaches

* Holistically-Nested Edge Detection (HED)
* Kornia Edge Detection

---

## Experiments

### Classical Edge Detection

Implementation and comparison of:

* Sobel
* Prewitt
* Roberts
* Canny

### Scale-Space Analysis

Investigation of how Gaussian smoothing (σ) affects detected edges and image details.

### Illumination Analysis

Study of how different lighting conditions influence edge detection performance.

### Real-Time Detection

Live edge detection using a webcam and OpenCV.

### Deep Learning Edge Detection

Application of HED, a CNN-based edge detector trained on BSDS500.

### Benchmark Comparison

Comparison between:

* Canny
* HED
* Kornia

using images from the BSDS500 dataset.

---

## Dataset and Resources

The project uses:

### Custom Images

* Lotus
* Woman
* Coins
* Squirrel
* Controlled illumination images

### External Dataset

* BSDS500 (Berkeley Segmentation Dataset)

Used for evaluating modern edge detection approaches.

---

## Repository Structure

```text
.
├── DetectiaMuchiilor.ipynb
│
├── images/
│   ├── lotus.jpg
│   ├── woman.jpg
│   ├── coins.png
│   ├── veverita.webp
│   └── LuminaDeIntensitate*.png
│
├── models/
│   ├── deploy.prototxt
│   └── hed_pretrained_bsds.caffemodel
│
├── requirements.txt
└── README.md
```

---

## Technologies Used

* Python
* OpenCV
* NumPy
* Matplotlib
* Scikit-Image
* SciPy
* PyTorch
* Kornia
* Jupyter Notebook

---

## Additional Resources

The pretrained HED model (`hed_pretrained_bsds.caffemodel`) is not included due to its size.

To run the HED experiments, download the model from the original repository and place it inside the `models/` folder.

---

## Key Takeaway

This project represents a learning and exploration journey through edge detection techniques, from classical gradient-based operators to modern deep learning methods.

Rather than focusing on a single algorithm, the notebook investigates how different approaches behave under various conditions and highlights the strengths and limitations of each method.
