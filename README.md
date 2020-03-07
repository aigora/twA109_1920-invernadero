# Mini Invernadero Inteligente

Este proyecto consistirá en un pequeño invernadero en el que el usuario podrá observar sus variables de humedad, temperatura y luminosidad, además de poder variarlas, de forma que las plantas de su interior estén en las condiciones óptimas.

## Integrantes del equipo

Jaime Pérez Calvo, 
Cristina Trapero Giles, @ctgiles

## Objetivos del trabajo

Los objetivos previstos son, como hemos dicho antes, observar y controlar las funciones de un invernadero para cuidar adecuadamente de las plantas que tiene en su interior. Para ello, por un lado, se utilizará una serie de sensores que recojan la humedad, la temperatura y la luminosidad. 
Para medir la temperatura, utilizaremos un sensor propio para ello; para la humedad un sensor que la mide directamente de la tierra de las plantas; y para medir la luminosidad, pensamos utilizar un sensor LDR o parecido. Se baraja acompañar los resultados de las mediciones con una salida en pantalla en la urna, no solo en la pantalla del ordenador. 
Por otro lado, una vez recogidos los datos, se controlarán las variables mencionadas antes, es decir, si necesita más temperatura, se pondrá en marcha una resistencia calefactora (que requiere de una fuente de 12 V externa y, por consecuente, un relé), si necesita menos, se pondrá en marcha un ventilador (la posición no tiene que ser la del esquema, se buscará cual es la mejor para que cumpla su función de disminuir la temperatura). Para la luz, se utilizará un sistema de leds si la luz natural no fuese suficiente. Por último, para la humedad se utilizará un control de bombeo de riego (vienen los kits completos). 

## Hardware previsto: 

Se pretende utilizar el PC, desde donde se programará una placa Arduino. No hemos pensado en utilizar ninguna APP para el móvil, pero no descartamos que según avance el proyecto veamos conveniente introducirla.

## Software previsto:

El lenguaje de programación será C, no sabemos aún si compilarlo con DevC++ o con la propia plataforma de Arduino.
