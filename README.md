# 📊 TelecomX Análisis de pérdida de clientes
## 🎯 Descripción del Proyecto
Este proyecto ofrece un análisis detallado del abandono de clientes (churn) en la empresa de telecomunicaciones TelecomX. Su objetivo principal es identificar patrones y factores de riesgo asociados a la pérdida de clientes, y proponer estrategias efectivas para reducir esta tasa mediante técnicas de análisis de datos y visualización.
## 🔍 Objetivos Principales
- Análisis Exploratorio de Datos (EDA) comprehensive de la base de clientes
- Identificación de factores que influyen en el churn de clientes
- Visualizaciones estratégicas para comunicar insights clave
- Recomendaciones accionables para reducir el abandono de clientes
- Cuantificación del impacto económico del churn
## 📊 Dataset
- Tamaño: 7,267 registros de clientes
- Formato: JSON con estructura anidada
- Características: 20+ variables incluyendo datos demográficos, servicios contratados y estado de churn

## Variables Principales

- Demográficas: CustomerID, Gender, SeniorCitizen, Partner, Dependents
- Servicios: PhoneService, MultipleLines, InternetService, OnlineSecurity, etc.
- Contractuales: Contract, PaymentMethod, PaperlessBilling
- Financieras: MonthlyCharges, TotalCharges, tenure
- Target: Churn (Yes/No)

## 🛠️ Configuración del Entorno
### Requisitos 
### - Python 3.7+
### - Jupyter Notebook o JupyterLab

Instalación Rápida de Dependencias

### Instalar todas las dependencias desde el archivo requirements.txt
### pip install -r requirements.txt

# 🔄 Flujo del Proyecto

## 📊 Parte 1: Análisis Exploratorio 
## (telecom_churn_analysis_fbeltran.ipynb)

- Carga y limpieza de datos
- Análisis exploratorio de datos (EDA)
- Visualizaciones y insights
- Identificación de patrones de churn

## 🤖 Parte 2: Machine Learning 
## (telecom_churn_ml_prediction.ipynb)

- Preparación de datos para ML
- Entrenamiento de 7 modelos predictivos
- Evaluación con métricas completas
- Análisis de importancia de variables
- Recomendaciones estratégicas basadas en IA
  
## 📈 Resultados Principales
### 🔢 Métricas Clave

- Tasa de Churn Global: 26.5%
- Impacto Económico Anual: ~$2.8M en pérdidas
- Clientes en Riesgo: 1,927 clientes activos
- Potencial de Ahorro: ~$700K anuales con 25% de reducción

## 🚨 Factores de Alto Riesgo

| Factor|	Tasa de Churn|	Impacto|
|-------|--------------|---------|
|Contratos mes a mes|	42.7%|	Alto|
|Pago con cheque electrónico	|45.3%	|Alto|
|Clientes nuevos (≤12 meses)	|47.4%	|Crítico|
|Servicio Fiber Optic	|30.9%	|Medio|
|Sin servicios adicionales	|35.0%	|Medio|

## 💰 Perfil Financiero
- Clientes que abandonan: $74.44 promedio mensual, 17.6 meses tenure
- Clientes que permanecen: $61.27 promedio mensual, 37.6 meses tenure
## 🎯 Recomendaciones Estratégicas
### 🟥 Acciones Inmediatas (0-3 meses)
- Migración de Pagos: Incentivar el cambio desde cheque electrónico
- Campañas de Retención: Focalizar en contratos mes a mes
- Descuentos Dirigidos: Para clientes con alta probabilidad de deserción
### 🟨 Acciones a Medio Plazo (3-12 meses)
- Sistema de Alerta Temprana: Implementar scoring de riesgo de deserción
- Programa de Onboarding: Mejorar experiencia primeros 12 meses
- Optimización de Precios: Rebalancear tarifas vs servicios

### 🟩 Acciones a Largo Plazo (12+ meses)

- Modelo Predictivo: Machine Learning para predicción de churn
- Programa de Lealtad: Incentivos por permanencia a largo plazo
- Segmentación Avanzada: Estrategias personalizadas por segmento

## 📊 Visualizaciones Incluidas

- Distribución de Churn por categorías demográficas
- Análisis de Supervivencia por tenure
- Heatmaps de Correlación entre variables
- Gráficos de Barras para factores de riesgo
- Distribuciones de variables financieras
- Dashboard Ejecutivo con métricas clave

## 🔧 Características Técnicas
### Procesamiento de Datos
- ETL Robusto: Manejo de datos faltantes y inconsistencias
- Limpieza Inteligente: Corrección automática de valores erróneos
- Validación de Calidad: Verificación de integridad de datos
  
### Funciones Principales
- safe_float_conversion(): Conversión segura de tipos de datos
- calculate_churn_metrics(): Cálculo de métricas de negocio
- generate_risk_segments(): Segmentación por nivel de riesgo

### Modelos de Machine Learning
- Logistic Regression: Modelo lineal con interpretabilidad
- Random Forest: Ensemble de árboles con alta precisión
- Gradient Boosting: Boosting secuencial optimizado
- K-Nearest Neighbors: Clasificación por proximidad
- Support Vector Machine: Clasificador de margen máximo
- Decision Tree: Árbol interpretable con reglas claras
- Naive Bayes: Clasificador probabilístico eficiente

## 📚 Metodología

- Extracción: Carga y parseo del JSON original
- Transformación: Limpieza y normalización de datos
- Análisis Exploratorio: Estadísticas descriptivas y univariadas
- Análisis Bivariado: Relaciones entre variables y churn
- Visualización: Creación de gráficos estratégicos
- Insights: Identificación de patrones y oportunidades
- Recomendaciones: Desarrollo de estrategias accionables

## 📄 Licencia
- Este proyecto es parte de un desafío académico/profesional para análisis de datos en telecomunicaciones.

## 🤝 Contribuciones
Para contribuir al proyecto:

- Fork el repositorio
- Crear una rama para la nueva funcionalidad
- Realizar cambios y commit
- Push a la rama
- Crear un Pull Request
