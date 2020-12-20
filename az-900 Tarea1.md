Login con Command Line Interface instalado

az login 



 ![login]([AZ900_PRACTICA_VM_UBUNTU_AZCLI/img1.png at main · CastilloGit/AZ900_PRACTICA_VM_UBUNTU_AZCLI (github.com)](https://github.com/CastilloGit/AZ900_PRACTICA_VM_UBUNTU_AZCLI/blob/main/img/img1.png)

Creación del grupo de recursos

 ![image-20201220102635695](C:\Users\jcarl\AppData\Roaming\Typora\typora-user-images\image-20201220102635695.png)

Creación de recursos bajo el grupo

 ![image-20201220102641608](C:\Users\jcarl\AppData\Roaming\Typora\typora-user-images\image-20201220102641608.png)

Comprobante en el portal de Azure del grupo de recursos

 ![image-20201220102645495](C:\Users\jcarl\AppData\Roaming\Typora\typora-user-images\image-20201220102645495.png)

 

Da error en el login ssh hago reset de password (Pa$$w0rd12345) dentro de la máquina virtual creada.

 ![image-20201220102651659](C:\Users\jcarl\AppData\Roaming\Typora\typora-user-images\image-20201220102651659.png)

 

Conecto por ssh a la máquina virtual

 ![image-20201220102656673](C:\Users\jcarl\AppData\Roaming\Typora\typora-user-images\image-20201220102656673.png)

Actualiza el S.O. 

sudo apt-get update 

 ![image-20201220102703942](C:\Users\jcarl\AppData\Roaming\Typora\typora-user-images\image-20201220102703942.png)

##  

## Upgrade

sudo apt upgrade

 ![image-20201220102718461](C:\Users\jcarl\AppData\Roaming\Typora\typora-user-images\image-20201220102718461.png)

## Instalación del servidor Apache

sudo apt install -y apache2 apache2-utils

 ![image-20201220102725821](C:\Users\jcarl\AppData\Roaming\Typora\typora-user-images\image-20201220102725821.png)

Comprobar el estatus del servidor web

 ![image-20201220102732178](C:\Users\jcarl\AppData\Roaming\Typora\typora-user-images\image-20201220102732178.png)

Mensaje web cd /var/www/html

 ![image-20201220102736776](C:\Users\jcarl\AppData\Roaming\Typora\typora-user-images\image-20201220102736776.png)

Poner nota en la página

 ![image-20201220102741123](C:\Users\jcarl\AppData\Roaming\Typora\typora-user-images\image-20201220102741123.png)

 

Habilito puerto 80

 ![image-20201220102746696](C:\Users\jcarl\AppData\Roaming\Typora\typora-user-images\image-20201220102746696.png)

Comprobante de cambios

 

 ![image-20201220102751600](C:\Users\jcarl\AppData\Roaming\Typora\typora-user-images\image-20201220102751600.png)

 
