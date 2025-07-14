# 📊 Dashboard de Ventas en Excel  
*Análisis Comercial Interactivo y Visualización de KPIs*

---

## 📖 Descripción

Este proyecto consiste en el desarrollo de un **dashboard interactivo en Microsoft Excel** para analizar y visualizar los datos de ventas de una empresa. El objetivo principal es proporcionar una herramienta que permita entender el comportamiento comercial por país, producto y agente, y facilite la **toma de decisiones estratégicas** en base a datos históricos.

El trabajo abarca todo el flujo de análisis de datos: desde la limpieza y transformación inicial, hasta el diseño final de un tablero dinámico con segmentadores (slicers), visualizaciones clave y KPIs destacados.

---

## 🗂 Estructura del Proyecto

├── data/
│ └── pedidos_ventas.xlsx # Datos originales de ventas
├── dashboard/
│ └── dashboard_ventas.xlsx # Dashboard final con visualizaciones y segmentadores
├── analysis/
│ └── hoja_analisis.xlsx # Hoja auxiliar con KPIs y cálculos intermedios
├── README.md


---

## 🛠 Instalación y Requisitos

Este proyecto se ejecuta directamente en **Microsoft Excel (2016 o superior)**.

### Requisitos:

- Microsoft Excel (recomendado: versión con soporte para segmentadores y gráficos dinámicos)
- Habilitación de macros y vínculos dinámicos, si corresponde

**No es necesario ningún lenguaje de programación ni instalación adicional.**

---

## 📈 Transformación y Limpieza de Datos

Se realizaron los siguientes pasos para asegurar la calidad de los datos:

- Conversión de formatos de fecha al estándar legible.
- Revisión de campos numéricos para asegurar coherencia (por ejemplo, detección de precios negativos).
- Eliminación de duplicados y registros incompletos.
- Documentación y control de valores faltantes o atípicos.
- Validación de consistencia en códigos de país y producto.
- Separación de métricas calculadas en una **hoja exclusiva de análisis** para facilitar su mantenimiento.

---

## 📊 KPIs Calculados

En la hoja de análisis se calcularon los siguientes indicadores clave de rendimiento:

- **Importe Total de Ventas (€)**: Suma del valor total de los pedidos.
- **Cantidad Total de Productos Vendidos**: Total de unidades vendidas.
- **Precio Promedio de Venta**: Promedio ponderado por producto.
- **% Pedidos Facturados**: Relación entre pedidos emitidos y pedidos facturados.
- **Ventas por Familia y Subfamilia**: Análisis del rendimiento por tipo de producto.
- **Desempeño por Agente Comercial**: Total de ventas individuales por vendedor.

---

## 📊 Visualizaciones Incluidas

El dashboard contiene gráficos dinámicos y filtros interactivos:

- **Tarjetas de KPIs**: Importe total, unidades vendidas, precio promedio.
- **Pie Chart**: Porcentaje de pedidos facturados vs. no facturados.
- **Gráfico de líneas**: Evolución mensual de ventas.
- **Gráfico de barras**: Ventas por familia de producto.
- **Gráfico por país**: Comparativa geográfica de ventas.
- **Tabla por agente**: Desempeño comercial individual.
- **Segmentadores (slicers)**: Filtros por país, subfamilia y agente comercial para análisis personalizado.

---

## 🔍 Insights Clave

- **Septiembre** muestra un pico de ventas significativo, especialmente en **España**.
- Las familias **"Envases Plásticos Alimentación"** y **"Sacos y Mallas Tejidas"** concentran la mayor parte de las ventas.
- Algunos países tienen un rendimiento comercial bajo, lo que abre oportunidades para estrategias focalizadas.
- Se sugiere aplicar **promociones en meses de baja venta** para balancear la estacionalidad.
- Correlación preliminar entre precios promedio más bajos y mayor volumen de unidades vendidas.

---

## 📌 Próximos Pasos

- Añadir **variación intermensual (%)** para comparar rendimientos entre periodos.
- Explorar correlaciones entre variables clave (precio, país, agente).
- Implementar tooltips o notas de ayuda en el dashboard para facilitar su uso.
- Ajustar la paleta de colores y fondo para mejorar la **legibilidad visual**.
- Automatizar carga de datos nuevos en la hoja de análisis.

---

## 🤝 Contribuciones

Este proyecto es parte de un ejercicio formativo. Sin embargo, se agradecen sugerencias o comentarios para su mejora.

---

## ✒️ Autor

- **Susana Mariño Pouso**  
  [@smarinopouso](https://github.com/smarinopouso)

---

## ✅ Estado del Proyecto

✔ Transformación y limpieza de datos completa  
✔ KPIs relevantes calculados y representados  
✔ Dashboard interactivo con slicers  
🔄 Documentación actualizada (README en raíz del proyecto)  
🛠 Mejoras visuales y analíticas en desarrollo

---