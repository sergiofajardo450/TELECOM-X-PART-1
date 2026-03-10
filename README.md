# Telecom X - Análisis de Evasión de Clientes (Churn)

## Descripción del Proyecto

Este proyecto tiene como objetivo analizar la **evasión de clientes (Churn)** en la empresa Telecom X utilizando herramientas de análisis de datos en Python.

La empresa enfrenta una alta tasa de cancelaciones de servicio, por lo que este análisis busca identificar **patrones y factores asociados al abandono de clientes**. Los resultados obtenidos permitirán generar **insights estratégicos** que pueden ayudar al equipo de Data Science a desarrollar modelos predictivos y estrategias de retención.

El análisis incluye la extracción de datos desde una API en formato JSON, su procesamiento mediante técnicas de **ETL (Extracción, Transformación y Carga)** y la realización de un **Análisis Exploratorio de Datos (EDA)** acompañado de visualizaciones.

---

## Objetivos del Proyecto

* Importar y manipular datos desde una API.
* Aplicar procesos de **limpieza y transformación de datos**.
* Explorar la estructura y características del dataset.
* Analizar la distribución de la evasión de clientes.
* Identificar relaciones entre el churn y variables demográficas, categóricas y numéricas.
* Generar visualizaciones para detectar patrones relevantes.
* Elaborar conclusiones y recomendaciones estratégicas.

---

## Fuente de Datos

Los datos utilizados en este proyecto provienen de un repositorio público en GitHub y están disponibles en formato JSON.

Dataset utilizado:

https://github.com/ingridcristh/challenge2-data-science-LATAM/blob/main/TelecomX_Data.json

Este dataset contiene información relacionada con:

* Datos demográficos de los clientes
* Tipo de contrato
* Servicios contratados
* Método de pago
* Cargos mensuales y totales
* Estado de evasión del cliente (Churn)

---

## Tecnologías Utilizadas

Este proyecto fue desarrollado utilizando las siguientes herramientas y bibliotecas de Python:

* Python 3
* Pandas
* Matplotlib
* Seaborn

Estas bibliotecas permiten realizar manipulación de datos, análisis estadístico y visualización de información.

---

## Estructura del Proyecto

El proyecto sigue una estructura de análisis de datos dividida en las siguientes etapas:

1. **Extracción de datos**

   * Carga del dataset desde una API en formato JSON.

2. **Exploración de datos**

   * Identificación de columnas, tipos de datos y estadísticas básicas.

3. **Detección de problemas**

   * Identificación de valores nulos, duplicados e inconsistencias.

4. **Limpieza y transformación de datos**

   * Corrección de tipos de datos
   * Eliminación de valores faltantes o duplicados.

5. **Análisis descriptivo**

   * Cálculo de métricas como media, mediana y desviación estándar.

6. **Análisis de evasión**

   * Visualización de la distribución de clientes que cancelan el servicio.

7. **Análisis por variables categóricas**

   * Comparación del churn con variables como género, tipo de contrato y método de pago.

8. **Análisis por variables numéricas**

   * Comparación del churn con variables como cargos mensuales y tiempo de permanencia.

9. **Conclusiones y recomendaciones**

   * Identificación de factores asociados al abandono de clientes.

---

## Instalación y Requisitos

Para ejecutar este proyecto necesitas tener instalado:

* Python 3.x
* Jupyter Notebook o Google Colab (opcional)

También es necesario instalar las siguientes librerías:

```bash
pip install pandas matplotlib seaborn
```

---

## Cómo Ejecutar el Proyecto

1. Clonar el repositorio:

```bash
git clone https://github.com/tu_usuario/tu_repositorio.git
```

2. Acceder al directorio del proyecto:

```bash
cd tu_repositorio
```

3. Ejecutar el notebook o script de Python donde se encuentra el análisis.

Si utilizas Jupyter Notebook:

```bash
jupyter notebook
```

Luego abre el archivo correspondiente y ejecuta las celdas del análisis.

---

## Resultados del Análisis

A partir del análisis exploratorio se identificaron algunos patrones importantes:

* Los clientes con **contratos mensuales presentan mayor tasa de evasión**.
* Los clientes con **mayores cargos mensuales** tienen mayor probabilidad de cancelar el servicio.
* Los clientes con **mayor tiempo de permanencia en la empresa** tienden a mantenerse más tiempo.

Estos hallazgos pueden ayudar a diseñar estrategias para **reducir la pérdida de clientes**.

---

## Recomendaciones

Basado en los resultados obtenidos, se sugieren las siguientes estrategias:

* Incentivar contratos de mayor duración.
* Implementar programas de fidelización para nuevos clientes.
* Revisar los planes con cargos mensuales elevados para mejorar su competitividad.
* Desarrollar modelos predictivos que permitan anticipar la evasión de clientes.


