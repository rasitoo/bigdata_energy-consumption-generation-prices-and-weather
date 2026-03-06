# ⚡ Proyecto: Forecasting de Demanda Eléctrica en España

## 📁 Archivos Creados

### 1. 📓 **Forecasting_Energia_Espana.ipynb**
Notebook principal del proyecto con:
- ✅ Descripción completa del trabajo y responsabilidades del equipo (3 personas)
- ✅ Importación de librerías
- ✅ Carga y exploración del dataset
- ✅ Conversión a series temporales
- ✅ Análisis de valores nulos
- ✅ Imputación con interpolación lineal
- ✅ **Análisis meteorológico completo** (sección crítica) 🌡️
- 📝 Secciones restantes: ver archivo de estructura completa

### 2. 📋 **README.md** (este archivo)
Guía de uso y estructura del proyecto

---

## 🎯 Objetivo del Proyecto

**Predecir la demanda eléctrica en España** utilizando:
- Modelos estadísticos (SARIMA)
- Machine Learning (Random Forest, Gradient Boosting)
- **Variables meteorológicas como factores explicativos clave** 🌡️

**Dataset:** [Energy Consumption, Generation, Prices and Weather - Spain](https://www.kaggle.com/datasets/nicholasjhana/energy-consumption-generation-prices-and-weather)

---

## 🚀 Cómo Usar Este Proyecto

### Paso 1: Descargar el Dataset
1. Descarga `energy_dataset.csv` de Kaggle
2. Colócalo en la misma carpeta que el notebook

### Paso 2: Abrir el Notebook
Abre `Forecasting_Energia_Espana.ipynb`


---

## 🌡️ ⭐ ÉNFASIS EN VARIABLES METEOROLÓGICAS

**PUNTO CLAVE:** Las weather features son **fundamentales** para explicar la demanda eléctrica.

**Lo que debes demostrar:**
1. Correlación temperatura-demanda (✅ ya incluido en el notebook)
2. Weather features en feature engineering (temp_lag, temp_rolling)
3. Feature importance: temperatura en TOP 3
4. Conclusión: temperaturas extremas → mayor demanda

---

## 📚 Recursos

- **README.md**: Este archivo con instrucciones
- **Forecasting_Energia_Espana.ipynb**: Notebook con base del proyecto

---

**¡Mucha suerte! 🚀**