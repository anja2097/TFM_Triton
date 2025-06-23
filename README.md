<p align="center">
  <img src="img/UPV.jpg" alt="Logo UPV" height="70">
  &nbsp;&nbsp;&nbsp;&nbsp;
  <img src="img/MIC.png" alt="Logo MIC" height="70">
</p>

<p align="center">
  <img src="img/Triton.png" alt="Logo Triton" height="160">
</p>

<h1 align="center">TFM_Triton</h1>

<p align="center">
  Optimización de modelos CNN y Transformers usando Triton
</p>

# Optimización de redes neuronales para GPUs con Triton

**Trabajo Fin de Máster - Máster Universitario en Ingeniería de Computadores y Redes - DISCA - UPV**  
**Autor**: Antonino Ciordia Barcos
**Tutor**: Enrique S. Quintana-Ortí, Adrián Castelló  

---

## 🎯 Objetivo

Este TFM estudia el impacto del uso de [Triton](https://github.com/openai/triton), un lenguaje y compilador para kernels personalizados en GPU, en la **optimización de modelos de deep learning**, como:

- **Convolutional Neural Networks (CNNs)**

Se analiza el rendimiento frente a implementaciones tradicionales en PyTorch y CuPy y se exploran ventajas a nivel de coste computacional, flexibilidad y portabilidad del código.

---

## 🧠 Tecnologías usadas

- `Python 3.10`
- `Triton` (OpenAI)
- `PyTorch`
- `NumPy`, `Pandas`, `Matplotlib`
- `Jupyter Notebook`

---

## 📁 Estructura del repositorio

```text
TFM_Triton/
│
├── Ejecucion_modelos.ipynb       <- Notebook principal con ejecución de pruebas
├── requirements.txt              <- Librerías necesarias
├── resultados/                   <- Directorios con resultados y salidas
├── LICENSE                       <- Licencia del proyecto
└── README.md                     <- Este documento
