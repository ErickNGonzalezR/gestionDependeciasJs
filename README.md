# Gestión de Paquetes y Dependencias en JavaScript
## Iniciación de un proyecto con npm
- Da instrucciones cuando lo inicializamos, que nos permite construir la base del proyecto generando un archivo llamado package.json

        npm init
    
- Crea el archivo package.json sin las preguntas del anterior comando

        npm init -y
    
## Instalación de dependencias 

        npm install moment 

- Es una herramienta que funciona para validad que el código cumpla con un estándar no suele ser utilizada en producción
        
        npm install eslint

- Es una herramienta que funciona para validad que el código cumpla con un estándar lo cual la va a guarda como una dependencia que solamente va a ser utilizada en el entorno de desarrollo y nunca va a ser llevada a producción 

        npm install eslint --save-dev

###        
    npm install eslint -D

- Para instalar dependencias que se van a llevar a producción

        npm install react 
###
    npm install react -S
###
    npm install react --save

- Para ver los paquetes que tenemos instalados en el proyecto

        npm list
    
- Para instalar de forma opcional una dependencia se utiliza -o   

      npm install eslint -o
   
- Para instalar una version en particular de una dependencia  (hay que saber la version que se quiere instalar) @version 

      npm install json-server@0.16.0 

- Para instalar la version mas reciente de una dependencia

      npm install json-server@latest
    
- Para instalar las dependencias que se a clonado de internet

      npm install 

### Para validar que una dependencia no tenga conflicto con las dependencias que ya están instaladas 
    
- Simula una inhalación pero sin instalar nada en el proyecto 

      npm install react-dom --dry-run 

### Para instalar paquetes globales en nuestro pc
        
        npm install-g nombrePaquete

- Para ver que paquetes tenemos instalado de forma global

        npm list -g

## Como correr comandos 
 1. Entramos a package.json
 2. Buscamos donde dice Scripts

        "scripts": {
            "test": "echo \"Error: no test specified\" && exit 1"
            "start":"node src7index.js"
        },
-
