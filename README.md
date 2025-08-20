# TelecomX_LATAM-2
Telecom X: análisis de evasión de clientes - Parte 2
Análisis de Churn (Deserción de Clientes) 

    Proyecto de Ciencia de Datos: Predicción de Churn en una empresa de telecomunicaciones 
     

Este repositorio contiene un análisis completo de deserción de clientes (churn) utilizando un dataset de telecomunicaciones. El objetivo es identificar los factores que influyen en que un cliente abandone el servicio y desarrollar un modelo de Machine Learning para predecirlo con alta precisión. 
 
🎯 Objetivo 

Predecir si un cliente dejará el servicio (churn) basado en características como: 

    Contrato, servicios contratados, método de pago, antigüedad, cargos mensuales, etc.
 
🧰 Tecnologías utilizadas 

    Python (pandas, scikit-learn, matplotlib, seaborn)
    Machine Learning: Random Forest, Regresión Logística
    Preprocesamiento: Limpieza de datos, One-Hot Encoding, conversión a numérico
    Validación: AUC-ROC, matriz de confusión, validación cruzada
 
📊 Resultados clave 

    AUC-ROC: 0.8442 → Alto poder predictivo
    Modelo optimizado con GridSearchCV
    Identificación de variables clave: Contract_Month-to-month, tenure, Charges.Monthly, InternetService_Fiber optic
 
📁 Estructura del repositorio 
