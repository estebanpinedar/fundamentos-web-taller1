# Taller 1 - Fundamentos Web
Nombre: Esteban Pineda Rodriguez
Este repositorio contiene el primer taller de HTML de la asignatura
Fundamentos de Programacion Web.

## Estructura HTML

Al abrir `index.html`, el navegador muestra el contenido ubicado dentro de `body`. El contenido de `title` se puede observar en la pestana del navegador y, segun el navegador, en el titulo de la ventana.

## Verificacion de codigo

### Caso A

**Problema identificado:** La etiqueta `img` no usa el atributo `href` para cargar una imagen.

**Correccion realizada:** Se cambio `href` por `src`.

```html
<img src="multimedia/imagen1.jpg" alt="Fotografia de un lago">
```

**Fuente consultada:** [MDN - elemento img](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/img).

### Caso B

**Problema identificado:** La etiqueta `a` no usa el atributo `src` para indicar su destino.

**Correccion realizada:** Se uso el atributo `href`.

```html
<a href="https://developer.mozilla.org/">Consultar MDN</a>
```

**Fuente consultada:** [MDN - elemento a](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/a).

### Caso C

**Problema identificado:** La etiqueta `source` necesita el atributo `src` para indicar el archivo de video.

**Correccion realizada:** Se cambio `href` por `src`.

```html
<video controls>
    <source src="multimedia/video.mp4" type="video/mp4">
</video>
```

**Fuente consultada:** [MDN - elemento source](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/source).

### Caso D

**Problema identificado:** `correo` no es un valor valido para el atributo `type` de `input`.

**Correccion realizada:** Se uso el valor estandar `email`.

```html
<input type="email" name="correo">
```

**Fuente consultada:** [MDN - input type=email](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/input/email).

### Caso E

**La afirmacion es:** Falsa.

**Justificacion:** La etiqueta estandar de HTML para insertar una imagen es `img`, no `image`. `img` es un elemento vacio, por lo que no utiliza una etiqueta de cierre.

```html
<img src="multimedia/imagen2.jpg" alt="Ilustracion digital">
```

**Fuente consultada:** [MDN - elementos vacios](https://developer.mozilla.org/en-US/docs/Glossary/Void_element).
