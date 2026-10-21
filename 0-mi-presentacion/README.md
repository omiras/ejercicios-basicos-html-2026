# 0. Mi primera página: me presento

Vas a crear una pequeña presentación para que el grupo te conozca y, de paso, empezar a escribir HTML. Puedes utilizar tu nombre, un apodo o inventar un personaje; comparte solo lo que quieras contar.

## Qué vas a practicar

- Diferenciar un encabezado de un párrafo.
- Usar `h1`, `h2`, `h3` y `p` con apertura y cierre.
- Organizar el contenido por niveles.
- Guardar un archivo y comprobar sus cambios en el navegador.

**En este ejercicio no utilizaremos atributos, CSS, JavaScript, imágenes, enlaces ni listas.** Trabajaremos con texto, encabezados y párrafos.

## Antes de empezar

Abre `index.html` en VS Code. La estructura del documento ya está preparada: escribe tu presentación **entre `<body>` y `</body>`**. No necesitas memorizar todavía el resto de la estructura.

Abre también ese archivo en el navegador. Si necesitas ayuda para hacerlo, consulta el README de la carpeta principal.

## Construye tu presentación, paso a paso

Después de cada paso, guarda el archivo con **Ctrl + S** y comprueba el resultado en el navegador. Si no usas Live Server, recuerda recargar la página.

1. **Tu nombre.** Añade un único encabezado principal `h1` con tu nombre o apodo.
2. **Una breve introducción.** Debajo, escribe un párrafo `p` de una o dos frases para presentarte.
3. **Tus intereses.** Añade un encabezado `h2` titulado «Mis intereses» y, debajo, un párrafo contando algo que te guste hacer.
4. **Un interés en detalle.** Dentro de ese apartado, añade un encabezado `h3` que nombre una afición concreta. Debajo, escribe otro párrafo explicando por qué te gusta. Este subapartado forma parte de «Mis intereses».
5. **Tu objetivo.** Añade un nuevo `h2` titulado «Qué me gustaría aprender» y un párrafo explicando algo que esperas conseguir en el curso. Este apartado está al mismo nivel que «Mis intereses».
6. **Revisa la organización.** Comprueba que los párrafos están fuera de los encabezados y que has cerrado cada etiqueta.

El resultado tendrá **un `h1`, dos `h2`, un `h3` y cuatro párrafos**. El contenido lo eliges tú. La página tendrá el aspecto sencillo que le da el navegador: no hay que añadir decoración.

## Comprueba tu trabajo

- [ ] Mi nombre aparece como encabezado principal.
- [ ] Hay una introducción y dos apartados principales.
- [ ] Una afición tiene su propio subapartado dentro de «Mis intereses».
- [ ] He escrito cuatro párrafos, cada uno dentro de su propio elemento `p`.
- [ ] Todas las etiquetas que he añadido tienen apertura y cierre.
- [ ] No he escrito atributos: mis etiquetas de apertura contienen solo el nombre, por ejemplo `<p>`.
- [ ] Al cambiar una frase, guardarla y recargar, veo el cambio en el navegador.

Para terminar, explica a una persona del grupo por qué la afición concreta lleva `h3` y «Qué me gustaría aprender» lleva `h2`. No elijas el nivel solo por el tamaño de letra.

## Pistas: consulta solo lo que necesites

<details>
<summary>No recuerdo cómo escribir un elemento</summary>

Una etiqueta de apertura indica dónde empieza el elemento y otra de cierre dónde termina. La de cierre incluye `/`. Por ejemplo, en una página sobre astronomía:

```html
<p>La Luna es el satélite natural de la Tierra.</p>
```

Sustituye el texto por el tuyo. Para un encabezado, utiliza la etiqueta del nivel que corresponda.

</details>

<details>
<summary>No sé qué nivel de encabezado elegir</summary>

Piensa en el índice de un libro: `h1` sería el título del libro, `h2` el título de un capítulo y `h3` un apartado de ese capítulo. Cuando empiezas otro capítulo vuelves a `h2`.

</details>

<details>
<summary>He pulsado Intro, pero el navegador no separa los párrafos</summary>

Los saltos de línea que escribes en el editor no crean párrafos HTML. Cada párrafo necesita su propia apertura y cierre con `p`. No uses espacios o saltos de línea repetidos para organizar el contenido.

</details>

<details>
<summary>El navegador no muestra mis cambios</summary>

Comprueba que has guardado el archivo, que estás viendo el mismo `index.html` que estás editando y que has recargado el navegador. Si ves etiquetas escritas como texto, revisa que el archivo termine en `.html` y no en `.txt`.

</details>

## Documentación para este ejercicio

- [Encabezados y párrafos — MDN](https://developer.mozilla.org/es/docs/Learn_web_development/Core/Structuring_content/Headings_and_paragraphs): consulta cómo relacionar los niveles de encabezado con la organización del contenido.
- [Sintaxis básica de HTML — MDN](https://developer.mozilla.org/es/docs/Learn_web_development/Core/Structuring_content/Basic_HTML_syntax): revisa apertura, cierre y anidamiento. Esa página también explica atributos; todavía no los necesitas aquí.

## Si terminas antes (opcional)

Añade otro subapartado `h3` con un párrafo dentro de «Mis intereses». Antes de escribirlo, decide dónde debe colocarse para que siga formando parte de ese apartado.

Si necesitas ayuda de la IA, puedes pedir: «Estoy aprendiendo encabezados y párrafos de HTML, sin atributos. Dame una pista sobre este paso sin escribir mi presentación completa». Incluye el paso y tu intento.
