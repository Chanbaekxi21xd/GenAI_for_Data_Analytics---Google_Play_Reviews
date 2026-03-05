# 🤖 Análisis de Reseñas de Aplicaciones con GenAI y Dashboard Interactivo

✨[Dashboard generado con AI](https://ai.studio/apps/5985937e-1e3b-4e06-a4f5-c61944138b63) 📊

## 📌 Descripción
Este proyecto analiza reseñas de aplicaciones de **Google Play** con el objetivo de comprender la satisfacción de los usuarios, identificar problemas recurrentes y evaluar el impacto de las respuestas del desarrollador.  

A partir de un dataset en formato **.xlsx**, se realizó un proceso de **limpieza y preparación de datos**, incluyendo la creación de una nueva columna de **sentimiento de las reseñas** utilizando herramientas de **Inteligencia Artificial Generativa (GenAI)**.  

Posteriormente, los datos procesados fueron utilizados para generar un **dashboard interactivo**, permitiendo explorar patrones en las calificaciones, identificar temas frecuentes en reseñas negativas y analizar cómo factores como las respuestas del desarrollador influyen en la percepción de los usuarios.

---

## 🎯 Objetivo
Analizar las reseñas de aplicaciones para identificar patrones de satisfacción, problemas frecuentes y tendencias en las calificaciones, utilizando técnicas de análisis de datos e inteligencia artificial para apoyar la toma de decisiones en el desarrollo y mejora de aplicaciones.

---

## 🛠 Tecnologías y herramientas utilizadas
- **Herramientas de GenAI** para análisis y generación de insights  
- **Power BI / herramientas de visualización** para el dashboard interactivo  
- **Excel (.xlsx)** como fuente de datos  
- **Procesos de limpieza y transformación de datos**

---

## ⚙ Metodología

### 1. Limpieza y preparación de datos
- Revisión de calidad de datos: valores nulos, outliers y consistencia de tipos.
- Corrección de inconsistencias en el dataset.
- Creación de una nueva columna de **sentimiento de las reseñas** basada en el contenido de `review_description`.

### 2. Análisis Exploratorio de Datos (EDA)
- Análisis descriptivo de variables numéricas (promedio, mediana y dispersión).
- Segmentación de datos por variables relevantes.
- Análisis de relaciones entre variables (correlaciones o análisis bivariado).

### 3. Análisis de preguntas clave
Se analizaron aspectos como:
- Distribución de las calificaciones (**ratings**) y proporción de reseñas positivas vs negativas.
- Problemas o temas más frecuentes en reseñas negativas.
- Diferencias en rating o `thumbs_up` cuando existe **respuesta del desarrollador**.
- Evolución del rating o sentimiento a lo largo del tiempo y entre versiones de la aplicación.

### 4. Storytelling basado en datos
Se construyó una narrativa orientada a la toma de decisiones que incluye:
- Contexto del análisis
- Hallazgos principales
- Evidencia basada en datos
- Recomendaciones e implicaciones para mejorar la experiencia del usuario.

### 5. Dashboard interactivo
Se desarrolló un dashboard que permite explorar los resultados dinámicamente mediante filtros y visualizaciones, incluyendo:
- Distribución de ratings
- Análisis de sentimiento de reseñas
- Comparación entre reseñas con y sin respuesta del desarrollador
- Tabla o ranking interactivo con métricas clave
