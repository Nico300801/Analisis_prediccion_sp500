# Análisis y predicción del S&P 500 con LSTM

Este proyecto explora el uso de **redes neuronales LSTM (Long Short-Term Memory)** para modelar y predecir la evolución del índice **S&P 500** a partir de datos históricos agregados semanalmente.

El objetivo principal es **aplicar técnicas de análisis de series temporales y Deep Learning en un contexto financiero**, evaluando sus posibilidades y limitaciones en un problema real.

> ⚠️ Este proyecto tiene fines **educativos y demostrativos**. No pretende ser un sistema de inversión ni de trading real.

---

## 📌 Objetivos del proyecto

- Analizar la evolución histórica del índice S&P 500.
- Preparar los datos como una serie temporal adecuada para Deep Learning.
- Entrenar un modelo LSTM para predicción de precios.
- Evaluar el rendimiento del modelo y reflexionar sobre sus limitaciones.
- Presentar conclusiones realistas sobre la predicción de mercados financieros.

---

## 🧠 Tecnologías y librerías utilizadas

- Python 3
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- TensorFlow / Keras
- Jupyter Notebook

---

## 📊 Metodología

1. **Obtención y carga de datos**
   - Datos históricos del S&P 500.
   - Agregación a frecuencia semanal para reducir ruido.

2. **Análisis exploratorio**
   - Visualización de la serie temporal.
   - Identificación de tendencias generales.

3. **Preprocesado**
   - Normalización de los datos.
   - Creación de ventanas temporales (*time windows*).

4. **Modelado**
   - Implementación de una red LSTM.
   - Entrenamiento y validación del modelo.

5. **Evaluación**
   - Comparación entre valores reales y predichos.
   - Uso de métricas de error para evaluar el rendimiento.

6. **Conclusiones**
   - Análisis crítico de los resultados.
   - Discusión sobre la dificultad de predecir mercados financieros.

---

## 📈 Resultados

El modelo es capaz de capturar **tendencias generales** de la serie temporal, pero presenta limitaciones importantes a la hora de anticipar movimientos bruscos del mercado.

Estos resultados confirman una conclusión:  
> *Los mercados financieros son impredecibles a partir de precios pasados.*

---

## 🚧 Limitaciones y posibles mejoras

Algunas extensiones interesantes para el proyecto serían:

- Comparar el LSTM con modelos baseline (por ejemplo, predicción del valor anterior).
- Incluir variables macroeconómicas adicionales.
- Ajustar hiperparámetros y arquitectura del modelo.
- Probar otros enfoques de series temporales (ARIMA, Prophet, Transformers).

---

## ▶️ Cómo ejecutar el proyecto

1. Clona este repositorio:
   ```bash
   git clone https://github.com/tu-usuario/tu-repositorio.git

2. Instala las dependencias necesarias

3. Abre el notebook: jupyter notebook analisis_sp500.ipynb
