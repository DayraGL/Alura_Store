# 🛒 Análisis de Rendimiento: Alura Store

Este proyecto presenta un análisis integral de datos para la cadena de tiendas **Alura Store**. A través del procesamiento de datos de múltiples sedes, hemos extraído KPIs clave sobre ventas, logística y satisfacción del cliente para apoyar la toma de decisiones estratégicas.

## 🚀 Tecnologías Utilizadas
* **Python 3.x**
* **Pandas**: Limpieza y manipulación de datos.
* **Seaborn & Matplotlib**: Visualización de datos estadística.
* **Folium**: Mapeo geográfico interactivo.
* **Google Colab**: Entorno de desarrollo.

## 📊 Insights Principales

### 1. Logística y Costos de Envío
Se identificó que la **Tienda 1** presenta los costos de envío más elevados (Promedio: R$26,018.61. Esto sugiere una oportunidad para renegociar contratos de flete o revisar la zona de cobertura.

![image](https://github.com/DayraGL/Alura_Store/blob/main/AverageShipping%20CostperStore.png)

### 2. Composición de Ventas
La categoría de **Muebles** representa el mayor volumen de ventas, lo que indica una fuerte preferencia del mercado por estos productos.

![image](https://github.com/DayraGL/Alura_Store/blob/main/categories_porcentage_graphic.png)

### 3. Satisfacción del Cliente (KPI de Salud)
A pesar del volumen de ventas, la satisfacción varía significativamente entre sedes. El análisis de distribución muestra que la **Tienda Y** mantiene la mayor lealtad de clientes.

![image](https://github.com/DayraGL/Alura_Store/blob/main/satisfation_per_store.png)

## 🗺️ Análisis Geográfico
Utilizando coordenadas de latitud y longitud, generamos un mapa de calor que revela una alta concentración de demanda en la región de **Bogotá**, donde actualmente no contamos con una sede física.

## 🛠️ Cómo ejecutar el proyecto
1. Clona este repositorio:
   `git clone https://github.com/tu-usuario/challenge-alura-store.git`
2. Instala las dependencias:
   `pip install pandas matplotlib seaborn folium`
3. Abre el archivo `Challenge_Alura_Store.ipynb` en Google Colab o Jupyter Notebook.

---
Desarrollado con ❤️ por Dayra G. durante el Challenge de Alura Latam.
