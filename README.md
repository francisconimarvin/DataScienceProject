# Data Science Project — Análisis de Relojes Amazon

Proyecto grupal para la asignatura **Programación para la Ciencia de Datos (SCY1101)** — Evaluación Parcial 3.

## 📌 Problema

Analizar el dataset de relojes de pulsera para hombre vendidos en Amazon, con el objetivo de identificar patrones en precios, ratings y popularidad entre marcas, y construir visualizaciones interactivas que faciliten la exploración de estos resultados.

## 📊 Dataset

- **Archivo:** `Amazon_Men_Wrist_Watches.csv`
- **Contenido:** información de relojes de pulsera masculinos publicados en Amazon (marca, precio, rating, número de reseñas, entre otros).
- **Origen:** dataset público de Amazon (Men's Wrist Watches).

## 🧹 Preparación de datos

- Limpieza y conversión de la columna `price` (eliminación de comas, texto y valores nulos).
- Conversión de `number_of_reviews` (normalización de valores abreviados en miles, ej. "1.2K" → 1200).
- Tratamiento de valores nulos en `rating`.
- Creación de la variable categórica `rating_categoria` (Excelente / Bueno / Bajo).

## 📈 Visualizaciones interactivas (Plotly)

1. Distribución de ratings promedio por marca (histograma interactivo).
2. Distribución de precios promedio por marca (histograma interactivo).
3. Segmentación de relojes por clusters (K-Means + PCA) en un scatter interactivo.

Cada visualización incluye su interpretación en el notebook.

## 🖥️ Mini Dashboard

Resumen de resultados clave: comparación de modelos y perfil de clusters (precio, rating, popularidad) por segmento de mercado.

## 🛠️ Tecnologías

- Python (Pandas, NumPy)
- Visualización: Matplotlib, Seaborn, Plotly
- Machine Learning: Scikit-learn (Random Forest, Regresión Lineal/Ridge, K-Means, PCA)
- Control de versiones: Git / GitHub

## 🚀 Cómo ejecutar

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/francisconimarvin/DataScienceProject.git
   ```
2. Instalar dependencias:
   ```bash
   pip install pandas numpy matplotlib seaborn plotly scikit-learn
   ```
3. Abrir `Evaluación_1.ipynb` en Jupyter Notebook o Google Colab y ejecutar las celdas en orden.

## 👥 Integrantes

- Ricardo (Nombre completo)
- Marvin (Nombre completo)
- *(agregar resto del equipo)*

## 📅 Entrega

Evaluación Parcial 3 — Programación para la Ciencia de Datos — Julio 2026
