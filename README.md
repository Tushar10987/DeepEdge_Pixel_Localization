# Deep Learning Pixel Localization (50x50 Image)

## Problem Statement
Predict the (x, y) coordinates of a single bright pixel (value = 255)
in a 50x50 grayscale image using deep learning techniques.

## Approach
- Generated a synthetic dataset with uniform random pixel placement
- Formulated the task as a supervised regression problem
- Trained a shallow CNN to regress pixel coordinates
- Evaluated performance using loss curves, visual overlays, and pixel error metrics

## Results
- Mean localization error: ~0.58 pixels
- Median localization error: ~0.51 pixels
- Stable training and validation convergence

## Dependencies
- Python 3.10
- TensorFlow
- NumPy
- Matplotlib
- Scikit-learn

Install dependencies:
```bash
pip install tensorflow numpy matplotlib scikit-learn
