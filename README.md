# Dashboard de Monitoreo de KPIs Área Comercial

## Descripción

Dashboard en Power BI para el monitoreo de KPIs comerciales, actividad de distribuidores y desempeño de ventas.


## Objetivo del proyecto

Desarrollar un dashboard de Business Intelligence en Power BI para monitorear y analizar indicadores clave del área comercial, proporcionando visibilidad sobre el desempeño de distribuidores, comportamiento de pedidos y métricas de ventas. La solución permite facilitar el seguimiento operativo y apoyar la toma de decisiones mediante KPIs interactivos y análisis de tendencias comerciales.


## KPIs Principales

- Distribuidores con pedido por semana
- Ticket promedio
- Ventas promedio por asesor comercial
- Distribuidores nuevos por semana y por zona comercial
- Distribuidores inactivos
- Crecimiento con medias móviles


## Funcionalidades Principales

- Monitoreo de KPIs comerciales en tiempo real
- Seguimiento de nuevos distribuidores y distribuidores activos
- Análisis de pedidos por semana, mes y periodo comercial
- Visualización de ticket promedio y métricas de ventas
- Análisis de desempeño por región y zona comercial
- Tendencias de crecimiento y comportamiento comercial
- Filtros interactivos y capacidad de drill-down para análisis detallado
- Visualización ejecutiva orientada a la toma de decisiones


## Arquitectura de Datos

```plaintext
SQL Database
      ↓
SQL Queries
      ↓
ETL automatizado con Python
      ↓
Cloud Storage / BigQuery
      ↓
Modelo Semántico Power BI
      ↓
Dashboard KPIs Comerciales
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

  <img width="1422" height="802" alt="Captura de pantalla 2026-05-11 133623" src="https://github.com/user-attachments/assets/bea91d51-2511-4de7-a94c-d82b4c1726dd" />
  <br>
  <br>
<img width="761" height="787" alt="Captura de pantalla 2026-05-11 133905" src="https://github.com/user-attachments/assets/bd18d3e5-9c88-411b-a095-d9a722bf2253" />
  <br>
  <br>
<img width="702" height="737" alt="Captura de pantalla 2026-05-11 133945" src="https://github.com/user-attachments/assets/287ad217-d521-45bc-ba02-28cbbbf1c4f3" />
  <br>
  <br>
<img width="1421" height="797" alt="Captura de pantalla 2026-05-11 134024" src="https://github.com/user-attachments/assets/6e628794-ac76-4578-8e25-ed375d73c1a2" />




## Insights Clave

- Identificación de periodos con mayor volumen de pedidos y crecimiento comercial
- Detección de zonas comerciales con mayor concentración de distribuidores activos
- Variaciones relevantes en el ticket promedio entre regiones y periodos de tiempo
- Monitoreo del comportamiento de incorporación de nuevos distribuidores
- Mayor visibilidad del desempeño comercial mediante KPIs centralizados e interactivos
- Identificación de tendencias y patrones comerciales para apoyar la toma de decisiones


## Valor de Negocio

Este dashboard permite centralizar y monitorear los principales indicadores del área comercial, proporcionando visibilidad sobre el desempeño de distribuidores, comportamiento de ventas y tendencias de pedidos. La solución facilita la toma de decisiones estratégicas, el seguimiento operativo y la identificación de oportunidades de crecimiento mediante análisis interactivos y KPIs orientados al negocio.
