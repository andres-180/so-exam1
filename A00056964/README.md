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




