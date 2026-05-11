# Dashboard de Monitoreo de KPIs Área Comercial

## Descripción
Dashboard de Business Intelligence desarrollado en Power BI para monitorear el ingreso y desempeño de nuevos distribuidores en una empresa del sector cosmético. 
La solución proporciona visibilidad sobre el crecimiento de distribuidores, distribución geográfica, tendencias de incorporación y KPIs clave del proceso de onboarding, facilitando la toma de decisiones comerciales y estrategias de expansión.


## Objetivo del proyecto
Desarrollar una solución analítica que permita monitorear el proceso de incorporación de nuevos distribuidores, identificar tendencias de crecimiento comercial y brindar visibilidad operativa mediante KPIs interactivos y análisis geográfico.


## KPIs Principales

- Nuevos distribuidores registrados
- Crecimiento semanal, mensual y anual
- Distribución por región y zona comercial
- Tendencias de incorporación
- Métricas de desempeño comercial


## Funcionalidades Principales
- Seguimiento de nuevos registros de distribuidores
- Análisis geográfico por región/estado y zona comercial
- Tendencias semanales/mensuales/anuales de incorporación
- Monitoreo de KPIs y métricas de desempeño
- Filtros interactivos y capacidad de drill-down


## Arquitectura de Datos

```plaintext
Base de Datos SQL
        ↓
Consultas SQL
        ↓
Procesamiento y automatización con Python
        ↓
Google BigQuery
        ↓
Modelo Semántico en Power BI
        ↓
Dashboard y actualización programada
```

## Proceso ETL
1. Extracción de datos desde una base de datos SQL
2. Transformación y carga automatizada mediante scripts en Python
3. Almacenamiento de información en Google BigQuery
4. Conexión del modelo semántico de Power BI al entorno cloud
5. Actualización programada para monitoreo continuo de KPIs


## Herramientas Utilizadas
- Power BI
- Power Query
- DAX
- Modelado de Datos
- Python
- SQL
- Google BigQuery


  
## Dashboard Preview
  <img width="447" height="615" alt="Captura de pantalla 2026-05-08 191615" src="https://github.com/user-attachments/assets/7329400f-72cb-4cd1-9443-e46b3d3726fa" />
  <br>
  <br>
  <img width="457" height="442" alt="Captura de pantalla 2026-05-08 191817" src="https://github.com/user-attachments/assets/9c8c2cc2-715f-4e80-8f91-7d14698a862d" />
  <br>
  <br>
  <img width="453" height="469" alt="Captura de pantalla 2026-05-08 192236" src="https://github.com/user-attachments/assets/4b6185f4-e03c-4a2b-bade-f5317c9dfd44" />


## Insights Clave
•Identificación de regiones con mayor captación de nuevos distribuidores
•Monitoreo de tendencias de crecimiento comercial por periodo
•Detección de variaciones en desempeño entre zonas comerciales
•Mayor visibilidad del proceso de onboarding y desempeño comercial


## Valor de Negocio
Este dashboard permite a los equipos comerciales y operativos identificar oportunidades de crecimiento, monitorear el desempeño de adquisición de distribuidores y mejorar la visibilidad del proceso de incorporación de nuevos distribuidores.
