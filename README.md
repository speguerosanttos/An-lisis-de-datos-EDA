# 📊 Análisis de Campañas de Marketing Bancario - 2025

## 🧾 Descripción del Proyecto

Este proyecto tiene como objetivo analizar los datos de campañas de marketing telefónico realizadas por una institución bancaria portuguesa, combinando esta información con características demográficas de sus clientes. Se ha utilizado **Python** como herramienta principal de análisis, aplicando técnicas de limpieza, transformación, visualización y extracción de insights en un entorno de **Jupyter Notebook**.

## 📁 Contenido del Dataset

Se han utilizado dos fuentes de datos principales:

- `bank-additional.csv`: contiene información de campañas telefónicas realizadas a clientes, incluyendo variables como edad, educación, historial de contacto, duración de llamadas y si aceptaron o no el producto ofrecido.
- `customer-details.xlsx`: contiene información demográfica y de comportamiento de clientes (ingresos, número de hijos, visitas web mensuales, fecha de alta como cliente). Incluye 3 hojas según el año de incorporación (2012, 2013 y 2014).

## 🎯 Objetivos del Análisis

1. Detectar patrones en el perfil de clientes que aceptan el producto ofrecido.
2. Relacionar variables demográficas (edad, ingreso, estado civil) con la aceptación.
3. Evaluar el impacto del número de contactos y campañas previas.
4. Comparar variables como préstamos, nivel educativo y visitas web con la conversión.
5. Visualizar relaciones clave a través de gráficos descriptivos.
6. Obtener recomendaciones para mejorar la efectividad de futuras campañas.

## 📈 Elementos Clave del Análisis en Jupyter Notebook

El análisis incluye:

- **Gráficos de dispersión y hexbin** para explorar relaciones entre variables numéricas.
- **Gráficos de barras agrupadas** para estudiar cómo variables categóricas (educación, préstamos, estado civil) influyen en la respuesta.
- **Boxplots** para analizar la distribución de edad en función del resultado.
- **Mapas de calor** para evaluar correlaciones entre variables cuantitativas.
- **Cálculo de tasas de conversión** por grupo y análisis porcentuales.

Además, se ha realizado una limpieza exhaustiva de los datos, transformación de tipos y combinación de datasets con `merge()` usando claves únicas.

## 🧠 Conclusiones Iniciales

- Los clientes sin préstamos personales tienden a aceptar más el producto ofrecido.
- El nivel educativo y el estado civil tienen una relación evidente con la decisión de suscripción.
- No se observa una fuerte correlación lineal entre edad e ingreso, pero hay patrones visibles por segmentos.
- La cantidad de contactos puede afectar negativamente si es excesiva, especialmente en campañas repetidas.

## 🧠 Conclusiones Finales

Este análisis proporciona información valiosa para segmentar campañas y optimizar el contacto con los clientes. A continuación, se detallan las principales conclusiones extraídas:

#### **1. Perfil de Cliente Ideal para la Campaña**

- **Educación universitaria y sin préstamos personales**: mayor tasa de aceptación del producto.
- **Estado civil soltero o divorciado**: más receptivos en comparación con clientes casados.
- **Ingreso medio-alto y edad entre 30 y 45 años**: más propensos a responder positivamente.

#### **2. Canales y Contactos**

- **Número de contactos moderado**: mantener la frecuencia de llamadas baja parece más efectivo.
- **Resultados negativos en campañas anteriores** afectan el éxito de las actuales.

#### **3. Oportunidades de Mejora**

- Segmentar campañas futuras por perfil demográfico y educativo.
- Ajustar la estrategia de contacto para evitar desgaste del cliente.
- Evaluar patrones estacionales y duración óptima de llamadas.

## 🛠 Herramientas Utilizadas

- **Python**
- **Pandas** y **NumPy** para la manipulación de datos.
- **Matplotlib** y **Seaborn** para visualización.
- **Jupyter Notebook** como entorno de análisis interactivo.

## 📂 Estructura del Proyecto

📦 marketing_bank_analysis_2025
├── Archivo README.md
├── /data
│ ├── bank-additional.csv
│ └── customer-details.xlsx
├── /notebooks
│ └── eda_bank_marketing.ipynb

## 📌 Créditos

Proyecto desarrollado por **Sara Peguero Santos**.

