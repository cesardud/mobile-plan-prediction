# 📱 Mobile Plan Prediction

Este proyecto desarrolla un modelo de clasificación para predecir cuál plan móvil es más adecuado para un usuario de Megaline: **Smart** o **Ultra**. Basado en el comportamiento mensual de clientes actuales, el modelo ayuda a recomendar el plan óptimo para nuevos usuarios.

---

## 🎯 Objetivo

- Clasificar usuarios en base a sus patrones de uso (llamadas, mensajes, internet) para recomendarles un plan.
- Comparar varios modelos de clasificación y elegir el mejor con base en su exactitud (accuracy).
- Superar un umbral mínimo de precisión del **75%**.

---

## 🧠 Modelos utilizados

Se probaron tres modelos:
-Árbol de clasificación
-Bosque aleatorio de clasificación
-Modelo logístico

---

## 🛠️ Herramientas y tecnologías

- `pandas`
- `numpy`
- `scikit-learn`
- `Jupyter Notebook`

---

## 📂 Dataset

Archivo: `users_behavior.csv`  
Cada fila representa a un usuario, con las siguientes columnas:

- `calls`: número de llamadas mensuales
- `minutes`: duración total de llamadas
- `messages`: número de mensajes de texto
- `mb_used`: tráfico de internet usado en MB
- `is_ultra`: etiqueta objetivo (1 si usa el plan Ultra, 0 si usa Smart)

---

## 📊 División de datos

- 60% entrenamiento
- 20% validación
- 20% prueba final

---

## 🚀 Cómo ejecutarlo

1. Clona este repositorio:
   ```bash
   git clone https://github.com/tu-usuario/mobile-plan-prediction.git
   cd mobile-plan-prediction
   pip install -r requirements.txt
   jupyter notebook code.ipynb

