#    Practica 1 GIT: Inicio 
Para el correcto desarrollo de esta práctica se debe rellenar sobre esta plantilla el desarrollo de cada pregunta con capturas sobre el comando realizado y evidencias.

También se deberá entregar el link al repositorio.
###  Clonar repositorio externo
###  Creación de repositorio local

## 1.-Clonar repositorio externo

1. En un terminal posicionaros donde se creará el directorio del proyecto.
2. Clonad el proyecto de la libreria Jquery que lo mantiene en github.
* https://www.github.com/jquery/jquery.git
    Para ello usaremos el comando "git clone https://www.github.com/jquery/jquery.git"
![captura clone](img/1.png)
3. Entrad en el directorio creado (jquery) y mostrad un log de los estados por los que ha pasado el proyecto.
    Usaremos el comando "git log" para ver una lista de los estados del proyecto
![captura log](img/2.png)

## 2.-Crear un repositorio local

1. Cread un directorio donde vamos a empezar el proyecto y acceder a él.
    Creamos el directorio y nos situamos en él
2. Inicializad el repositorio 
    Usamos el comando "git init" para inicializar el repositorio
    ![git init](img/3.png)
3. Cread un primer archivo "archivo1.txt"
    En la consola usamos el comando "echo "CONTENIDO_DEL_ARCHIVO" > archivo1.txt"
    ![crear archivo](img/4.png)
4. Visualizad el estado del proyecto
    Usamos el comando "git status"
    ![status](img/5.png)
5. Pasad el archivo del espacio de trabajo a la zona de preparación.
    Usamos el comando "git add NOMBRE_DEL_ARCHIVO"
    ![add](img/6.png)
6. Visualizad de nuevo el estado del proyecto
    Hacemos "git status" para ver el estado.
    ![status](img/6.png)
7. Realizad el primer commit y visualizad de nuevo el estado del proyecto.
    Usamos "git commit -m "COMENTARIO""
    ![commit](img/6.png)
8. Cread dos archivos más al proyecto. "archivo2.txt" y "archivo3.txt"
    Creamos los archivos con "echo" 
    ![echo](img/8.png)
9. Pasad el segundo archivo a la zona de preparación.
    Pasamos el archivo a la zona de preparación con "git add"
    ![add2](img/9.png)
10. Haced Segundo commit del proyecto.
    Usamos el comando "git commit -m "COMENTARIO""
    ![commit2](img/10.png)
11. Añadid el ultimo archivo a la zona de preparación y realizad el commit.
    Lo mismo, hacemos "git add archivo3.txt" seguido de "git commit -m "COMENTARIO""
    ![commit 3](img/11.png)
12. Mostrad el log de todos los cambios.
    Usamremos el comando "git log"
    ![log](img/12.png)
13. Cambiad el archivo "archivo1.txt" y verificad el estado de git.
    Vamos a cambiar el contenido con el comando "echo "CUALQUIER_TEXTO" >> archivo1.txt". Usamos "git status para ver el estado del proyecto", vemos que sale en rojo (modified).
    ![status](img/13.png)
14. Pasad el archivo a la zona de preparación.
    Usamos "git add archivo1.txt"
    ![git add](img/14.png)
15. Modificad los archivos 2 y 3 del proyecto. Verificad estado del git.
    Modificamos los archivos como hemos hecho antes con archivo1.txt. hacemos "git status". Vemos que archivo1 está en verde (staging) y archivo 2 y 3 en rojo (modified)
    ![status](img/15.png)
16. Pasad los archivos 2 y 3 a la zona de preparación.
    Usaremos el comando "git add archivo2.txt archivo3.txt"
    ![add](img/16.png)
17. Realizar el commit de los cambios realizados.
    Usaremos el comando "git commit -m "COMENTARIO""
    ![commit](img/17.png)
18. Mostrad el log de todos los cambios.
    Usamos "git log", vemos los estados por los que ha pasado el proyecto. 
    ![log](img/18.png)


