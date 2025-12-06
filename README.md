# DataScience_Datawarehouse_and_insights_Vanish_data
Mini Data Warehouse con datos de Vanish  Este proyecto implementa un pequeño data warehouse diseñado para practicar y demostrar conceptos de modelado analítico.  Utiliza un esquema estrella (star schema) con tablas de hechos y dimensiones construidas a partir de datos de Vanish. 
## 🧪 Exploratory Data Analysis (EDA)

- `notebooks/EDA_ventas.ipynb`: análisis exploratorio de datos de ventas.
- `notebooks/EDA_clientes.ipynb`: análisis de clientes y segmentación.

## 🧱 Data Warehouse / Modelado Dimensional

- `sql/dim_cliente.sql`: script de creación de la dimensión cliente.
- `sql/fact_ventas.sql`: tabla de hechos de ventas.
- `docs/modelo_dimensional_ventas.pdf`: diagrama estrella.

## 📊 Dashboards (Power BI)

- `powerbi/ventas_dashboard.pbix`: dashboard de ventas.
- Screenshots en `img/ventas_dashboard.png`.

## 📁 Estructura del repositorio

```text
/notebooks/      → Jupyter Notebooks de EDA  
/sql/            → Scripts SQL para DW  
/powerbi/        → Archivos .pbix  
/docs/           → PDFs, reportes  
/img/            → Imágenes usadas en el README
