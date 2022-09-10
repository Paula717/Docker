# <b>Instalar Docker en Windows 10</b>

<b><u>Requisitos minimos</u></b>

<cite style="display:block; text-align: justify">

* Windows 10 64-bit: Pro, Enterprise, or Education (Build 16299 o superior).
* Procesador de 64 bits.
* 4 GB RAM.
* Habilitar en la BIOS la característica (el nombre varia en función del procesador que tenga tu equipo) “Intel VR” o “VR-x” o “Virtualization Technology” o «AMD-V».</cite>

# <b>Instalar Docker </b>

<cite style="display:block; text-align: justify">No existe una versión de docker que funcione de forma nativa en Windows 10 sino que lo que realmente vamos a hacer es crear una máquina virtual en Hyper-V con docker embebido la cual nos permitirá ejecutar comandos de forma transparente desde la consola de Powershell o MS-DOS como si realmente la aplicación se ejecutara de forma nativa.

Lo primero que haremos sera activar la característica Hyper-V en nuestro Windows.

Escribimos Caracteristicas de Windows.</cite>

![instalacion](img_Instalacion/img01.png)

<cite style="display:block; text-align: justify"> Buscamos y marcamos la opción Hyper-V, pulsamos en Aceptar para realizar la instalación de la característica.</cite>

![instalacion](img_Instalacion/img02.png)

<cite style="display:block; text-align: justify"> Una vez finalizada la instalación, reiniciamos nuestro equipo para que se guarden y se apliquen los cambios realizados. </cite>

![instalacion](img_Instalacion/img03.png)

<cite style="display:block; text-align: justify"> Una vez activado Hyper-V y reiniciado el equipo el siguiente paso será descargar el instalador de Docker Desktop, para eso nos dirigimos a la pagina de [Docker Docs][1_0], la cual nos proporcionara un enlace directo para descargar [Docker Desktop en Windows][1_1].</cite>

[1_0]:https://docs.docker.com/desktop/install/windows-install/

[1_1]:https://desktop.docker.com/win/main/amd64/Docker%20Desktop%20Installer.exe

![instalacion](img_Instalacion/img04.png)

<cite style="display:block; text-align: justify"> Una vez descargado el instalador, lo ejecutamos.</cite>



# Mas Información
* [Instalar Docker en Windows 10][2_1]
* [Docker oficial][2_2]


[2_1]:https://tutorialesit.com/instalar-docker-en-windows-10/
[2_2]:https://www.docker.com/

