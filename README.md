# Framework Foundation

The_tattooed_dragon es el proyecto que sera construido con por medio del framework de Foundation.

Primero que todo para empezar un proyecto con foundation hay que instalr este framework en nuestra conputadora, si tienes windows hay que hacer unos pasos antes de comenzar la instalacion.

-Instala Nodejs LTS.
-Verifica si tienes git.
-Habre la terminal de comandos de **Nodejs** en modo administrador y ejecuta el sig comando.
```
npm install --global --production windows-build-tools
```
De aqui para adelante, podemos escribir los sigientes comados para instalar foundatioin en cualquier sistema operativo.

-Instala el siguinete paquete.
```
npm install --global foundation-cli
```
situate en el lugar donde vas a piner tu proyecto.

-Escribe el sigiente comando para crar la capeta que contendra tu proyecto
```
foundation new
```
El cual arrojara 3 preguntas:

-¿Que quieres construir hoy?
-¿Como se llamara el proyecto?
-¿Que pantallas quieres usar?
**Escoge ZURB Template**


**Nota:** con el comando __npm start__ ejecuta el proyecto para ver como avanza. Con el comando __npm run build__ transpilara tu proyecto a las carpeta dist. Eliminda dist de la lista del archivo .gitignore para ser enviado al repositorio remoto de GitHub.

Cuando quIeras enviar el primer commit a Github deberas enviar hacer los sigientes pasos:

-inicializa git en tu proyecto 

-crea un repositorio remoto en GitGub y copia la direccion SSH

-Conecta tu repositorio local con tu repositorio remoto con este comando:

```
git remote add prod "copia la direccion sin comillas"
```

-Ejecuta el sigiente comando:
```
npm run build
```
puedes borrar el archivo styleguide.html si quieres despuede de haber terminado el comando.

-Asegurate de tener eliminda dist de la lista del archivo .gitignore para ser enviado al repositorio remoto de GitHub.

-Crea el commit

-Envia el commit a GitHub con este comando.

```
git subtree push --prefix dist prod "nombre de la rama sin commilas"
```

