# Análisis de KPIs de Tienda con Looker Studio y Google Sheets

En este proyecto he utilizado **Google Sheets como fuente de datos en la nube** y **Looker Studio (Google Data Studio)** para construir un informe interactivo que permite analizar el comportamiento semanal de una tienda a través de indicadores clave de rendimiento (KPIs).

El objetivo es demostrar cómo se puede trabajar de forma práctica y efectiva en la nube, conectando datos en tiempo real y visualizándolos con herramientas de Business Intelligence.

## Fuentes de datos

### 🗂 Hoja: `RATIOS SEMANA`

Contiene datos semanales relacionados con ventas, horas trabajadas y productividad:

- **Semana**: Identificador principal de los datos.
- **Nº Semana**: Orden secuencial de la semana (usado para diseño visual).
- **Venta PEP**: Previsión de ventas para la semana.
- **Venta Real**: Ventas reales obtenidas.
- **Horas PEP**: Previsión de horas de personal necesarias.
- **Horas Real**: Horas realmente trabajadas.
- **Productividad PEP**: Previsión de productividad.
- **Productividad Real**: Productividad alcanzada.

> 📌 **Nota:** La *productividad* es un KPI clave: se calcula como la relación entre **unidades vendidas** y **horas trabajadas**.

![Ratios Semana](https://github.com/user-attachments/assets/fe85e07c-ea60-4622-b496-4d2703a08b4a)

---

### 🗂 Hoja: `PARTICIPACIÓN`

Esta hoja permite analizar la participación semanal de distintas familias de productos:

- **Semana**: Identificador principal.
- **Familia**: Categoría del producto.
- **Participación**: Porcentaje de ventas que representa dicha familia.

> 📌 **Nota:** La participación no representa el 100%, ya que algunas familias han sido excluidas del análisis.

![Participación](https://github.com/user-attachments/assets/bc67cf41-696e-4f50-9fd8-5c2c03b31622)

---

### 🗂 Hoja: `MERMA`

Incluye el porcentaje de merma por familia de producto:

- **Semana**: Identificador principal.
- **Familia**: Categoría del producto.
- **Merma**: Porcentaje de merma sobre la venta.

![Merma](https://github.com/user-attachments/assets/93d2b0f0-872d-45af-8720-8b1612ad6df4)

---

### 🗂 Hoja: `OBJETIVOS MERMA`

Define los objetivos de merma que la tienda debe alcanzar por familia de producto.

---

## Herramientas utilizadas

- **Google Sheets**: Fuente de datos dinámica en la nube.
- **Looker Studio**: Visualización interactiva de KPIs.
- **Google Cloud** (indirectamente): Trabajo 100% en la nube, sin archivos locales.

---

## Objetivo del proyecto

Demostrar mi capacidad para:

✅ Integrar y analizar datos en la nube  
✅ Crear dashboards con enfoque práctico y visual  
✅ Medir y comparar KPIs clave (ventas, productividad, participación, merma)  
✅ Usar herramientas modernas de BI como Looker Studio

---

## Visualización del Dashboard

Este es el enlace del dashboard creado con Looker Studio. Es una visualización sencilla, pero nos ofrece una vista rápida y clara del comportamiento del negocio:

🔗 [Ver Dashboard en Looker Studio](https://lookerstudio.google.com/s/rw1NQMLw_eQ)
