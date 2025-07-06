# Análisis Comparativo de Rendimiento de Tiendas – Alura Store

[![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/fsoto21/CHALLENGE_ALURA_STORE_Fausto_Soto/blob/main/ALURA_STORE.ipynb)

---

## 📚 Índice

1. [Resumen Ejecutivo](#-1-resumen-ejecutivo)  
2. [Introducción](#-2-introducción)  
3. [Datos y Metodología](#-3-datos-y-metodología)  
4. [Análisis de Resultados](#-4-análisis-de-resultados)  
   - [4.1 Ingresos Totales y Transacciones](#-41-ingresos-totales-y-transacciones)  
   - [4.2 Ventas por Categoría](#-42-ventas-por-categoría)  
   - [4.3 Calificación Promedio de Clientes](#-43-calificación-promedio-de-clientes)  
   - [4.4 Productos Más y Menos Vendidos](#-44-productos-más-y-menos-vendidos)  
   - [4.5 Costo Promedio de Envío](#-45-costo-promedio-de-envío)  
   - [4.6 Desempeño Geográfico](#-46-desempeño-geográfico)  
5. [Discusión de Hallazgos](#-5-discusión-de-hallazgos)  
6. [Recomendaciones](#-6-recomendaciones)  
7. [Conclusión](#-7-conclusión)  
8. [Consideraciones Adicionales](#-8-consideraciones-adicionales)  
9. [Acceso al Proyecto](#-9-acceso-al-proyecto)  
10. [Tecnologías Utilizadas](#-tecnologías-utilizadas)  

---

## 📌 1. Resumen Ejecutivo

Este informe presenta un análisis integral del desempeño de las cuatro tiendas (Tienda 1, Tienda 2, Tienda 3 y Tienda 4) de la cadena Alura Store en el período 2020–2023. Se examinaron métricas como ingresos, ventas por categoría, calificaciones, productos más y menos vendidos, costos logísticos y comportamiento geográfico.

👉 **Recomendación preliminar:** Evaluar el cierre o mejora de la Tienda 4, por su bajo rendimiento en ingresos y ventas.

---

## 🧭 2. Introducción

El Sr. Juan busca decidir cuál de sus cuatro tiendas vender. Para ello se realiza un análisis comparativo de desempeño operativo, comercial y logístico de cada tienda con base en datos históricos. El objetivo es identificar la tienda con menor desempeño global.

---

## 📊 3. Datos y Metodología

- **Fuente:** Archivos CSV por tienda (2020-2023).
- **Variables:** Precio, Costo de envío, Fecha de compra, Calificación, Producto, Categoría, Método de pago, Coordenadas.
- **Herramientas:** Python, Pandas, Matplotlib.
- **Método:** Análisis descriptivo y visual mediante gráficos de barras, líneas, pastel, dispersión y mapas de calor.

---

## 📈 4. Análisis de Resultados

📎 [Notebook de análisis y gráficas en GitHub](https://github.com/fsoto21/CHALLENGE_ALURA_STORE_Fausto_Soto.git)

### 💵 4.1 Ingresos Totales y Transacciones

| Tienda   | Ingresos Totales (USD)        |
|----------|-------------------------------|
| Tienda 1 | 497,373.95                    |
| Tienda 2 | 517,759.36                    |
| Tienda 3 | 519,471.82 **(más alto)**     |
| Tienda 4 | 465,670.32 **(más bajo)**     |

---

### 🗂️ 4.2 Ventas por Categoría

- Las ventas por categoría varían notablemente por tienda.
- Tienda 3 y Tienda 2 lideran en categorías como "Tecnología" y "Muebles".
- Tienda 4 muestra menor diversidad y volumen de ventas.

---

### 🌟 4.3 Calificación Promedio de Clientes

- Todas las tiendas mantienen calificaciones entre 3.93 y 4.16.
- Tienda 4 tuvo la mejora más notoria en 2023 (4.16).
- Tienda 1 y Tienda 2 mostraron descenso en calificaciones.

---

### 📦 4.4 Productos Más y Menos Vendidos

| Tienda   | Producto Más Vendido (Unidades)         | Producto Menos Vendido (Unidades)           |
|----------|----------------------------------------|---------------------------------------------|
| Tienda 1 | Armario (60 uds)                       | Auriculares con micrófono (33 uds)          |
| Tienda 2 | Iniciando en programación (65 uds)    | Juego de mesa (32 uds)                       |
| Tienda 3 | Kit de bancas (57 uds)                 | Bloques de construcción (35 uds)             |
| Tienda 4 | Cama box (62 uds)                      | Guitarra eléctrica (33 uds)                  |

---

### 🚚 4.5 Costo Promedio de Envío

| Tienda   | Costo Promedio de Envío (USD)           |
|----------|----------------------------------------|
| Tienda 1 | 26,018.61 **(más alto)**                |
| Tienda 2 | 25,216.24                              |
| Tienda 3 | 24,805.68                              |
| Tienda 4 | 23,459.46 **(más bajo)**                |

---

### 🗺️ 4.6 Desempeño Geográfico

- Se generaron mapas de dispersión y calor para visualizar la densidad de ventas por coordenadas.
- Tienda 3 mostró una distribución más amplia y activa de ventas geográficas.
- Tienda 4 tiene menor cobertura territorial.

---

## 🧠 5. Discusión de Hallazgos

- Tienda 3 se destaca por sus altos ingresos, buena satisfacción del cliente y amplio alcance geográfico.
- Tienda 1 combina ingresos relativamente bajos con un costo de envío alto, lo que afecta su rentabilidad.
- Tienda 2 mantiene un rendimiento promedio en la mayoría de indicadores.
- Tienda 4 tiene el costo logístico más bajo, pero también la menor facturación y cobertura, aunque con mejoras en la calificación de clientes.

---

## ✅ 6. Recomendaciones

- **Cerrar o vender Tienda 4**, salvo que se implementen estrategias fuertes de marketing y fidelización para mejorar su desempeño.
- **Reforzar Tienda 3** con inversión en inventario y expansión, dado su equilibrio positivo en métricas clave.
- **Monitorear Tienda 1** por su alto costo logístico relativo que podría estar afectando su competitividad.

---

## 📌 7. Conclusión

- Tienda 3 lidera el rendimiento general entre las cuatro tiendas.
- Tienda 4 presenta vulnerabilidades significativas y es la candidata principal para la venta o cierre.
- La decisión debe considerar rentabilidad real, costos operativos y potencial de crecimiento futuro.

---

## 🎯 8. Consideraciones Adicionales

- Evaluar ubicación física, contratos de alquiler y gastos operativos asociados.
- Revisar campañas de marketing específicas por tienda.
- Analizar segmentación de clientes y adecuación del catálogo de productos localmente.

---

## 📁 9. Acceso al Proyecto

- 🔗 [Repositorio en GitHub](https://github.com/fsoto21/CHALLENGE_ALURA_STORE_Fausto_Soto.git)

---

## ✅ Tecnologías Utilizadas

- Python  
- Pandas  
- Matplotlib  
- Jupyter Notebook  
