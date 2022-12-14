# 馃弲 Proyecto IoT

<p align="justify">Este notebook utiliza sensores de Grove que miden la temperatura, el nivel de humedad y la luminosidad para crear un invernadero monitorizado para controlar que las plantas tengan las mejores condiciones para vivir. Las condiciones son monitoreadas en el stick LED de Grove y el zumbador de Grove. Se genera una alerta si las condiciones valoradas en conjunto no son las adecuadas. Tambi茅n notifica mediante un correo electr贸nico si una planta est谩 enferma o tiene una plaga.</p>

A continuaci贸n se muestra un video explicativo del proyecto: &nbsp; &nbsp; <a href="https://drive.google.com/file/d/1yOyLGcmgdzOI8c3AalYxPiZ4govED0hD/view?usp=share_link" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/google_drive/google_drive-icon.svg" alt="gcp" width="40" height="40"/> </a>

## 馃挭馃徑 Objetivos:

<p align="justify">Realizar una aplicaci贸n IoT completa basada en el hardware PYNQ-Z2 utilizado durante la desarrollo del tema.</p>

<p align="justify">Este proyecto final conllevar谩 la aplicaci贸n de los conocimientos como son la gesti贸n de sensores, actuadores y displays, la
recopilaci贸n de datos, el an谩lisis de resultados y la interactuaci贸n con el usuario entre otras. El trabajo debe dar como resultado una aplicaci贸n que interact煤e con/para/con los usuarios en cada contexto.</p>

<p align="justify">Los objetivos m铆nimos esperables son:</p>

- <p align="justify">Gesti贸n y uso de m铆nimo 2 sensores/actuadores digitales y anal贸gicos.</p>
- <p align="justify">Uso de interruptores y/o switches de la placa base.</p>
- <p align="justify">Gesti贸n de funcionalidades y estructuraci贸n de estas mediante las librer铆as adecuadas (matplotlib, arduinoseedstudio, numpy, cv2, haar, opencv, ...).</p>
- <p align="justify">Creaci贸n de un 鈥渘otebook鈥? central.</p>
- <p align="justify">Recogida, an谩lisis y representaci贸n de resultados.</p>
- <p align="justify">Interacci贸n con la aplicaci贸n de forma remota (uso de mqtt, suscripci贸n y publicaci贸n en topics, etc.).</p>
- <p align="justify">Documentaci贸n de todo el proyecto.</p>
- <p align="justify">Demostrable para su presentaci贸n y defensa en la fecha de examen.</p>

## 馃梻 Orden de los documentos

<p align="justify">Cada uno de los documentos necesarios para la realizaci贸n del proyecto se encuentran en la parte superior del repositorio. En estas encontraremos 4 archivos:</p>

- <p align="justify">README.md con la informaci贸n necesaria.</p>

- <p align="justify">notebook_plant_monitoring_system.ipynb, proyecto/cuaderno central completo.</p>
    
- <p align="justify">Manual Monitor Invernadero Base Shield V2 Con Sensores De Grove.pdf, Informe que documenta adecuadamente el proyecto y sus resultados. Estructura m铆nima habitual de objetivos, resoluci贸n metodolog铆a, definici贸n y an谩lisis del proyecto, an谩lisis cr铆tico y representaci贸n de resultados obtenidos, documentaci贸n y referencias.</p>
 
- Carpeta "fotos" donde podemos encontrar las imagenes utilizadas para la detecci贸n de enfermedades.

<p align="justify">Adem谩s se adjunta tambi茅n en este README el video explicativo del proyecto comentado anteriormente, en este caso, en una nueva plataforma:</p>

-  <p align="justify"><a href="https://youtu.be/J7LJK8ByvNM" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/youtube.svg" alt="elenamarreroo" height="30" width="40" /></a> Presentaci贸n. Uso de un demostrador in-situ, grabaci贸n de un video para verificar el funcionamiento de la aplicaci贸n desarrollada, acciones remotas, etc.</p>

 ## 馃摉 Referencias
* [Grove water_sensor](https://www.seeedstudio.com/Grove-Water-Sensor.html) 
* [Grove temperature](https://www.seeedstudio.com/Grove-Temperature-Sensor.html) 
* [Grove light_sensor](https://www.seeedstudio.com/Grove-Light-Sensor-v1-2-LS06-S-phototransistor.html) 
* [Grove buzzer](https://www.seeedstudio.com/Grove-buzzer.html)  
* [Grove servo](https://www.seeedstudio.com/Grove-Servo-Sensor.html) 
* [Grove Base Shield V2.0](https://www.seeedstudio.com/Base-Shield-V2.html)   

## 馃攳 脷ltima vez que fue revisado
* 16 Enero 2022
    + Initial version

## 馃懎 Equipazo:

<img src="https://user-images.githubusercontent.com/98991004/200303069-0b484d2e-7935-48ac-b9b0-ba2135e4a0d7.png" align="right" width="200" height="150">

Este proyecto ha sido realizado por: 

- Irina Filimonova Sevcenco
- Elena Marrero Castellano

## 馃搫 Licencia 

Este repositorio est谩 bajo la Licencia (GNU General Public License v3.0) - mira el archivo [LICENSE.md](LICENSE.md) para detalles.
