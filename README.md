
# Trabajo Final de VC

Este proyecto es el trabajo final del grupo 24, consiste en un programa que hace seguimiento de tus manos para poder controlar el ratón remotamente. En este readme se explicará la instalación y como utilzar el programa

[Instalación](#instalacion)
[como usar el programa](#comousar)

## instalacion

<a name="instalacion"></a>

para utilizar el programa hay que instalar un environment de python 3.11.5 e instalar las siguientes librebrias

``` 
pip install opencv-python

pip install mediapipe

pip install mouse

pip install pyautogui

pip install pygame 
```
Una vez abierto el programa tendrá que ejecutar ``proyecto_final.ipynb`` con el environment creado. 

## Como usar el programa

<a name="comousar"></a>

Una vez instalado otro, lo único que tenemos que hacer es ejecutar todas las celdas. Se abrirá una ventana con la primera cámara que detecte, si se le habré una cámara con la que no este conforme busque la siguiente linea en el codigo 
``` video  =  cv2.VideoCapture(0)```
Y vaya subiendo el número ``0`` hasta encontrar la cámara que desea.
Una vez que se vea usted en la cámara extienda la mano hasta que se detecte la mano como se ve en la siguiente imagen
 * ![image](https://github.com/Kronn0/VC_TF/assets/92724148/aa85aa25-1ce9-4cd7-808e-14022581b3e4)



 Los controles son los siguientes:

* ![image](https://github.com/Kronn0/VC_TF/assets/92724148/689a620a-6765-47db-8e99-0e096a3f980b)



Este es el gesto para que el ratón le siga el dedo índice.

* ![image](https://github.com/Kronn0/VC_TF/assets/92724148/fb0a0970-4dd8-4b79-8f55-43fa6a415aa0)


Este gesto es para clickear el ratón con el botón izquierdo. Puede mantener este gesto si quieres hacer un click mantenido y mover el ratón 

* ![image](https://github.com/Kronn0/VC_TF/assets/92724148/85fe74bb-4495-4bf8-a6b3-9e75b5771aae)


Este gesto es para clickear el ratón con el botón derecho.

* ![image](https://github.com/Kronn0/VC_TF/assets/92724148/963b582b-9f62-4972-9f9c-6fafec63e931)

Para apretar el botón izquierda de flechas

* ![image](https://github.com/Kronn0/VC_TF/assets/92724148/0e88821e-fa1e-4f4a-9ca8-392900b75718)

Para apretar el botón derecho de flechas





