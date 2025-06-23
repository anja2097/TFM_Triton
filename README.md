<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/2/2d/Logo_UPV_color.svg" height="80">
  <img src="logo-mic.png" height="80">
</p>

# TFM_Triton

**Trabajo Fin de Máster - MIC (UPV)**  
**Autor/a**: Anja2097  
**Título**: _Uso del lenguaje Triton para optimizar CNN y Transformers en GPU_

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
