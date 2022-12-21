1. Creación de un proyecto en IntelliJ

![Creación de Priyecto](./img/1.png)

2. primer commit

- Creamos un proyecto limpio en Intellij

![Creación de Priyecto](./img/2.png)
  
  ```bash
  git init
  ```
  
- Creamos una rama m_ejercicioGit
      
![Creación de Priyecto](./img/3.png)

  ```bash
 git checkout -b m_ejercicioGit o git branch m_ejercicioGit
 ```
  
![Creación de Priyecto](./img/4.png)
    
 ```bash
 git status
 ```
 
 - Añadimos el commit **creo un proyecto limpico con IntelliJ**
     
![Creación de Priyecto](./img/5.png)
  
  ```bash
  git add .
  git commit -m "creo un proyecto limpico con IntelliJ"
  ```
  
3. segundo commit

- Ejecutamos el main y crea la carpeta .out

![Creación de Priyecto](./img/7.png)

 ```bash
 git status
 git add .
 git commit -m "acabo de ejecutar el main"
 ```
 
4. tercer commit

- creamos .gitignore, lo creamos con el comando "nano .gitignore" o cualquier editor
- Lo podemos crear el .gitignore, por editor por ejemplo **nano .gitignore**

![Creación de Priyecto](./img/8.png)

 ```bash
 nano .gitignore, notepadd++ .gitignore o code .gitignore
 ```
 
- Le añadimos .out y lo guardamos **Ctrl izquierdo + o**

![Creación de Priyecto](./img/9.png)

 ```bash
 Ctrl izquiedo + o  para guardar y Ctrl izquierdo + x para salir 
 ```
 
 - Nos queda commitear **añadido gitignore**     
![Creación de Priyecto](./img/10.png)

```bash
 git status
 git add .
 git commit -m "añadido gitignore"
 ```

5. cuarto commit

- creamos el objeto Empleado y muestra objeto Empleado(Editando main) y ejecutmos Main.java

![Creación de Priyecto](./img/11.png)
  
  ```bash
  git status
  git add .
  git commit -m "programa que crea y muestra un objeto empleado"
  ```
  
6 . quinto commit

- Eliminanms el directorio .out con **git rm -r out/**

![Creación de Priyecto](./img/12.png)
  
  ```bash
  git rm -r out/
  ```
  
  - ültimo nos queda commitear  **eliminando directorio out**  

![Creación de Priyecto](./img/13.png)
  
 ```bash
 git status
 git add .
 git commit -m "eliminando directorio out"
 ```
  
7 . sexto commit

- Añadimos el READMe.md y la carpeta img(con sus imágenes correspondientes)

![Creación de Priyecto](./img/14.png)
  
```bash
git status
```

 - Último nos queda commitear     

![Creación de Priyecto](./img/15.png)
 
 ```bash
 git add .
 git commit -m "añadido el README"
 ```

8. septimo commit

- introducido problema a solucionar. Modificamos el Main.java(para solucionar el problema del Empleado)

![Creación de Priyecto](./img/16.png)

```bash
git status
git add .
git commit -m "introducido problema a solucionar"
```

9. octavo commit

- Ejecutamos Main.java para que se vuelva a crear el directorio .out para despúes solucionar el problema

![Creación de Priyecto](./img/17.png)
  
```bash
git status
git add .
git commit -m "vuelvo a subir out para corregir luego el .gitignore y comprobar su f…"
```
     
   
10. noveno commit

- Modificamos .gitignore para corregir el problema del directorio .out(para que lo ignore)
- Editamos .gitignore **nano gitignore**
- Cambiamos .out por out/

![Creación de Priyecto](./img/8.png)

```bash
nano .gitignore Ctrl izquierdo + o para guardar y Ctrl izquierdo + x para salir
```

- Nos queda commitear **corregido .gitignore para ignorar carpeta out**

![Creación de Priyecto](./img/19.png)

```bash
git status
git add .
git commit -m "corregido .gitignore para ignorar carpeta out"
```

11. decimo commit

- Modificamos Main.java, para hacer inmutable Empleado.nombre
- Nos queda commitear **Haciendo inmutable el campo Empleado.nombre**

![Creación de Priyecto](./img/20.png)
  
```bash
git status
git add .
git commit -m "Haciendo inmutable el campo Empleado.nombre"
```

12. once commit

- Elminamos el directorio .out "git rm -r out/"

![Creación de Priyecto](./img/21.png)
  
```bash
git rm -r out/
```

 - Último nos queda commitear **elimino carpeta out**     

![Creación de Priyecto](./img/22.png)
    
```bash
git status
git add .
git commit -m "elimino carpeta out"
```

13. doce commit

- Modificamos el Main.java y lo ejecutamos, ahora si ignora el directorio .out/
- Por último nos queda commitear **ahora ssí ignora correctamente out**

![Creación de Priyecto](./img/23.png) 
  
```bash
git status
git add .
git commit -m "ahora ssí ignora correctamente out"
```
  
