## SO-EXAM 1

**Nombre:** Joan Sebastián García Delgado
**Código:** A00329796

## Descripción

Realizar primer parcial del curso Sistemas Operativos Universidad Icesi

## Solución

**1 punto** Nombre y código agregados
**2 punto** Ortografía y redacción

**3 punto**

1. En la página oficial de Debian, en la sección de descargar la ISO, hay un archivo con el nombre SHA1SUMS que hace referencia al código de validación de la primer ISO que fue la que descargamos
https://ibb.co/dwhpjn

2. Una vez dado click en SHA1SUM nos encontramos las claves de verificaciones para las ISO, en nuestro caso nos sirve la primera
https://ibb.co/grmRVS

3. Nos paramos en la carpeta donde descargamos la ISO y para usuarios Linux como yo, ejecutamos el comando --> shasum 'nombreImagen.iso' y este comando nos arrojará la clave de verificación de la hizo descargada
https://ibb.co/eHQaPn

4.Por último validos los dos códigos de verificación que tenemo (el de la página de Debian y el arrojado por el comando) estas dos claves tienen que ser identicas para poder utilizar la hizo con plena confianza.
https://ibb.co/jwtvPn

**4 punto**
Se utilizaron los siguientes comandos para obtener información del SO instalado
   13  cat /proc/cpuinfo
   14  cat /etc/issue
   15  cat /etc/debian_version
   16  uname -m
   17  getconf WORD_BIT
   18  history > comandos.txt

**5 punto**
Se realizó a través de las configuraciones de la VM una configuración de interface tipo puente y se conectó a la VM desde PuttY
https://ibb.co/b77aqS

**6 punto**
Para la instalación de git se debe utilizar el siguiente comando
--> sudo apt-get install git
https://ibb.co/mG9APn
Se oprime la tecla S para continuar la descarga y la instalación

Para la instalación de tig se debe utilizar el siguiente comando
--> sudo apt-get install tig
https://ibb.co/jCvTAS

Adjunto imagen con el historial de commits

**7 Punto**
Para exportar:
1. En la ventana de Virtual Box, en el Menú de la parte superior, oprimimos Archivo->Exportar servicio virtualizado
2. Se le abrirá una ventana con las maquinas virtuales disponibles para virtualizar. PD: Las maquinas tienen que estar apagadas
https://ibb.co/bBJRx7
3. Una vez escogida la VM, le damos click en Siguiente y ahora escogemos el formato OVF de la VM y el destino de almacenamiento
https://ibb.co/ij3FqS
4. Damos CLick en siguiente, modificamos si queremos algunos datos de la VM
https://ibb.co/hGHaqS
5. Por último damos Click en Exportar y esperamos que VirtualBox exporte la maquina
https://ibb.co/kqpYc7

Para importar:
1. En la ventana de Virtual Box, en el menú de la parte superior, oprimimos Archivo->Importar servicio virtualizado
2. Se abrirá una ventana para escoger la VM a importar
https.//ibb.co/dvY4jn
3. Damos Click en siguiente y verificamos los datos de la VM
https://ibb.co/d5pc4n
4. Por último damos click en Importar y esperamos que Virtual Box importe la maquina
htpps://ibb.co/dzdFqS

**8 punto**
https://ibb.co/jtSGVS

**9 punto**
https://github.com/ikermatias/so-exam1
