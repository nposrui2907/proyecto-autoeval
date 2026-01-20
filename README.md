Comandos
1º git config --global user.name nposrui2907
2º git config --global user.mail nposrui2907@iesfuengirola1.es
3º git config user.name
4º git config user.mail
5º git init
6º touch index.html
7º touch README.txt
8º touch secreto.txt
9º git add index.html
9º git commit -m "Nestor Postigo Ruiz: Estructura inicial html"
10º git branch incluir-estilos
11º git switch incluir-estilos
12º git add estilos.css index.html
13º git switch master
14º git remote add origin https://github.com/nposrui2907/proyecto-autoeval.git
15º git push -u main
16º git pull origin main
17º 

Preguntas
==================================================
1. ¿Para qué sirve el comando git init?¿Qué carpeta oculta se crea automáticamente para rastrear los cambios?.
para crear un repositorio en git, se crea una carpeta llamada .git
2. ¿Qué comando has usado para confirmar que tu identidad es la correcta antes de empezar?
git config user.name
git config user.mail
==================================================
1. ¿Por qué es importante el uso de .gitignore en proyectos profesionales?
Ya que te permite ignorar archivos que no van a ser cambiados y al hacer status/commits de archivos con nombres parecidos no dar problemas
2. Si un archivo está "preparado" (staged), ¿en qué área de Git se encuentra y cuál es el comando para ver esta diferencia antes de confirmar?.
Está en el área de preparacion, y se puede ver con git status
==================================================
1. ¿Qué ocurre con los archivos de tu carpeta local cuando saltas de una rama a otra? 
Es una pregunta muy buena XD supongo que se crea un registro con los archivos/info del main cuando estás en la rama secundaria y biceversa
2. ¿Cuál es la principal ventaja de trabajar con ramas independientes en lugar de hacer todo en la rama main?.
tenerlo todo mejor ordenado/administrado además de que al fusionar los cambios es más facil ver errores/incompatibilidades.
==================================================
1. Al clonar un repositorio, ¿qué nombre recibe por defecto el servidor remoto en nuestra configuración local?.
El nombre del repositorio
2. ¿Qué comando usarías para ver la URL del servidor remoto que acabas de configurar?
git remote -v
==================================================
1. ¿Qué comandos has utilizado para comprobar si el repositorio local está actualizado? 
Ni idea he accedido desde vscode
2. ¿Cuál es la diferencia fundamental entre ejecutar un git fetch y git pull según lo que acabas de experimentar?.
el fetch es como fusionar lo que está en github con tu repositorio local y el pull es sobreescribir lo del local con lo de github
==================================================
