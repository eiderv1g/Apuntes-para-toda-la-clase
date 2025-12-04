[**Clase siguiente →**](resumen-clase07.md)

[**← Clase anterior**](resumen-clase05.md)
# 💻 CLASE 06
## 📎 CÓDIGO
### MULTIMEDIA

**AUDIO**
- Básico y con un atributo de **controls**:<br>
`<audio src="archivo.mp3" type="audio/mp3" controls></audio>`

- Atributos de: **loop, autoplay**<br>
`<audio src="archivo.mp3" type="video/mp4" **autoplay loop** controls></audio>`

**IMÁGENES**
- Básico con la etiquete `<figure>`
```
<figure>
  <img src="imagen.jpg" alt="Descripción de la imagen">
  <figcaption>Esta es la descripción de la imagen</figcaption>
</figure>
```

- `<figure>` → Contenedor del contenido visual
- `<img>` → Imagen o contenido visual
- `<figcaption>` → Pie de foto o descripción del contenido

**VIDEO**
- Básico:<BR>
 `<video width="400px" src="../video/tiposredesVideo.mp4" controls type="video/mp4"></video>`

- También pueden usarse atributos de: **controls, autoplay, loop, muted**<br>
`<video width="400px" src="../video/tiposredesVideo.mp4" type="video/mp4" controls autoplay loop muted></video>`

- Para videos de Youtube<br>
`<iframe width="454" height="807" src="https://www.youtube.com/embed/XCs2Ga2dWYY"
        title="Etiquetas básicas de lenguaje de marcado HTML." frameborder="0"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
        referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>`

**CANVAS**
- Sirve para dibujar gráficos y generar contenido visual de forma dinámica usando JavaScript:
```
<canvas id="canvas2">
        <script>
            let c = document.getElementById("canvas2");
            let ctx = c.getContext("2d");
            ctx.fillStyle = "lightblue";
            ctx.fillRect(10, 10, 100, 100);
            ctx.fillStyle = "red";
            ctx.font = "20px Arial";
            ctx.fillText("Hola!", 30, 65);
        </script>
    </canvas>
```

⚠️*OJO!!! Aquí tenemos código embebido, es decir, hemos metido un script de javascript en nuestro html. Esto NO ES una práctica recomendada, pero en este ejemplo se hace únicamente con fines didácticos*

### MÁS FORMULARIOS: REPASO Y COSITAS NUEVAS

**ETIQUETAS PRINCIPALES**

- `<form>` Contenedor del formulario; envía los datos al servidor.
- `<input>` Campo de entrada (*texto, número, email, password, etc.*).
- `<label>` Etiqueta descriptiva asociada a un input.
- `<textarea>` Campo para texto largo (varias líneas).
- `<select>` Menú desplegable.
- `<option>` Opciones dentro de un select
- `<button>` Botón (enviar, reset o acciones personalizadas).

**INPUTS MÁS COMUNES**
- `text` Texto corto.
- `password` Contraseñas (oculta caracteres).
- `email` Validación básica de correo.
- `number` Números con min, max y step.
- `radio` Selección única entre varias opciones.
- `checkbox` Selección múltiple.
- `date, time, datetime-local` Fecha y hora.
- `file` Subir archivos.
- `range` Selector numérico tipo barra deslizante.
- `color` Selector de color.

**ATRIBUTOS HTML MODERNOS**

- `required` Indica que el campo es obligatorio antes de enviar el formulario
- `placeholder` Texto guía dentro del campo que desaparece al escribir.
- `pattern` Expresión regular para validar el formato del contenido del input.
- `autofocus` Hace que el cursor se sitúe automáticamente en ese campo al cargar la página.
- `autocomplete` Controla si el navegador sugiere datos guardados (*ej.: on / off*).
- `min,max` Establecen valores mínimo y máximo permitidos en campos numéricos, fechas, etc.
- `step` Define el incremento permitido entre valores (*ej.: de 2 en 2*).
- `size` Establece el ancho visible del campo (en caracteres).
- `readonly` Campo solo de lectura; se muestra pero no se puede editar, aunque sí se envía.
- `disabled` Desactiva el campo; no se puede usar y no se envía con el formulario.
- `pattern` Se usa para definir una expresión regular que valide el formato del texto ingresado en un campo `<input>` antes de enviar el formulario.
Si el contenido no cumple el patrón, el formulario no se envía.

## 📎 TAREAS
📌 **Ejercicio formulario**<br>
- Ejercicio 3 en la carpeta HTML<br>
- Enlace: https://github.com/olga3emes/proyectos


## 📎 EXTRAS
- El servicio Antibotnet de OSI: https://chromewebstore.google.com/detail/osi-servicio-antibotnet/hhljghnmjahiaofikeljkjnhbeoiclbh?pli=1
- PHIND, un buscador de IA bastante útil: https://www.phind.com/
- Deepseek, otra IA: https://www.deepseek.com/
- Enlaces útiles para desarrollo: https://developer.mozilla.org/en-US/ || https://www.w3.org/

[**Clase siguiente →**](resumen-clase07.md)

[**← Clase anterior**](resumen-clase05.md)
