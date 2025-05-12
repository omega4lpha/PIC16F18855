# PIC16F18855

## 1. Historia
El PIC16F18855 es un microcontrolador de 8 bits desarrollado por Microchip Technology, lanzado en la década de 2010 como parte de la familia PIC16. Destaca por su bajo consumo de energía y su capacidad para aplicaciones embebidas gracias a funciones como Core Independent Peripherals (CIP), convertidores analógico-digitales (ADC) de alta resolución y comunicación serial avanzada (I2C, SPI, UART). Es compatible con el entorno de desarrollo MPLAB X y el compilador XC8, lo que facilita su programación y depuración en aplicaciones industriales y educativas.


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

Acá detallaré cuales son los usos de PIC

---

## 3. Ejemplos de Aplicación

### 3.1. **Control de un LED RGB**
Ejemplo del led

### 3.2. **Sensor de Temperatura con Display LCD**
Ejemplo del LED

---

## Conclusión

Acá va la conclusión

---

## Referencias

[^1]: Microchip Technology, s.f. "PIC16F18855". https://www.microchip.com/en-us/product/pic16f18855#Overview
