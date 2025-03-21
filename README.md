# 🏦 Detección de Fraude en Transacciones Financieras 🚀

## 📌 Introducción
Este proyecto busca identificar transacciones fraudulentas en un sistema bancario digital. Se aplican técnicas de **análisis exploratorio de datos (EDA)** y **machine learning** para predecir fraudes.

## 📊 Dataset
El dataset contiene **1,048,575 transacciones**, categorizadas en:
- **PAYMENT** – Pagos a terceros
- **TRANSFER** – Transferencias bancarias
- **CASH_OUT** – Retiros de efectivo
- **DEBIT** – Débito automático
- **CASH_IN** – Depósitos en cuenta

Las transacciones fraudulentas están etiquetadas con `isFraud = 1`.

## 🎯 Objetivo del Proyecto
- Identificar patrones de fraude en transacciones bancarias.
- Entrenar un modelo de **Regresión Logística** para detectar fraudes.
- Optimizar el modelo con **SMOTE** y ajuste de umbral para mejorar la detección.

## 🛠️ Herramientas Utilizadas
- **Python** (`pandas`, `numpy`, `matplotlib`, `seaborn`)
- **Machine Learning**: `scikit-learn`
- **Balanceo de Datos**: `imbalanced-learn` (SMOTE)
- **Visualización de Datos**: `matplotlib`, `seaborn`

## 📈 Resultados Clave
- **Los fraudes ocurren mayormente en `TRANSFER` y `CASH_OUT`.**
- **El modelo logró un `Recall = 0.72` y un `ROC AUC Score = 0.96`.**
- **Se redujeron los falsos positivos en un 56% tras ajuste de umbral.**

## 🚀 Cómo Usar el Proyecto
1. **Instalar dependencias**:
   ```bash
   pip install -r requirements.txt
