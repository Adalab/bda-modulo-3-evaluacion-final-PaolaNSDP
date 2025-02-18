# **Análisis de Clientes en el Programa de Lealtad de una Aerolínea**

## **Descripción del Proyecto**

Este proyecto analiza el comportamiento de los clientes dentro de un programa de lealtad de una aerolínea. Se utilizan dos conjuntos de datos: uno sobre la actividad de vuelo (reservas, distancias, puntos) y otro sobre el perfil de los clientes (ubicación, educación, ingresos). El objetivo es explorar, limpiar, visualizar y evaluar diferencias significativas en el número de vuelos reservados según el nivel educativo.

---

## **Fase 1: Exploración y Limpieza**

- **Exploración inicial:** Identificación y gestión de valores nulos, atípicos y problemas de datos.
- **Limpieza:** Imputación de valores nulos y ajuste de tipos de datos para el análisis.

---

## **Fase 2: Visualización**

Se crearon gráficas para responder preguntas clave, incluyendo:
- Distribución de vuelos reservados por mes.
- Relación entre distancia de vuelos y puntos acumulados.
- Comparación de salario promedio por nivel educativo.
- Distribución de clientes por estado civil y género.

---

## **Fase 3: Evaluación de Diferencias por Nivel Educativo**

- **Preparación de datos:** Filtrado de las columnas relevantes: 'Flights Booked' y 'Education'.
- **Análisis:** Realización de la prueba estadística Kruskall-Wallis que muestra diferencias significativas en los vuelos reservados entre los niveles educativos.
- **Prueba comprobación:** Realización del test de Mann-Whitney entre los grupos significativos. Los resultados muestran que el **Grupo 1** tiene diferencias con otros grupos, pero las distribuciones de vuelos son similares.

---

## **Conclusión**

El análisis indica que, aunque existen diferencias estadísticas significativas en los vuelos reservados entre los grupos educativos, las diferencias prácticas son pequeñas debido a la similitud en las distribuciones.

---

## **Cómo Ejecutar el Proyecto**

1. **Clonar el repositorio:**

   
