# Ajedrez-en-tiempo-real
Construir su propio juego de varios jugadores de ajedrez usando Socket.io siguiendo los pasos de este laboratorio.



En este laboratorio, vamos a hacer un juego de ajedrez multijugador que, cuando sus movimientos se muestran en la pantalla de tu oponente en tiempo real. Instantáneamente!

# Descripción general de laboratorio
# Objetivos de aprendizaje

Después de completar los ejercicios de esta práctica de laboratorio, usted será capaz de:

- Crear una aplicación web Node.js, ejecutar y depurar de forma local
- Crear un servidor de base Socket.io
- Publica tu servidor en Azure desde GitHub

Tiempo estimado para completar esta práctica: 60 minutos

# Requisitos previos de software

Con el fin de completar el laboratorio, se necesita lo siguiente pre-requisitos

- Windows 10, Mac OS 10 Yosemite, o Linux
- Código Visual Studio
- Node.js

# cuentas en línea de requisitos previos

Con el fin de completar el laboratorio, se necesitan los siguientes requisitos previos cuentas en línea

- Cuenta de Microsoft - necesarios para utilizar Microsoft Azure
- Microsoft Azure suscripción - Una versión de prueba es suficiente
- GitHub - necesarios para implementar código para Azure

# Una nota sobre el uso de pasos completados

Este laboratorio contiene el código para cada uno de los pasos completados abajo. Siéntase libre de ver o utilizar el código de los pasos si se pierde o necesita ayuda. Si reemplaza el código de uno de los pasos, o se salta algunos pasos, tendrá que instalar los paquetes dependencias nodo para ese paso. Este paso no es necesario si la están siguiendo, junto con los siguientes pasos

 > npm install

# Ejercicio 1: Crear una aplicación de nodo y ejecutarlo localmente

# Guía 
Vamos a crear una aplicación web Node.js básicos que sirve algunos de contenido HTML utilizando el marco Express y ejecutarlo localmente.

# Crear la carpeta del proyecto

1.Abra el símbolo del sistema Node.js de la barra de tareas o mediante su búsqueda en Inicio.

![Alt text](https://github.com/dwcares/RealTimeWeb-HOL/blob/master/Images/1.png "Optional title")

2.Hacer una nueva carpeta llamada ajedrez que contendrá nuestro código fuente y navegar hacia él

> mkdir chess
> cd chess

3.Después de crear la carpeta, ahora lo que necesita para crear los metadatos paquete para su aplicación nodo. Este archivo incluirá toda la decencia de proyectos.

> npm init

4.Esto le guiará a través de un tutorial, mantenga los valores predeterminados excepto nombre de su archivo app.js

![Alt text](https://github.com/dwcares/RealTimeWeb-HOL/blob/master/Images/2.png "Optional title")
       Nota: El archivo debe ser nombrado app.js o server.js para ejecutarse en Azure.
