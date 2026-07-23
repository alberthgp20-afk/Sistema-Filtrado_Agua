# 03. Diagrama de Caja Negra

## Introducción

El diagrama de caja negra representa el funcionamiento general del sistema sin mostrar los procesos internos. Su propósito es identificar claramente las entradas que recibe el prototipo, el procesamiento general que realiza y las salidas que genera.

Este tipo de diagrama permite comprender el comportamiento del sistema desde un punto de vista funcional, facilitando la identificación de los recursos necesarios y los resultados esperados.

---

# Entradas

El sistema recibe los siguientes elementos de entrada:

- Agua proveniente del aljibe.
- Energía eléctrica para alimentar los componentes electrónicos.
- Parámetros de configuración del sistema.
- Información obtenida por los sensores.

---

# Proceso

Una vez que el sistema detecta la disponibilidad de agua, esta es impulsada mediante bombas hacia el sistema de filtración.

Durante el recorrido se realiza el tratamiento físico del agua mediante materiales filtrantes.

Posteriormente los sensores realizan la medición de:

- Turbidez
- pH
- Sólidos Disueltos (TDS)
- Nivel del agua

El ESP32 procesa la información obtenida y la prepara para su visualización y análisis.

---

# Salidas

El sistema genera las siguientes salidas:

- Agua tratada.
- Valores de pH.
- Valores de turbidez.
- Valores de TDS.
- Nivel del agua.
- Información para monitoreo del sistema.

---

# Objetivo

Representar el comportamiento general del prototipo mediante la relación entre entradas, proceso y salidas, sin profundizar en la implementación interna de cada componente.

---

# Herramienta utilizada

El diagrama fue elaborado utilizando Draw.io para facilitar su documentación dentro del repositorio del proyecto.
