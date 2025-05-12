# PIC16F18855

## 1. Historia
El PIC16F18855 es un microcontrolador de 8 bits desarrollado por Microchip Technology, lanzado en el 2010 como parte de la familia PIC16. Tiene un bajo consumo de energía y alta capacidad para aplicaciones embebidas gracias a funciones como Core Independent Peripherals (CIP), convertidores analógico-digitales (ADC) de alta resolución y comunicación serial avanzada (I2C, SPI, UART). Es compatible con el entorno de desarrollo MPLAB X y el compilador XC8, lo que facilita su programación y depuración en aplicaciones industriales y educativas.


**Figura 1: Diagrama del microcontrolador PIC16F18855**

![PIC16F18855](https://media.microchip.com/silicon-devices/medium/pic16f18855-m3x.png)

*Fuente: Microchip Technology*

---


### 1.1. Carácteristicas

A continuación, de describen las características básicas de acuerdo con Microchip Technology[^1] del microcontrolador PIC16F18855

| Característica                  | Valor     |
|-------------------------------|-----------|
| Program Memory Size (KB)       | 14        |
| RAM                            | 1024      |
| Data EEPROM (bytes)            | 256       |
| Pin Count                      | 28        |
| Operation Voltage Max. (V)     | 5.5       |
| Operation Voltage Min. (V)     | 1.8       |


### 1.2. Diferencias entre un Microcontrolador y un Microprocesador

A diferencia de los microprocesadores, el PIC16F18855 (el cual es un microcontrolador ) no consta de un sistema operativo para su funcionamiento. En lugar de eso, está diseñado para ejecutar directamente código embebido escrito en lenguajes como C o ensamblador, sin necesidad de capas intermedias de software. Esto lo hace ideal para aplicaciones específicas donde se requiere una respuesta rápida, bajo consumo de energía y alta integración de periféricos en un solo dispositivo.
Su capacidad de procesamiento es menor, pensado precisamente para tareas de menor complejidad, analizando sus entradas y salidas (I/O) en base a sus componentes internos y cambios de voltaje.

| Característica               | Microcontrolador (ej: PIC16F18855)     | Microprocesador                        |
|-----------------------------|----------------------------------------|----------------------------------------|
| Integración                 | Incluye CPU, memoria, I/O y periféricos| Solo contiene la unidad central de proceso (CPU) |
| Propósito                   | Aplicaciones embebidas específicas     | Computadoras generales o sistemas complejos |
| Programación                | Fácil de programar con lenguajes simples| Requiere sistema operativo y software complejo |
| Costo                       | Bajo                                   | Alto                                   |
| Consumo de energía          | Bajo                                   | Generalmente más alto                  |

Los microcontroladores como el PIC16F18855 están optimizados para tareas específicas, mientras que los microprocesadores son más potentes pero requieren más componentes externos y recursos.

---

## 2. Usos del PIC16F18855

El PIC16F18855 tiene usos en sistemas embebidos donde se requiere bajo consumo energético, una programación simplificada en C++ o ASEMBLY. Entre sus usos más comunes se encuentran:

- Automatización industrial (control de motores, monitoreo de sensores).
- Domótica (control de luces, cerraduras, temperatura).
- Equipos médicos portátiles.
- Electrónica de consumo (juguetes inteligentes, electrodomésticos).
- Sistemas educativos para enseñanza de programación y electrónica básica.
- Prototipos de IoT cuando se combinan con módulos de comunicación externa.

Gracias a sus periféricos independientes del núcleo (CIP), puede ejecutar tareas simples sin requerir constantemente la intervención del procesador, optimizando así el consumo de energía.


---

## 3. Entorno de programación 

Para poder programar al PIC16F18855 se utiliza el **IDE MPLAB ® Xpress IDE** ofrecido por Microship Technology[^2], siendo una herramienta que aporta flexibilidad, permitiendo programar, depurar y cargar el código al PIC16F18855.

**Figura 2: Logo de MPLAB**

![MPLAB](img/mplab-xpress-ide-transparent-background.avif)

*Fuente: Microchip Technology*

Dentro de MPLAB se usará MCC (MPLAB ® Code Configurator), para poder asignar las entradas y salidas a cada pin correspondiente para los ejemplos a continuacion.

---

## 3. Ejemplos de Aplicación

Los ejemplos a demostrar en este informe son obtenidos del libro "Programación de microcontoladores PIC paso a paso"[^3] de Carlos Urioz Zamarreño

### 3.1. **Control de un LED por pulsador**
E

### 3.2. **Sensor de Temperatura con Display LCD**
Ejemplo del LED

---

## Conclusión

El microcontrolador PIC16F18855 representa una excelente opción para desarrolladores que buscan una solución eficiente, económica y versátil para sistemas embebidos. Su conjunto de periféricos integrados, bajo consumo de energía y facilidad de programación lo hacen ideal tanto para aplicaciones industriales como educativas. Con capacidades como ADC de alta resolución, múltiples interfaces de comunicación y periféricos independientes del núcleo, el PIC16F18855 permite diseñar dispositivos confiables, compactos y eficientes sin requerir hardware externo complejo. Es un claro ejemplo de cómo la integración y simplicidad pueden potenciar la innovación en proyectos electrónicos modernos.

---

## Referencias

[^1]: Microchip Technology, s.f. "PIC16F18855". https://www.microchip.com/en-us/product/pic16f18855#Overview
[^2]: Microchip Technology, s.f. "MPLAB® Xpress Cloud-Based IDE". https://www.microchip.com/en-us/tools-resources/develop/mplab-xpress
[^3]: Carlos Ruiz Camarreño, 2021. "Programación de microcontoladores PIC paso a paso". https://feriachilenadellibro.cl/producto/9786075387413-programacion-de-microcontroladores-pic-paso-a-paso/
