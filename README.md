# EXAMEN DESPLIEGE


1º Paso CREACIÓN BASE DE LAS RAMAS PRINCIPALES DEL PROYECTO

- Creación de un directorio en local
- Iniciar un proyecto con "git init"
- Creación de README.md
- Commit para que la rama main tenga contenido
- Crear un repositorio remoto al que subir el proyecto y hacer colaborador a mi otro yo
- Subida del proyecto a GitHub con "git remote add origin git@github.com:Cristina2M/examen-despliege.git"
- Subir a remoto la rama main con "git push -u origin main"
- Crear la rama develop con "git checkout -b develop"
- Subir a remoto la rama develop "git push -u origin develop"


2º paso ESTRUCTURA BÁSICA DEL PROYECTO

- Creación del directorio src (sin contenido, el contenido lo hace mi otro yo)
- Creación del package.json con "npm init -y" y se configuran los scripts
- Creación del archivo .gitignore
- Creación de la estructura para el workflow
- Creación de la estructura para los tests
- No se crea la carpeta docs, se genera con el comando "npm run build-docs"

3º paso MI OTRO YO CLONA EL REPOSITORIO
- Clono el repositorio "git clone git@github.com:Cristina2M/examen-despliege.git"
- Me traigo todas las ramas y creo la de feature "git fetch --all"   "git checkout deploy"   "git checkout -b feature/NOMBRE-DEL-ARCHIVO"    "git push -u origin feature/NOMBRE-DEL-ARCHIVO"
- Creo los archivos de src, cada uno en un feature diferente
- Voy creando Pull Request de cada feature hacia develop (NO HACIA MAIN, MAIN NO SE TOCA)
- Si no hay conflictos, se aceptan los Pull Request

4º paso CREACIÓN TESTS Y ACTION
- Creo el test para app.js
- Creo el contenido de ci.yml en el que verifica que haya js, realiza los tests y después genera la documentación
  

### URL PROYECTO DESPLEGADO
https://cristina2m.github.io/examen-despliege/src/