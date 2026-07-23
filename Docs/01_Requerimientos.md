# 01. Requerimientos del Proyecto

## Introducción

Antes de iniciar el diseño del prototipo fue necesario identificar las necesidades que debía satisfacer el sistema. Estos requerimientos sirvieron como base para definir las funciones del prototipo, seleccionar los componentes electrónicos y establecer los criterios de diseño.

El sistema fue concebido para apoyar el tratamiento y monitoreo del agua proveniente de aljibes rurales mediante un proceso automatizado de filtración y adquisición de datos.

---

# Requerimientos Funcionales

Los requerimientos funcionales describen las tareas que el sistema debe realizar para cumplir con los objetivos del proyecto.

| Código | Requerimiento |
|---------|---------------|
| RF-01 | Medir el nivel de agua mediante sensores. |
| RF-02 | Medir la turbidez del agua antes y después del proceso de filtración. |
| RF-03 | Medir la concentración de sólidos disueltos (TDS). |
| RF-04 | Medir el pH del agua. |
| RF-05 | Activar automáticamente las bombas de agua durante el proceso de filtración. |
| RF-06 | Permitir el transporte del agua entre las diferentes etapas del sistema. |
| RF-07 | Procesar la información obtenida por los sensores mediante un ESP32. |
| RF-08 | Mostrar los resultados obtenidos durante el monitoreo del sistema. |
| RF-09 | Permitir realizar pruebas de funcionamiento del prototipo. |

---

# Requerimientos No Funcionales

Los requerimientos no funcionales establecen las características de calidad que debe cumplir el sistema.

| Código | Requerimiento |
|---------|---------------|
| RNF-01 | El sistema debe ser de bajo costo. |
| RNF-02 | Debe utilizar componentes electrónicos de fácil adquisición. |
| RNF-03 | Debe ser modular para facilitar futuras modificaciones. |
| RNF-04 | Debe permitir el reemplazo de sensores sin modificar toda la estructura. |
| RNF-05 | Debe ser seguro para trabajar con agua y dispositivos electrónicos. |
| RNF-06 | Debe ser fácil de ensamblar y mantener. |
| RNF-07 | La documentación del proyecto debe encontrarse organizada en GitHub. |

---

# Restricciones del Proyecto

Durante el desarrollo del prototipo se tuvieron en cuenta las siguientes restricciones:

- Presupuesto limitado para la adquisición de componentes.
- Tiempo de desarrollo correspondiente a un semestre académico.
- Disponibilidad limitada de algunos sensores electrónicos.
- El prototipo fue construido a escala como prueba de concepto.
- Las pruebas fueron realizadas en un ambiente controlado.

---

# Criterios de Aceptación

El proyecto se considera funcional cuando cumple las siguientes condiciones:

- El sistema transporta el agua correctamente entre las etapas del proceso.
- Los sensores realizan lecturas de las variables establecidas.
- El ESP32 procesa correctamente la información.
- El sistema de filtración funciona sin presentar fugas importantes.
- Es posible observar el comportamiento general del prototipo durante las pruebas.

---

# Resultado Esperado

Se espera obtener un prototipo capaz de integrar procesos de filtración, monitoreo y automatización, permitiendo evaluar parámetros relacionados con la calidad del agua y sirviendo como una alternativa de bajo costo para futuras investigaciones sobre tratamiento de agua en aljibes rurales.

