# Análisis de Registros de Llegadas a Medellín

Este proyecto procesa y analiza datos de llegadas a Medellín desde un archivo CSV.  
Incluye limpieza de datos, cálculo de estadísticas, detección de duplicados, identificación de valores atípicos (outliers) y visualización de resultados.

## Contenido del Script

1. **Carga de datos**
   - Lectura del archivo CSV `registro_llegadas_a_medellin_dic2024.csv`.
   - Limpieza de espacios y conversión de formatos de fecha.
   - Conversión de columnas de texto a numéricas.

2. **Detección de duplicados**
   - Registros duplicados exactos.
   - Registros duplicados por coincidencia en la fecha de salida.

3. **Estadísticas descriptivas**
   - Cálculo de valores mínimo, máximo, media y moda de la duración.

4. **Detección y clasificación de outliers**
   - Método IQR (Rango Intercuartílico).
   - Clasificación como “Debajo del límite inferior” o “Encima del límite superior”.
   - Cálculo de frecuencia y porcentaje de cada tipo.

5. **Enriquecimiento de datos**
   - Día de la semana (número y nombre en español).
   - Hora del día.

6. **Visualizaciones**
   - **Duración media por día del mes**: gráfico de barras.
   - **Cantidad de outliers por día de la semana**: gráfico de barras.

## Requisitos

Instalar las librerías necesarias antes de ejecutar el script:

## Estructura
.
├── analisis_llegadas.py

├── registro_llegadas_a_medellin_dic2024.csv

└── README.md

