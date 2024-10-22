# capacitacion-ramas
repositorio para mostrar el uso de ramas con gitflow

## Comandos de git que se usarán

crear nueva rama (solo se prodrán crear ramas de feature)
```bash
git switch -c feature/<nombre-tarea>
```

git 
cambiar de rama
```bash
git switch <nombre-rama>
```

ver las ramas que existen
```bash
git branch
```

al terminar una tarea, fusionar con la rama develop
```bash
git switch develop #primero cambiarse a la rama develop
git merge feature/<nombre-tarea> # para fusionarse con develop
```
