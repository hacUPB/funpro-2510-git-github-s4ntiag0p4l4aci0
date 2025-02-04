```
____                      _ _             _         _                 _ 
|  _ \ ___ _ __   ___  ___(_) |_ ___  _ __(_) ___   | | ___   ___ __ _| |
| |_) / _ \ '_ \ / _ \/ __| | __/ _ \| '__| |/ _ \  | |/ _ \ / __/ _` | |
|  _ <  __/ |_) | (_) \__ \ | || (_) | |  | | (_) | | | (_) | (_| (_| | |
|_| \_\___| .__/ \___/|___/_|\__\___/|_|  |_|\___/  |_|\___/ \___\__,_|_|
          |_|
          
```

Repositorio local: 

    Una breve idea

Un repositiorio local nos permite tener una carpeta o directorio dinámico, el cual no solo nos permite guardar la información, sino el historial de versiones de la misma. Hay 3 espacios en los que se puede tener la información. El primero es el directorio, que es la carpeta tradicional, cuando se considera necesario hacer una "copia de seguridad" se añade al stage (git add), que es un guardado intermedio, es como el limbo. Luego se pasa al repositorio por medio de un commit (git commit -m). El repositorio es como la copia de seguridad de Whatsapp en Drive, guarda lo que llevas por si se pierde la información,si se pierde la información, se restaura y se comienza desde donde se haya dejado. Para el repositorio, no se tiene que perder la información para acceder a la copia de seguridad, antes bien, se crean ramas sobre las versiones anteriores, como si fuera un laboratorio de ensayos, por si algo sale mal no afecte la rama principal con todo el trabajo



    El paso a paso

Primero se creamos un nuevo directorio y nos ubicamos en el 
```
- mkdir --> crea un directorio
cd -------> nos ubica en la dirección deseada

```
![Image](../images/imga.png)


Creamos un archivo readme

```
touch readme.md --> crea el archivo
```
![Image](../images/imgb.png)


Establecemos la carpeta como repositorio

```
git init --> vuelve la carpeta un repositorio
```
![Image](../images/imgc.png)

Cambiamos la rama a main

```
git branch -m master main -- nos permite cambiar el nombre de la rama
```
![Image](../images/imgd.png)

Para la edición o ceación de archivos 

```
git touch ârchivo+ext^ --> crea el archivo


git add . --> para añadir todo lo del directorio

git commit -m --> para pasar al repositorio

```
![Image](../images/imgd1.png)

Para editar un archivo 

```
nombre editor ^nombre archivo /carpeta / .--> para la carpeta actual^
```
![Image](../images/imgd2.png)