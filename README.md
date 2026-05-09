# latam-trafico-productividad
Modelo de análisis de tráfico y productividad económica para 5 ciudades LATAM — Python, EDA y recomendaciones para LADB

# Análisis de Tráfico y Productividad Económica — LATAM
> **Python · SQL · EDA · ETL · Google Sheets**
> TripleTen Data Analytics Bootcamp — 2026 · Cliente: Latin American Development Bank (LADB)

## Descripción
Modelo de análisis que relaciona los índices de tráfico vehicular con la productividad económica (PIB per cápita) en 5 ciudades de América Latina. El objetivo fue identificar qué ciudades deberían ser priorizadas para inversión en infraestructura de transporte.

---

## Problema de negocio
El Latin American Development Bank (LADB) necesitaba priorizar su presupuesto de inversión en infraestructura urbana entre múltiples ciudades candidatas. La decisión requería evidencia basada en datos sobre la relación entre congestión de tráfico y pérdida de productividad económica.

**Pregunta clave:** ¿En qué ciudades el tráfico impacta más negativamente la productividad y justifica mayor inversión?

---

## Ciudades analizadas
| Ciudad | País | Índice de tráfico | PIB per cápita |
|--------|------|-------------------|----------------|
| Bogotá | Colombia | 37.61 | $11,442 |
| Ciudad de México | México | — | — |
| Lima | Perú | — | — |
| Santiago | Chile | — | — |
| Buenos Aires | Argentina | — | — |

---

## Proceso

### 1. Recolección y limpieza de datos (ETL)
- Extracción de datos de índices de tráfico y PIB per cápita por ciudad
- Limpieza con Python (pandas): manejo de nulos, normalización de formatos, eliminación de outliers

### 2. Análisis exploratorio (EDA)
- Distribución de índices de tráfico por ciudad
- Correlación entre nivel de congestión y PIB per cápita
- Visualización de patrones por ciudad y región

### 3. Modelo de análisis y scoring
- Creación de índice compuesto: impacto del tráfico en productividad
- Ranking de ciudades por necesidad de inversión
- Identificación de Bogotá como ciudad prioritaria

### 4. Recomendaciones estratégicas
- Informe para el LADB con hallazgos y propuestas de inversión
- Visualizaciones en Google Sheets para comunicación ejecutiva

---

## Resultados
- **Bogotá identificada como ciudad prioritaria** con índice de tráfico de 37.61 y PIB per cápita de $11,442
- Correlación negativa confirmada entre congestión de tráfico y productividad económica en las 5 ciudades
- Recomendaciones estratégicas entregadas al LADB para optimizar la asignación de recursos en infraestructura urbana

---

## Herramientas utilizadas

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![Google Sheets](https://img.shields.io/badge/Google%20Sheets-34A853?style=flat&logo=googlesheets&logoColor=white)

`Python (pandas, NumPy)` · `SQL` · `EDA` · `ETL` · `Visualización de datos` · `Google Sheets`

---

## Archivos del repositorio
| Archivo | Descripción |
|---------|-------------|
| `analisis_latam.ipynb` | Notebook Python con EDA completo |
| `queries.sql` | Consultas SQL de extracción y transformación |
| `dashboard.xlsx` | Visualizaciones y tablas de resultados |
| `reporte_ladb.pdf` | Informe de recomendaciones para el LADB |
| `images/` | Gráficas del análisis exploratorio |

---

*Desarrollado por [Jhon Fredy Fajardo Rodriguez](https://www.linkedin.com/in/jhon-fajardo-ingeniero-de-sistemas/) · Data Analyst Junior*
