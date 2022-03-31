<h1 align="center "># Taller lll (Linux 1)</h1>

<p align="center">
<b>Ivan Andres Guapacha</b>
</p>


## 1. Comprimir el directorio Bisabuelo y Bisabuela (tar)

Para comprimir vamos a utilizar el comando **tar**  con las banderas de:  
-c: para crear el comprimido .tar    
-v: para ver el proceso y   
-f: para especificar el nombre del comprimido

<img src="Comprimir Bisabuelo.png" />

<img src="Comprimir Bisabuela.png" />

## Comprimir el directorio Bisabuelo y Bisabuela en formato tar.gz, bz2 

Para comprimir en el formato tar.gz vamos a agregar la bandera z en el comando para que la compresión sea gzip 

<img src="Comprimir Bisabuelo targz.png" />

<img src="Comprimir Bisabuela targz.png" />

Y para comprimir en el foramto bz2 debemos usar la bandera -j 

<img src="Comprimir Bisabuelo tarbz2.png" />

<img src="Comprimir Bisabuela tarbz2.png" />

## 2 Listar los archivos comprimidos

Para listar los archivos comprimidos vamos a usar el comando tar con las banderas -tvf


<img src="Listar Bisabuelo tar.png" />

Para listar los comprimidos en tar.gz añadimos la bandera -z en el comando usando anteriormente 

<img src="Listar Bisabuelo targz.png" />


## 3 Descomprimir los directorios /Bisabuela y /Bisabuelo en las rutas /tmp y /root

Para descomprimir los archivos vamos a utilizar el comando tar -xvf y con la bandera -C indicamos la ruta de destino 

<img src="Descomprimir Bisabuelo.png" />

Para archivos de tipo tar.gz podemos utilizar el mismo comando

<img src="Descomprimir Bisabuela.png" />

Aca podemos ver como quearon los archivos en sus respectivas carpetas

<img src="Muestra Bisabuela.png" />

<img src="Muestra Bisabuelo.png" />

## 4 Comprimir los directorios usando la herramienta o paquete (zip, unzip) y descomprimir

Comprimir 

<img src="Comprimir zip.png" />

Para descromprimir usamos la bandera -d para indicar donde se va a descromprimir 

<img src="Descomprimir unzip.png" />





