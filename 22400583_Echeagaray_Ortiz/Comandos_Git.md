1. git init: Crea un nuevo repositorio en la carpeta actual
   "git init"

2. git clone: Descarga un repositorio remoto a tu máquina
   "git clone https://github.com/usuario/proyecto.git"

3. git config: Configura opciones de usuario (nombre, correo, etc.)
   "git config --global user.name 'Jorge'"
   "git config --global user.email 'jorgeemilio@gmail.com'"

4. git add: Añade archivos al área de preparación (staging)
   "git add archivo.txt"
   "git add ."

5. git commit: Guarda los cambios en el historial con un mensaje
   "git commit -m 'Agregué login'"

6. git status: Muestra el estado actual de los archivos
   "git status"

7. git rm: Elimina archivos del repositorio y del disco
   "git rm archivo.txt"

8. git mv: Renombra o mueve archivos manteniendo historial
   "git mv viejo.txt nuevo.txt"

9. git log: Muestra el historial de commits
   "git log"
   "git log --oneline"

10. git diff: Compara cambios entre versiones o ramas
    "git diff main nueva-rama"

11. git show: Muestra detalles de un commit específico
    "git show abc123"

12. git branch: Lista o crea ramas
    "git branch"
    "git branch feature-login"

13. git checkout: Cambia de rama o restaura archivos
    "git checkout feature-login"

14. git switch: Alternativa moderna a checkout para cambiar de rama
    "git switch main"

15. git merge: Fusiona cambios de una rama en otra
    "git merge feature-login"

16. git rebase: Reaplica commits sobre otra rama
    "git rebase main"

17. git remote: Administra conexiones a repositorios remotos
    "git remote add origin https://github.com/usuario/proyecto.git"

18. git push: Envía commits locales al repositorio remoto
    "git push origin main"

19. git pull: Descarga y fusiona cambios desde el remoto
    "git pull origin main"

20. git fetch: Descarga cambios del remoto sin fusionarlos
    "git fetch origin"
