# E-Commerce Customer Analysis

## 📊 Análisis de ventas y comportamiento de clientes

Proyecto de análisis de datos enfocado en comprender el desempeño comercial de un negocio de E-Commerce, identificar patrones de compra, evaluar el comportamiento de los clientes y transformar los datos en insights accionables para la toma de decisiones.

El análisis integra limpieza y preparación de datos, análisis exploratorio, KPIs de negocio, segmentación RFM y preparación de información para visualización ejecutiva en Tableau.

---

## 🎯 Objetivo de negocio

El objetivo del proyecto es analizar las transacciones de un negocio de comercio electrónico para comprender:

- Cómo evoluciona el revenue a través del tiempo.
- Qué países y productos generan mayor valor.
- Qué clientes tienen mayor impacto económico.
- Cuánto depende el negocio de clientes recurrentes.
- Cómo se distribuye y concentra el revenue.
- Qué segmentos de clientes requieren estrategias diferentes de retención y crecimiento.

El propósito final es convertir datos transaccionales en información útil para apoyar decisiones comerciales.

---

## ❓ Preguntas de análisis

Durante el proyecto se buscaron respuestas a preguntas como:

- ¿Cuál es el comportamiento general de las ventas?
- ¿Qué mercados generan mayor revenue?
- ¿Cuáles son los productos con mejor desempeño?
- ¿Qué clientes aportan mayor valor al negocio?
- ¿Qué tan importante es la recurrencia de compra?
- ¿Existe concentración significativa del revenue en determinados clientes?
- ¿Qué segmentos pueden identificarse mediante RFM?
- ¿Qué clientes presentan oportunidades de retención o reactivación?

---

## 🛠️ Herramientas utilizadas

- Python
- Pandas
- NumPy
- Jupyter Notebook
- Tableau
- GitHub

---

## 🔎 Metodología

El proyecto se desarrolló mediante un flujo de análisis dividido en tres etapas principales:

### 1. Limpieza y preparación de datos

Se revisó la calidad del dataset y se prepararon las variables necesarias para trabajar con información consistente y adecuada para el análisis.

### 2. Análisis exploratorio

Se estudiaron diferentes dimensiones del negocio:

- Evolución de ventas.
- Rendimiento por país.
- Rendimiento por producto.
- Comportamiento de clientes.
- Recurrencia de compra.
- Concentración de ingresos.
- Pedidos de alto volumen.

### 3. Segmentación y preparación para dashboard

Se aplicó segmentación RFM utilizando:

- **Recency:** tiempo desde la última compra.
- **Frequency:** frecuencia de compra.
- **Monetary:** valor económico generado por el cliente.

Posteriormente se prepararon datasets específicos para alimentar el dashboard ejecutivo.

---

## 📈 KPIs y dimensiones analizadas

El análisis contempla indicadores relacionados con:

- Revenue.
- Número de pedidos.
- Clientes.
- Frecuencia de compra.
- Valor económico por cliente.
- Rendimiento mensual.
- Rendimiento por país.
- Rendimiento por producto.
- Segmentación RFM.
- Concentración de ingresos.

---

## 👥 Segmentación de clientes

El análisis RFM permite diferenciar grupos de clientes según su comportamiento y valor para el negocio.

Entre los segmentos identificados se encuentran:

- **Champions**
- **Loyal Customers**
- **At Risk**

Esta clasificación facilita el diseño de estrategias diferenciadas de fidelización, retención y reactivación.

---

## 💡 Principales hallazgos

El análisis permitió detectar aspectos relevantes del comportamiento comercial:

1. Los clientes recurrentes representan un componente importante del valor económico generado por el negocio.
2. El revenue presenta concentración en determinados clientes, por lo que resulta importante monitorear la dependencia de clientes de alto valor.
3. La segmentación RFM permite identificar clientes especialmente valiosos y clientes con riesgo de abandono.
4. El rendimiento varía entre países y productos, permitiendo identificar mercados y categorías con diferente aportación comercial.
5. El análisis combinado de revenue, frecuencia y comportamiento de compra permite pasar de una visión puramente transaccional a una estrategia centrada en clientes.

---

## 🎯 Recomendaciones de negocio

A partir del análisis se pueden considerar acciones como:

- Diseñar estrategias de fidelización para clientes **Champions** y **Loyal Customers**.
- Crear campañas de reactivación para clientes **At Risk**.
- Monitorear periódicamente la concentración del revenue.
- Priorizar mercados y productos con mayor contribución económica.
- Utilizar la segmentación de clientes para personalizar campañas comerciales.
- Dar seguimiento a los KPIs mediante un dashboard ejecutivo.

---

## 📊 Dashboard

El proyecto incluye un dashboard desarrollado en Tableau para facilitar la exploración visual de los principales indicadores y resultados del análisis.

**Tableau Public:**  
https://public.tableau.com/views/E-CommerceSalesCustomerAnalytics_17868365296540/ExecutiveSalesOverview?:language=es-ES&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

> Próximamente se agregarán capturas del dashboard directamente en este repositorio.

---

## 📁 Estructura del proyecto

```text
ecommerce-customer-analysis/
│
├── 01_data_cleaning.ipynb
│   └── Limpieza y preparación de los datos.
│
├── 02_exploratory_analysis.ipynb
│   └── Análisis exploratorio y generación de insights.
│
├── 03_dashboard_preparation.ipynb
│   └── Preparación de KPIs y datasets para Tableau.
│
├── data/
│   ├── clean/
│   └── dashboard/
│
└── README.md
