# Robust Deepfake Video Detection Using CNN-Based Spatial Features and Temporal Consistency Analysis

## Overview

This project presents a deep learning-based framework for detecting deepfake videos using Convolutional Neural Networks (CNNs) and temporal consistency analysis.

The proposed system extracts spatial facial features from video frames and combines them with temporal analysis to identify inconsistencies across consecutive frames for accurate deepfake detection.

---

## Research Status

📌 Research Paper Submitted to:

**International Conference on Applied Intelligent Devices, Machine Learning and Data Science (AIDML 2026)**

**Paper Title:**  
Robust Deepfake Video Detection Using CNN-Based Spatial Features and Temporal Consistency Analysis

⚠️ The paper is currently under review and has not yet been published.

Therefore, the complete manuscript and source files are not publicly included in this repository at this stage.

---

## Features

- Deepfake video detection using deep learning
- CNN-based spatial feature extraction
- Temporal inconsistency analysis
- Face detection and preprocessing
- Binary classification (Real / Deepfake)
- Efficient and scalable pipeline
- High detection accuracy

---

## Methodology

The proposed pipeline includes:

1. Video Frame Extraction
2. Face Detection and Cropping
3. Image Preprocessing
4. CNN-based Spatial Feature Extraction
5. Temporal Analysis
6. Feature Fusion
7. Classification Layer
8. Real/Deepfake Prediction

---

## Technologies Used

- Python
- TensorFlow
- Keras
- OpenCV
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## Dataset

The model is evaluated using publicly available datasets including:

- FaceForensics++
- DFDC Dataset
- Celeb-DF

---

## Experimental Results

| Metric | Value |
|--------|--------|
| Accuracy | 98.33% |
| Precision | 98.88% |
| Recall | 97.78% |
| F1-Score | 98.32% |

---

## Repository Contents

```bash
robust-deepfake-video-detection/
│
├── implementation/
├── images/
├── dataset/
├── results/
├── requirements.txt
└── README.md
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/bharath-ganga/robust-deepfake-video-detection.git
```

Install required packages:

```bash
pip install -r requirements.txt
```

Run the project:

```bash
jupyter notebook
```

---

## Results and Analysis

The proposed model successfully combines spatial and temporal analysis to improve deepfake video detection performance. Experimental evaluation demonstrates strong classification accuracy and robustness across manipulated video datasets.

---

## Authors

- Dr. S. Bharath Bhushan
- Ragi Chandramouli
- Naga Malleswara Rao P
- Ganga Bharath

---

## License

This project is intended for academic and research purposes only.

---

## Future Work

- Improve generalization on unseen datasets
- Reduce computational complexity
- Explore transformer-based architectures
- Real-time deepfake detection optimization
