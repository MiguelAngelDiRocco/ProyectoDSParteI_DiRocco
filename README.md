🌍 Proyecto de Análisis de Datos Climáticos Globales
📌 Descripción
Este proyecto tiene como objetivo analizar patrones climáticos globales mediante un dataset que contiene más de 75.000 registros y 41 variables relacionadas con condiciones atmosféricas, calidad del aire y factores astronómicos.

Se exploran relaciones significativas entre temperatura, humedad, velocidad del viento e índices de contaminación (PM2.5) para comprender mejor fenómenos climáticos, variaciones ambientales y su impacto en la salud pública.

🎯 Objetivos Analíticos
Identificar los países con mayor nivel promedio de PM2.5 (polución).

Investigar la relación entre velocidad del viento y niveles de PM2.5.

Analizar la distribución global de temperaturas.

Determinar qué países presentan índices UV peligrosamente altos.

Evaluar si la presión atmosférica varía significativamente entre países.

Explorar la correlación entre humedad y niveles de PM2.5.

🌎 Contexto Global
Con el aumento del cambio climático y los eventos meteorológicos extremos, comprender estas variables es crucial para:
✅ La salud pública
✅ La planificación ambiental
✅ El diseño de modelos predictivos que anticipen condiciones críticas como alta polución o extremos climáticos.

🧪 Hipótesis
Concentración de contaminantes: Países con mayor PM2.5 estarán asociados a zonas con alta densidad poblacional o condiciones que favorecen la acumulación de contaminantes.

Latitud e índice UV: Los países cercanos al ecuador presentarán índices UV significativamente más altos.

Relación humedad - PM2.5: Mayores niveles de humedad influirán en la dispersión o acumulación de PM2.5.

Distribución térmica: La mayoría de los registros se concentrarán en rangos cálidos, reflejando patrones tropicales y templados.

📊 Metodología
EDA (Análisis Exploratorio de Datos): Exploración inicial, revisión de nulos y duplicados.

Filtrado de outliers: Eliminación de valores extremos en velocidad del viento y PM2.5 para asegurar consistencia.

Visualización de datos: Uso de gráficos con matplotlib y seaborn para extraer insights claros.

Análisis comparativo: Identificación de top 10 países según diferentes variables.

📈 Tecnologías utilizadas
Python

Pandas

Matplotlib

Seaborn

Google Colab

📂 Estructura del Proyecto
ProyectoDSParteI_DiRocco.ipynb → Notebook principal con análisis y visualizaciones.

README.md → Documento explicativo del proyecto.

🔗 Dataset
Fuente: Global Weather Repository - Kaggle
