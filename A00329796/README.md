## SO-EXAM 1

**Nombre:** Joan Sebastián García Delgado
**Código:** A00329796

## Descripción

Realizar primer parcial del curso Sistemas Operativos Universidad Icesi

## Solución

**1 punto** Nombre y código agregados 

**2 punto** Ortografía y redacción

**3 punto**

1. En la página oficial de Debian, en la sección de descargar la ISO, hay un archivo con el nombre SHA1SUMS que hace referencia al código de validación de la primer ISO que fue la que descargamos.

<a href="https://imgbb.com/"><img src="https://image.ibb.co/bO6FPn/Captura_de_pantalla_de_2018_03_27_14_50_20.png" alt="Captura de pantalla de 2018 03 27 14 50 20" border="0" /></a>

2. Una vez dado click en SHA1SUM nos encontramos las claves de verificaciones para las ISO, en nuestro caso nos sirve la primera.

<a href="https://imgbb.com/"><img src="https://image.ibb.co/dtJJc7/Captura_de_pantalla_de_2018_03_27_14_51_11.png" alt="Captura de pantalla de 2018 03 27 14 51 11" border="0" /></a>

3. Nos paramos en la carpeta donde descargamos la ISO y para usuarios Linux como yo, ejecutamos el comando -->
~~~
shasum 'nombreImagen.iso' 
~~~
y este comando nos arrojará la clave de verificación de la hizo descargada.
<a href="https://ibb.co/eHQaPn"><img src="https://preview.ibb.co/gq09jn/Captura_de_pantalla_de_2018_03_27_14_52_15.png" alt="Captura de pantalla de 2018 03 27 14 52 15" border="0" /></a>

4.Por último validos los dos códigos de verificación que tenemo (el de la página de Debian y el arrojado por el comando) estas dos claves tienen que ser identicas para poder utilizar la hizo con plena confianza.
<a href="https://ibb.co/jwtvPn"><img src="https://preview.ibb.co/gMZfqS/Captura_de_pantalla_de_2018_03_27_14_56_16.png" alt="Captura de pantalla de 2018 03 27 14 56 16" border="0" /></a>

**4 punto**

Se utilizaron los siguientes comandos para obtener información del SO instalado.
~~~
   13  cat /proc/cpuinfo
   14  cat /etc/issue
   15  cat /etc/debian_version
   16  uname -m
   17  getconf WORD_BIT
   18  history > comandos.txt
   ~~~

**5 punto**

Se realizó a través de las configuraciones de la VM una configuración de interface tipo puente y se conectó a la VM desde PuttY. 
<a href="https://imgbb.com/"><img src="https://image.ibb.co/dv84jn/Captura_de_pantalla_de_2018_04_01_20_23_53.png" alt="Captura de pantalla de 2018 04 01 20 23 53" border="0" /></a> 

**6 punto**

Para la instalación de git se debe utilizar el siguiente comando.
~~~
--> sudo apt-get install git 
~~~ 
<a href="https://ibb.co/mG9APn"><img src="https://preview.ibb.co/dnuc4n/Captura_de_pantalla_de_2018_04_01_20_35_12.png" alt="Captura de pantalla de 2018 04 01 20 35 12" border="0" /></a> 

Se oprime la tecla S para continuar la descarga y la instalación. 

Para la instalación de tig se debe utilizar el siguiente comando.
-->
~~~
sudo apt-get install tig
~~~ 
<a href="https://ibb.co/jCvTAS"><img src="https://preview.ibb.co/ccgeH7/Captura_de_pantalla_de_2018_04_01_21_45_46.png" alt="Captura de pantalla de 2018 04 01 21 45 46" border="0" /></a>

Adjunto imagen con el historial de commits.

<a href="https://ibb.co/bXCGHH"><img src="https://preview.ibb.co/bHmMjx/Captura_de_pantalla_de_2018_04_01_23_19_52.png" alt="Captura_de_pantalla_de_2018_04_01_23_19_52" border="0"></a>

**7 Punto**

Para exportar:
1. En la ventana de Virtual Box, en el Menú de la parte superior, oprimimos Archivo->Exportar servicio virtualizado.
2. Se le abrirá una ventana con las maquinas virtuales disponibles para virtualizar. PD: Las maquinas tienen que estar apagadas.

<a href="https://imgbb.com/"><img src="https://image.ibb.co/iOPMVS/Captura_de_pantalla_de_2018_04_01_21_49_06.png" alt="Captura de pantalla de 2018 04 01 21 49 06" border="0" /></a>

3. Una vez escogida la VM, le damos click en Siguiente y ahora escogemos el formato OVF de la VM y el destino de almacenamiento.

<a href="https://imgbb.com/"><img src="https://image.ibb.co/nE7x4n/Captura_de_pantalla_de_2018_04_01_21_49_53.png" alt="Captura de pantalla de 2018 04 01 21 49 53" border="0" /></a>

4. Damos CLick en siguiente, modificamos si queremos algunos datos de la VM.

<a href="https://imgbb.com/"><img src="https://image.ibb.co/kEkjjn/Captura_de_pantalla_de_2018_04_01_21_50_21.png" alt="Captura de pantalla de 2018 04 01 21 50 21" border="0" /></a>

5. Por último damos Click en Exportar y esperamos que VirtualBox exporte la maquina.

<a href="https://imgbb.com/"><img src="https://image.ibb.co/hODFqS/Captura_de_pantalla_de_2018_04_01_21_50_47.png" alt="Captura de pantalla de 2018 04 01 21 50 47" border="0" /></a>

Para importar:
1. En la ventana de Virtual Box, en el menú de la parte superior, oprimimos Archivo->Importar servicio virtualizado.
2. Se abrirá una ventana para escoger la VM a importar.

<a href="https://ibb.co/dvY4jn"><img src="https://preview.ibb.co/kO5vqS/Captura_de_pantalla_de_2018_04_01_22_03_58.png" alt="Captura de pantalla de 2018 04 01 22 03 58" border="0" /></a>

3. Damos Click en siguiente y verificamos los datos de la VM.

<a href="https://ibb.co/d5pc4n"><img src="https://preview.ibb.co/iMA6x7/Captura_de_pantalla_de_2018_04_01_22_04_12.png" alt="Captura de pantalla de 2018 04 01 22 04 12" border="0" /></a>

4. Por último damos click en Importar y esperamos que Virtual Box importe la maquina.

<a href="https://imgbb.com/"><img src="https://image.ibb.co/e85vqS/Captura_de_pantalla_de_2018_04_01_22_04_29.png" alt="Captura de pantalla de 2018 04 01 22 04 29" border="0" /></a>

**8 punto**

<a href="https://imgbb.com/"><img src="https://image.ibb.co/fepVqS/Captura_de_pantalla_de_2018_04_01_23_16_26.png" alt="Captura de pantalla de 2018 04 01 23 16 26" border="0" /></a>

**9 punto**
https://github.com/ikermatias/so-exam1
