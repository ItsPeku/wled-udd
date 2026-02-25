# Proyecto Iluminación WLED versión 2.0

Instructivo sobre la contsrucción, actualización y la utilización de el harware del dispositivo WLED para Diseño de espacios y objetos de la Universidad del Desarrollo.

<img title="Caja_WLED_2.0" alt="foto del dispositivo encendido" src="/imagenes/CajaEncendida.jpeg" style="width : 600px;">

### Mejoras del proyecto

* #### Rediseño de carcasa para la electronica
* #### Implementación de electronica integrada
* #### Aumento de Sockets conectados a Esp32 de 3 a 13 en total:
  * Impllementacion de Sockets negativos y positivos para sensores externos
  * Implementacion de Sockets de logica (D4, RX2, TX2, D5, D18 y D19)
  * Posibilidad de conectar sensores y dispositivos, al  ser reprogramado
* #### Mejora en visibilidad de las luces de comunicación de la Esp32

### Materiales necesarios para el proyecto

* 1 Esp32 devkit
* 1 Fuente de poder de 5.3v a 12v
* 1 Resistencia de 1K  Ω y 680 Ω
* 2 Diodos 1N4001
* 1 Condensador 1000uf 25V
* 1 Conector barrel jack 5.5 
* 2 Pin Header Hembra SMT para XBee 10pin
* 1 Conversor DC-DC Step Down  LM2596
* 1 Socket Circuitos integrados  8 pin y un Comparador de voltaje LM358
* 5 Terminal Block de 3.5mm 2 pines y 1 Terminal Block de 3.5mm 3 pines
* 1 Placa PCB Virgen de al menos 6 CM x 8 CM)
* 1 Tira led 5v/12v compatible ([listado de tiras compatibles](https://kno.wled.ge/basics/compatible-led-strips/))
* 1 Dispositivo de control (Celular o Computador)
* 8 Insertos M3
* 2 Distanciadores M3 20mm + 6mm
* 8 Pernos M3 6mm
* Filamento de impresión 3d

### Uso del dispositivo

#### Instalación de software

Para utilizar el dispositivo WLED 2.0, el usuario deberá escojer entre las siguientes 2 opciones de sofware:

* En el caso de usar WLED (sin necesidad de programar) utilice [Este tutorial](https://github.com/exploratec-udd/wled-udd)

* En el caso de querer programar el dispositivo manualmente, se recomienda utilizar ([Arduino IDE](https://www.arduino.cc/en/software/)) 

    $$\color{red}\Huge{\textsf{¡Considerar!}}$$

    Programar el dispositivo requiere conocimiento en el idioma de programacion C++ y los pines que pueden ser utilizados son los mencionados anteriormente, en conjunto con el pin dedicado a los leds (D2).

#### Uso del hardware

Para utilizar los Sockets de conección de este dispositivo es necesario tener un desatornillador de paleta mediano, se recomienda trenzar la punta de los cables antes de insertarlos.

|<!-- -->|<!-- -->|
 |:---:|:---:|
 |Uso del destornillador|Trenzado de cable|
 |![Uso del destornillador](/imagenes/desatornillador.jpeg)|![Trenzado de cable](/imagenes/cable.jpeg)|

# Los sockets agrupados en 3 están dedicados al control de las luces led, y el socket del medio está conectado al pin logico D2 de a ESP32


>documentado por [Sofía Pérez Gutiérrez](https://github.com/ItsPeku) 2026
