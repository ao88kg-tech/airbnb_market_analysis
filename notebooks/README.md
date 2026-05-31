# Análisis del Mercado de Airbnb en Nueva York

## Descripción del Proyecto

Este proyecto analiza el mercado de alojamientos Airbnb en la ciudad de Nueva York con el objetivo de identificar los factores que influyen en el precio y la popularidad de las propiedades.

A través de técnicas de limpieza de datos, análisis exploratorio y visualización, se busca obtener información útil para anfitriones y personas interesadas en comprender el comportamiento del mercado de alquileres de corta estancia.

---

## Pregunta de Negocio

**¿Qué factores influyen en el precio y la popularidad de los alojamientos Airbnb en Nueva York?**

---

## Dataset

Se utilizó el conjunto de datos **New York City Airbnb Open Data**, que contiene información de aproximadamente 49,000 alojamientos registrados en Airbnb.

El dataset incluye variables como:

* Ubicación del alojamiento
* Tipo de propiedad
* Precio por noche
* Número de reseñas
* Disponibilidad anual
* Número mínimo de noches requeridas

---

## Herramientas Utilizadas

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Metodología

1. Inspección inicial de los datos.
2. Identificación y tratamiento de valores faltantes.
3. Detección y eliminación de valores atípicos en la variable precio.
4. Análisis exploratorio de datos (EDA).
5. Creación de visualizaciones para identificar patrones.
6. Generación de insights y recomendaciones de negocio.

---

## Principales Hallazgos

### 1. Manhattan concentra los precios más altos

Manhattan presentó el precio promedio más elevado entre todos los boroughs analizados, consolidándose como el segmento premium del mercado.

### 2. Los alojamientos completos dominan la plataforma

Las propiedades tipo *Entire home/apartment* representan la mayor parte de la oferta disponible y registran los precios promedio más altos.

### 3. Los precios accesibles generan más interacción

Los alojamientos con precios bajos y medios tienden a acumular una mayor cantidad de reseñas, sugiriendo una mayor rotación de huéspedes.

### 4. Un precio elevado no garantiza mayor popularidad

Se observó que los alojamientos más costosos no necesariamente son los que reciben más reseñas o reservas.

---

## Recomendaciones de Negocio

* Implementar estrategias de precios competitivos para incrementar la ocupación.
* Aprovechar la ubicación como ventaja competitiva en mercados premium como Manhattan.
* Considerar habitaciones privadas como una opción rentable para nuevos anfitriones.
* Monitorear constantemente la relación entre precio y demanda para optimizar ingresos.

---

## Visualizaciones

El proyecto incluye análisis visual sobre:

* Distribución de precios.
* Precio promedio por borough.
* Distribución por tipo de alojamiento.
* Precio promedio por tipo de alojamiento.
* Popularidad por borough.
* Relación entre precio y número de reseñas.

---

## Estructura del Proyecto

```text
airbnb-market-analysis/
│
├── data/
│   └── AB_NYC_2019.csv
│
├── notebooks/
│   └── nyc_airbnb_market_analysis.ipynb
│
├── images/
│
└── README.md
```

---

## Autor

Ana Karen Ortega Gómez

Proyecto desarrollado como parte de mi portafolio profesional de Análisis de Datos.
