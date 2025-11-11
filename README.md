# Image Compression and Classification Project with ML

[![GitHub Pages](https://img.shields.io/badge/GitHub-Pages-brightgreen)](https://tunombre.github.io/compression-project/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://python.org)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

Comprehensive project that implements image compression algorithms, handwritten digit classification, and photo mosaic generation using advanced image processing and machine learning techniques.

## 🚀 Key Features

- **Custom DCT Compression**: Compression algorithm that outperforms JPEG in certain scenarios
- **MNIST Classification**: Multiple ML + HOG models for digit recognition (98.94% accuracy)
- **Mosaic Generator**: Three different methods for creating photo mosaics
- **Comparative Analysis**: Quantitative evaluation with PSNR, SSIM, and ΔE

## 📊 Notable Results

| Metric | Result | Improvement vs. Baseline |
|---------|-----------|-------------------|
| Compression (PSNR) | 24.65 dB | +0.24 dB vs JPEG |
| Classification (SVM+HOG) | 98.94% | +0.63% vs raw pixels |
| Mosaic (PSNR) | 11.622 | Best combined method |

## 🛠️ Technologies Used

- **Python 3.8+**
- **Libraries**: NumPy, scikit-image, scikit-learn, OpenCV, Matplotlib
- **Algorithms**: DCT, HOG, KNN, SVM, Decision Trees
- **Metrics**: PSNR, SSIM, ΔE, Accuracy

## 📁 Project Structure
```
compression-project/
├── notebooks/                  
│   ├── TP2_completo.ipynb 
├── docs/                 
│   ├── TP_finished_rapport.pdf
│   └── TP_finished.pdf
├── images/                  # Images and results
└── index.html               # Project website
```
## ⚡ Installation and Use


# Clone the repository
```
git clone https://github.com/jmalfaro2019/image_compressing-ml.git
cd compression-project
```


# Install dependencies
```
pip install -r requirements.txt
```

# Run the notebook
```
jupyter notebook notebooks/iris_analysis.ipynb
```
## 🔗 [View Project on GitHub Pages](https://jmalfaro2019.github.io/image_compressing-ml/)

📄  Full Report
📋  [Download PDF Report](docs/TP_finished_rapport.pdf)

👨‍💻 Author
Jose Alfaro - [GitHub](https://github.com/jmalfaro2019) - [LinkedIn](https://www.linkedin.com/in/jose-alfaro-334327291)

### ⭐ Did you like this project? Give the repository a star!
