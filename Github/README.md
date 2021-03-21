# CIS311 : Actividades en Ciencias Sociales
## Sesión 1 : Cómo utilizar Github

### Antes de empezar, asegúrense de tener lo siguiente!

1. Ya tienen una cuenta en Github ? Si no, crea una en https://github.com/join (Bonus: si usan su email @pucp, postulen a https://education.github.com/students para obtener una cuenta Pro)
2. Mándame tu nombre de usuario a csolisu@pucp.edu.pe
3. Ya tienes instalado Github Desktop ? En caso no lo tengas, ve a https://desktop.github.com/ e instálalo. 
4. Has iniciado sesión en Github Desktop? En caso no, inicia sesión con tu cuenta creada. 
5. Has sido invitadx al repo https://github.com/CIS311-PUCP/letras_canciones
6. Has aceptado la invitación al repo ? 
7. Tienen un editor de texto instalado ?  
7.1 En windows, puede ser notepad, en mac, el textedit 
7.2 En general, el mejor editor de texto es Sublime https://www.sublimetext.com/

### Cómo usar Github

Los objetivos de aprendizaje de hoy serán:

- Explorar un proyecto de Github y ver en qué contribuyen los otros miembros. 
- Descargar un repo de Github y que tú puedas trabajar en este. 
- Crear un espacio en el repo del proyecto en el que tú puedas trabajar. 
- Realizar cambios y mejoras al proyecto, y poder subir esos cambios. 
- Crear mi propio proyecto!

### Qué es un contribuidor? 

>> Básicamente alguien que contribuye con código a un repositorio (repo). 
Entiende y sigue instrucciones del administrador del repo.  


- Github contribuye a solucionar el problema del "Documento_Final.docx".

<img src="./img/phdcomics.png" alt="drawing" width="400" />

- E inclusive del "Documento_final_final_finalisimo.docx"

- Nuestra solución común es llamar al documento 
    - Paper_for_review_csu_200321.docx
    - Paper_for_review_csu_200321_ae_comments.docx

- Github trackea no solo las iniciales y la hora, sino cada edición hecha al documento. 

>> OJO: github no lee archivos binarios (o archivos que no sean texto)

- Github también soluciona: 
    - Problemas de copia conflictiva (Dropbox, etc)
    - No puedo reproducir los resultados de mi tesis
    - Quién escribió esto hace muchos anios

Los conceptos que manejaremos hoy son 3: 

## 1. Clone (clonar)

Clonar es similar a descargar un repositorio. 
La diferencia entre clonar y descargar es que **Github recuerda de dónde descargamos el repositorio**. Esto es necesario para saber a dónde mandar nuestros cambios cuando seamos contribuidores. 

### Cómo clonar un repo
1. Vayan a https://github.com/CIS311-PUCP/letras_canciones
2. Hagan click en el botón verde que dice *Code*
3. Dale click en *Open with Github Desktop*
4. Selecciona la carpeta de tu computadora donde se clonará el repo. **NO** lo clones en una carpeta compartida de Dropbox, Box, etc. 

Finalmente, explora el folder clonado! Compáralo con lo que viste en Github. 



### 2. Commit 

- Qué es un control de versiones? 

Por ejemplo, miremos al control de versiones que tiene un google doc: 

<img src="./img/version_control_drive.png" alt="drawing" width="400" />

Todas las versiones de este documento están almacenadas. Se pueden ver los cambios que hizo cada contribuidora al documento. Sin embargo, Google docs almacena todas las versiones!!!

Para no tener que guardar todas estas versiones, Git  **usa los commits para indicar las differencias significativas entre versión y version**

Cada commit es una captura de los archivos del proyecto en determinado momento, y lo compara respecto al commit anterior. 

Cada commit tiene un timestamp (dentro de este ya tiene un id que incluye fecha y hora)

#### Cómo hacer un commit ? 
Antes de hacer un commit, necesitamos saber sobre los branches, por ahora les mostraré cómo hacer un commit. 

- Creé un nuevo archivo .txt llamado lyrics en mi folder clonado. 
- Usé github desktop para hacer commit al repo. 
- Confirmen que ven el archivo
- Ven el sync en Github Desktop ?

Ahora podemos empezar a explorar el repo https://github.com/CIS311-PUCP/letras_canciones

Vemos que la lista de commits es más significativa ya que solo nos muestra los cambios importantes que hemos hecho. 


https://github.com/CIS311-PUCP/letras_canciones/commits  
<br>

</br>

OJO 2: Ven que hice un pull ???


### 3. Branch

- Los branches son la propiedad "killer"/genial de Git. Esto hace a Git una herramienta poderosa de colaboración y no solo de control de versiones! 

- Los branches **permiten crear una copia del código donde puedes experimentar/jugar** con él. Si te gusta el resultado, **puedes mergear el experimento a la versión principal** 

- Esta versión no-lineal es más fidedigna a cómo se trabaja en la vida real. 

<img src="./img/simple_git.png" alt="drawing" width="400" />

## Explorando branches

Puedes cambiar la rama en */commits*, qué sucede cuando cambias la rama allí ?

Cual es la versión clonada en tu computadora? Cuando se clona un repo **todas las versiones** son clonadas, pero **solo una** es la que se muestra en nuestra carpeta. 

Hagan la prueba de cambiar la rama, en https://github.com/CIS311-PUCP/letras_canciones/, cambia acaso el contenido? 


Un flujo de trabajo típico en Git implica tener varias ramas. Hay otras herramientas en Github qhe vuelve este flujo de trabajo muy manejable, sin embargo, está fuera del alcance de hoy. 

## Creando una branch

- Ve a https://github.com/CIS311-PUCP/letras_canciones, y dale click al botón que dice (símbolo branch) main. **Asegúrate que sea el main!!!**

- Escribe tu nombre "nombre_apellido" en el cuadro de diálogo y dale click para crear la branch. 

### Combinando el commit y el branch 

### Ahora quiero que colabores en el repo de la clase!

1. Asegúrate de que tu rama aparezca en GitHub Desktop. Sitúate en ella. Esto significa que esta rama está checkeada (checked out).

2. Abre un editor de texto. 
3. Googlea la letra de tu canción favorita y cópiala en el editor de texto que acabas de abrir.  
4. Guarda el archivo en formato *.txt* con el nombre tunombre_cancion. 

## Al fin nuestro primer commit!!!
1. Abre el tab de cambios (changes) en Github Desktop. 
2. Github desktop se ha dado cuenta que hay nuevos cambios a tu repo.

3. Sigue los siguientes 3 pasos para hacer commit en tu branched repo:  
    1. Asegúrate de que tus cambios estén marcados. 
    2. Escribe un mensaje de commit. 
    3. Haz click en el boton de sync. 


### Checkea tu commit en Github

Ve a https://github.com/CIS311-PUCP/letras_canciones/network
- Puedes encontrar tu commit ? 

Ve a https://github.com/CIS311-PUCP/letras_canciones/commits
- Puedes ver tu commit? Asegúrate de mirar tu branch. 

## Pull requests 

Una propiedad adicional a los branches es el **pull request**
Cuando las ediciones que hiciste están listas para ser mergeadas con el *main*, puedes hacer un pull request, lo cual integrará tus ediciones en la rama *main*. 

Es común que el acceso a la rama *main* solo la tenga el repo maintainer (no todos los contribuidores).

- Ve a https://github.com/CIS311-PUCP/letras_canciones/pulls y dale click a *New pull request*
- Asegúrate de que la branch *main* esté seleccionada como *base:* branch. 
- Selecciona tu branch como *compare:* branch
- Scrollea para ver que tus ediciones son las que quieres que se integren con la main branch, dale click a *Create pull request*





## PARA TERMINAR

### Y ahora cómo creo mis propios repos???

Usualmente, Github servirá para almacenar proyectos individuales. Reordenando los pasos aprendidos a lo largo de este tutorial, podemos crear nuestros propios repos!

1. Ve a la página principal de Github. Dale click al botón verde que dice *New*

<img src="./img/create_repo.png" alt="drawing" width="300" />

2. Luego, elige el nombre del repo!. 
Tambien tenemos otras opciones, como agregar una descripción del repo, volverlo público/privado, agregarle un .gitignore, un README.md, y una licencia. Creen el repositorio!

<img src="./img/create_repo1.png" alt="drawing" width="400" />

3. Una vez creado el repo, te dan las siguientes instrucciones. Dale click a *Set up in Desktop*

<img src="./img/create_repo2.png" alt="drawing" width="400" />

4. Aparecerá el siguiente cuadro, acepten 

<img src="./img/create_repo3.png" alt="drawing" width="400" />

5. Finalmente,  github les pedirá que elijan la carpeta asociada al repo. Elijan una carpeta que **no esté en Dropbox, Box, etc** !. Un

6. Listo, ya tienes un folder asociado a un repo en tu computadora. Intenta hacer tu primer commit y verifica que 

OJO: NO OLVIDEN DE HACER COMMIT CONSTANTEMENTE A SU TRABAJO!!! 
OJO 2: NO OLVIDEN SINCRONIZAR DESPUES DE HACER COMMIT!!!

## Otros recursos de aprendizaje: 

### Aprender Github desde el command line: 



- En este tutorial, hemos lo visto los elementos esenciales para utilizar Github. 
