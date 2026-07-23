# 02. Diagrama de Flujo

## Introducción

El diagrama de flujo representa la secuencia lógica de funcionamiento del prototipo automatizado de tratamiento de agua. A través de este diagrama es posible visualizar las decisiones y procesos que realiza el sistema desde el momento en que se detecta agua en el aljibe hasta la obtención de los datos de monitoreo.

Este diagrama facilita la comprensión del comportamiento del sistema y sirve como guía durante el desarrollo de la programación y las pruebas de funcionamiento.

---

# Descripción del funcionamiento

El proceso comienza verificando si existe suficiente agua disponible para iniciar el tratamiento.

Si el nivel de agua es adecuado, el sistema activa la bomba principal para transportar el agua hacia el sistema de filtración.

Durante el recorrido, el agua atraviesa las diferentes capas de materiales filtrantes encargadas de reducir la presencia de partículas e impurezas.

Posteriormente, los sensores realizan las mediciones de los parámetros establecidos:

- Nivel de agua.
- Turbidez.
- pH.
- Sólidos disueltos (TDS).

La información obtenida es procesada por el ESP32, el cual puede enviarla para su visualización y análisis.

Finalmente, el sistema finaliza el ciclo de monitoreo y queda preparado para realizar una nueva medición cuando sea necesario.

---

# Secuencia del proceso

1. Inicio del sistema.
2. Verificación del nivel de agua.
3. Activación de la bomba.
4. Transporte del agua hacia el filtro.
5. Proceso de filtración.
6. Lectura de los sensores.
7. Procesamiento de la información.
8. Visualización de los resultados.
9. Fin del proceso.

---

# Objetivo del diagrama

Representar de manera clara el funcionamiento general del prototipo, mostrando la secuencia de operaciones necesarias para realizar el tratamiento y monitoreo del agua.

---

# Software utilizado

El diagrama fue elaborado utilizando Draw.io debido a su facilidad para representar procesos mediante diagramas de flujo y su compatibilidad con GitHub.
