# Análisis y Segmentación de Clientes de Centros Comerciales

## Descripción

Este proyecto presenta un análisis exploratorio y de segmentación de clientes de centros comerciales utilizando técnicas de análisis de datos, visualización y aprendizaje automático.

El análisis busca identificar patrones en las características demográficas y de comportamiento de los clientes, con el propósito de obtener grupos de clientes con características similares.

## Objetivo

Analizar las características de los clientes de un centro comercial para identificar patrones y segmentos de comportamiento mediante técnicas de análisis de datos y clustering.

### Objetivos específicos

- Explorar y comprender el conjunto de datos.
- Analizar las características demográficas de los clientes.
- Examinar la relación entre ingresos anuales y comportamiento de gasto.
- Preparar los datos para el análisis.
- Identificar patrones y grupos de clientes.
- Utilizar técnicas de clustering para segmentar clientes.
- Representar visualmente los resultados.
- Interpretar los segmentos obtenidos.

## Dataset

El proyecto utiliza el conjunto de datos **Mall Customers**, obtenido de Kaggle.

El dataset contiene **200 registros y 5 variables**:

| Variable | Descripción |
|---|---|
| `CustomerID` | Identificador único del cliente |
| `Gender` | Género del cliente |
| `Age` | Edad del cliente |
| `Annual Income (k$)` | Ingreso anual en miles de dólares |
| `Spending Score (1-100)` | Puntuación de gasto asignada al cliente |

El archivo original utilizado en el proyecto se encuentra en:

`data/raw/Mall_Customers.csv`

## Metodología

El proyecto se desarrolla mediante las siguientes etapas:

### 1. Exploración de los datos

Se realiza una revisión inicial del conjunto de datos mediante:

- Visualización de los primeros registros.
- Información general de las variables.
- Estadísticas descriptivas.
- Revisión de tipos de datos.
- Análisis de las características de los clientes.

### 2. Preprocesamiento

Se realiza la preparación de los datos necesarios para continuar con el análisis y la segmentación de clientes.

### 3. Análisis exploratorio

Se estudian las principales características de los clientes y las relaciones entre variables como:

- Edad.
- Ingreso anual.
- Puntuación de gasto.
- Género.

### 4. Segmentación de clientes

Se aplican técnicas de clustering para identificar grupos de clientes con características similares.

La segmentación permite analizar diferentes perfiles de comportamiento dentro del conjunto de datos.

### 5. Visualización

Se utilizan gráficos para facilitar la identificación e interpretación de patrones y grupos de clientes.

## Resultados

El análisis permite identificar diferentes patrones entre las características de los clientes, especialmente en relación con sus ingresos anuales y puntuación de gasto.

La segmentación permite agrupar clientes con características similares y facilita la interpretación de diferentes perfiles de comportamiento.

Los resultados y visualizaciones detalladas pueden consultarse en el notebook del proyecto.

## Tecnologías utilizadas

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Habilidades demostradas

-Análisis exploratorio de datos (EDA)
-Limpieza y preparación de datos
-Análisis de variables
-Visualización de datos
-Segmentación de clientes
-Machine Learning no supervisado
-Interpretación de resultados
-Python para análisis de datos

## Autor

Sebastián Díaz

Estudiante de Ingeniería de Sistemas
