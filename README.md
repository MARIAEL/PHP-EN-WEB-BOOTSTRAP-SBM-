#Instalar SFTP en Sublime text
Antes de instalar sftp comprobar que  tenemos instalado el Package control (ctrl+shift+p), sino es así instalarlo desde esta [pagina](https://packagecontrol.io/installation).    

   ![](http://grabilla.com/0520d-f519a486-d25b-4703-af85-3eec40fd771f.png)
  
  
Para ello debemos copiar el código del cuadro izquierdo para sublime text 2 o 3 dependiendo de nuestra versión en el cuadro inferior de la consola de sublime text (show > console). 

![](http://grabilla.com/0520d-ded97eae-0ddf-4b16-b685-6e06f51ff6c2.png)


Abrimos el package control (ctrl+shift+p) y empezamos a escribir "pa", nos aparecera varias opciones bajo seleccionamos "Package control: install package".

![](http://grabilla.com/0520d-ded97eae-0ddf-4b16-b685-6e06f51ff6c2.png)  


![](http://grabilla.com/0520d-57fe0d4e-a3d1-406a-a895-4ac8f8b64181.png)

una vez seleccionado escribimos sftp y seleccionamos la primera opción, 

![](http://grabilla.com/0520d-cb3edfa7-59e8-4cdb-ab69-1226e61d17ee.png)



tras unos segundos reiniciamos SBT y ya estamos en disposición para configurar la conexión a nuestro servidor de forma remota.  

Creamos un nuevo proyecto arrastrando la carpeta del mismo hasta SBT, seguidamente pulsamos con el botón derecho sobre la carpeta > SFTP/FTP > map to remote.  

![](http://grabilla.com/0520d-ab804826-4936-4c13-a07b-278233718daf.png)

La configuración debe quedar de la siguiente forma:  
    "upload_on_save": true,  
    "host": "nuestraip",  
    "user": "username",  
    "password": "password",  
    "remote_path": "/var/www/html/nuestraweeb",  
    ...

#Creamos una carpeta llamada IFCT0509
  
(En el escritorio de Windows creamos la carpeta botón dr.)  

Crear archivo llamado index.php, dentro de esa carpeta 

Crear otro que llamamos header.php, donde incluiremos el código de la cabecera.  

Crear otro que llamamos footer.php, donde incluiremos el código del pie.

![](http://grabilla.com/0520d-2fb907f1-0606-424e-b1c5-6198b911074c.png)

Nos situamos en el archivo index.php y escribimos html y TAB  

![](http://grabilla.com/0520d-328d780e-6e50-4145-9550-368d3edf5b63.png)

Ahora hemos de pegar el código para acceder a las librerías de Bootstrap desde un CDN en el archivo _header.php    

Para ello hemos de ir a la web **http://getbootstrap.com/getting-started/**

y copiar el código siguiente:  

![](http://grabilla.com/0520d-9ddbcdc4-6805-4cb7-b2d6-978b57a716fe.png) 

Teclear html TAB y pegarlo tras <head>  

![](http://grabilla.com/0520d-e1a5ff50-573f-4301-94a0-0e389c6b830f.png)

Grabar.  

El archivo _footer.php dejarlo así:  

![](http://grabilla.com/0520d-fdb3c514-c5cc-41a9-9d10-926baa5e07b5.png)  

Grabar.

El archivo que hemos creado index.php lo dejamos así:  

![](http://grabilla.com/0520d-07a66e2d-def4-4192-b908-e6ed6fda22a5.png)

Ahora hemos de crear en SBM un fichero llamado jquery.js  

Para ello iremos a la web de jquery para obtenerlo.  

![](http://grabilla.com/0520d-74678d04-79c9-4304-97b5-f754a88456f5.png)  

Hacer clic en botón derecho y abrir enlace en una pestaña nueva 

![](http://grabilla.com/0520d-fe8fa3ec-2236-42c0-baed-29be6f2d22f0.png)  

Nos aparecerá el código, hay que seleccionarlo todo y pegarlo en el fichero jquery.js  

![](http://grabilla.com/0520d-045345a3-c58d-49b9-883f-02f956934c76.png)

![](http://grabilla.com/0520d-39e34666-afd1-43dc-9008-0a666c9dc0d4.png)

A continuación vamos al fichero _footer.php y poner:  

![](http://grabilla.com/0520d-88fce9b6-2891-43e4-9893-ef66f7adde8b.png)

Ya podemos trabajar.


