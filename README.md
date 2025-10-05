# sistema-predictivo-rio-piura
Sistema predictivo basado en Machine Learning para proyectar desbordes del río Piura (2025)
Sistema Predictivo de Desbordes del Río Piura – Proyección 2025
Este proyecto implementa un **modelo de Machine Learning (Random Forest)** para predecir la **probabilidad de desbordes del río Piura**, integrando variables hidrometeorológicas como:
- Nivel de precipitación  
- Caudal del río (m³/s)  
- Porcentaje de humedad relativa  
- Temperatura media  
- Número de desbordes por año  
- Área afectada (km²)  
- Duración del evento (horas)  
- Nivel de daño reportado  
##  Descripción técnica
El sistema utiliza un enfoque **supervisado** mediante el modelo **Random Forest**, con validación temporal (`TimeSeriesSplit`) y análisis interpretativo con **SHAP**.  
Incluye visualización avanzada con **Plotly**, mostrando métricas, correlaciones y un **dashboard interactivo** que proyecta la probabilidad de desborde hacia el **año 2025**.
## Tecnologías empleadas
- Python (Google Colab)
- Pandas, NumPy
- Scikit-learn (Random Forest)
- SHAP (interpretabilidad del modelo)
- Matplotlib, Seaborn, Plotly
##  Métricas del modelo
- **ROC-AUC:** ~0.85  
- **F1-Score:** ~0.80  
- **Validación cruzada temporal (TimeSeriesSplit)**  

## Cómo ejecutar
1. Abre el notebook en [Google Colab](https://colab.research.google.com/)
2. Sube tus datasets:  
   `caudal.xlsx`, `nivel.xlsx`, `precip.xlsx`, `clima.xlsx`, `eventos.xlsx`
3. Ejecuta todas las celdas  
4. Visualiza el **dashboard interactivo final** con resultados y métricas

## Resultados esperados
- Predicción de desbordes del río Piura con proyección hacia 2025  
- Identificación de variables hidrometeorológicas más influyentes  
- Análisis visual e interpretativo para toma de decisiones

## 👨‍💻 Autor:Evangelista Sifuentes Raul Yhampiher
**[ Asesor Técnico / Desarrollador del Modelo]**  
📍 Proyecto de investigación aplicada – Universidad Nacional Mayor de San Marcos / 
🔗 [LinkedIn](https://www.linkedin.com/in/macroinformatica/)  
<img width="1761" height="600" alt="newplot (2)" src="https://github.com/user-attachments/assets/596b4620-7292-47df-9460-16f1396d0dcb" />

