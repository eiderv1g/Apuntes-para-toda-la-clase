# 💻 CLASE 01
## 📎 TEORÍA 
### CONCEPTOS BÁSICOS: SO, KERNELL Y LLAMADAS AL SISTEMA
- **Sistema Operativo:** Un sistema operativo (SO) es el software principal de una computadora o dispositivo que se encarga de:<br>
· Controlar el hardware (procesador, memoria, disco, pantalla, etc.)<br>
· Administrar los recursos del sistema<br>
· Permitir la ejecución de programas<br>
· Facilitar la interacción entre el usuario y la máquina

- **Kernell:** núcleo del SO. Es responsable de las funciones críticas: administrar la memoria, asignar tiempo de CPU, comunicarse con los dispositivos de entrada y salida, o garantizar que un programa no interfiera con otro. Sin él, tu ordenador sería un conjunto de piezas incapaces de trabajar juntas.

- **Llamadas al Sistema:** son los mecanismos que permiten a un programa pedirle servicios al sistema operativo, como acceder a archivos, usar la memoria, comunicarse por red o controlar dispositivos.

- **Linux:** es un sistema operativo libre y de código abierto basado en Unix, usado en computadoras, servidores, dispositivos móviles y sistemas embebidos.

- **Distribuciones de Linux:** son sistemas operativos completos que combinan el kernel Linux con programas, herramientas y un entorno gráfico.

- **Virtualización:** es una tecnología que permite crear versiones virtuales de recursos físicos, como computadoras, servidores, sistemas operativos o discos, para que funcionen de forma independiente en un mismo equipo.<br> *Puedes tener Windows y Linux funcionando al mismo tiempo en una misma PC gracias a la virtualización.*

## 📎 ALGUNOS TIPS
👉 **Comandos**
- `uname` nos muestra información del sistema operativo y del kernel.
- `dmesg` muestra los mensajes del kernel (arranque del sistema, dispositivos, errores, hardware, USB, discos, etc.)
- `touch archivo2` te crea un archivo nuevo llamado "archivo2"
- `strace touch archive2` muestra qué es lo que pasa o qué llamadas al sistema suceden al ejecutar "touch archive2"

👉 **DistroSea**
- Nos permite probar diferentes distribuciones de Linux de manera online.
- Enlace: https://distrosea.com/es/

## 📎 TAREAS
👉 **Sysinternals**
- Instalar las herramientas de Sysinternals
- Enlace:  https://learn.microsoft.com/es-es/sysinternals/downloads/sysinternals-suite

👉 **Virtualización**
- Instalar un gestor de virtualización como virtualbox 
- Enlace: https://www.virtualbox.org/

**Para habilitar la virtualización, hay que hacerlo desde la BIOS. Yo encontré la info por youtube, hay varios vídeos con distintas interfaces según el ordenador y tal. No es difícil de hacer.* 

👉 **Ubuntu**
- Descarga e intenta instalar Ubuntu para Linux 
- Enlace: https://ubuntu.com/download/server

👉 **SSH**
- Descarga e intenta instalar el paquete SSH
- Enlace: https://www.ionos.es/digitalguide/fileadmin/DigitalGuide/Screenshots_2022/ubuntu-server-ssh-setup.png<br>
<img src= "img/ubuntu-server-ssh-setup.png" width="500">