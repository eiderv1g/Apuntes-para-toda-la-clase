# 💻 CLASE 02
## 📎 TEORÍA 
### ALGUNOS CONCEPTOS NUEVOS:

**-Diferencias entre carpeta y repositorio-**<br>
Una **carpeta** Una carpeta es un contenedor en la computadora que sirve para organizar archivos (documentos, imágenes, programas, etc.).
- Guarda archivos
- Sin control de versiones
- Sin seguimiento de cambios
- No permite trabajar en equipo
- Sirve para organización personal

Un **repositorio** es un proyecto que almacena archivos junto con su historial de cambios, usando un sistema de control de versiones como Git. Puede estar en tu computadora o en línea (por ejemplo, en GitHub).
- Guarda archivos y su historial
- Tiene control de versiones (**Git**)
- Tiene seguimiento de cambios (**commits**)
- Permite trabajar en equipo
- Se usa mucho para desarrollo de Software

**-Git-**<br>
Git es un sistema de control de versiones distribuido, creado por Linus Torvalds en 2005, que permite a los desarrolladores registrar los cambios en el código fuente de un proyecto a lo largo del tiempo y colaborar con otras personas de forma eficiente.

**-Encabezados-**
- `<h1>Encabezado mega importante</h1>`
- `<h2>Encabezado importante</h2>`
- `<h3>Encabezado no tan importante</h3>`
- `<h4>Encabezado poco importante</h4>`
- `<h5>Encabezado poquito importante</h5>`
- `<h6>Encabezado menos importante</h6>`

## 📎 ALGUNOS TIPS
👉 **Para esta clase...**
- Ten siempre a mano el **pdf de la Unidad 1** (*en recursos extra de la asignatura*) 
- Tienes que tener **Visual Studio Code instalado** https://code.visualstudio.com/
- Instala las **extensiones** que pasó Olga ([enlaces](resumen-clase01))
- Tienes que haberte creado una **cuenta en GitHub** https://github.com/ y haberla **sincronizado** con tu VSCode
- Tienes que haberte **instalado Git** https://git-scm.com/
- Instálate también esta extensión: **Git Graph** https://marketplace.visualstudio.com/items?itemName=mhutchie.git-graph

👉 **Cómo abrir Git en Visual Studio Code**
1. En la interfaz de VSC, vamos a la barra de arriba y buscamos Terminal
2. Terminal > New Terminal > Se nos abre una terminal en la parte inferior de la interfaz
3. En este nuevo recuadro, en la barra de arriba seleccionamos el símbolo que hay junto al +, se nos despliega una lista y si lo habéis instalado correctamente (https://git-scm.com/) os aparecerá la opción de Git Bash. Le damos
4. Ya lo tenemos. Además, verás todas las consolas que tienes abiertas en la columna de la derecha. Puedes cerrar las que no estés usando y quedarte solo con la de Git Bash

- **Configurar usuario y e-mail**<br>
· git config --global user.name "Nombre Apellido"<br>
· git config --global user.email email@dominio.com

👉 **Cómo subir nuestro código y modificaciones a nuestra cuenta de GitHub**

*Primero que nada, ¿esto por qué es útil? No solo para compartir código en, por ejemplo, equipos de trabajo, sino también para almacenar nuestros proyectos y recuperarlos desde GitHub en caso de que lo perdamos en nuestro equipo, como si de una nube se tratase.*

```0. Creamos en la ubicación deseada una carpeta, la abrimos desde VSC y creamos un nuevo archivo html dentro de esta carpeta (podréis ver la carpeta y su contenido en la pestaña del explorador, a la izquierda)
1. Ahora, vamos a crear un repositorio. Lo podemos hacer de dos formas distintas:

- Desde la bash de Git -> en la consola, escribimos el comando git init y pulsamos Enter
-  En la izqda. del todo de la interfaz de VSC, nos vamos a la pestaña de Source Control y le damos al botón de Iniciar Repositorio 

2. Nos vamos al código de nuestro archivo html y le hacemos algunas modificaciones (lo que queráis, por ejemplo, añadirle comentarios, algún párrafo extra en el body, etc.)

3. En la pestaña de Source Control, en el recuadro vacío que pone “Mensaje” podemos nombrar a estos cambios como queramos. Después le damos a botón de Commit (o como sea en español) y por último a Publish Branch

4. Si sincronizasteis bien vuestro VSC con la cuenta de GitHub, el repositorio se subirá correctamente a la misma. Id a vuestra cuenta y comprobadlo (buscad en repositorios) Ahí debería estar vuestro proyecto

5. En Git Hub, si abrís vuestro archivo, en la pestaña de code veréis su código. En la pestaña Blame, veréis su historial de modificaciones
```

👉 **Cómo nos bajamos (clonar) este repositorio desde nuestra cuenta de GitHub**

*Vamos a imaginar que hemos perdido o se nos ha borrado la carpeta que creamos antes con nuestro nuevo archivo html (vamos, que te la borres). ¡Que no cunda el pánico! Vamos a recuperar ese proyecto gracias a que lo habíamos subido en GitHub*

```1. Vamos a nuestro proyecto en GitHub (buscad en el icono de vuestro perfil y darle a “Repositories”)

2. Seleccionamos nuestro proyecto. Una vez abierto le damos a la pestañita verde de “<> Code”y copiamos la url que aparece

3. Abrimos VSC, y abrimos la carpeta en la que queremos clonar nuestro proyecto

4. abrimos nuestra terminal Git y ejecutamos el siguiente comando: 
git clone “la url que hemos copiado, sin entrecomillarla”

5. Pues ya lo tenemos
```

👉 **Comandos para el BASH de Git (*tipo Linux*)**
- `ls` nos muestra lo que tenemos en el directorio actual
- `ls -la` nos muestra archivos ocultos
- `clear` nos limpia la terminal
- `git init` inicia un repositorio. Fíjate que se añade una “U” junto al nombre de nuestro archivo, en el explorador
- `git log` para ver todo el historial de cambios
- `git clone url de nuestro repositorio` nos descarga el código del repositorio que tenemos colgado en Git Hub en la ubicación en la que nos hallemos
- `pwd` nos indica cual es nuestra ubicación actual

👉 **Configurar usuario y e-mail**
- `git config --global user.name "Nombre Apellido"`
- `git config --global user.email email@dominio.com`

## 📎 TAREAS
📌 **Dale caña**<br>
Practica todo lo visto en los 📎**TIPS** de este resumen:
- Abrir Git en Visual Studio Code
- Configurar nuestro usuario y mail
- Probar la sincronización de cambios
- Practicar todos los códigos html y comandos nuevos



⚠️⚠️⚠️ **No olvides consultar y repasar exhaustivamente los apuntes de la asignatura en la plataforma. Si solo estudias la teoría a partir de estos mini-resúmenes, probablemente te falten muchos conceptos para poder aprobar el exámen. Estos resúmenes son una ayuda extra y desinteresada, no la guía oficial para sacarse el grado. ¡¡Ánimo y a por ello!!**