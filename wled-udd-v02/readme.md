
# Version 2.0 de el Proyecto Iluminación WLED

Instructivo sobre la utilización del dispositivo, cambios aplicados y fabricación para estudiantes de Diseño de espacios y objetos de la Universidad del Desarrollo y miembros de ExploraTec.

![imagen]()

## Cambios del proyecto

*Placa integrada para alojar todos los componentes elecronicos

* Cambio de salida de led para evitar dependencia a conector
  
* Aumento de salidas y entradas del dispositivo, siendo en total:
  
   - Una entrada dedicada para el Led
   - 6 entradas y/o salidas para sensores (D4,RX2,TX2,D5,D18 y D19)
   - 2 salidas positivas (izquierda)
   - 2 salidas negativas (derecha)
     
* Entrada de voltaje desde 5.2v a 9v

* Carcasa remodelada impresa en 3D para mantener componentes y conectores protejidos

* Luces indicadoras de estado de la ESP 32



## Uso del dispositivo

### Software:

El dispositivo puede utilizar tanto Wled (recomendado) como ser programado en Arduuino IDE

 - **Para aprender a usar Wled, consulte [La versión Anterior](https://github.com/exploratec-udd/wled-udd)**

 - Para la programación a través de Arduino IDE, [descargue la aplicación](https://www.arduino.cc/en/software/) y en algunos casos, los [Drivers para ESP 32](https://www.silabs.com/software-and-tools/usb-to-uart-bridge-vcp-drivers?tab=downloads)

$$\color{red}\Huge{\textsf{¡Considerar!}}$$
   
#### El uso de Arduino IDE requiere crear un programa que pueda utilizar este dispositivo por lo que si se desea programar hay que tomar en cuenta los pines que se deseen utilizar para esto mismo.
   
### Conectar Arduino IDE a ESP 32

Para conectar el programa al microcontrolador es necesario descargar desde el mismo el codificador de la placa. Primero, entra en la aplicación en la pestaña de placas.

![imagen]()

luego, busca el nombre "ESP 32" y descargas la opción que posee ese nombre exacto.

![imagen]()
  
### Subir codigo a ESP 32

Para subir el codigo que se desee utilizar en el dispositivo primero es recomendable revisar errores del mismo, esto se hace con el boton de verificar del programa.

![gif]()

Al verificar que este no posee ningún error, se debe conectar la ESP 32 al computador, desde el programa busca en que puerto se encuentra conectado y luego presiona el boton de subir para que se actualize el codigo.

![gif]()


_________________________________

### Hardware

### Para fabricar la version 2.0 de el proyecto Iluminación WLED se requiere de los siguientes componentes:

  * Placa de prototipado ESP 32

  * Placa PCB virgen de al menos 60 x 80 mm

  * Resistencia 1K  Ω y de Resistencia 680 Ω

  * 2 Pin Header Hembra SMT para XBee de 10 pines

  * Socket Circuitos integrados  8 pines

  * Comparador de voltaje LM358

  * Conversor DC-DC Step Down  LM2596

  * 1 Terminal Block de 3.5mm de 3 pines y 5 Terminal Block de 3.5mm de 2 pines

  * 2 Diodos 1N4001

  * Condensador 1000uf 25V

  * Conector barrel jack 5.5

  * 2 Distanciadores M3 20mm + 6mm

  * 8 Inserto M3 y 8 Pernos M3 6mm

  * Carcasa impresa en 3D

### Plano en vista explosiva

![imagen]()

**$$\color{red}\Huge{\textsf{¡Importante!}}$$**

#### Para fabricar el dispositivo es necesario utilizar la maquina de fresado. Para su uso consulte [el siguiente manual](https://github.com/exploratec-udd/othermill-udd)

>documentado por [Sofía Pérez Gutiérrez](https://github.com/ItsPeku) 2026
