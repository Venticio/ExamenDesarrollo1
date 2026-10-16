# SAVIA — examen N.º 1

Proyecto estático HTML + CSS. Abrir `index.html` en el navegador. No necesita dependencias.

El sitio incluye la página Inicio y las plantillas `pages/menu.html`, `pages/equipo.html` y `pages/eventos.html` con contenido central pendiente. Siga exclusivamente las especificaciones del examen para conocer el comportamiento esperado. No modifique el tema general ni sustituya el proyecto por otro.

## Diagnóstico de cinco incidencias

| N.º | Comportamiento observado | Causa técnica y ubicación | Corrección realizada | Prueba de verificación | Autor |
|---|---|---|---|---|---|
| 1 | ![Evidencia Incidencia 1](image.png)| ![Causa en el css, esta en column](image-1.png)| ![Cambiado a row](image-2.png)|![Prueba de como se visualiza con row](image-3.png) | Cambio detectado y hecho por Arwy|
| 2 |Boton de nuestra carta lleva a eventos, y faltan los botones|El href era incorrecto y faltan los botones en index.html|Se corrigio el href y se añadieron los botones |Se observa al ejecutar la pagina|Vinicio| 
| 3 |![Como se ve en el link al presionar, marca un #, no hay buen direccionamiento](image-4.png) | ![Como se observa, el direccinoamiento es hacia # en efecto](image-5.png)|![Se creo el direccionamiento hacia pages/menu.html](image-6.png) |![Al dar click en el boton, el link cambia y direcciona a menu](image-7.png) |Arwy|
| 4 |![Como se ve el boton en rojo](image-4.png) | ![Ubicacion de la incidencia solucionada](incidencia4.png)|Por medio de la etiqueta del id se cambio el fondo|El boton se observa de diferente color |Vinicio |
| 5 |![Al verse en 375 de ancho, los links se salen y permite desplazamiento incorrectamente](image-8.png) |![En el css no existia un media para el 375 de ancho](image-9.png) |![Se agrego el media de 375 para que sea el maximo y de ahi para abajo se vea correctamente](image-10.png) |![Asi esta ya corregido](image-11.png) |Arwy|

## Responsables de las funcionalidades

| Estudiante | Página asignada | Rama | Commits principales |
|Vinicio Castro Gonzalez|C01894|Equipo|ramaf2| Agregado el feature 2 a develop|
|Arwy Zamora Segura - C28616 | Menu | ramaf1 | "Agregadas las imagenes, css y hecho el menu de la pagina menu.html" y tambien "Merge pull request #8 Feature 1 completa "|

## Evidencias Git

| Funcionalidad/corrección | PR hacia develop | Revisor | Resultado de merge / conflicto si ocurrió |
|---|---|---|---|
| | | | |

## Verificación final
Registrar las pruebas de funcionamiento a 1280 px y 375 px, enlaces y páginas.




(Commit para crear main)
(Commit para crear branches principales incluyendo develop)