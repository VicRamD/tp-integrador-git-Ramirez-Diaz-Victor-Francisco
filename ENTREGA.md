# Entrega del Trabajo Práctico Integrador

## Datos del participante

- Nombre y apellido: Víctor Francisco Ramírez Diaz
- Curso: Introducción a Git y Github para la gestión de Proyectos Digitales
- Fecha de entrega: 11/09/2026

## Enlaces

- Repositorio de GitHub: https://github.com/VicRamD/tp-integrador-git-Ramirez-Diaz-Victor-Francisco
- Issue: 
    1. https://github.com/VicRamD/tp-integrador-git-Ramirez-Diaz-Victor-Francisco/issues/1
    1. https://github.com/VicRamD/tp-integrador-git-Ramirez-Diaz-Victor-Francisco/issues/2
    1. https://github.com/VicRamD/tp-integrador-git-Ramirez-Diaz-Victor-Francisco/issues/3
    1. https://github.com/VicRamD/tp-integrador-git-Ramirez-Diaz-Victor-Francisco/issues/4
- Pull request:
    1. https://github.com/VicRamD/tp-integrador-git-Ramirez-Diaz-Victor-Francisco/pull/5
    1. https://github.com/VicRamD/tp-integrador-git-Ramirez-Diaz-Victor-Francisco/pull/6
    1. https://github.com/VicRamD/tp-integrador-git-Ramirez-Diaz-Victor-Francisco/pull/7

## Comandos principales utilizados

Indicar los comandos utilizados durante el trabajo:

- git init
- git status
- git add
- git commit -m
- git log --oneline
- git remote add origin
- git remote -v
- git push
- git push -u origin
- git branch
- git switch -c
- git switch main
- git pull

## Descripción del proceso

El proyecto se inició con la creación de un repositorio git local vacio utilizando el comando `git init`. Cree los archivos de la estructura minima sugeridad y tras ello cree el correspondiente repositorio remoto en mi cuenta de github. Con `git add .` los agregué a la staging area, con `git commit -m ""` cree un commit para guardar los cambios hechos hasta ese momento. Con 
`git remote add origin https://github.com/VicRamD/tp-integrador-git-Ramirez-Diaz-Victor-Francisco` establecí la conexión con el repositorio remoto. Con `git push`subí los cambios al repsotiorio remoto. Tras esos pasos iniciales cree issues en mi repositorio remoto con tareas para realizar y cree ramas con `git switch -c nombre-rama` para completarlas (esto lo hice tarea a tarea y no todas de una sola vez). Al trabajar con las ramas use `git add`, `git commit` y `git push -u origin rama` para guardar y subir los cambios en las ramas al repositorio remoto. Ahí realicé las correspondientes pull request e hice merge a los cambios en las ramas hacia la rama main. Luego con `git switch main` y `git pull` regresaba a la rama main y traía los cambios al repositorio local.

## Dificultades encontradas

No hubo grandes dificultades. Solamente una vez que intenté usar el comando `git push` para subir cambios en la primer rama creada, pero recibí un mensaje de que falló en la consola. Lo resolví sencillamente leyendo el documento del trabajo integrador, donde muestra que el comando debe agregar -u origin. `git push -u origin nombre-rama`.

## Reflexión final

En mi caso como he estudiado en una carrera que enseña programación ya tenía por lo menos los conocimientos más básicos en git. Este curso me ha servido para no solo aprender nuevos comandos, sino para tener ideas más claras de los conceptos involucrados en el proceso de manejo de estos repositorios remotos y locales, y aprender sobre buenas prácticas.