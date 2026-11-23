# Retail Analytics 2025 – Análisis Comercial

## Descripción del proyecto

Proyecto de **análisis de datos comerciales** desarrollado con **Python, SQL y Streamlit**, utilizando una base de datos **SQLite** con información ficticia de ventas, productos, puntos de venta, compras, proveedores y stock correspondiente al año **2025**.

El objetivo es transformar datos comerciales en **información útil para la toma de decisiones**, permitiendo analizar el desempeño del negocio, evaluar la rentabilidad, controlar el inventario e identificar oportunidades de mejora.

## Vista previa del dashboard

Aplicación web interactiva desarrollada con **Streamlit**.

![Vista previa del dashboard](resumencomercial.gif)

## Objetivos

- Analizar la **facturación** y el **volumen de ventas**.
- Identificar los **productos y categorías** con mayor participación.
- Comparar el rendimiento de los distintos **puntos de venta**.
- Evaluar **márgenes y rentabilidad**.
- Analizar **compras y desempeño de proveedores**.
- Detectar situaciones de **stock crítico**.
- Presentar indicadores y resultados mediante **dashboards interactivos**.

## Proceso de trabajo y herramientas utilizadas

El proyecto se desarrolló mediante distintas etapas, utilizando cada tecnología según su función dentro del proceso de análisis.

### 1. Preparación y limpieza de datos con Python

Se utilizó **Python** para realizar el proceso de **preparación, limpieza y transformación de los datos**.

Entre las tareas realizadas se incluyen:

- **Exploración inicial** de los conjuntos de datos.
- Revisión de registros y estructura de las tablas.
- **Detección y tratamiento de datos faltantes**.
- **Identificación y eliminación de registros duplicados**.
- Corrección de inconsistencias.
- **Validación de tipos de datos y formatos**.
- Transformación y preparación de la información para el análisis.

Se utilizaron principalmente **Python y Pandas** para garantizar la calidad y consistencia de los datos antes de incorporarlos al análisis.

### 2. Consultas y análisis con SQL

Se utilizó **SQL** para consultar y analizar la información almacenada en la base de datos **SQLite**.

Se desarrollaron consultas para:

- Calcular **indicadores comerciales**.
- Analizar ventas por período, producto, categoría y punto de venta.
- Obtener información sobre **compras y proveedores**.
- Calcular **márgenes de rentabilidad**.
- Analizar niveles de **inventario**.
- Generar resultados agrupados y rankings para los dashboards.

Las consultas SQL permiten **extraer, relacionar y organizar la información** necesaria para cada indicador y visualización.

### 3. Base de datos SQLite e integración con Streamlit

La información se organizó en una base de datos **SQLite**, que funciona como **fuente de datos del proyecto**.

Mediante **Python y SQLite** se estableció la conexión entre la base de datos y la aplicación desarrollada con **Streamlit**.

De esta manera, los dashboards pueden ejecutar **consultas sobre la base de datos** y mostrar los resultados directamente en la aplicación, sin necesidad de cargar manualmente los datos cada vez que se consulta un indicador.

### 4. Desarrollo de dashboards con Streamlit

Se desarrolló una **aplicación web interactiva con Streamlit** para presentar los principales resultados del análisis.

La aplicación está organizada en **tres módulos principales**:

**Resumen comercial**

- **Facturación total**.
- **Unidades vendidas**.
- **Cantidad de tickets**.
- **Ticket promedio**.
- Análisis de ventas por período, producto, categoría y punto de venta.

**Rentabilidad y stock**

- **Margen bruto**.
- **Porcentaje de margen**.
- **Productos con stock crítico**.
- **Unidades faltantes**.
- Análisis de rentabilidad e inventario.

**Compras y proveedores**

- **Total comprado**.
- **Unidades compradas**.
- **Cantidad de compras**.
- **Costo promedio unitario**.
- Análisis de proveedores y abastecimiento.

## Capturas de pantalla

### Resumen comercial

![Resumen comercial](resumencomercial.gif)

### Rentabilidad y stock

![Rentabilidad y stock](rentabilidad.gif)

### Compras y proveedores

![Compras y proveedores](compras.gif)

## Tecnologías utilizadas

- **Python:** limpieza, transformación, validación y procesamiento de datos.
- **Pandas:** manipulación y análisis de datos.
- **SQL:** consultas y extracción de información.
- **SQLite:** almacenamiento de la información en una base de datos relacional.
- **Streamlit:** desarrollo de la aplicación web y dashboards interactivos.
- **ECharts:** creación de visualizaciones y gráficos.
- **HTML y CSS:** personalización del diseño de la aplicación.
- **Jupyter Notebook:** exploración y desarrollo del análisis.

## Estructura del proyecto

```text
DASHBOARD_RETAIL_ANALYTICS/
│
├── app.py
├── consultas.py
├── conexion.py
│
├── dashboards/
│   ├── resumen_comercial.py
│   ├── rentabilidad_stock.py
│   └── compras_proveedores.py
│
├── graficos/
│
├── assets/
│   ├── style.css
│   ├── logo_retail.png
│   └── capturas/
│       ├── dashboard.gif
│       ├── resumen_comercial.png
│       ├── rentabilidad_stock.png
│       └── compras_proveedores.png
│
└── README.md
```

La **base de datos SQLite** se encuentra en la carpeta SQL del proyecto y es utilizada por la aplicación mediante la conexión configurada en **Python**.

## Resultado

El proyecto integra distintas etapas del **análisis de datos**: preparación y limpieza con **Python**, consultas con **SQL**, almacenamiento en **SQLite** y visualización mediante una **aplicación web desarrollada con Streamlit**.

El resultado es una herramienta de **análisis comercial** que permite explorar indicadores, evaluar el desempeño del negocio y obtener información relevante para la **toma de decisiones**.

---

**Proyecto desarrollado con fines de práctica y portfolio profesional.**

**Gladys Ramos**
