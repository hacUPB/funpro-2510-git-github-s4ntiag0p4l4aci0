


```


                           _ _             _                                  _        
                          (_) |           (_)                                | |       
  _ __ ___ _ __   ___  ___ _| |_ ___  _ __ _  ___    _ __ ___ _ __ ___   ___ | |_ ___  
 | '__/ _ \ '_ \ / _ \/ __| | __/ _ \| '__| |/ _ \  | '__/ _ \ '_ ` _ \ / _ \| __/ _ \ 
 | | |  __/ |_) | (_) \__ \ | || (_) | |  | | (_) | | | |  __/ | | | | | (_) | || (_) |
 |_|  \___| .__/ \___/|___/_|\__\___/|_|  |_|\___/  |_|  \___|_| |_| |_|\___/ \__\___/ 
          | |                                                                          
          |_|                                                                          

                                                                                                                                                                                  
```
Repositorio remoto: 

    Una breve idea

Anteriormente, habíamos comparado la idea de un repositorio con la copia de seguridad de Whatsapp, un repositorio remoto, funciona incluso más parecido a este sistema, dado que nos permite tener acceso al repositorio desde la nube y por tanto en otro dispositivo, como cuando uno cambia de celular. Ahora bien, la idea de los repositorios remotos en GitHub, va muchísimo más allá de eso, ya que al tener un repositorio en la nube este se puede compartir con otras personas y hacer ediciones en distintas ramas para luego unirlas y obtener los resultados de un trabajo conjunto. Con git clone, podemos acceder localmente al repositorio, y con git push subir a la nube los cambios. Para mantener la versión local actualizada, usamos git pull para actualizar las ramas locales con respecto a las de la nube. En mi caso, el primer día accedí al repositorio remoto desde un computador de la universidad, y este trabajo fue desarrollado en un pc personal.   

    Paso a Paso
----

         Nota:

-  A mi en un repositorio remoto me gusta ir añadiendo a medida que cada cambio se hace, porque el respaldo online me parece esencial. Es por eso que explicaré el metodo de creión de un repositorio remoto más directo, para que desde el inicio todo el repositorio se esté sincronizando. Es decir primero generar el repositorio remoto y luego clonarlo, así la información desde un principio tendrá respaldo.





    El paso a paso

Primero creamos el repositorio remoto en GitHub (después de acceder)

![Image](../images/imge.png)

![Image](../images/IMGF.png)


Copiamos el link del repositorio remoto

![Image](../images/imgg.png)


Clonamos el repositorio con git bash (localmente)

```
git clone ^link^ --> clona el repositorio
```
![Image](../images/imgh.png)

Se crea un archivo y se sigue ésta ruta para mantener el repositorio sincronizado

```
git touch ârchivo+ext^ --> crea el archivo

git add . --> para añadir todo lo del directorio

git commit -m --> para pasar al repositorio

git push origin main --> para pasar al repositorio remoto

```
![Image](../images/imgi.png)

para sincronizar los cambios online a la versión local se utiliza 

```
git pull

```
Para editar un archivo 

```
nombre editor ^nombre archivo /carpeta / .--> para la carpeta actual^
```
![Image](../images/imgd2.png)