¿Qué comando utilizaste en el paso 11? ¿Por qué?
el comando utilizado fue git reset head~1
- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
use un git log para ubicar el hash del commit eliminado en el paso anterior y luego hice un rest <hash>
- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
este merge no causo problemas
- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
este causo  conflict debido a que el git-nuestro.md tenia contenido distinto en ambas ramas.
- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
este merge no causo problemas.
- ¿Qué comando o comandos utilizaste en el paso 25?
para hacer el diagrama utilice git log --graph --oneline --all
- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
no podria ser un fast-forward, porque en la rama title tiene cambios que no hay en rama main, por lo que necesitamos hacer un merge no-ff para que main pueda accerder a todos los commits de title.
- ¿Qué comando o comandos utilizaste en el paso 27?
para deshacer el merge del 27 sin perder cambiosn en el working copy use el git reset head~1
- ¿Qué comando o comandos utilizaste en el paso 28?
git reset hard, esto elimina todo lo del working copy
- ¿Qué comando o comandos utilizaste en el paso 29?
para eliminar la rama use git branch -D
- ¿Qué comando o comandos utilizaste en el paso 30?
para esto utilice git reflog ubique el hash y luego git reset <hash>
- ¿Qué comando o comandos usaste en el paso 32?
con este git log busque el commit inicial y luego git reset <hash del commit inicial>
- ¿Qué comando o comandos usaste en el punto 33?
mismo metodo que con el paso 30, git reflog- git reset.
