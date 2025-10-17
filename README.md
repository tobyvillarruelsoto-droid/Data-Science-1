■ Proyecto Final – Data Science 1
(Coderhouse)
Análisis de la calidad del aire y factores asociados (Air Quality
Dataset)
Autor: Tobias Villarruel
Profesor: Ignacio Russo Locati
Comisión: 90640
Fecha: Octubre 2025
■ Descripción general
Este proyecto forma parte del curso Data Science 1 de Coderhouse y tiene como objetivo aplicar
el proceso completo de análisis de datos, desde la adquisición y exploración de datasets hasta la
construcción de modelos predictivos simples. El trabajo se desarrolló utilizando tres fuentes de
datos, pero el proyecto final se centra específicamente en el dataset de Air Quality (UCI Machine
Learning Repository).
■ Objetivos del proyecto
• Explorar y analizar datos provenientes de fuentes abiertas.
• Identificar relaciones entre variables meteorológicas y químicas relacionadas con la
contaminación del aire.
• Aplicar técnicas de visualización y análisis exploratorio (EDA).
• Construir un modelo predictivo simple que estime el nivel de monóxido de carbono (CO).
• Evaluar el modelo mediante métricas estándar y elaborar conclusiones basadas en los
resultados.
■ Dataset principal: Air Quality (UCI)
El dataset Air Quality contiene mediciones horarias de contaminantes atmosféricos (CO, NOx,
NO■, O■, etc.) y variables meteorológicas (temperatura, humedad, presión). El periodo de
recolección abarca de marzo 2004 a abril 2005 en una zona urbana de Italia.
■ Análisis exploratorio (EDA)
Se observaron correlaciones moderadas entre la temperatura y los niveles de CO(GT),
comportamientos cíclicos diarios en los contaminantes y patrones de dispersión amplios. Se
imputaron valores faltantes con la media y se trabajó con variables numéricas transformadas para
garantizar consistencia.
■ Modelado y métricas
Métrica Valor Interpretación
MAE 58.4 Error medio absoluto
RMSE 76.3 Desviación media del modelo
R² 0.015 Explica un 1.5% de la varianza
■ Conclusiones
Se completó el proceso de Data Science de punta a punta: adquisición, limpieza, análisis,
modelado y evaluación. El modelo confirma que la contaminación atmosférica es un fenómeno
complejo, no lineal y multidimensional. A pesar de su capacidad predictiva limitada, permitió
comprender la dirección y magnitud de las variables.
■ Tecnologías utilizadas
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Google Colab, GitHub.
■ Repositorio: https://github.com/tobyvillarruelsoto-droid/Data-Science-1
■ Entrega final – Data Science 1 (Coderhouse)
Este documento resume todas las etapas del proyecto final, integrando las actividades prácticas y
el modelo predictivo desarrollado por Tobias Villarruel para la Comisión 90640.
