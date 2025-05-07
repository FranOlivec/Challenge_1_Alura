# 📊 Data Science Challenge – Análisis de Rendimiento de Tiendas

Este repositorio contiene el desarrollo del primer challenge del curso de Data Science con Python de Alura Latam. El objetivo fue realizar un análisis de ventas, calificaciones, costos logísticos y categorías de productos de cuatro tiendas ficticias para determinar cuál de ellas presenta el peor desempeño y debería cerrarse.

---

## 🎯 Propósito del análisis

El análisis busca **apoyar la toma de decisiones estratégicas** para una empresa que posee cuatro tiendas, mediante el estudio de datos de ventas y logística. Se utilizaron datos como:

- Facturación total
- Categoría más vendida
- Calificación promedio por cliente
- Productos más y menos vendidos
- Costo de envío promedio
- (Opcional) Distribución geográfica de las ventas

La conclusión general se basa en un enfoque de rendimiento integral, considerando tanto ingresos como eficiencia operativa y percepción del cliente.

---

## 📁 Estructura del proyecto

AluraStoreLatamTerminadoFOV/
│
├── AluraStoreLatamTerminadoFOV.ipynb # Notebook con todo el desarrollo del análisis
├── README.md # Este archivo explicativo
└── (opcional) /imagenes # Carpeta para guardar visualizaciones exportadas


- El notebook `AluraStoreLatamTerminadoFOV.ipynb` contiene todas las etapas del análisis, desde la importación de datos hasta la visualización de resultados.
- Los datos se importan directamente desde archivos CSV alojados en GitHub (no es necesario descargar archivos localmente).

---

## 📈 Ejemplos de gráficos e insights obtenidos

### 💰 Ingresos totales por tienda
Gráfico de barras comparando la facturación acumulada de cada tienda.  
**Insight:** Tienda 1 tuvo el mayor ingreso, pero otras métricas mostraron debilidades.

### 🪑 Ventas de la categoría “Muebles”
Gráfico de barras mostrando cuántas unidades de "Muebles" vendió cada tienda.  
**Insight:** Aunque es la categoría más vendida en todas las tiendas, Tienda 2 y Tienda 1 tienen menos ventas que las otras dos.

### ⭐ Calificación promedio por tienda
Gráfico de líneas con puntos destacando la satisfacción del cliente.  
**Insight:** Tienda 1 tiene la peor calificación promedio (3.98).

### 🚚 Costo promedio de envío por tienda
Gráfico de barras horizontales mostrando los costos logísticos por tienda.  
**Insight:** Tienda 1 presenta el mayor costo de envío por venta.

---

## 🧠 Conclusión principal

Aunque Tienda 1 tiene buenos ingresos, presenta **debilidades estratégicas**:

- La **calificación promedio más baja**
- **Menores ventas** de la categoría clave (“Muebles”)
- **Costos logísticos más altos**

📉 Por estas razones, se recomienda cerrar **Tienda 1** y enfocar recursos en las otras tiendas con mejor rendimiento global.

---

## ▶️ Instrucciones para ejecutar el notebook

1. Abre [Google Colab](https://colab.research.google.com/).
2. Sube el archivo `challenge_ventas.ipynb` o ábrelo desde GitHub.
3. Asegúrate de **conectarte a un entorno de ejecución** (menú superior: “Conectar”).
4. Ejecuta cada celda con `Shift+Enter` en orden.
5. No necesitas descargar los datos: los archivos CSV se cargan directamente desde URLs públicas.

📦 Requisitos:
- Python 3 (incluido por defecto en Google Colab)
- Bibliotecas: `pandas` (solo para importación), `matplotlib`

---

## ✍️ Autora

**Francisca Olivares**  
Ingeniera en Bioprocesos | Especialista en Medio Ambiente y Minería  
Apasionada por el análisis de datos, la toma de decisiones basada en evidencia y la visualización clara de información.
