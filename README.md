# Actividad6_CC3S2

### Explicación de temas

- **`git config`:**  
Nos permite configurar opciones como usuario, correo o editor.
- **`init`:**  
Nos permite crear un nuevo repositorio git en la carpeta actual donde estemos.
- **`add/commit`:**  
Para añadir cambios al área de staged, el commit nos permite guardar confirmaciones en el historial de git.
- **`log`:**  
Nos muestra el historial de commits del repositorio.
- **ramas:**  
Se pueden crear nuevas ramas y luego cambiar a estas. También podemos unir dos ramas y, si hay conflictos, podemos solucionarlo manualmente.
- **`cherry-pick`:** 
 Nos permite seleccionar un commit específico para pasarlo a la rama donde estemos actualmente
- **`stash`:**  
Nos permite guardar temporalmente los cambios que no estén confirmados.

### Comandos que generaron `logs`

- **`branches.txt`:**  
    - `git branch -vv > logs/branches.txt`
- **`config.txt`:**  
    - `git config --list > logs/config.txt`
- **`git-version.txt`:**  
    - `git --version > logs/git-version.txt`
- **`init-status.txt`:**  
    - `git status > logs/init-status.txt`
- **`log-oneline.txt`:**  
    - `git log --oneline > logs/log-oneline.txt`

### Prueba de Pull Request con otro repositorio

Para realizar el ejercicio de creación de un PR para simular trabajo en equipo, se tuvo que crear un nuevo repositorio con nombre: [repo_pr](https://github.com/AlbeCamp21/repo_pr)