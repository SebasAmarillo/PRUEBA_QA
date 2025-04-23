Angel Sebastian Amarillo Delgado.

# <p align="center"> **PRUEBA AUTOMATIZADA CON POSTMAN+NEWMAN** </p>
______
<p style="text-align: justify;">1 Se debe descargar los archivos Automation.postman_environment.json y PruebaTecnica.postman_collection.json, luego guardar los dos en una carpeta del ordenador, se debe contar con los siguientes prerrequisitos para continuar con la ejecución: </p>

- Tener instalado POSTMAN.
- Tener instalado Newman.
- Tener instalado Newman con HTML EXTRA.

<p style="text-align: justify;">Si no cuenta con Newman ni html extra instalado puede hacerlo ejecutando los siguientes comandos desde la terminal</p>

- npm install -g newman
- npm install -g newman-reporter-htmlextra

<p style="text-align: justify;">2. Luego debemos abrir una terminal en la ubicación donde tenemos los archivos descargados anteriormente y ejecutar el comando siguiente comando: </p>

- newman run PruebaTecnica.postman_collection.json -e Automation.postman_environment.json

<p style="text-align: justify;">Después de ejecutar el comando podemos visualizar en la terminal el resultado de la ejecución de la prueba, mostrando la cantidad de request e interacciones enviadas, de igual forma muestra un cuadro con el resumen de las pruebas éxitos y fallidas si hubo, ver imagen: </p>

<p align="center">
  <img src="/Api_Postman+Newman/Imagenes/ejecucion.PNG">
</p>


