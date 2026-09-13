**Alexis Adhemar Covarrubias Sánchez**

**2630026**

**Creación y sincronización de repositorios con Git y GitHub**

**Objetivo:** *Crear y sincronizar un repositorio de Git con Github*

*-Para esta practica cree un repositorio local en el que meti 2 archivos con diferentes contenidos, despues vicule el repositorio local con uno en github para subir el commit, posteriormente modifique uno de los archivos desde github, para despues hacer lo mismo desde el repositorio local, finalizando asi la practica.*

|***COMANDOS ULITIZADOS***|***FUNCIÓN***|
|-|-|
|```cd```|*Cambiar de directorio*
|```mkdir```|*Crear una nueva carpeta*
|```git init```|*Crear un repositorio*
|```git branch -M```|*Renombra la rama actual*
|```git status```|*Reviar el estado del repositorio*
|```git add -A```|*Mover los archivos a la zona de staging*
|```git commit -m```|*Crear un commit*
|```git log```|*Revisar el historial de commits del repositorio*
|```git remote add origin```|*Agregar y guardar la dirección de un repositorio remoto*
|```git push origin main```|*Subir los cambios del repositorio local al remoto*
|```git pull origin main```|*Descargar y combinar los cambios recintes del repoitorio remoto con el repositorio local*
|```git push```|*Subir cambios del repositorio local al remoto*

***EXPLICACIÓN:***

1- Para crear el repositorio local primero cree una carpeta en el escritorio, a esta le meti dos archvios diferentes uno ```.txt``` y uno ```.md```, despues cree el repositorio dentro de la carpeta con ```git init```

2- Para vincular el repositorio local con Github, primero en github cree un nuevo repositorio, copie la URL proporcionada y en la terminal use ```git remote add origin``` + URL, con eso vinculando ambos repositorios

3- Habiendo vinculado ambos repositorios use ```git push origin main``` para subir el commit al repositorio remoto

4- En Github, modifique uno de los archivos, para despues en la terminal usar ```git pull origin main``` para descargar y combinar los cambios echos desde el repositorio remoto

5- Desde el repositorio local nuevamente volvi a modificar el mismo archivo, para despues usar ```git push``` para subir las nuevas modificaciónes al repositorio remoto

-Los archivos son un ```.txt``` y un ```.md```, el txt. fue el modificado varias veces desde los diferents repositorios, el .md contiene la explicación de la practica

-En conclusión la practica me parecio buena, sencilla, pero buena para aprender y agilizar el crear y vincular repositorios de Git.


c: