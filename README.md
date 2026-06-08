# Proyecto Arduino: Robot Wall-E Autónomo

Este proyecto consiste en la construcción y programación de un robot móvil inspirado en Wall-E, utilizando una placa Arduino. El robot es capaz de moverse de forma autónoma y esquivar obstáculos gracias a su sensor ultrasónico (que simula sus ojos) y un servomotor (que simula su cuello).

## Materiales

- 1 Arduino Uno
- 1 Controlador de motores (Módulo L298N)
- 2 Motores DC con motorreductor (y ruedas o sistema de orugas)
- 1 Sensor Ultrasónico (HC-SR04)
- 1 Servomotor (SG90)
- 1 Chasis (puede ser acrílico, impresión 3D o cartón reciclado)
- 1 Portapilas y baterías
- Cables jumper (Macho-Macho y Macho-Hembra)

## Conexión Básica

- **Sensor Ultrasónico:** Conecta el pin Trig al pin 12 y el pin Echo al pin 11 del Arduino.
- **Servomotor:** Conecta el cable de señal (naranja/amarillo) al pin 9.
- **Motores:** Conecta los motores al módulo L298N, y los pines de control (IN1, IN2, IN3, IN4) a los pines digitales del Arduino (ej. 4, 5, 6 y 7).
- **Alimentación:** Asegúrate de compartir las tierras (GND) entre el Arduino y el módulo L298N.

## Archivos del proyecto

- `Codigo_Wall_E.ino` (Contiene la lógica de movimiento y detección de obstáculos)
- `README.md` (Documentación del proyecto)

## Cómo usarlo

1. Ensambla el chasis y fija todos los componentes electrónicos de forma segura.
2. Realiza el cableado siguiendo el esquema de conexión.
3. Abre el archivo `Codigo_Wall_E.ino` en tu Arduino IDE.
4. Conecta tu placa Arduino al computador mediante el cable USB.
5. Sube el código a la placa.
6. Desconecta el cable USB, enciende el portapilas y observa a tu Wall-E explorar su entorno.

## Fecha de presentación: Jueves, 02 de Julio