Login con Command Line Interface instalado

az login 



 ![login](https://github.com/CastilloGit/AZ900_PRACTICA_VM_UBUNTU_AZCLI/blob/main/img/img1.png)

Creación del grupo de recursos

 ![login](https://github.com/CastilloGit/AZ900_PRACTICA_VM_UBUNTU_AZCLI/blob/main/img/img2.png)

Creación de recursos bajo el grupo

 ![login](https://github.com/CastilloGit/AZ900_PRACTICA_VM_UBUNTU_AZCLI/blob/main/img/img3.png)

Comprobante en el portal de Azure del grupo de recursos

 ![login](https://github.com/CastilloGit/AZ900_PRACTICA_VM_UBUNTU_AZCLI/blob/main/img/img4.png)

 

Da error en el login ssh hago reset de password (Pa$$w0rd12345) dentro de la máquina virtual creada.

 ![login](https://github.com/CastilloGit/AZ900_PRACTICA_VM_UBUNTU_AZCLI/blob/main/img/img5.png)

 

Conecto por ssh a la máquina virtual

 ![login](https://github.com/CastilloGit/AZ900_PRACTICA_VM_UBUNTU_AZCLI/blob/main/img/img6.png)

Actualiza el S.O. 

sudo apt-get update 

 ![login](https://github.com/CastilloGit/AZ900_PRACTICA_VM_UBUNTU_AZCLI/blob/main/img/img7.png)

##  

## Upgrade

sudo apt upgrade

 ![login](https://github.com/CastilloGit/AZ900_PRACTICA_VM_UBUNTU_AZCLI/blob/main/img/img8.png)

## Instalación del servidor Apache

sudo apt install -y apache2 apache2-utils

 ![login](https://github.com/CastilloGit/AZ900_PRACTICA_VM_UBUNTU_AZCLI/blob/main/img/img9.png)

Comprobar el estatus del servidor web

 ![login](https://github.com/CastilloGit/AZ900_PRACTICA_VM_UBUNTU_AZCLI/blob/main/img/img10.png)

Mensaje web cd /var/www/html

 ![login](https://github.com/CastilloGit/AZ900_PRACTICA_VM_UBUNTU_AZCLI/blob/main/img/img11.png)

Poner nota en la página

 ![login](https://github.com/CastilloGit/AZ900_PRACTICA_VM_UBUNTU_AZCLI/blob/main/img/img12.png)

 

Habilito puerto 80

 ![login](https://github.com/CastilloGit/AZ900_PRACTICA_VM_UBUNTU_AZCLI/blob/main/img/img13.png)

Comprobante de cambios

 

![login](https://github.com/CastilloGit/AZ900_PRACTICA_VM_UBUNTU_AZCLI/blob/main/img/img14.png)

 
