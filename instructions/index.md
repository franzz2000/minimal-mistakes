---
layout: page
title: Instrucciones de uso
tags: [instrucciones, infusor, paliativos, medicación]
modified: 2016-03-02T20:53:07.573882-04:00
comments: false
image:
  feature: sample-image-1.jpg
  credit: 
  creditlink: 
---
La aplicación Infusor App está diseñada para que sea sencilla de utilizar.

A pesar de ello tiene diferentes aspectos que hay que tener en cuenta durante su uso, que se explicará en el siguiente apartado.

## Instalación

Primeramente es necesario que descargue la aplicación de la tienda asociada a su móvil. El requisito  necesarios para iOS es tener la versión 9.x o superior y de Android es tener la versión 4.x o superior.

<div>
<div class="codigoQr">
{% include _googleplay.html %}
</div>
<div class="codigoQr">
{% include _appstore.html %}
</div>
</div>

## Uso
El uso de la aplicación es sencillo. Básicamente existen 3 pestañas que recogen la información sobre las características del infusor, la medicación que se quiere utilizar y los resultados del cálculo. En Android las encontramos en la parte superior, en iOS en la inferior de la pantalla. En ambos casos aparecen con un texto y un icono.

<img class="captura" src="{{ site.url }}/images/pestanas_ios.png" alt="Pestañas">

### Infusor

Pulsando sobre el primer icono (Infusor) se pueden introducir datos relacionados con el infusor:

  * Volumen del infusor en ml: Es el volumen total del infusor indicado por el fabricante. Es obligatorio.
  * Flujo del infusor en ml/h: El flujo indicado por el fabricante. Es obligatorio.
  * Factor de corrección: Permite ajustar el volumen según indicaciones del fabricante en caso de utilizar diluyente diferente al recomendado por el fabricante, como suero fisiológico o glucosado. Es opcional.

Con estos datos, la aplicación calcula cuánto tiempo puede funcionar el infusor, teniendo en cuenta cual es la capacidad mínima recomendada y el volumen máximo.

En el último apartado, se ha de especificar el tiempo deseado de funcionamiento del infusor, en días y/u horas. Este tiempo ha de encontrarse dentro del rango de duración indicado. No es necesario que el número de horas sea menor que 24, el programa recalculará automáticamente los datos para ajustarlo a los días. Ejemplo: Si dejamos en blanco los días y añadimos el valor 48 a las horas, el programa entenderá que se quiere utilizar el infusor durante 2 días. Esto lo reflejará en el apartado de resultados.

### Medicamentos

Pulsando sobre el segundo icono (Medicamentos), se pueden introducir los diferentes medicamentos incluidos en la aplicación.

* Para *añadir un medicamento* es necesario pulsar sobre el símbolo + y rellenar los datos solicitados. La dosificación que hay que introducir es la cantidad de medicamento que se quiere administrar en 24 horas (1 día) en las unidades que se indican en el campo.
* Para eliminar un medicamento, hay que deslizar el dedo sobre el medicamento en la lista hacia la izquierda y pulsar sobre el botón de Borrar.
* En caso de querer modificar algún dato de medicamento, primero hay que eliminarlo y luego añadirlo de nuevo con los nuevos datos.

Una vez añadidos los datos, se puede pulsar sobre el botón de Cálculo.

### Cálculo

En este apartado se mostrarán los resultados. Éstos aparecen en diferentes bloques.

* Duración del infusor: Muestra el tiempo de utilización del infusor en días completos y horas 
* Volumen total necesario para que funcione el tiempo asignado
  * Volumen medicamentos: Es el volumen de medicamentos calculado según la presentación de medicamentos utilizada
  * Volumen dilución: Es el volumen que necesitaremos añadir para llegar al volumen total
* Medicamentos: Aparece una lista con el tipo de presentación del medicamento a utilizar y, en verde, el numero de unidades. Si aparece el número en color rojo, entonces indica una fracción de una ampolla. Si el valor es superior a la cantidad de una ampolla, entonces indica que no tenemos suficientes existencias.

El título de un bloque en rojo, nos indica que existe algún problema con los datos. Por ejemplo, que el volumen calculado de medicación sea superior a la capacidad máxima del infusor.

## Menú

En la esquina superior derecha de la aplicación encontramos el icono de menú. En caso de tener una tablet con resolución elevada, el menú aparecerá automáticamente en el lado izquierdo de la pantalla.

En este menú nos encontramos con diferentes opciones:


<img class="captura" src="{{ site.url }}/images/menu.png" alt="Menú">

Las 2 primeras opciones nos permiten resetear los valores de la infusión actual o volver a ella.

La opción de "Existencias" nos permite indicar el número de unidades que tenemos de cada presentación. Por defecto tenemos 100 unidades de cada una. El número de unidades se puede modificar en este apartado, pudiendolas adaptar a la cantidad de medicación que tengamos.

En el apartado de configuración, se podrá cambiar el porcentaje considerado mínimo del infusor (adaptable a las indicaciones de cada fabricante)
