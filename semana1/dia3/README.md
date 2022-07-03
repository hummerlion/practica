* Los archivos que tengan la extencion .md son  de tipo Mark down,
    este archivo permite  tener una documentacion de nuestro proyecto, por que al llamarse  README.md github.com lo reconoce como archivo de
    documentacion lo  cual hace que se muestre en la pagina inicial
 
 ```
 git init
 ```
 - este comenado solo se hace una vez por  proyecto,  sirve para  inicializar nuetro proyecto  con ``.git``
 👁️ crea una carpeta oculta llamada .git
 
 
 ``
 git status
 ``
 - para poder listar y ver los aarchivos pestan listos para subir
 - en caso los archivos no esten listos se veran de color rojo
 - y cuando lo esten sera de color verde
 
 ```
 git add . 
 git add nombre_del_archivo
 ```
-  se encarga de  agregar lsoa rchivoa a la memoria de GIt  es decir los guarda en un stash
 
 ```
 git commit -m "comentario"
 ```
 
 - Crea un punto en la linea de tiempo   de nuestro cambios y  a estos se les es posible adjuntar un comentario 
 - los comentarios deben de estar relacionados a los que se hace ,mesto  es  un recomendacion
 
 ```
 git push origin main
 git push origin master
 ```
 
 - sireve para  poder subir los cambios a nuestro repositorio en la nube, en este caso  github


 ```  
 git pull origin main
```

 - se encarga de descargar los cambios de nuestro repositorio en la nube,  en este  caso github.com


```
git clone url_de_github.com
```
 - la forma en la cual yo puedo descargar proyectos  desde cualqueir computadora  
  este comando me crea una carpeta con el nombre del repositorio



 ```  
 git branch
 ```

 - sirve para poder listar lo branch que tengo localmente y  me dicen en cual me enuentro actualmente


 ```
 git checkout -b  nombre_del_branch
 ```

 - sirve para crear un branch  y poder trabjar en el 

 ``` 
 git checkout  nombre_del_branch
 ```
  - sirve para  moverse entre  branch  o ramas

  ```
  git restore --stage nombre_del_file
```
 - sirve para  ignorar un file  y no subirlo a la nube
 
  

  
