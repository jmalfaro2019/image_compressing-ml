# Proyecto de Compresión de Imágenes y Clasificación con ML

[![GitHub Pages](https://img.shields.io/badge/GitHub-Pages-brightgreen)](https://tunombre.github.io/compression-project/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://python.org)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

Proyecto integral que implementa algoritmos de compresión de imágenes, clasificación de dígitos manuscritos y generación de mosaicos fotográficos usando técnicas avanzadas de procesamiento de imágenes y machine learning.

## 🚀 Características Principales

- **Compresión DCT Personalizada**: Algoritmo de compresión que supera JPEG en ciertos escenarios
- **Clasificación MNIST**: Múltiples modelos ML + HOG para reconocimiento de dígitos (98.94% precisión)
- **Generador de Mosaicos**: Tres métodos diferentes para crear mosaicos fotográficos
- **Análisis Comparativo**: Evaluación cuantitativa con PSNR, SSIM y ΔE

## 📊 Resultados Destacados

| Métrica | Resultado | Mejora vs Baseline |
|---------|-----------|-------------------|
| Compresión (PSNR) | 24.65 dB | +0.24 dB vs JPEG |
| Clasificación (SVM+HOG) | 98.94% | +0.63% vs raw pixels |
| Mosaico (PSNR) | 11.622 | Mejor método combinado |

## 🛠️ Tecnologías Utilizadas

- **Python 3.8+**
- **Librerías**: NumPy, scikit-image, scikit-learn, OpenCV, Matplotlib
- **Algoritmos**: DCT, HOG, KNN, SVM, Árboles de Decisión
- **Métricas**: PSNR, SSIM, ΔE, Accuracy

## 📁 Estructura del Proyecto
```
compression-project/
├── notebooks/                  
│   ├── TP2_completo.ipynb 
├── docs/                 
│   ├── TP_finished_rapport.pdf
│   └── TP_finished.pdf
├── images/                  # Imágenes y resultados
└── index.html               # Página web del proyecto
```
## ⚡ Instalación y Uso


# Clonar el repositorio
```
git clone https://github.com/jmalfaro2019/image_compressing-ml.git
cd compression-project
```


# Instalar dependencias
```
pip install -r requirements.txt
```

# Ejecutar el notebook
```
jupyter notebook notebooks/iris_analysis.ipynb
```
## 🔗 [Ver Proyecto en GitHub Pages](https://jmalfaro2019.github.io/image_compressing-ml/)

📄  Reporte Completo
📋  [Descargar Reporte PDF](docs/TP_finished_rapport.pdf)

👨‍💻 Autor
Jose Alfaro - [GitHub](https://github.com/jmalfaro2019) - [LinkedIn](https://www.linkedin.com/in/jose-alfaro-334327291)

### ⭐ ¿Te gustó este proyecto? ¡Dale una estrella al repositorio!
