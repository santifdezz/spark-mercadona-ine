# spark-mercadona-ine
Análisis y visualización de datos de productos de Mercadona y categorías del INE (2024-2025) utilizando PySpark y Power BI.
# Análisis de Datos: Mercadona e INE (2024-2025)

Este proyecto tiene como objetivo la recolección, limpieza, análisis y visualización de datos provenientes de dos fuentes principales:

- **Productos de Mercadona**: Datos sobre los productos disponibles en la cadena de supermercados Mercadona.
- **Categorías del INE**: Información sobre diferentes categorías económicas y demográficas en España.

Los datos serán procesados y analizados utilizando **PySpark**, y los resultados serán visualizados a través de **Power BI** para obtener insights relevantes sobre consumo y patrones demográficos en España durante el periodo 2024-2025.

## Tecnologías y Herramientas Utilizadas

- **PySpark**: Procesamiento de datos a gran escala.
- **Power BI**: Visualización interactiva de los datos.
- **Python**: Código para procesamiento y análisis.
- **Mercadona API** y **INE Open Data**: Fuentes de datos.

## Flujo del Proyecto

1. **Recolección de Datos**:
   - Obtención de datos de productos de Mercadona.
   - Obtención de datos sobre categorías del INE.
   
2. **Limpieza y Transformación de Datos**:
   - Uso de PySpark para limpiar, transformar y combinar los datos.
   
3. **Análisis y Modelado**:
   - Análisis descriptivo para entender patrones de consumo y categorías demográficas.
   
4. **Visualización**:
   - Creación de dashboards interactivos en Power BI para presentar los resultados.

## Estructura del Proyecto
├── ipc.ipynb # Analisis y limpieza de datos del IPC- INE
├── ipc_spark.ipynb # Jupyter Notebook para procesamiento de datos y graficos desde servidor SPARK 
├── mercadona_api.ipynb # Scripts en PySpark para el procesamiento de 
├── PowerBI.pdf# Archivo explicativo con como lo he utilizado y recorrido para su funcionamiento (2024)
└── README.md # Este archivo


## Instrucciones

### Requisitos

1. **Python 3.x**
2. **PySpark** (instalar con `pip install pyspark`)
3. **Power BI Desktop** para visualizar los dashboards.

### Instalación

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/santifdezz/spark-mercadona-ine.git
    ```
2. Instalar las dependencias de Python::
   ```bash
  cd mercadona-ine-data-analysis
  pip install -r requirements.txt
    ```
## Uso
  1. Procesamiento de Datos:
  Ejecuta los scripts en la carpeta pyspark_scripts/ para procesar y limpiar los datos de Mercadona y el INE.

  2. Visualización en Power BI:
  Abre los archivos .pbix en Power BI Desktop para explorar los dashboards y obtener insights de los datos procesados.
