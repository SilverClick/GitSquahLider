# PASOS A SEGUIR:

-Primer paso: Hacemos dos commits iniciales con cambios en la rama main.

```
 public class Main {
    public static void main(String[] args){
        //modificacion a
        //modificacion b

```
-Segundo paso: Subo mis cambios a mi repositorio creado y el colaborador
hace 3 commits con cambios en una nueva rama llamada colaborador y la sube al 
repositorio.
```
public class Colaborador {
    //1
    //2
    //3
}


```

-Tercer paso: El líder crea una rama nueva llamada líder y hace 3 commits 
con cambios como el colaborador.
```
public class Main {
    public static void main(String[] args){
        //modificacion a
        //modificacion b
        //modificacion c
        //modificacion d
        //modificacion e
        //modificacion f
    }
}

```
-Cuarto paso: El líder con un git pull colaborador se trae esa rama del
repositorio.

-Quinto paso: El líder hace un merge --squash desde la main a la rama
colaborador y luego a su rama líder y hace un commit con estos cambios.
