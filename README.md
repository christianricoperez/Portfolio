---
# 📈 Portafolio de Data Analytics
Bienvenido a mi colección de proyectos.

---

## 📊 Proyecto 1: Superstore - Sales Performance Review 2025

**Descripción:**
Este dashboard interactivo está diseñado para proporcionar una revisión exhaustiva del rendimiento de ventas durante el año 2025. Permite a los gerentes analizar tendencias, 
identificar los productos de mejor rendimiento, evaluar la efectividad por región y monitorear los indicadores clave de rendimiento (KPIs) para asegurar los objetivos de negocio.

**Funcionalidades Clave:**
* **Análisis de Tendencias:** Visualización del crecimiento de ventas mes a mes.
* **Desglose Geográfico:** Evaluación del rendimiento por distintas regiones o territorios.
* **Métricas Clave (KPIs):** Tasa de Conversión, Ingresos Totales y Valor Promedio de Transacción.

**Preguntas de Negocio que Responde:**

* **Rentabilidad y Estrategia de Precio:** ¿Cuáles son las categorías y subcategorías que generan la **mayor pérdida neta** y requieren una revisión de precio o descuento?
* **Gestión de Calidad y Servicio:** ¿Cuál es la **Tasa de Devoluciones** por región y, basándose en la razón de la devolución, cuál es el principal problema (daños, producto incorrecto, etc.)?
* **Concentración Geográfica:** ¿Qué regiones o estados son los **más rentables** (generando el 80% de las ganancias) y dónde se debe enfocar la inversión?
* **Impacto de la Campaña:** ¿Cómo ha impactado el **Gasto en Marketing (ROAS)** en las ventas de cada categoría de producto (Mobiliario, Tecnología, Oficina)?

**Herramientas Utilizadas:**
* **Visualización:** Looker Studio
* **Fuente de Datos:** Google Sheets (Hoja de cálculo estructurada)

[**Ver Dashboard Interactivo en Vivo**](https://lookerstudio.google.com/reporting/2257e463-8eca-43de-b713-e8d58ea1beb6)

### 📂 Dataset del Proyecto (Archivos CSV)

Puedes hacer clic en el nombre de cada archivo para ver la estructura de datos utilizada en el modelado del informe:

* Ventas/Órdenes: [Sample - Superstore - Orders.csv](/Data/Sample%20-%20Superstore%20-%20Orders%20-%20Sample%20-%20Superstore%20-%20Orders.csv)
* Marketing: [Sample - Superstore - Marketing.csv](/Data/Sample%20-%20Superstore%20-%20Marketing%20-%20Sample%20-%20Superstore%20-%20Marketing.csv)
* Devoluciones: [Sample - Superstore - Returns.csv](/Data/Sample%20-%20Superstore%20-%20Returns%20-%20Sample%20-%20Superstore%20-%20Returns.csv)
* Clientes: [Sample - Superstore - Customers.csv](/Data/Sample%20-%20Superstore%20-%20Customers%20-%20Sample%20-%20Superstore%20-%20Customers.csv)







---
## 🏠 Proyecto 2: Análisis Exploratorio de Precios de Viviendas (EDA)

Este proyecto demuestra un flujo de trabajo de **Data Science** dedicado a la **limpieza, exploración y preparación rigurosa de datos complejos**, esencial para cualquier análisis estadístico o modelado posterior.

* **Análisis Completo en Notebook:** [EDA - House Prices Dataset](https://github.com/christianricoperez/Portfolio/blob/main/EDA_HousePrices.ipynb)

**Contenido:**

* **Manejo de Valores Nulos:** Imputación de valores.
* **Feature Engineering:** Creación de nuevas variables.
* **Transformación de Variables:** Aplicación de logaritmos para **normalizar** la variable objetivo (`SalePrice`).
* **Análisis Exploratorio:** Identificación de *outliers* y visualización de correlaciones clave con **Python (Pandas, Seaborn)**.

### 💾 Dataset del Proyecto (Archivos CSV)

El análisis utiliza el conjunto de datos de precios de viviendas, el cual está disponible para su descarga en la carpeta de datos del repositorio.

* [Datos de Entrenamiento: HousePrices_train.csv](/Data/houseprices_train.csv)

