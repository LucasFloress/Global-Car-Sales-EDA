# Global-Car-Sales-EDA
Un análisis exploratorio de datos (EDA) exhaustivo sobre un dataset de 50.000 registros de ventas de vehículos, enfocado en descubrir patrones de depreciación, tendencias de mercado y anomalías en los datos.

## 📋 Descripción del Proyecto
Este proyecto simula un escenario real de Data Science donde se procesan datos crudos para extraer valor de negocio. El objetivo principal fue limpiar, transformar y visualizar un conjunto de datos masivo para responder preguntas clave sobre qué factores influyen más en el precio final de un vehículo.

**Datos Clave:**
* **Dataset:** 50.000 registros (Simulado/Mock Data).
* **Fuente:** Kaggle - Global Car Sales Analysis.
* **Enfoque:** Limpieza de datos, Ingeniería de Características y Visualización.

## 🛠️ Tecnologías Utilizadas
* **Python 3.x**
* **Pandas:** Manipulación y limpieza de datos (Manejo de duplicados y nulos).
* **Seaborn & Matplotlib:** Visualización de datos estadística.
* **Jupyter Notebook:** Entorno de desarrollo interactivo.

## 🔍 Metodología y Hallazgos

### 1. Limpieza y Validacion
Se realizó un proceso de validación de integridad, eliminando registros duplicados y verificando la consistencia de tipos de datos.

### 2. Ingeniería de Características (Feature Engineering)
Para mejorar el análisis, generé nuevas variables:
* **`Antigüedad`:** Calculada a partir del año de fabricación para medir la depreciación directa.
* **`Generacion`:** Segmentación de vehículos en décadas (1980s, 1990s, etc.) para análisis de tendencias temporales.

### 3. Insights Principales (Resultados)
* **Correlación Precio-Antigüedad:** Se confirmó una correlación negativa fuerte. Los vehículos pierden valor drásticamente después de los primeros 5 años.
* **Anomalía de Datos (Pensamiento Crítico):** Durante el análisis por tipo de combustible, detecté una inconsistencia histórica: el dataset registra una presencia significativa de vehículos **Híbridos** en las décadas de 1980 y 1990, lo cual es tecnológicamente anacrónico. Esto confirma la naturaleza sintética del dataset y resalta la importancia de validar la lógica de negocio más allá del código.

## 📊 Visualizaciones Destacadas
El notebook incluye:
* **Mapas de Calor:** Para ver la correlación entre variables numéricas.
* **Boxplots:** Análisis de distribución de precios por tipo de combustible (detectando outliers en gama alta).
* **Scatterplots:** Relación entre Kilometraje y Precio.

## 🚀 Cómo ejecutar este proyecto
1. Clona el repositorio:
   ```bash
   git clone [https://github.com/tu-usuario/nombre-del-repo.git](https://github.com/tu-usuario/nombre-del-repo.git)
