# 💻 CLASE 02
## 📎 TEORÍA 
### CONCEPTOS NUEVOS
**- UEFI VS BIOS -**<br>
**BIOS (Basic Input/Output System)** y **UEFI (Unified Extensible Firmware Interface)** son tipos de firmware que se usan para iniciar el hardware del computador y cargar el sistema operativo.
- **BIOS:** es el más tradicional y antiguo. Su interfaz es muy simple y solo admite discos de hasta 2 TB y arranque en modo MBR (Master Boot Record). Es menos rápido y seguro.
- **UEFI:** es la versión más moderna que reemplaza a la BIOS. Soporta discos grandes y arranques en modo **GPT (GUID Partition Table)**. Tiene interfaz gráfica, arranque más rápido y funciones como Secure Boot. 

**- BOOTLOADERS -**<br>
El firmware, ya sea BIOS o UEFI, entrega el control a un **bootloader** (cargador de arranque). El bootloader es un pequeño programa cuyo único trabajo es encontrar y cargar el kernel del sistema operativo. Los más conocidos son **GRUB** (usado en la mayoría de distribuciones Linux), y **BOOTMGR** (el gestor de arranque de Windows).

**- TIPOS DE ARRANQUE -**
- **Lecacy (modo de compatibilidad CSM que emula BIOS sobre hardware UEFI):** , útil para sistemas antiguos o herramientas que dependen de MBR.
- **Seguro: (Secure Boot en UEFI):** que valida firmas de los binarios de arranque
- **Múltiple: (multi-boot):** donde uno o varios bootloaders ofrecen un menú para elegir sistema operativo (*ej: GRUB detecta Windows y Linux*). Entender estos roles 4 firmware, esquema de particionado, ESP/MBR y bootloader4 te permite diagnosticar por qué un equipo arranca (o no) y cómo intervenir con precisión.

❓ *Y por cierto, ¿Qué es un firmware? -> un tipo de software básico que está grabado directamente en el hardware de un dispositivo y que permite que que el hardware y el software se comuniquen y que el dispositivo arranque y funcione correctamente*

**- MBR Y GPT -**<br>
Son dos métodos para organizar las particiones en un disco duro.
- **MBR (Master Boot Record)** es más antiguo y tiene límites (como soportar discos de hasta 2 TB).
- **GPT (GUID Partition Table)** es más moderno, no tiene ese límite y funciona mejor con UEFI.

<br>

**- NAT Y BRIDGE -**
- **NAT (Network Address Translation):** La máquina virtual comparte la conexión de red del host. Puede acceder a Internet, pero no es visible directamente en la red local.
- **Bridge (Puente):** La máquina virtual se conecta como si fuera un dispositivo más en la red local. Tiene su propia IP y es visible por otros equipos.

## 📎 ALGUNOS TIPS
👉 **Ping**
- Un ping es una herramienta que se usa para comprobar si un dispositivo en una red (como otro ordenador o servidor) está activo y se puede comunicar.
- El comando `ping` sirve para comprobar si una computadora o servidor está conectado a la red y medir el tiempo de respuesta.
- Ejemplo: `ping google.com`
- Para detener ping, pulsa **Ctrl + z**.

## 📎 TAREAS
📌 **Windows 10**
- Instala Windows 10 en un USB
- Enlace: https://www.microsoft.com/es-es/software-download/windows10 

📌 **Windows Server**
- Instala Windows Server en tu VirtualBox
- Enlace: https://www.microsoft.com/es-mx/evalcenter/download-windows-server-2025

📌 **Tarea avanzada**
- Después de instalar y arrancar Windows server… desde un arranque de recuperación, **¿podrías cambiar la contraseña?**
- Tutorial: https://www.youtube.com/watch?v=ynFVtiI4agc
