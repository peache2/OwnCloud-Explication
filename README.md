# OwnCloud-Manual

## Instalar la versión 7.4 de PHP a Ubuntu 24.04

##### Instalar los requisitos previos para el PPA:
> sudo apt install software-properties-common -y

##### Instala las herramientas necesarias para que podamos trabajar con nuestros archivos personales (PPA).
> LC_ALL=C.UTF-8 sudo add-apt-repository ppa:ondrej/php -y

#####  Usaremos este comando para actualizar los repositorios:
> sudo apt update

##### Instal·la les llibreries de PHP de la versió 7.4
> sudo apt install php7.4 -y
> sudo apt install -y php libapache2-mod-php7.4
> sudo apt install -y php7.4-fpm php7.4-common php7.4-mbstring php7.4-xmlrpc php7.4-soap php7.4-gd php7.4-xml php7.4-intl php7.4-mysql php7.4-cli php7.4-ldap php7.4-zip php7.4-curl
