# APUNTES SKYLAB
---
## COMANDOS DE TECLAS EN SUBLIME TXT, TERMINAL Y MARKDOWN
  
### TERMINAL (MAC)
- `ls` ==> sirve para listar una carpeta  
- `mkdir` ==> crea una carpeta  
- `cd` ==> navegas entre carpetas   
- `pwd` ==> nos dice en que carpeta estamos  
- `touch` ==> crea un archivo vacío   
- `rm` ==> borra la carpeta, pero si esta llena, debo eliminar primero los archivos internos    
- `rm -rf` ==> fuerza a borrarlo todo, ojo como se utiliza!!!   

### SUBLIME TXT    
- `cmd + d` ==> selecciona todos los items iguales que quiera y puedo sustituirlos   
- `cmd + shift + P` ==> nos lleva a la paleta de comando de Sublime TXT  
- `Markdown preview`==> `preview in browser` ==> nos muestra como queda en el navegador   
 
### MARKDOWN  
- ***....*** ==> nos pone el texto dentro en negrita
- *....* ==> nos pone el texto dentro en cursiva  
- _...._ ==> nos pone el texto dentro en italica   
- '---'==> nos crea una linea de separación  
- ![my image](url que quiera poner) ==> al clicar en la imagen nos envia a la url  

## COMANDOS DE GIT  
- `git init` ==> inicializo un repositorio Git  
- `git status` ==> compruebo el estado del repositorio Git  
- `git config -l` ==> configura Git  
- `git add 'nombre del archivo'` ==> me pasa los cambios de repositorio al área de Staging  
- `git add --all` ==> igual que `git add` pero me pasa todos los archivos de la carpeta  
- `git commit -m 'información del cambio` ==> crea una version de repositorio lista para subir a GitHub  
- `git log` ==> muestra todos los cambios del repositorio  
- `git log --stat` ==> igual que `git log` pero obtengo toda la información  
- `git checkout 'número identificador del cambio'` ==> vuelvo a dicho estado del repositorio  
- `git checkout master` ==> vuelvo a la primera versión del repositorio  
***podemos crear un archivo `gitignore.git` donde meter lo que queremos que el repositorio ignore***

#### EJEMPLOS

```Javascript
var sum = function (a, b) {
    var resulSum = a + b;
    return resulSum.toFixed(3);
  } 
```