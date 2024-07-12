# Pasos para crear un repositorio con **git init**
===
  
## 1. Crear la carpeta del repositorio local
---
  
En la ubicación deseada, creamos la carpeta local del repositorio:
![Creacion de carpetas del repositorio](./retos_2/1%20-%20Creación%20carpetas.png)
---
  
## 2. Inicializar el repositorio
---
  
Ahora toca inicializar el repositorio (en local) con _git init_
![git init](./retos_2/2%20-%20Inicializar%20repositorio.png)
---
  
## 3. Crear el repositorio a _GitHub_
---
  
Lo siguiente crear el repositorio local a la nube, creando un repositorio en GitHub con el mismo nombre
Como ya hemos creado el fichere README, no es necesario marcar esa opcion cuando lo creemos.
![Crear repositorio en GitHun](./retos_2/3%20-%20Crear%20repositorio%20en%20GitHub.png)
---
  
## 4. Enlazar los repositorios
---
  
A continuación, debemos enlazar ambos repositorios, utilizando los siguientes comandos
  
```
git remote add origin [aqui va el enlace]
git branch -M main
git push -u origin main
```
![Enlazar repositorios](./retos_2/4%20-%20Enlazar%20repositorios.png)
En mi caso, mi rama principal ya se llama main, por lo que no necesito renombrarla, pudiendo omitir ese comando
  
## 5. Sincronizar los repositorios
---

En caso de ser necesario, ya que al enlazar los repositorios hacemos un *git push*, podemos y debemos añadir
 las modificaciones al repositorio en la nube con los siguientes comandos:

```
git add .
git commit -m "comentario descriptivo"
git push
```
