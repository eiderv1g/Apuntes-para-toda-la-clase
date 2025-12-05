
[**Clase siguiente →**](clase04.md)

[**← Clase anterior**](clase02.md)

# 💻 CLASE 03
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

## 📎 TAREAS
📌 **Windows 10**
- Instala Windows 10 en un USB
- Enlace: https://www.microsoft.com/es-es/software-download/windows10 

📌 **Windows Server**
- Instala Windows Server en tu VirtualBox
- Enlace: https://www.microsoft.com/es-mx/evalcenter/download-windows-server-2025
- Un tutorial muy útil: https://www.youtube.com/watch?v=5wJ_x5qudto&t=618s 

📌 **Tarea avanzada**
- Después de instalar y arrancar Windows server… desde un arranque de recuperación, **¿podrías cambiar la contraseña?**
- Tutorial: https://www.youtube.com/watch?v=ynFVtiI4agc
<br><br> 

[**Clase siguiente →**](clase04.md)

[**← Clase anterior**](clase02.md)