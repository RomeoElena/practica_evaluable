<h1 align="center">Entornos de Desarrollo</h1>

<p align="center">
  <img src="https://codingnomads.co/wp-content/uploads/2021/02/how-to-use-github-git-tutorial-website-featured-image.png" alt="GIT & GITHUB">
</p>



<h2 align="center">Descripción del Ejercicio</h2>

La práctica evaluable se enfoca en familiarizarnos con Git y GitHub. Iniciamos creando un repositorio local llamado practica_evaluable y realizando diversos documentos para el manejo de comandos, desde la creación de archivos hasta el trabajo con ramas y repositorios remotos.


<h2 align="center">Resumen de Comandos entre git y github:</h2>

### 1. Configuración Inicial
- `git init`: Inicia un nuevo repositorio Git.
- `git config --global user.name "Tu Nombre"`: Configura el nombre de usuario.
- `git config --global user.email "tu@email.com"`: Configura la dirección de correo electrónico.

### 2. Gestión de Archivos
- `git add .`: Añade todos los archivos al área de preparación.
- `git commit -m "Mensaje de commit"`: Realiza un commit con un mensaje descriptivo.
- `git reset nombre_del_archivo.txt`: Revierte cambios en un archivo específico.

### 3. Trabajo con Ramas y Repositorio Remoto
- `git branch nombre-de-la-rama`: Crea una nueva rama.
- `git checkout nombre-de-la-rama`: Cambia a una rama existente.
- `git merge nombre-de-la-rama`: Fusiona cambios de una rama a otra.
- `git remote add origin URL-del-repositorio`: Conecta el repositorio local con el remoto en GitHub.
- `git push -u origin nombre-de-la-rama`: Sube los cambios al repositorio remoto.

### 4. Etiquetas y Clonado
- `git tag -a V1 -m "Versión 1"`: Crea una etiqueta.
- `git clone URL-del-repositorio practica_evaluable_2`: Clona un repositorio remoto a un nuevo directorio local.

### 5. Conflictos y Fusiones
- `git revert HEAD`: Revierte el último commit.
- `git pull origin nombre-de-la-rama`: Obtiene cambios del repositorio remoto.
- `git branch -d nombre-de-la-rama`: Borra una rama local.
- `git push origin --delete nombre-de-la-rama`: Borra una rama en el repositorio remoto.
- `git merge nombre-de-la-rama`: Fusiona una rama con la rama actual.

### 6. Añadiendo un README y Sincronización Final
- `git push origin --tags`: Sube las etiquetas al repositorio remoto.
- `git checkout -b nombre-de-la-rama`: Crea y cambia a una nueva rama.
- `git push origin nombre-de-la-rama`: Sube una nueva rama al repositorio remoto.

### 7. Trabajo con Archivos
- `rm nombre_del_archivo.txt` o `del nombre_del_archivo.txt`: Elimina un archivo no rastreado.
- `git rm nombre_del_archivo.txt`: Elimina un archivo rastreado.
- `git rm --cached nombre_del_archivo.txt`: Elimina un archivo del área de trabajo, pero lo mantiene en el historial.

### Otros Comandos
- `git log --oneline`: Muestra la historia de commits.
- `git status`: Muestra el estado actual del repositorio.
- `git fetch`: Obtiene cambios del repositorio remoto sin aplicarlos.
- `git tag`: Muestra las etiquetas existentes.
<p align="center">
  <img src="https://images.unsplash.com/photo-1608389168343-ba8aa0cb3a63?q=80&w=500&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" alt="Thanks!">
</p>

