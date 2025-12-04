# 💻 CLASE 0X
## 📎 PRÁCTICA RAID 5
**¿Qué es RAID 5?**

**-HACER UN RAID 5-**
- Abre Ubuntu Server
- Se crean 3 discos:<br>
· 3 discos de 500MB<br>
· Podéis guardar estos discos, por ejemplo, en la misma carpeta donde tengáis el Ubuntu instalado<br>
· *Si tenéis discos ahí de antes, no hace falta que los quitéis ni que los eliminéis ni nadaaa.*

**Vamos a ver si Linux reconoce estos discos...**
- Arrancamos Ubuntu
- Ejecutamos el comando ya visto de `sudo dmesg | grep "sd"`
- Apuntamos los discos con los que vamos a instalar el RAID
- Vamos a usar el comando (*Si no estuviese instalado este comando, escribiríamos: `sudo apt-get update` para actualizar, y luego lo instalaríamos con `sudo apt-get install -y mdadm`*)

- `sudo mdadm --create /dev/md0 --level=5 --raid-devices=3 /dev/sdb /dev/sdc /dev/sdd` (*Siendo sdb, sdc y sdd los discos que hemos instalado hoy*)


