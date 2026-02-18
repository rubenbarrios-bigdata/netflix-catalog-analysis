## 🎬 Netflix Data Explorer: Análisis Estratégico de Contenido

## 📝 Descripción
Este proyecto realiza un Análisis Exploratorio de Datos (EDA) sobre el catálogo de Netflix (2008-2021). El objetivo es identificar patrones en la estrategia de la plataforma, analizando la distribución geográfica, las clasificaciones de audiencia y las tendencias en la duración de los contenidos.

## 🛠️ Tecnologías y Librerías
Para este análisis utilizamos el stack clásico de Ciencia de Datos en Python:

Pandas 🐼: Limpieza y manipulación de datos.

NumPy 🔢: Operaciones numéricas y manejo de valores nulos.

Matplotlib 📉: Creación de visualizaciones base.

Seaborn 🎨: Gráficos estadísticos avanzados (Boxplots y Heatmaps).

## ⚙️ Procesamiento de Datos (Data Wrangling)
Se aplicaron técnicas de limpieza para garantizar la calidad de los "insights":

Tratamiento de Nulos: Se identificaron valores faltantes en director y country, etiquetándolos como "Unknown" para evitar el sesgo de selección.

Transformación de Tipos: Se convirtió la columna duration de texto a tipo numérico (float), eliminando sufijos para permitir cálculos estadísticos.

## 📊 Hallazgos Principales
Análisis de Duración: Mediante el uso de Boxplots, descubrimos que los Documentales 📹 mantienen una duración estándar, mientras que los Dramas 🎭 presentan una alta variabilidad.

Globalización: El análisis muestra una expansión agresiva en mercados internacionales, aunque con una fuerte concentración de datos desconocidos en la producción original.

Fuente: Kaggle – Netflix Movies and TV Shows
https://www.kaggle.com/datasets/shivamb/netflix-shows

