1. Creación de repositorio en GitHub, inicializándolo con un README.md y el .gitignore que
GiHub ofrece para Java.

![Creación de Priyecto](./img/1.png)

2. Modificación de este README.md desde GitHub para indicar lo dos primeros pasos.

1. Primer commit

![Creación de Priyecto](./img/2.png)

 ```bash
 git status
 git add .
 git commit -m "Update README.md"
 ```

3. Clonando el repositorio remoto

![Creación de Priyecto](./img/3.png)

 ```bash
 git clone https://github.com/andvigofp/ejerciciosGit.git
 ```

4. Creo un proyecto en ese directorio con intellinj

![Creación de Priyecto](./img/4.png)

2. Segundo commit 

- Nos queda commitear **creando proyecto en intellij**

![Creación de Priyecto](./img/5.png)

```bash
 git status
 git add .
 git commit -m "creando proyecto en intellij"
 ```

6. ¡Ups! el proyecto se creó en una subcarpeta. Muevo su contenido al directorio raiz del
repo.

- Movemos el contendio de la subcarpeta al contendido al directorio raiz

![Creación de Priyecto](./img/6.png)

![Creación de Priyecto](./img/7.png)

3. Tercer commit

- Por último nos queda commitear **moviendo el proyecto a la carpeta raiz del repo**

![Creación de Priyecto](./img/8.png)

```bash
 git status
 git add .
 git commit -m "moviendo el proyecto a la carpeta raiz del repo"
 ```

- Nos queda subir a remoto

```bash
 git remote add origin https://github.com/andvigofp/ejerciciosGit.git
 git push -u origin master
 ```
