# ActividadFormativaM2-Equipo5
M2 Actividad 1- Cómputo en la nube - Google Colab - Git - GitHub.

## Clonar repositorio remoto  en repositorio local (pc)
git clone https://github.com/EstebanPerez25/ActividadFormativaM2-Equipo5.git

## Subir cambios desde repositorio local:
* git add .  (Sube cambios realizados localmente a zona de preparación, para ser rastreados por git)
* git commit -m "Mensaje explicativo de los cambios realizados"  (Sube contenido al repositorio local)
* git push  (Sube contenido al repositorio remoto)

## Bajar cambios desde repositorio remoto
* git fetch  (descarga contenido de rama pero sin actualizar repositorio local, para revisar cambios)
* git merge (Fusiona contenidos de dos ramas)
* git pull  (Descarga contenido de una rama de repositorio remoto a la rama local activa y ejecuta git merge inmediatamente


## Flujo de trabajo
1. Obtener versión actualizada (pull)
2. Editar notebooks en Jupyter Notebook/Lab
3. Guardar Notebook y **crear copia local** con otro nombre
4. Hacer git add, commit y push para subir archivo a GitHub
5. Obtener versión actualizada (pull) y repetir proceso
