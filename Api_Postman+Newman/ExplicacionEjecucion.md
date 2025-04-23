Angel Sebastian Amarillo Delgado.

# <p align="center"> **PRUEBA AUTOMATIZADA CON POSTMAN+NEWMAN** </p>
______
<p style="text-align: justify;">La ejecución de esta prueba será de un api con el fin de crear, modificar, consultar y eliminar un usuario.</p>

<p style="text-align: justify;">1 Se debe descargar los archivos Automation.postman_environment.json y PruebaTecnica.postman_collection.json, luego guardar los dos en una carpeta del ordenador, se debe contar con los siguientes prerrequisitos para continuar con la ejecución: </p>

- Tener instalado POSTMAN.
- Tener instalado Newman.
- Tener instalado Newman con HTML EXTRA.

<p style="text-align: justify;">Si no cuenta con Newman ni html extra instalado puede hacerlo ejecutando los siguientes comandos desde la terminal</p>

- npm install -g newman
- npm install -g newman-reporter-htmlextra

<p style="text-align: justify;">2. Luego debemos abrir una terminal en la ubicación donde tenemos los archivos descargados anteriormente y ejecutar el siguiente comando: </p>

- newman run PruebaTecnica.postman_collection.json -e Automation.postman_environment.json

<p style="text-align: justify;">Después de ejecutar el comando podemos visualizar en la terminal el resultado de la ejecución de la prueba, mostrando la cantidad de request e interacciones enviadas, de igual forma muestra un cuadro con el resumen de las pruebas éxitos y fallidas si hubo, ver imagen: </p>

### <p align="justify"> **Ejecución en terminal** </p>

<p align="center">
  <img src="/Api_Postman+Newman/Imagenes/ejecucion.PNG">
</p>

<p style="text-align: justify;">3 Ahora realizaremos la ejecución, pero realizando un reporte con html extra, para ello debemos ejecutar el siguiente comando: </p>

- newman run PruebaTecnica.postman_collection.json -e Automation.postman_environment.json -r htmlextra

<p style="text-align: justify;">Luego de ejecutar el comando, en la carpeta donde se encuentran los archivos se crea automáticamente una carpeta nombrada Newman que en su interior cuenta con el reporte html, ver imagen: </p>

<p align="center">
  <img src="/Api_Postman+Newman/Imagenes/report.PNG">
</p>

<p style="text-align: justify;">Al abrir el reporte HTML encontramos un apartado de resumen, total request, pruebas fallidas y prueba omitida, acá también podemos encontrar los respectivos request y response de cada prueba, realmente es un reporte muy completo con la información de la ejecución de la prueba, ver imagen: </p>

### <p align="justify"> **Reporte HTML** </p>

<p align="center">
  <img src="/Api_Postman+Newman/Imagenes/html.PNG">
</p>

<p align="center">
  <img src="/Api_Postman+Newman/Imagenes/html1.PNG">
</p>

<p align="center">
  <img src="/Api_Postman+Newman/Imagenes/html2.PNG">
</p>

<p align="center">
  <img src="/Api_Postman+Newman/Imagenes/html3.PNG">
</p>

<p style="text-align: justify;">De esta forma podemos ver una ejecución de una prueba de api automatizada desde POSTMAN con NEWMAN</p>

### <p align="justify"> **Muchas gracias** </p>
