En este documento se ensuentra la solución del parcial 1:   
Punto 1:   
Nombre: Andrés Felipe Pérez Belalcazar   
Código: A00056964   
   
Punto 3:   
Para validar la imagen    
1) Una vez descargada (el link de descarga es: https://www.debian.org/distrib/netinst#smallcd), debemos acceder a: https://cdimage.debian.org/debian-cd/current/amd64/iso-cd/MD5SUMS para poder ver el checksum de lo que hemos descargado.   
2) Descargamos el programa que obtendra el checksum de la imagen descargada de: http://download.cnet.com/MD5-SHA-Checksum-Utility/3001-2092_4-10911445.html lo ejecutamos y elegimos la imagen de debian que hemos descargado en el campo "File". El programa automáticamente generará el MD5 y los SHA (utilizados para encriptar).    
3) En el campo "Hash" pegamos el checksum obtenido en el paso 1, en nuestro caso es el codigo que esta al lado del campo "debian-9.4.0-amd64-netinst.iso"  
4) Hacemos clic en verify y nos aparecerá un cuadro de dialogo confirmando que la imagen es correcta o lo contrario.

Punto 4:
Instalación de debian 9 e información del SO
1) Abrimos el programa VirtualBox y damos clic en la opción "Nueva".
2) Configuramos el nombre, tipo y versión de SO a instalar (en este caso es Linux, Debian) y damos clic en "Siguiente"
3) Asignamos la cantidad de RAM a usar, en mi caso elegí 4GB y damos clic en "Siguiente".
4) Damos clic en "Crear".
5) Damos clic en "siguiente".
6) Elegimos el tipo de almacenamiento que deseamos, dinámico (recomendado) o fijo. En cualquiera de los dos casos le asignamos un espacio en disco y damos clic en crear.
7) Procedemos a iniciar la máquina Debian, para esto en Virtualbox damos clic en "iniciar" y luego debemos elegir la imagen de la Debian para poder arrancar la instalación del SO.
8) A continuación configuramos el idioma regional y del teclado (en mi caso español para ambos) y damos clic en "Continuar".
9) Luego nos pedirá un dominio de red, lo podemos dejar en blanco y damos clic en "Continuar".
10) En el campo "clave del superusuario" escribimos la contraseña de root que el el usuario principal que utiliza Linux, la confirmamos y damos clic en "Continuar". 
11) Creamos un nuevo usuario, de damos un nombre y una contraseña, damos clic en continuar y esperamos a que realize las connfiguraciones pertinentes.
12) Nos aparecerá la ventana de particionamiento de discos, en esta parte se encuentras varias opciones, seleccionamos "Instalación guiada" - uso completo del disco y damos clic en "Continuar".
13) A continuación damos clic en las siguientes opciones por defecto hasta llegar a la vista de la información de las particiones, seleccionamos la deseada (en mi caso la física) y damos clic en "Siguiente". El sistemas nos preguntara si deseamos escribir los cambios en en disco asi que seleccionamos "Si" y damos clic en continuar. El sistema continuará configurando el volumen.
14) Nos pedirá que configuremos la unidad de CD/DVD, en mi caso no lo deseo hacer, asi que elegimos la opción "No" y damos clic en "Continuar".
15) En la ventana "Configurar el gestor de paquetes" selecionamos "Colombia" y elegimos un mirror de los que aparecen disponibles. Damos clic en "Continuar".
16) Damos clic en "Continuar" si no deseamos configurar el proxy y esperamos a que terminen las configuraciones.
17) Nos preguntara accerca de una encuesta sobre los paquetes, seleccionamos "No" (a menos que la quiera hacer) y damos clic en "Continuar".
18) A continuación apareceran una lista de paquetes adicionales que se pueden instalar (son opcionales) en mi caso selecciono "SSH server" que posiblemente sea usado más adelante y damos clic en "Continuar".
19) Esperamos a que las configuraciones terminen (este proceso puede tardar un poco).











