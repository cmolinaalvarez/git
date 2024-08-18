# Comandos Git
| Comando                 | Descripcion                                                           | 
|-------------------------|-----------------------------------------------------------------------|
| git init                | Inicializa un repositorio GIT en un directorio local                  | 
| git clone <URL>         | Clona un repositorio GIT desde una URL remota                         | 
| git add [archivo]       | Agrega cambios de un archivo al área de preparacion o Stage           | 
| git add .               | Agrega todos los cambios al área de preparacion o Stage               | 
| git commit -m "mensaje" | Guarda los cambios en el repositorio con un mensaje                   | 
| git status              | Muestra el estado actual del repositorio                              | 
| git push                | Envía los cambios locales al repositorio remoto                       | 
| git pull                | Obtiene los cambios desde el repositorio remoto y los fusiona localmente| 
| git branch              | Lista todas las ramas del repositorio                                 | 
| git branch <nombre>     | Crea una nueva rama con el nombre especificado                        | 
| git checkout <rama>     | Cambia a la rama especificada                                         | 
| git checkout -b dev     | Crea la rama local dev y se posiciona en ella                                       | 
| git merge <rama>        | Fuciona una rama específica con la rama en la que me encuentro ubicado| 
| git log                 | Muestra el historial de confirmaciones                                | 
| git log --oneline                | Muestra el historial de confirmaciones en lineas             | 
| git log --pretty=format:"%h%x09%an%x09%ad%x09%s"| Muestra el historial de confirmaciones formateado| 
| git reset <archivo>     | Deselecciona los cambios de un archivo en el área de preparacion      | 
| git branch <nombre>     | Crea una nueva rama con el nombre especificado                        | 
| git reset --hard        | Restablece el estado del repositorio a una confirmación específica    | 
| git stash               | Guarda los cambios locales en una pila temporal                       | 
| git stash pop           | Recupera los cambios almacenados en la pila temporal                  | 
| git remote -v           | Muestra las URL de los repositorios remotos                           | 
| git remote add <nombre> <URL>| Agrega un nuevo repositorio remoto con el nombre y la URL especificados| 
| git rm <archivo>        | Elimina un archivo del control de versiones                           | 
| git mv <archivo1> <archivo2> | Cambia el nombre de un archivo en el control de versiones        | 
| git fetch| Nos trae la información de la información nueva que se encuentra en la rama remota   |
| git branch -d NombreRama| Borrar una rama de forma local                                        |



[Más comandos git](https://gist.github.com/dasdo/9ff71c5c0efa037441b6)
