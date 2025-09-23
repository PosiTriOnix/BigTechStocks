# 📈 Proyecto 3 – Análisis de Big Tech Stocks

Este proyecto forma parte del bootcamp **Skill Up Data (Laboratoria+)**.  
El objetivo es **analizar los precios históricos de acciones de empresas tecnológicas (Big Tech)**, explorando su volatilidad, correlaciones y posibles recomendaciones de inversión.

---

## 🎯 Objetivos
- Analizar el comportamiento histórico de las acciones de Big Tech.  
- Calcular retornos diarios y evaluar volatilidad.  
- Identificar correlaciones entre empresas para estrategias de diversificación.  
- Generar visualizaciones que apoyen la toma de decisiones de inversión.  

---

## 📂 Estructura del repositorio
Proyecto3_BigTechStocks/
│
├── Proyecto3_Stocks_Gaby.ipynb   # Notebook principal en Google Colab
├── data/                         # Datasets (o link a Kaggle/Drive si son muy grandes)
├── images/                       # Gráficas exportadas para presentación
├── README.md                     # Este archivo
└── requirements.txt              # (Opcional) librerías necesarias

---

## ⚙️ Librerías principales
- pandas  
- numpy  
- matplotlib / seaborn  
- plotly (para gráficos interactivos)  

---

## 🚀 Cómo usar el notebook
Haz clic aquí para abrir el notebook en Colab:  

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/PosiTriOnix/BigTechStocks/blob/main/Stocks.ipynb)

### Pasos
1. Ejecuta la celda **`Setup & Reload`** al inicio:  
   - Monta Google Drive.  
   - Carga y limpia el dataset.  
   - Calcula variables como `daily_return`.  
   - Genera o carga el archivo `.parquet` para acelerar sesiones futuras.  

2. Corre las celdas de análisis:  
   - Tendencias de precios.  
   - Distribución de retornos (boxplots).  
   - Correlaciones (heatmaps).  
   - Rankings de volatilidad y retorno promedio.  

---

## 📊 Resultados principales
- **Apple (AAPL)** y **Microsoft (MSFT)** → mayor estabilidad (baja volatilidad).  
- **Tesla (TSLA)** y **Nvidia (NVDA)** → más volátiles, con alto potencial de ganancia/riesgo.  
- **IBM** → baja correlación con el resto, ideal para diversificación.  
- Alta correlación entre **AAPL, MSFT, GOOGL, META** → se mueven en bloque, menor diversificación.  

---

## 🖼️ Ejemplo de visualización
![Ejemplo gráfico de correlación](images/correlacion.png)

---

## 📝 Notas
- Dataset: [Kaggle – Big Tech Stock Prices](https://www.kaggle.com/).  
- Los archivos originales `.xlsx` están en `/data`.  
- Se recomienda trabajar con la versión `.parquet` para mayor velocidad en Colab.  
