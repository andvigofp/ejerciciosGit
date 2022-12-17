1. Creamos un repositorio nuevo en github con un README y un .gitignore

![Creación de Priyecto](./img/1.png)

2. Creamos un proyecto nuevo marcando la opción "Create Git repository"

![Creación de Priyecto](./img/2.png)

3. Hacemos un git status, para ver si hubo cambios

![Creación de Priyecto](./img/3.png)

4. Añadimos el repo de github como remoto e intentamos hacer un pull (recordemos que lo hemos creado con un README y un .gitignore)

![Creación de Priyecto](./img/4.png)

# No podemos hacer un pull por tener cambios en stage local que no hemos commiteado (los
# ficheros del proyecto local). Al crear el proyecto marcando la opción "Create Git repository",
# se ha hecho un git init y, aparentemente, se han añadido al stage (se ha hecho un git add) pero
# no hemos hecho un commit.

![Creación de Priyecto](./img/5.png)

5. Ahora los cambios están sin trackear. Intentamos de nuevo hacer un pull.

![Creación de Priyecto](./img/6.png)

# Al haber creado un .gitignore en remoto y otro en local, hay un conflicto entre estos ficheros

6. Podemos eliminar el .gitignore local si queremos quedarnos con el remoto:

![Creación de Priyecto](./img/7.png)

7. Ya tenemos descargado lo que estaba en remoto (el README y el .gitignore de GitHub) en
la rama main (rama por defecto en GitHub) a nuestra rama master local.

![Creación de Priyecto](./img/8.png)

![Creación de Priyecto](./img/9.png)

# Ahora commiteamos el proyecto local y lo subimos al repositorio.


# Observamos que se ha subido correctamente pero en la rama master (que era en la que
# estábamos trabajando en local), mientras que la rama main se mantiene con su primer
# commit.

![Creación de Priyecto](./img/10.png)

![Creación de Priyecto](./img/11.png)

8. Eliminamos la rama main en el repositorio de GitHub

# Primero tenemos que poner la rama master por defecto

![Creación de Priyecto](./img/12.png)

![Creación de Priyecto](./img/13.png)

# Ahora podemos eleminar la rama m_ejercicioGit3(Simulo la rama main)

![Creación de Priyecto](./img/14.png)

![Creación de Priyecto](./img/15.png)

9. Modificamos el proyecto local (commit: "añadiendo código para probar las propiedades de Java")

# Añadimos objeto Empleado y modificamos Main, lo ejecutamos para probar

![Creación de Priyecto](./img/16.png)


![Creación de Priyecto](./img/17.png)

10. Creamos una nueva rama para corregir un bug:
[INTENTAD ARREGLARLO POR VOSOTROS MISMOS]:
Las especificaciones de nuestro programa nos impiden que una persona cambie de nombre.

# Creamos la rama fixBug1 con "git checkout -b fixBug1 o git branch fixBug1, git checkout fixBug1"

![Creación de Priyecto](./img/18.png)



# git checkout sirve para cambiar de commit (en este caso de rama, una rama es un identificador 
# que apunta a un determinado commit --que es el último de su rama--'). La opción -b crea una rama nueva (no podríamos hacer checkout a una rama que no existe).

11. Corregimos este problem, commiteamos la corrección en la rama y la pusheamos.

# Modificamos Empleado.java y Main.java, para arreglar el bug del nombre del empleado

![Creación de Priyecto](./img/19.png)

# Por ultimo lo puseamos para subir la rama fixBug1

![Creación de Priyecto](./img/20.png)

12. Mergeamos a master la rama con el bug ya solucionado

# Primero nos cambiamos a la rama master "git checkout master"

![Creación de Priyecto](./img/22.png)

# Ahora podemos mergear sin problema 

![Creación de Priyecto](./img/21.png)





