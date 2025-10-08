# Actividad Práctica 1 - Data Science 1 (Coderhouse)

**Alumno:** Tobias Villarruel  
**Curso:** Data Science 1 - Coderhouse  

---

## 🎯 Objetivo
La presente actividad tiene como propósito identificar **tres datasets** que cumplan con las siguientes condiciones:
- Al menos **2000 filas**
- Al menos **15 columnas**

Cada dataset se carga mediante la librería **Pandas** y se realiza una breve descripción de las **variables potencialmente interesantes**, considerando el contexto del caso.

---

## 🗂️ Estructura del repositorio
coderhouse-ds1-proyecto-final/
│
├── 📄 Actividad_Practica_1_Villarruel_FINAL.ipynb ← Notebook principal con el análisis
│
└── 📁 data/
└── 📁 raw/
├── WDIData.csv
├── air_quality.csv
└── Global_Development_2000_2020.csv

yaml
Copy code

---

## 📊 Datasets utilizados

| Nº | Dataset | Fuente | Filas | Columnas | Descripción |
|----|----------|---------|--------|-----------|--------------|
| 1 | **World Development Indicators (Argentina)** | [World Bank Open Data](https://databank.worldbank.org/source/world-development-indicators) | +2000 | +60 | Indicadores económicos, sociales y de desarrollo del Banco Mundial. Se filtraron los datos correspondientes únicamente a Argentina, conservando la estructura y volumen necesarios. |
| 2 | **Air Quality (UCI)** | [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Air+Quality) | 9357 | 15 | Mediciones de gases contaminantes, temperatura y humedad registradas por una estación ambiental en Italia. |
| 3 | **Global Development Indicators (2000–2020)** | [Kaggle Dataset](https://www.kaggle.com/datasets/michaelmatta0/global-development-indicators-2000-2020) | +4000 | +20 | Indicadores económicos, sociales y ambientales globales correspondientes al período 2000–2020. |

---

## ⚙️ Librerías utilizadas
- **pandas**
- **numpy**
- **matplotlib**
- **seaborn**
- **pathlib**

---

## 🧠 Resultados y observaciones
- Todos los datasets cumplen con los requisitos de la consigna.  
- Se verificaron correctamente los tamaños mínimos (≥2000 filas y ≥15 columnas).  
- Las variables seleccionadas permiten distintos tipos de análisis exploratorio:  
  - **WDI (Argentina):** evolución histórica de indicadores económicos y sociales.  
  - **Air Quality:** relación entre variables ambientales y contaminantes.  
  - **Global Dev:** correlaciones entre desarrollo humano y crecimiento económico.

---

## ✅ Checklist de la consigna
- [x] 3 datasets seleccionados.  
- [x] Todos cumplen con los requisitos mínimos.  
- [x] Carga mediante librería Pandas.  
- [x] Descripción de variables relevantes.  
- [x] Notebook funcional y probado.  
- [x] Proyecto subido correctamente a GitHub.

---

## 📎 Enlace al repositorio
> *https://github.com/tobyvillarruelsoto-droid/Data-Science-1*
