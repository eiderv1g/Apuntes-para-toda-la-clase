[**Clase siguiente →**](resumen-clase04.md)

[**← Clase anterior**](resumen-clase02.md)
# 💻 CLASE 03
## 📎 TEORÍA
### ALGUNOS CONCEPTOS NUEVOS:
**Etiqueta HTML:** es una instrucción que se usa para definir la estructura y el contenido de una página web.

**Diferencia entre etiquetas semánticas y no semánticas:**
| Etiquetas semánticas              | Etiquetas no semánticas             |
| --------------------------------- | ----------------------------------- |
| Tienen significado                | No tienen significado               |
| Indican qué contiene el bloque    | Solo agrupan o dan estilo           |
| Mejoran la accesibilidad y el SEO | No aportan información al contenido |


**Atributos HTML:** son propiedades que se añaden a las etiquetas para darles información extra o modificar su comportamiento.

## 📎 CÓDIGO 

### ETIQUETAS HTML
- Enlaces: `<a href="https://www.google.com">Visita Google</a>`
- Párrafos: `<p>Este es un párrafo de ejemplo en mi página web</p>`
- Línea separadora: `<hr>` ó `<hr/>` (nunca `</hr>`)
- Salto de línea: `<br>`

### FORMATOS EN HTML 
*>> OJO!! evitad usar esto y reservad hacer las cosas bonitas para CSS*
- `<b>negrita</b>` /o `<strong>` para semántica
- `<i>cursiva</i>` /o `<em>` para semántica
- `<u>subrayado</u>`
- `<mark>resaltado</mark>`
- `<del>tachado</del>`
- `<small>texto pequeño</small>`
- `<sup>superíndice</sup>`
- `<sub>subíndice</sub>`
- `<big>texto grande</big>`

### LISTAS HTML: SINTÁXIS BÁSICA 

```
<ul> 
    <li>Elemento de lista 1</li> 
    <li>Elemento de lista 2</li> 
    <li>Elemento de lista 3</li> 
</ul> 

<ol> 
    <li>Elemento de lista ordenada 1</li> 
    <li>Elemento de lista ordenada 2</li> 
    <li>Elemento de lista ordenada 3</li> 
</ol>

```
### ATRIBUTOS HTML
- **href** se usa para especificar la URL o ruta a la que apunta el enlace o recurso<br>
`<a href="https://www.google.com/">Visita Google</a>` 
 
- **id** se usa para identificar de forma única un elemento dentro de una página web<br>
`<p id="nombre"> párrafo </p>`

- **name** identifica un elemento<br>
`<p id="nombre" name="nombre">párrafo</p>`

### ENLAZAR DISTINTAS PARTES DE UNA MISMA PÁGINA 
Digamos que en una página en la que hay que hacer mucho scroll, queremos tener una forma sencilla de ir desde el principio de la página hasta el final: 

1.	Al principio de nuestra página, tenemos un párrafo en el que pone "PRINCIPIO DE LA PÁGINA"<br> 
`<p> PRINCIPIO DE LA PÁGINA </p>`  

2.	Al final de nuestra página, tenemos un párrafo en el que pone "FINAL DE LA PÁGINA"<br> 
`<p> FINAL DE LA PÁGINA </p>` 

3.	Añadimos identificadores a estos párrafos (inicio y final)<br> 
```
<p id="inicio"> PRINCIPIO DE LA PÁGINA </p>

(...) 

<p id="final"> FINAL DE LA PÁGINA </p>
```

4.	Y ahora, ¡vamos a enlazar! Usaremos `#` seguido del identificador correspondiente: <br>
`<a href="#final">Ir al final</a>` 
-> Para que al pulsar "Ir al final" nos lleve al final de la página<br>
`<a href="#inicio">Volver al principio</a>`
-> Para que al pulsar "Volver al principio" nos lleve al principio de la página

### ENVIAR CORREOS 
*Existen opciones mejores y más sofisticadas para hacer esto, pero de momento no está de más conocer esta manera simple:*<br>
`<a href="mailto:olga.moreno@thepower.education"</a>`

### INSERTAR IMÁGENES 
Para insertar una imagen, la tenemos que enlazar:<br> 
`<img src="../img/01-C.jpg" alt="Ilustración 1" width="300" alt="ilustración personal">`

- Solo usamos el atributo **width** mientras no usemos css, ahora para salir al paso.

- El atributo **alt="aquí descripción de la imagen para invidentes"** es el texto alternativo, muy beneficioso para personas invidentes (*de hecho es bueno para posicionamiento, google te premia*)


## 📎 ALGUNOS TIPS
👉 **Para abrir el inspector**
- click dcho > Inspeccionar
- Método más rápido> pulsad F12 y chimpúm

👉 **Consejos generales**
- Evitad poner "estilos" en el html. Reservad esto para el CSS!
- Mantened vuestros archivos (html, css, js, imágene...) bien organizados y ordenados. Ayudaos de carpetas, nomenclatura, etc.
- Recuerda el concepto de etiquetas semánticas y no semánticas.

## 📎 TAREAS
📌 **Ejercicio pokemon**<br>
- Ejercicio 1 en la carpeta de HTML
- Enlace: https://github.com/olga3emes/proyectos

## 📎 EXTRAS

- Sitio web con la peor experiencia de usuario posible: https://userinyerface.com/
- Sitio web para revisar nuestro código: https://validator.w3.org/

[**Clase siguiente →**](resumen-clase04.md)

[**← Clase anterior**](resumen-clase02.md)


