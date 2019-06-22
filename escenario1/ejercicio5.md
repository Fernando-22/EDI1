# Espacio de Definicion Institucional - ISPDyT210
## Practica 2
### Ejercicios de Git de [KataKoda](https://www.katacoda.com/courses/git/1)
#### Escenario 1 - Commiteando archivos

**Paso 5 - Git Ignore**

A veces hay archivos o directorios particulares que nunca desea confirmar, como la configuración de desarrollo local. Para ignorar estos archivos, cree un archivo **.gitignore** en la raíz del repositorio.

El archivo **.gitignore** le permite definir comodines para los archivos que desea ignorar, por ejemplo **.tmp** ignorará todos los archivos con la extensión .tmp.

Cualquier archivo que coincida con un comodín definido no se mostrará en una salida de **git status** y se ignorará cuando se intente con el comando **git add**.

Solo se confirmarán los cambios agregados al área de preparación, no se incluirán los archivos en el directorio de trabajo que no hayan sido almacenados.

**Tarea**

Agregue y confirme un archivo **.gitignore** en el repositorio para ignorar todos los archivos **.tmp.**

**ProTip**

El **.gitignore** debe estar comprometido con el repositorio para garantizar que las reglas se apliquen en diferentes máquinas.

#### Solucion

> .gitignore
