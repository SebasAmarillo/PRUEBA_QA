Angel Sebastian Amarillo Delgado.

# <p align="center"> **PRUEBA AUTOMATIZADA CON CYPRESS** </p>
______
<p style="text-align: justify;">1. Se debe descargar el archivo comprimido frontend-cypress.zip y descomprimirlo en una carpeta del ordenador, se debe contar con los siguientes prerrequisitos para continuar con la ejecución: </p>

- Tener instalado Visual Studio Code.
- Tener instalado Cypress.
- Tener instalado Node.js.

<p style="text-align: justify;">2. Luego de descomprimir la carpeta abrimos Visual Studio Code y abrimos la carpeta donde podemos visualizar los archivos gmail.cy.js y logindemo.cy.js los cuales son los que debemos ejecutar para ver la prueba a realizar, ver la siguiente imagen: </p>

<p align="center">
  <img src="/Frontend_Cypress/Imagenes/archivos.png">
</p>

<p style="text-align: justify;">3. Ahora debemos ejecutar el comando npx cypress open en la terminal de Visual Studio Code con el fin de abrir la interfaz gráfica de Cypress para su ejecución, ver imagen: </p>

<p align="center">
  <img src="/Frontend_Cypress/Imagenes/coman_consol.png">
</p>

<p style="text-align: justify;">Se abrirá la siguiente pantalla donde debemos seleccionar la opción E2E Testing, ver imágen: </p>

<p align="center">
  <img src="/Frontend_Cypress/Imagenes/e2etesting.png">
</p>

<p style="text-align: justify;">Se abrirá una pagina en el navegador seleccionado de nuestra preferencia y podemos ver que se encuentran los archivos de gmail.cy.js y logindemo.cy.js, los cuales vamos a ejecutar, ya para su ejecución solo falta seleccionar alguno de los dos, ver imagen: </p>

<p align="center">
  <img src="/Frontend_Cypress/Imagenes/navegador_e2e.PNG">
</p>

### <p align="justify"> **Ejecución Login en Gmail** </p>

<p style="text-align: justify;">4. Primero haremos la prueba de Gmail la cual consiste en hacer un login en la pagina de Gmail, damos clic en el archivo y vemos como se ejecuta, ver imagen: </p>

<p align="center">
  <img src="/Frontend_Cypress/Imagenes/ejecucion_gmail.PNG">
</p>

<p style="text-align: justify;">Al lado izquierdo de la pantalla podemos ver el paso a paso de la ejecución de la prueba, ver imagen: </p>

<p align="center">
  <img src="/Frontend_Cypress/Imagenes/resultado_gmail.png">
</p>

### <p align="justify"> **Ejecución Login en Demo** </p>

<p style="text-align: justify;">5. Ahora haremos la prueba de login en el demo de la pagina orangehrm, damos clic en el archivo y vemos como se ejecuta, ver imagen: </p>

<p align="center">
  <img src="/Frontend_Cypress/Imagenes/ejecucion_demo.PNG">
</p>

<p style="text-align: justify;">vemos como realizo su login de forma exitosa, ver imagen: </p>

<p align="center">
  <img src="/Frontend_Cypress/Imagenes/exitoso_demo.PNG">
</p>

<p style="text-align: justify;">Al lado izquierdo de la pantalla podemos ver el paso a paso de la ejecución de la prueba, ver imagen: </p>

<p align="center">
  <img src="/Frontend_Cypress/Imagenes/resultado_demo.png">
</p>
