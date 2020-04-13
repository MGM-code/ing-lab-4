# Resolución trabajo practico n° 1 - Lab IV - UBP.
## Alumno: Matías Gallo

# Trabajo Práctico N° 1: Sistemas de control de versiones.
### 1- Objetivos de Aprendizaje
Utilizar herramientas de control de configuración de software, familiarizarse con la nomenclatura y conocer los comandos más utilizados.
Configurar el repositorio principal de cada alumno para la asignatura.

### 2- Consignas a desarrollar en el trabajo práctico:
Los ejercicios representan casos concretos y rutinarios en uso de este tipo de herramientas.
Documentar el proceso desarrollado utilizando las herramientas tecnológicas que creas necesarias.

### 3- Desarrollo:
#### 1- Instalar Git
Los pasos y referencias asumen el uso del sistema operativo Ubuntu, en caso otros SO seguir recomendaciones específicas.
Bajar e instalar el cliente git.
$ sudo apt install git
Bajar e instalar un cliente visual. Se puede utilizar el cliente del IDE que utiliza normalmente (vscode, por ejemplo).
Lista completa: https://git-scm.com/downloads/guis/

#### 2- Crear un repositorio local y agregar archivos
Crear un repositorio local en un nuevo directorio.
Agregar un archivo Readme.md, que contenga tu nombre y un link a tu CV. Tu cv será otro archivo en el mismo formato, en la misma carpeta.
Aclaración: No pongas información personal como DNI, email o telefono en tu cv, puede tener información Falsa si lo prefieren.
Crear los commits de cada caso y proveer mensajes descriptivos.

#### 3- Crear un repositorio remoto
Crear una cuenta en https://github.com
Crear un nuevo repositorio en dicha página (vacío)
Asociar el repositorio local creado en el punto 2 al creado en github.
Subir los cambios locales a github.

![Primer repositorio](https://drive.google.com/open?id=1YtBVYmOI_g3iCLovWH5ce9FsbisyJCJa)

#### 4- Familiarizarse con el concepto de Pull Request
Para algunos de los puntos proveer imágenes o videos.
Crear un branch local y agregar cambios a dicho branch.

![Branch](https://drive.google.com/open?id=1VFlsUobmHBJAWSrfFs6O8epVE943OIRB)

El cambio debe ser un archivo md donde se explique que es un pull request y un link a éste en el readme.
Subir el cambio a dicho branch y crear un pull request.

![Pull Request](https://drive.google.com/open?id=1NUcWZx3YQ7kdIy8PS82ytc9fW5z2DFPg)

Completar el proceso de revisión en github y mergear el PR al branch master.

![Merge](https://drive.google.com/open?id=1WV_lkzw7jG1n6Gic9bR3mRcFLq172Opf)

#### 5- Mergear código con conflictos
Para algunos de los puntos proveer imágenes o videos.
Instalar alguna herramienta de comparación
Ejemplos: SmartGit, GitEye, plugin para vscode. pycharm, etc
Clonar en un segundo directorio de tu equipo el repositorio creado en github.
En el clon inicial, modificar el CV.md cambiando algunas lineas.

![Clon](https://drive.google.com/open?id=1a51j0QIN4-3m_b5Oh2qB9aBPUyeq4FUN)

Hacer commit y subir el cambio a master a github.
En el segundo clon también realizar cambios en las mismas líneas que se modificaron en el otro directorio.

![Comparación de codigo](https://drive.google.com/open?id=1yiakWSq9L2UGFG9b0sDN7DLBrEzcmsUF)

Intentar subir el cambio, haciendo un commit y push. Mostrar el error que se obtiene.

![Conflictos](https://drive.google.com/open?id=1ZvIe4SV5oqF28kz2omgJtYt8UwlsoE3a)

Hacer pull y mergear el código (solo texto por ahora), mostrar la herramienta de mergeo como luce.
Resolver los conflictos del código.
Explicar las versiones LOCAL, BASE y REMOTE.
Pushear el cambio mergeado.

#### 6- Algunos ejercicios online
Entrar a la página https://learngitbranching.js.org/
Completar los ejercicios Introduction Sequence
Opcional - Completar el resto de los ejercicios para ser un experto en Git :D !!!

![Actividades](https://drive.google.com/open?id=16583Np8HIuTKwGFo-XN-0uZXqomFMw_a)

#### 7- Crear Repositorio de la materia
Crear un repositorio para la materia en github. Por ejemplo ing-lab-4 (Diferente al de este trabajo práctico)
Subir archivo(s) .md con los resultados, imágenes y/o videos de este trabajo práctico a ese repositorio. Puede ser en una subcarpeta trabajo-practico-01, con su propia rama, como mas le guste, pero en el README.md deberán explicar como encuentro el resultado.
