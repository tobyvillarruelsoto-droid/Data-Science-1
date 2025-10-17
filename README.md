# 🧠 Proyecto Final – Data Science 1 (Coderhouse)

### *Análisis de la calidad del aire y factores asociados (Air Quality Dataset)*

**Autor:** Tobias Villarruel  
**Profesor:** Ignacio Russo Locati  
**Comisión:** 90640  
**Fecha:** Octubre 2025  

---

## 📘 Descripción general

Este proyecto forma parte del curso **Data Science 1** de Coderhouse y tiene como objetivo aplicar el proceso completo de análisis de datos, desde la adquisición y exploración de datasets hasta la construcción de modelos predictivos simples.  

El trabajo se desarrolló utilizando tres fuentes de datos, pero el **proyecto final se centra específicamente** en el dataset de **Air Quality (UCI Machine Learning Repository)**.  

---

## 🎯 Objetivos del proyecto

- Explorar y analizar datos provenientes de fuentes abiertas.  
- Identificar relaciones entre variables meteorológicas y químicas relacionadas con la contaminación del aire.  
- Aplicar técnicas de visualización y análisis exploratorio (EDA).  
- Construir un modelo predictivo simple que estime el nivel de monóxido de carbono (CO).  
- Evaluar el modelo mediante métricas estándar y elaborar conclusiones basadas en los resultados.  

---

## 📂 Estructura del repositorio

Data-Science-1/
│
├── data/
│ └── raw/
│ ├── air_quality.csv
│ ├── WDIData.csv
│ └── global_development_indicators.csv
│
├── Actividad_Practica_1_Villarruel.ipynb
├── Actividad_Practica_2_Villarruel.ipynb
├── ProyectoDSParteI_Villarruel.ipynb
├── ProyectoDSParteII_Villarruel.ipynb
├── ProyectoParteIII_Villarruel.ipynb
└── README.md


---

## 📊 Dataset principal: Air Quality (UCI)

El dataset **Air Quality** contiene mediciones horarias de contaminantes atmosféricos (CO, NOx, NO₂, O₃, etc.) y variables meteorológicas (temperatura, humedad, presión).  
El periodo de recolección abarca desde marzo de 2004 hasta abril de 2005, en una zona urbana de Italia.  

**Variables destacadas:**
- `CO(GT)`: concentración de monóxido de carbono (ppm)  
- `C6H6(GT)`: concentración de benceno  
- `NOx(GT)`: concentración de óxidos de nitrógeno  
- `T`, `RH`, `AH`: temperatura, humedad relativa y absoluta  

---

## 🔍 Análisis exploratorio (EDA)

Durante el análisis exploratorio se observaron:  

- Correlaciones moderadas entre **temperatura** y **niveles de CO(GT)**.  
- Comportamientos cíclicos diarios en los contaminantes.  
- Patrones de dispersión amplios que indican influencia de factores externos no lineales.  

Se identificaron valores faltantes y se imputaron utilizando la **media aritmética**, garantizando consistencia en las variables numéricas antes del modelado.

---

## 🧮 Modelado y métricas

Se aplicó un modelo de **Regresión Lineal** para estimar los valores de `CO(GT)` a partir de las variables más relevantes seleccionadas con **SelectKBest (f_regression)**.  

**Métricas obtenidas:**

| Métrica | Valor | Interpretación |
|----------|--------|----------------|
| **MAE** | 58.4 | Error medio absoluto |
| **RMSE** | 76.3 | Desviación media del modelo |
| **R²** | 0.015 | El modelo explica el 1.5 % de la varianza de CO(GT) |

📈 *El modelo muestra una capacidad predictiva limitada, pero cumple el objetivo académico de implementar el flujo completo de análisis y modelado.*

---

## 🧭 Conclusiones

- Se completó el proceso de **Data Science end-to-end**: adquisición, limpieza, análisis, modelado y evaluación.  
- Los resultados reflejan la **complejidad no lineal** del fenómeno de contaminación atmosférica.  
- Aunque la regresión lineal presenta bajo poder explicativo, permitió comprender la dirección y magnitud de las relaciones.  
- Como trabajo futuro, se sugiere implementar **modelos no lineales** (Random Forest, Gradient Boosting) e incorporar nuevas variables externas (por ejemplo, tráfico y condiciones meteorológicas extendidas).  

---

## 🧰 Tecnologías utilizadas

- Python 3  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Google Colab / Jupyter Notebook  
- GitHub  

---

## 📎 Enlace al repositorio

🔗 [https://github.com/tobyvillarruelsoto-droid/Data-Science-1](https://github.com/tobyvillarruelsoto-droid/Data-Science-1)

---

### ✅ Entrega final – Coderhouse Data Science 1  

Este repositorio presenta la **versión final del proyecto** desarrollado por **Tobias Villarruel (Comisión 90640)** bajo la supervisión del profesor **Ignacio Russo Locati**, integrando todas las actividades prácticas, análisis exploratorios, visualizaciones, modelado predictivo y conclusiones académicas.

---
