# Automation-Estructura Base
Automation-Estructura Base

## Abrir dos ventanas independientes de Visual Studio Code.

# Fase 1:

## Paso 1: Crear el repositorio vacio de nuestro nuevo proyecto en Github.
## Paso 2: Clonarlo en la primera ventana de Visual Studio Code y ubicarlo en la ruta donde lo deseamos. Hasta aqui tendremos solo el Readme.


## Fase 2:

## Paso 1: Clonar el presente repositorio en la segunda ventana de Visual Studio Code y ubicarlo en otra ruta diferente a la de nuestro nuevo proyecto.
## Paso 2: Copiar todo el contenido del presente repositorio (Paso anterior) menos el Readme y la carpeta .git.
## Paso 3: Pegar lo que acabamos de copiar en la ruta de nuestro nuevo proyecto y ya apareceran en la primera ventana de Visual Studio Code.
## Paso 4: Ir a packeage.json y cambiar el nombre del proyecto (solo letras minusculas y sin espacios. ej: automation-abercrombie) y cambiar la descripcion.
## Paso 5: Limpiar dependencias con el comando 
                  powershell: Remove-Item -Recurse -Force node_modules
                  gitbash: rm -rf node_modules
## Paso 6: Instalar dependencias con el comando: npm install
## Paso 7: Cambiar la URL base en el archivo: cypress.config.js
## Paso 8: Guardar todos los cambios (Save All).
## Paso 9: Correr Cypress y debe pasar la prueba inicial.
## Paso 10: Hacer el Commit inicial.
## Paso 11: Desarrollar el proyecto.








