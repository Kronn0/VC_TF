
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
 * [Inserte Imagen]
 Los controles son los siguientes:

* [Inserte Imagen de apuntando hacia arriba]
Este es el gesto para que el ratón le siga el dedo índice.

* [Inserte imagen de Ok izquierdo]
Este gesto es para clickear el ratón con el botón izquierdo. Puede mantener este gesto si quieres hacer un click mantenido y mover el ratón 

* [Inserte imagen de Ok derecho]
Este gesto es para clickear el ratón con el botón derecho.



