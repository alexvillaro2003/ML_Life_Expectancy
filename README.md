# 📈 Predicción de la Esperanza de Vida 🌍

Este proyecto busca predecir la esperanza de vida en diferentes países del mundo utilizando técnicas de machine learning, a partir de factores de salud, económicos y sociales. El modelo está diseñado para apoyar en el análisis de políticas públicas, permitiendo entender qué factores contribuyen más a una vida más larga y saludable.

## 📌 Objetivo del Proyecto

El principal objetivo es construir un modelo que permita predecir la esperanza de vida de un país en función de una serie de variables que representan condiciones de salud, nivel económico y factores sociales. Esto ayudará a:

- Identificar los factores que tienen mayor impacto en la esperanza de vida.
- Comparar el nivel de desarrollo y condiciones de vida entre diferentes países.
- Apoyar la toma de decisiones y políticas de salud pública basadas en datos.

## 🔍 Descripción del Dataset

El dataset utilizado proviene de [Kaggle - Life Expectancy Data](https://www.kaggle.com/datasets/kumarajarshi/life-expectancy-who) y contiene información de 193 países entre los años 2000 y 2015. Entre las variables se encuentran factores económicos como el PIB per cápita, indicadores de salud como el acceso a vacunas, y factores sociales como la educación.

### Variables Principales

- **Adult Mortality**: Mortalidad en adultos (tasa de muertes entre los 15 y 60 años).
- **Alcohol**: Consumo de alcohol per cápita en adultos.
- **percentage expenditure**: Porcentaje de gasto en salud como parte del PIB.
- **BMI**: Índice de masa corporal promedio de la población.
- **Polio y Diphtheria**: Cobertura de inmunización en niños.
- **GDP**: Producto Interno Bruto per cápita.
- **Income composition of resources**: Índice de recursos económicos disponibles para los ciudadanos.
- **Schooling**: Años promedio de escolarización.
- **Life expectancy**: Variable objetivo (esperanza de vida).

## 🚀 Enfoque y Metodología

1. **Exploración de Datos**: Se analizan distribuciones y relaciones entre las variables y la esperanza de vida para entender la naturaleza de los datos.
2. **Preprocesamiento**: Limpieza de datos, manejo de valores faltantes y transformación de variables, para asegurar datos consistentes y listos para el modelado.
3. **Selección de Modelo**: Se exploran varios modelos de machine learning, como:
   - Regresión Lineal
   - Bosques Aleatorios
   - XGBoost
4. **Evaluación y Resultados**: Se evalúan los modelos en base a métricas como RMSE y R² para seleccionar el mejor modelo en términos de precisión y generalización.

## ✨ Resultados Esperados

- **Análisis de Factores Clave**: Comprender qué variables tienen mayor impacto en la esperanza de vida.
- **Modelo Predictivo**: Crear un modelo que prediga la esperanza de vida de un país con base en sus condiciones socioeconómicas y de salud.
- **Insights para Políticas Públicas**: Ofrecer información valiosa que podría ser utilizada por gobiernos y organizaciones para mejorar las condiciones de vida en países en desarrollo.

## 🤔 ¿Por Qué Este Proyecto es Importante?

Este análisis y predicción de la esperanza de vida puede ser fundamental para comprender y mejorar las condiciones de salud y bienestar a nivel global. Al identificar los factores que más influyen en la esperanza de vida, las organizaciones de salud y los gobiernos pueden diseñar intervenciones y políticas más efectivas, especialmente en países en vías de desarrollo.

## 🛠️ Herramientas Utilizadas

- **Lenguaje**: Python
- **Librerías**: `pandas`, `numpy`, `seaborn`, `matplotlib`, `scikit-learn`, `xgboost`

## 📄 Licencia

Este proyecto es de uso abierto bajo la licencia MIT.
