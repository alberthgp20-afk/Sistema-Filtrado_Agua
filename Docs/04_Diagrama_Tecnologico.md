# 04. Diagrama Tecnológico

## Introducción

El diagrama tecnológico representa la interacción entre los principales componentes electrónicos, mecánicos y de monitoreo que conforman el prototipo automatizado de tratamiento de agua.

Su propósito es mostrar cómo fluye la información y el agua a través del sistema, permitiendo comprender la función de cada elemento y la relación existente entre ellos.

---

# Descripción del sistema

El prototipo inicia con la captación de agua desde un aljibe. Mediante una bomba sumergible, el agua es transportada hacia el sistema de filtración compuesto por diferentes materiales filtrantes.

Durante el recorrido, los sensores de nivel, turbidez, pH y TDS realizan mediciones de la calidad del agua.

Toda la información es enviada al ESP32, encargado de procesar las señales provenientes de los sensores y controlar el funcionamiento del sistema.

Finalmente, los datos pueden visualizarse para analizar el estado del agua y verificar el desempeño del proceso de filtración.

---

# Componentes tecnológicos

## Captación

- Aljibe
- Agua

## Sistema hidráulico

- Bombas sumergibles
- Mangueras
- Recipientes

## Sistema de filtración

- Grava
- Arena
- Carbón activado
- Otros materiales filtrantes

## Sensores

- Sensor de nivel
- Sensor de turbidez
- Sensor de pH
- Sensor TDS

## Unidad de procesamiento

- ESP32

## Visualización

- Pantalla LCD/OLED (según la que utilizaron)
- Computador (para programación y pruebas)

---

# Objetivo

Mostrar la relación entre todos los componentes tecnológicos que intervienen en el funcionamiento del prototipo y facilitar la comprensión de su arquitectura general.

---

# Herramienta utilizada

El diagrama fue elaborado utilizando Draw.io para facilitar su edición y documentación dentro del repositorio.
