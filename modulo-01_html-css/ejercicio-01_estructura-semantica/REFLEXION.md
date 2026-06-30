# REFLEXION — Ejercicio 1.1: Estructura Semántica HTML

> **Instrucciones:** Completá este archivo DESPUÉS de terminar tu solución. Escribí con tus propias palabras. Respuestas copiadas de internet o generadas por IA sin elaboración propia no son válidas.
>
> Tiempo esperado para completar esta reflexión: 20–30 minutos.

---

## Sección 1 — Explicación de mi solución

*Describí en 150–250 palabras qué hace tu archivo HTML y cuáles fueron las decisiones de estructura que tomaste. No copies el código, explicá el razonamiento.*

> ✏️ **Tu respuesta aquí:**
>
> [En sí se elaboró un archivo HTML sobre un blog de IA, entiendo que se buscó el hecho de que entendamos las diferentes etiquetas para estructurar una página HTML. Como es el caso del HEADER que es la parte superior de la estructura, el body es el contenedor general de todo el contenido visible de la página y a su vez el footer es la parte inferior de la página.
Las decisiones de estructura las hice con los requerimientos solicitados, ya que nos indicaban cómo debía estructurarse desde cero el blog. También había que escribir un texto en el cual se explica sobre la IA, lo redacté de una manera breve.
El contenido en el main es lo más importante y lo que más destaco, porque es la estructura principal donde se encuentra el contenido del artículo visible para el usuario. Dentro de este utilicé article para representar el post del blog, y section para dividir la información.
Además, utilicé aside para agregar información complementaria relacionada al contenido principal. Estas etiquetas semánticas ayudan a estructurar mejor el HTML, para no utilizar divs.]

---

## Sección 2 — Preguntas conceptuales

Respondé cada pregunta. Las respuestas deben ser tuyas. Podés investigar, pero explicá con tus palabras.

### 2.1 — ¿Cuál es la diferencia entre `<section>` y `<article>`? ¿Cuándo usarías cada uno?

> ✏️ **Tu respuesta: Si lo vemos desde el lado humano, es como un diario o una revista. Hay una portada con distintas noticias, pero cada noticia completa sería un <.article>, ya que se puede leer e interpretar por sí sola. Dentro de esa noticia, podemos encontrar distintas partes o temas, y ahí es donde usaríamos <.section> para dividir la información en secciones más organizadas.**

---

### 2.2 — ¿Por qué es importante el atributo `datetime` en la etiqueta `<time>`? ¿Quién lo usa?

> ✏️ **Tu respuesta: Es importante porque permite que la fecha y hora se expresen en un formato estándar, entiendo algo así como cuando estamos realizando un diagrama de clases en el EA y en un atributo le ponemos tipo time. Esto ayuda a que las maquinas puedan interpretar el tiempo en que se redacta algo, por ejemplo.**

---

### 2.3 — Tu página tiene `<header>` en dos lugares: uno para la página y uno dentro del `<article>`. ¿Eso es válido? ¿Por qué?

> ✏️ **Tu respuesta: Esta bien en este tipo de paginas blogs ya que cada articulo tiene un header, algo asi como los diarios, como el ejemplo anterior.**

---

### 2.4 — Un motor de búsqueda como Google lee tu HTML. ¿Qué ventaja le da usar etiquetas semánticas versus usar solo `<div>` con clases?

> ✏️ **Tu respuesta: Este tipo de etiquetas ayuda a motores de busqueda a interpretar las cosas de mejor manera, es como si entendieran neutro y le hablaramos en neutro. Entiendo que con los divs es como hablar más general.**

---

### 2.5 — Encontrá **un error semántico** en el siguiente fragmento y explicá cómo lo corregirías:

```html
<div class="navigation">
  <div class="nav-item"><a href="/home">Inicio</a></div>
  <div class="nav-item"><a href="/about">Nosotros</a></div>
</div>

<div class="main-content">
  <div class="post-title">Mi primer artículo</div>
  <div class="post-body">
    <p>Contenido del artículo...</p>
  </div>
</div>
```

> ✏️ **Tu respuesta: A simple vista veo el < div class="navigation " >, se utiliza cuando usas un < nav> y a lo largo del codigo no lo utiliza.**

---

## Sección 3 — Decisiones técnicas

### 3.1 — ¿Qué etiqueta usaste para el logo y por qué? ¿Hay alternativas?

> ✏️ **Tu respuesta: Use < img>, creeria que se puede tambien un < a href> para que pueda hacer click. No se si existen otras maneras.**

---

### 3.2 — ¿Elegiste `<ul>` u `<ol>` para tu lista? ¿Por qué esa y no la otra?

> ✏️ **Tu respuesta: No sabia que existia <. ol>, busque y vi que es para secuencias que si o si requieren un orden predeterminado, <. ul> es para ordenar contenido de manera mas general tipo lista.**

---

### 3.3 — Si alguien accede a tu página solo con un lector de pantalla (sin ver el HTML), ¿podría navegar y entender el contenido? ¿Qué cambiarías para mejorar la experiencia?

> ✏️ **Tu respuesta Se supone que si porque esa sintaxis semantica que usamos es justamente para eso, para que un motor de busqueda pueda interpretarlo de manera neutra. Creo que esta bien organizada, yo le podria mas estilos para que quede mas correcta visualmente.**

---

## Sección 4 — Declaración de uso de IA

Marcá con una `x` lo que corresponda:

```
[X] Resolví el ejercicio completamente sin ayuda de IA
[X] Usé IA para entender algún concepto, pero escribí el código yo
[ ] Usé IA para generar un borrador que luego modifiqué y entendí
[ ] Usé IA extensamente y completé la reflexión para entender lo que hice
```

*Si usaste IA, describí brevemente cómo:*

> ✏️ **Tu respuesta (opcional si no usaste IA): la verdad no sabia lo de <. ol> y lo busque por ahi, es lo mismo que buscarlo en google porque tambien tiene IA la respuesta.**

---

## Sección 5 — Autoevaluación

En una escala del 1 al 5, ¿cuánto entendés ahora el concepto de HTML semántico?

```
[ ] 1 — Muy poco, necesito repasar
[ ] 2 — Entiendo lo básico
[ ] 3 — Lo entiendo bien
[X] 4 — Lo entiendo bien y puedo explicárselo a otro
[ ] 5 — Podría dar una clase sobre esto
```

*¿Qué parte te resultó más difícil?*

> ✏️ **Tu respuesta: Por ahi me costo seguir los lineamientos de los requerimientos, porque generalmente estructuro los HTML a mi gusto y aca tenia que seguir ordenes por así decirlo.**
