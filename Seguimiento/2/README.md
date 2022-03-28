<h1 align="center "># Taller ll (Linux 1)</h1>

<p align="center">
<b>Ivan Andres Guapacha</b>
</p>


## 1. Cambiar la contraseña del usuario root 

Para cambiar o recuperar la contraseña del usuario root lo primero que debemos hacer es cuando el sistema operativo esta arrancando mover las flechas para cargar la pantalla que nos permite elegir el inicio del sistema operativo y estando en esta pantalla vamos a precionar ctrl + e para modificar 

<img src="Inicio sistema operativo.png" />

En esta pantalla vamos a modificar rhgb quiet por  rb.break 

<img src="Arranque.png" />

<img src="Break.png" />

Luego de esto precionamos enter para mantener en la consola

<img src="Consola.png" />

En esta consola ejecutamos el comando mount  y luego ejecutamos el comando mount -o rw,remount /sysroot/

<img src="Mount.png" />

<img src="Remount.png" />

Luego ejecutamos el comando chroot /sysroot y luego passwd para cambiar la contraseña del usuario root

<img src="Chroot.png" />

Continuando con el proceso escribimos el comando touch y luego el comando exit

<img src="Touch.png" />

Luego de esto esperamos a que el sistema reinicie y con la contraseña que le pusimos podemos ingresar con el usuario root al sistema 

<img src="Root.png" />

## 2. Modificar el arbol genealogico creado en el taller 1 para agregar las carpetas Bisabuela, Bisabuelo, Nieto y Nieta con sus respectivos archivos txt 


Para esto lo primero que tenemos que hacer es crear las carpetas de Bisabuela y Bisabuelo con el comando mkdir

<img src="Bisabuelos.png" />


Luego de esto vamos a mover toda la carpeta Abuelo dentro de la carpeta Bisabuelo y tambien la carpeta Abuela la vamos a mover dentro de la carpeta Bisabuela

<img src="Mv1.png" />

Como paso siguiente vamos a ir hasta La carpeta hija e hijo y vamos a seguir creando el arbol con nieto y bisnieto 

<img src="CarpetasBisnietos.png" />

Y tambien vamos a crear los archivos que corresponden a cada carpeta

<img src="ArchivosBisnietos.png" />

Y esto mismo aplica para la otra rama de hija 

<img src="CarpetasBisnieta.png" />

Y tambien los archivos de Bisabuelo y Bisabuela

<img src="Archivos bisabuelos.png" />

Ahora si vamos a intercambiar los archivos de las carpetas masculinos para las carpetas feneminas

<img src="Mover1.png" />

<img src="Mover2.png" />

Y como resultado final tenemos lo siguiente:

<img src="Tree1.png" />

<img src="Tree2.png" />






















