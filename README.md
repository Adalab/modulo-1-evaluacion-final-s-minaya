# Mi proyecto

# Módulo 1: Ejercicio de Evaluación Final – Adalab

## Descripción del proyecto

Este proyecto consiste en el desarrollo de una **página web responsive** para promocionar una temporada especial de ofertas en una tienda, siguiendo el diseño proporcionado en [Zeplin](https://app.zeplin.io/project/64edc6ff56d7a924c51e7d4e/dashboard?sid=64edc714a6da492482d6af5a)
El objetivo es aplicar los conocimientos adquiridos durante el Módulo 1, incluyendo el uso de **HTML semántico**, **Sass**, **Flexbox**, **CSS**, **Grid** y **media queries**, además de incorporar algunas **transiciones y animaciones** como extras.

---

## Recursos iniciales

Antes de comenzar, debo seguir estos pasos:

1. **Crear un nuevo repositorio** desde GitHub Classroom usando el enlace proporcionado por Adalab.
2. **Clonar el repositorio** en mi ordenador.
3. **Descargar e incluir el starter kit de Adalab** para poder usar la sintaxis de Sass.
4. **Descargar imágenes e iconos** desde [esta carpeta](https://drive.google.com/drive/folders/1N9GaGI6o80wnGpNzIg0ZxG-ZY4bVpvuf)
5. **Acceder al diseño en [Zeplin](https://app.zeplin.io/project/64edc6ff56d7a924c51e7d4e/dashboard?sid=64edc714a6da492482d6af5a)**

---

## Maquetación

El proyecto se estructura en varios módulos o secciones según el diseño:

### Header (Menú de hamburguesa)

- El icono de la hamburguesa debe estar fijo en la parte superior izquierda de la pantalla y no debe desaparecer al hacer scroll. Debe ser un enlace a la página de [Adalab](https://adalab.es/) Este menú servirá para mostrar una lista de enlaces pero en esta evaluación no despliega ningún submenú.
- No desaparece al hacer scroll.
- No se requiere desplegar ningún submenú.

### Hero “Comienzos compartidos”

- Maquetado con **Flexbox**.
- La imágen debe ocupar el **alto (y ancho) completo de la pantalla del navegador** tanto en la versión móvil, como en la tablet y en la desktop (`100vh`).
- Además tiene un título y un texto.
- La imagen principal es decorativa, por lo que se aplica como `background-image`.
- El botón de flecha debe enlazar a la sección “Vuelta al cole”.

### Sección “Tu tienda de deporte”

- Sección blanca con dos títulos, un texto y un botón de comprar.
- Maquetación libre, utilizando las propiedades de CSS necesarias.
- El botón de Comprar es un enlace que lleva a la página de [Adalab](https://adalab.es).

### Sección “Vuelta al cole”

- Ninguno de los elementos es un enlace.
- Empezar ahora enlaza a la página de [Adalab](https://adalab.es).
- Los 3 elementos deben maquetarse con **CSS Grid**.
- Adaptación responsive usando **media queries**.

### Footer (Extra)

- Son dos listas de enlaces
- Se puede maquetar con el estilo que se desee.
- Todos los textos de las columnas **“Zapatillas”** y **“Twitter”** deben ser enlaces a [Adalab](https://adalab.es).
- El botón superior del footer debe enlazar al inicio de la página (hero).

---

- **Bonus:**
  - En el `:hover` de los botones (“Comprar” y “Empezar ahora”) incluir una **transformación** ( por ejemplo con `transition`.)
  - **A investigar:** Añadir una **animación en el botón del footer** para investigar las propiedades `animation`.

### Entrega

- La fecha límite de entrega es el Miércoles, 15 de octubre a las 23:59h.
- Solo debemos hacer commits y merges en la rama **main** de nuestro repositorio hasta la fecha límite. Si después de la evaluación queremos seguir trabajando en el ejercicio, lo podemos hacer en otra rama
  y no debemos mergearla hasta que el profesor lo indique.

# Normas y criterios de evaluación

- Ejercicio individual, aunque se puede pedir ayuda. Si se detecta que el código no es personal, se pasará directamente a la re-evaluación del módulo.
- Si no se supera al menos el 80% de los siguientes criterios o no se supera algún criterio clave (marcados con \*) se me pedirá que realice una re-evaluación.

## General

Usar una estructura adecuada de ficheros y carpetas para un proyecto web, y enlazar bien los distintos ficheros\*.

## HTML - Las secciones con asteriscos son imprescindibles

- Tener el código perfectamente indentado\*.
- Crear código HTML con sintaxis correcta, bien estructurado\*.
- Usar etiquetas HTML semánticas adecuadas para cada pieza de contenido\*.

## CSS / Sass - Las secciones con asteríscos son imprescindibles

- Tener el código perfectamente indentado\*.
- Crear código Sass con sintaxis correcta, bien estructurado\*.
- Usar algunas características de Sass como variables, anidación y parciales.
- Usar código CSS que usa de forma intensiva selectores de clase. **No usar selectores de etiqueta ni de
  id\***.
- Usar selectores de clase en inglés\*.
- Usar el modelo de caja de CSS de forma adecuada para espacicar tamaño, relleno y márgenes\*.
- Usar estilos de texto y fondo para distintos tipos de elementos.
- Usar flexbox de forma adecuada para organizar elemento en cajas fexibles\*.
- Usar media queries para que los diseños se ajusten a distintos tamaños de dispositivo\*.
  -Los puntos de breakpoint para el diseño de la evaluación son:
  -A partir de 768px versión de tablet
  -A partir de 1024px será la versión para desktop
- Usar posicionamiento para emplazar elementos fijos y absolutos en la pantalla.
- Usar CSS grid para emplazar elementos usando una rejilla.
- Usar transiciones CSS para dotar de dinamismo a un proyecto web.
