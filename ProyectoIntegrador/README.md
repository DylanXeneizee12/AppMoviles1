# 📱 TechStore Móvil

Aplicación desarrollada para la materia **Desarrollo de Software para Plataformas Móviles (7° 5ta)**.

El proyecto consiste en un catálogo de productos tecnológicos que consume información desde una API externa, permite filtrar y buscar productos, administrar favoritos y almacenar información localmente.

---

## 🧠 Conceptos que manejo con dominio

Los siguientes conceptos forman parte de conocimientos que ya venía trabajando y que puedo implementar y explicar de manera independiente:

* Variables con `let` y `const`.
* Arrays y objetos.
* Funciones, parámetros, argumentos y `return`.
* Condicionales `if / else`.
* Métodos de arrays como:

  * `forEach()`
  * `filter()`
  * `map()`
  * `push()`
  * `includes()`
* Manipulación del DOM.
* `document.querySelector()` y `querySelectorAll()`.
* `addEventListener()` y manejo de eventos.
* `textContent` e `innerHTML`.
* `classList` (`add`, `remove`, `toggle`, `contains`).
* `localStorage`.
* `JSON.stringify()` y `JSON.parse()`.
* Creación y manipulación de elementos HTML desde JavaScript.
* Manejo básico de `dataset`.
* Uso de operadores y expresiones lógicas.

Estos conceptos puedo utilizarlos y explicarlos de forma independiente porque ya los venía aplicando en proyectos anteriores.

---

## 🤖 Conceptos en los que utilicé apoyo de IA

Durante el desarrollo de este proyecto utilicé IA como herramienta de apoyo para comprender e implementar algunos conceptos que todavía estoy profundizando.

Los principales son:

* **ES Modules:** `import` y `export`.
* **Programación asíncrona:** `async` y `await`.
* **Promises y `Promise.all()`**.
* **Consumo de APIs mediante `fetch()`**.
* Conversión de respuestas mediante `.json()`.
* Manejo de errores con `try / catch`.
* **Arrow functions**.
* **Destructuring** de objetos.
* Método `reduce()`.
* Operador ternario.
* Método `closest()`.
* **Delegación de eventos**.
* Organización del código en diferentes módulos.

Si bien en estos conceptos necesité apoyo para comprender y completar la implementación, conozco su funcionamiento general, puedo identificar qué problema resuelve cada uno y puedo explicar la lógica utilizada en el proyecto.

Mi objetivo es seguir profundizándolos mediante la práctica y poder implementarlos de forma completamente independiente.

---

## 📂 Organización del proyecto

El proyecto se encuentra dividido en módulos según la responsabilidad de cada parte:

### `api.js`

Se encarga del consumo de la API externa mediante `fetch()`, utilizando programación asíncrona y `Promise.all()` para obtener los productos de diferentes categorías.

### `storage.js`

Se encarga de la persistencia de los productos favoritos mediante `localStorage` y JSON.

### `ui.js`

Contiene funciones relacionadas con la generación de las tarjetas de productos, filtrado del catálogo y cálculo del valor total.

### Archivo principal

Funciona como orquestador de la aplicación: conecta los módulos, maneja los eventos, actualiza la interfaz y controla el estado principal del catálogo.

---

## 🎯 Objetivo de aprendizaje

Además de completar el funcionamiento de la aplicación, el objetivo principal fue incorporar conceptos de JavaScript que todavía estoy aprendiendo, especialmente el consumo de APIs, la programación asíncrona y la utilización de módulos ES6.

Considero que los conceptos fundamentales utilizados en el proyecto ya forman parte de mis conocimientos y que los conceptos más avanzados se encuentran actualmente en proceso de profundización mediante la práctica.
