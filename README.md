# SVD and Its Applications: Movie Recommendation, PCA, and Image Compression

This project demonstrates the power and versatility of **Singular Value Decomposition (SVD)** in solving real-world problems through three practical implementations:
- 📊 **Movie Recommendation System**
- 📉 **Principal Component Analysis (PCA)**
- 🖼️ **Image Compression**

The notebook is written entirely in Python using standard libraries such as NumPy, Pandas, Matplotlib, and Scikit-learn.

---

## Features

- **Custom SVD Implementation**:
  - Implemented a custom SVD function for an input matrix
  - Compared the performance of the custom function and pythons inbuilt library SVD function.

- **Recommendation System**:
  - Uses SVD to approximate missing ratings in a user-item matrix.
  - Demonstrates how collaborative filtering predicts unknown user preferences.

- **PCA via SVD**:
  - Shows how dimensionality reduction is performed using the singular values.

- **Image Compression**:
  - Applies low-rank SVD approximation on grayscale images.
  - Visualizes original vs compressed image and reconstruction error.
