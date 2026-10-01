# 📊 Proyecto 7 – Análisis de Clientes ConnectaTel

## 📌 Objetivo del proyecto

El objetivo de este proyecto es analizar el comportamiento de los clientes de ConnectaTel para identificar patrones de uso de llamadas y mensajes, detectar problemas de calidad en los datos, encontrar valores atípicos (outliers) y segmentar a los usuarios según su edad y nivel de uso. Con estos resultados se generan recomendaciones que apoyen la optimización de la oferta comercial y la toma de decisiones.

---

## 📂 Datasets utilizados

El análisis se realizó utilizando tres conjuntos de datos:

- **plans.csv:** Información de los planes disponibles (precio, minutos incluidos, GB incluidos y costos adicionales).
- **users_latam.csv:** Información de los clientes (edad, ciudad, fecha de registro, plan contratado y estado de churn).
- **usage.csv:** Registro del uso de los servicios (llamadas, mensajes, duración y longitud de mensajes).

---

## 🔎 Etapas del análisis

El proyecto se desarrolló siguiendo las siguientes etapas:

1. Carga y exploración de los datasets.
2. Identificación de problemas de calidad de datos.
3. Limpieza de datos (valores nulos, sentinels y fechas inválidas).
4. Creación de estadísticas descriptivas por usuario.
5. Visualización de distribuciones mediante histogramas y boxplots.
6. Detección y análisis de outliers utilizando el método IQR.
7. Segmentación de clientes por edad y nivel de uso.
8. Elaboración de conclusiones y recomendaciones para el negocio.

---

## ▶️ Cómo ejecutar el notebook

Este proyecto puede ejecutarse en **Google Colab** o en un entorno de **Jupyter Notebook**.

### Google Colab

1. Abrir el archivo `.ipynb` en Google Colab.
2. Cargar los datasets en la carpeta `/datasets/` o actualizar las rutas de los archivos.
3. Ejecutar las celdas en orden desde el inicio del notebook.

---

## 🔄 Guía de reproducción

Para reproducir el análisis:

1. Descargar el notebook y los tres datasets.
2. Verificar que los archivos se encuentren en la carpeta `/datasets/`.
3. Ejecutar todas las celdas en orden.
4. Revisar las visualizaciones, segmentaciones e insights obtenidos.
5. Comparar los resultados con las conclusiones del análisis ejecutivo.

---

## 🛠️ Herramientas utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab / Jupyter Notebook

---

## 📈 Resultados principales

El análisis permitió:

- Identificar problemas de calidad de datos y corregirlos.
- Detectar usuarios con patrones de consumo intensivo mediante análisis de outliers.
- Segmentar clientes por edad y nivel de uso.
- Generar recomendaciones para optimizar la oferta comercial y fortalecer la fidelización de clientes.
