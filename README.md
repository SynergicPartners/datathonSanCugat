
##Instalacion git

Debian/Ubuntu

    apt-get install git

Fedora

    yum install git

Gentoo

    emerge --ask --verbose dev-vcs/git

Arch Linux

    pacman -S git

openSUSE

    zypper install git

FreeBSD

    cd /usr/ports/devel/git
    make install

Solaris 11 Express

    pkg install developer/versioning/git

OpenBSD

    pkg_add git

Win:  http://msysgit.github.io/


##Como usar git (clone, add, commit, push, checkout)

Clonar al directorio actual y entrar en la carpeta

    git clone https://github.com/SynergicPartners/hackatonsyn.git
    cd datatonSanCugat

Añadir uno a todos los ficheros nuevos generados en local

    git add <filename>
    git add .

Hacer commit de nuestros datoa cambiados reportando el cambio con mensaje

    git commit -m "Cambio en ..."

Actualizar definitivamente los cambios a repositorio siendo target: master, <nombre del branch el cual estamos trabajando>

    git push origin <target>

Crea una nueva rama llamada "rama1" y trabajar en ella

    git checkout -b rama1

##Herramientas para desarrollar

| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |


