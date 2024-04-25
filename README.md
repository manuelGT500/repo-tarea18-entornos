# Para añadir archivos al área de preparación
git add <nombre_archivo>

# Para hacer commit de los cambios
git commit -m "Mensaje descriptivo del commit"
Subir los Cambios al Repositorio Remoto
Una vez que hemos hecho commit de nuestros cambios en las ramas locales, los subimos al repositorio remoto en GitHub utilizando el comando git push. Por ejemplo:


git push origin feature
git push origin hotfix
Esto sube los cambios de las ramas feature y hotfix al repositorio remoto en GitHub.

# Fusionar Ramas
Para fusionar una rama con otra (por ejemplo, fusionar la rama feature con la rama develop), utilizamos el comando git merge. Por ejemplo:


git checkout develop
git merge feature
Esto fusiona los cambios de la rama feature en la rama develop. En caso de conflictos, Git nos pedirá que los resolvamos manualmente.

# Resolver Conflictos
Cuando hay conflictos durante la fusión de ramas, Git detiene el proceso y nos muestra los archivos en conflicto. Para resolverlos, editamos manualmente los archivos conflictivos para incorporar los cambios deseados. Luego hacemos commit de los cambios utilizando el comando git commit. Por ejemplo:

git add <archivo_con_conflictos>
git commit -m "Resolución de conflictos"
Recomendaciones Finales
Es importante recordar que la creación de ramas, realización de cambios, fusión de ramas y resolución de conflictos son partes fundamentales del flujo de trabajo en Git. Siempre es recomendable hacer un seguimiento cuidadoso de los cambios y colaborar con otros miembros del equipo para garantizar la integridad del código.