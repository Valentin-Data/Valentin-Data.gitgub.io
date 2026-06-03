---
layout: default
title: Análisis de Inventario
---
# Análisis de Datos de Inventario: Limpieza y Optimización

## 📊 Descripción del Proyecto
Este proyecto se centra en la gestión de datos de inventario con inconsistencias. El objetivo fue transformar un dataset "sucio" en información confiable y estructurada, permitiendo realizar un análisis de stock preciso para la toma de decisiones.

## 🛠️ Tecnologías y Herramientas
- **Lenguaje:** Python
- **Librerías:** - `pandas`: Para la manipulación, limpieza e imputación de datos.
    - `matplotlib`: Para la visualización de los resultados.
- **Entorno:** VS Code
- **Control de Versiones:** Git & GitHub

## 📝 Desafíos Resueltos
1. **Normalización:** Limpieza de símbolos de moneda ($) y estandarización de formatos de fecha mixtos (YYYY-MM-DD y DD/MM/YYYY).
2. **Imputación Inteligente:** Uso de funciones `groupby` y `transform` para completar datos faltantes en precios, evitando la pérdida de información.
3. **Análisis:** Agregación de stock por producto para identificar niveles de inventario.

## 📈 Visualización
Se generó un gráfico de barras que permite visualizar rápidamente el estado del stock por producto.

---
*Proyecto desarrollado como parte de mi formación en Análisis de Datos.*
