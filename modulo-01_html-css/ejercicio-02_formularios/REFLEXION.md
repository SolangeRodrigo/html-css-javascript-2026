# REFLEXION — Ejercicio [02]: [FORMULARIOS]

---

## Sección 1 — Explicación de mi solución

*Describí en 150–250 palabras qué hace tu solución y cuáles fueron las decisiones principales que tomaste.*

> ✏️ **Tu respuesta aquí: Mi solución es una pagina para contactarse con semantica accesible. Utilicé etiquetas como <.form>, <.fieldset> y <.legend> para agrupar los campos como datos personales, tipo de consulta y mensaje.**
**Cada campo tiene su <.label> asociado mediante el atributo for, mejora la accesibilidad para lectores de pantalla. También incorporé atributos como required, aria-required y aria-describedby para reforzar la validación y la accesibilidad sin usar JavaScript.**
**Use para validar tipos de input HTML5 (email, tel, text, textarea, select, radio y checkbox) junto con pattern para algunos campos. Además, agregué estilos en CSS para los estados :focus, :hover, :valid e :invalid..**
**Por último, incluí mensajes de error asociados a cada campo usando .error-message, y mantuve una estructura visual simple centrada en mejorar la usabilidad y la accesibilidad. Tambien agregue algunos colores en el diseño, para ponerle onda.**

---
La verdad esta parte no se si se realizan preguntas o esta incompleto el SPEC.md

## Sección 2 — Preguntas conceptuales

*Las preguntas conceptuales específicas de este ejercicio están en el `SPEC.md`. Respondé cada una aquí.*

### 2.1 — [La diferencia entre aria-required y required es:]

> ✏️ **Tu respuesta:required bloquea o inhabilita el envio del formulario y realiza todas las verificaciones necesarias. aria-required es para informar que es obligatorio , pero no valida.**

### 2.2 — [un label explícito con for es importante porque:]

> ✏️ **Tu respuesta: Permite asociar correctamente el texto con el campo y mejorar accesibilidad para lectores de pantalla.**

### 2.3 — [¿Por qué no usamos JavaScript?]

> ✏️ **Tu respuesta: La finalidad del ejercicio 02 es utilizar y comprender la validación nativa.**

---

## Sección 3 — Decisiones técnicas

### 3.1 — ¿Qué fue lo más difícil de este ejercicio y cómo lo resolviste?

> ✏️ **Tu respuesta: Todo, me costo un monton ponerle las verificaciones sin JS, no podia centrarlo, se me movian las cosas para la izquierda, tuve que forzar los estilos para este centrado.**

### 3.2 — ¿Qué cambiarías si tuvieras que hacerlo de nuevo?

> ✏️ **Tu respuesta: Utilizaria JavaScript para realizar las verificaciones pertinentes.**

### 3.3 — ¿Qué alternativas consideraste y por qué las descartaste?

> ✏️ **Tu respuesta: Agregas más estilos de los utilizados, si bien me parecia mejor.. intente no cambiar en su totalidad la consigna del ejercicio.**

---

## Sección 4 — Declaración de uso de IA

```
[ ] Resolví el ejercicio completamente sin ayuda de IA
[X] Usé IA para entender algún concepto, pero escribí el código yo
[ ] Usé IA para generar un borrador que luego modifiqué y entendí
[ ] Usé IA extensamente y completé la reflexión para entender lo que hice
```

*Si usaste IA, describí brevemente cómo:*

> ✏️ **Tu respuesta (opcional si no usaste IA): Utilice la IA para definiciones que por ahi no me cerraban o ciertas etiquetas que no entendía como funcionaban.**

---

## Sección 5 — Autoevaluación

En una escala del 1 al 5, ¿cuánto entendés ahora el concepto central de este ejercicio?

```
[ ] 1 — Muy poco, necesito repasar
[ ] 2 — Entiendo lo básico
[X] 3 — Lo entiendo bien
[ ] 4 — Lo entiendo bien y puedo explicárselo a otro
[ ] 5 — Podría dar una clase sobre esto
```
