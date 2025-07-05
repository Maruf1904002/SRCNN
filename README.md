# SRCNN Image Super-Resolution 🖼️

This project implements the **Super-Resolution Convolutional Neural Network (SRCNN)** in a Jupyter Notebook (`SRCNN_model.ipynb`). The goal is to learn end-to-end mapping from low-resolution to high-resolution images using deep learning.

## 📘 Key Highlights

- Architecture based on **SRCNN (Dong et al., 2014)**.
- Pre-processing steps: downscaling, cropping, normalization, patch extraction.
- Model built using **TensorFlow/Keras** with 3 convolutional layers.
- Visualizes training results and super-resolved image outputs.
- Performance comparison between input (LR) and generated (SR) images.

## 🧱 Requirements

- Python 3.x  
- Jupyter Notebook  
- tensorflow  
- numpy  
- matplotlib  
- scikit-image  
- pillow  

## 🚀 Getting Started

1. Clone the repository:
git clone https://github.com/Maruf1904002/SRCNN.git
2. Install dependencies:
pip install tensorflow numpy matplotlib scikit-image pillow
3. Run the notebook:
jupyter notebook SRCNN_model.ipynb

---

## 🔬 Background

SRCNN was one of the first deep learning models for single-image super-resolution. It was introduced by **Chao Dong et al. (2014)** and laid the foundation for many advanced architectures.

## 📂 Repository Contents

- `SRCNN_model.ipynb` — Implementation notebook with all steps from data processing to output visualization.

## 👤 Author

**Maruf Ahmed**  
Department of Electronics & Telecommunication Engineering  
Rajshahi University of Engineering & Technology (RUET)

## 📄 License

This project is open-source and free to use under the [MIT License](https://opensource.org/licenses/MIT).
