# Automation-Estructura Base
Automation-Estructura Base

## Paso 1: Crear el repositorio vacio en Github.
## Paso 2: Clonarlo en Visual Studio Code y ubicarlo en la ruta donde lo deseamos.
## Paso 3: Ir a packeage.json y cambiar el nombre (solo letras minusculas y sin espacios. ej: automation-abercrombie) y cambiar la descripcion.
## Paso 4: Limpiar dependencias con el comando 
                  powershell: Remove-Item -Recurse -Force node_modules
                  gitbash: rm -rf node_modules
## Paso 5: Instalar dependencias con el comando: npm install
## Paso 6: Cambiar la URL en el archivo: cypress.config.js
## Paso 7: Guardar todos los cambios (Save All).
## Paso 8: Correr Cypress y debe pasar la prueba inicial.
## Paso 9: Desarrollar el proyecto.
