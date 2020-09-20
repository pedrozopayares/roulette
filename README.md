# Roulette

Roulette es un juego de **ruleta** o **win wheel** que consiste en generar un número aleatorio para seleccionar un ganador de un listado que se ha cargado previamente.

## Requirimientos

Esta es una mini aplicación web que funciona en la ventana de un navegador como Google Chrome, Firefox o Safari. No requiere software adicional y la podrás correr sin permisos de seguridad especiales por parte de tu sistema.

## Instrucciones

La aplicación cuenta con tres vistas, que coinciden con los tres momentos más relevantes de su ejecución: Configuración, Ruleta y Lista de Ganadores.


### Configuración
En esta vista se debe establecer el número de rondas o sorteos que se harán en la ruleta. Es un número entero.

También, es necesario cargar la listado de participantes o elementos que pueden ser elegidos aleatoriamente. Estos deben tener un identificador asociado. Por ejemplo, si son personas, estos deben contar con ID que los identifique de manera única, como su número de DNI o cédula de ciudadanía. Esto es para evitar problemas si existen dos registros con el mismo nombre.

En el directorio *data* de la aplicación se encuentra un archivo de prueba que puede ser modificado. El formato debe ser CSV, y se puede editar con Excel o con un editor de texto.

### Ruleta
Este es el sorteo como tal. 

Esta vista cuenta con la imagen de una ruleta y un botón de girar. Esta parte utiliza el plugin WinWheel para crear la animación y generar los números aleatorios. Como la fecha de creación de la aplicación fue hace ya un rato, las versiones de los plugins y scripts de terceros pueden estar desactualizados.

Al completar todas las rondas de los sorteos, el botón Ver listado de ganadores se activará y podrás pasar a la tercera vista de la aplicación.

### Vista de todos los ganadores
En esta vista podrás ver una tabla con el listado de todos los ganadores que fueron seleccionados aleatoriamente del listado cargado previamente.

## Archivos de audio
Los plugins o scripts de terceros utilizados en esta aplicación son:
- jQuery
- Bootstrap
- WinWheel
- PageTransitions


## Archivos de audio
La aplicación cuenta con archivos de audios que de ninguna manera son de mi propiedad y solo se cargan aquí con fines educativos, para mostrar que puedes colocar algunos archivos de sonido para el audio de fondo.

Estos audios solo se activarán después de la primera interacción (click) por parte del usuario de la aplicación.

