# Estructura de etiqueta

### 1. Estructura Fundamental y Sintaxis

La base del desarrollo HTML se centra en las **etiquetas** y su estructura.

#### 1.1. Etiquetas (Tags)
Las etiquetas son los nombres clave de HTML que definen un elemento.

* **Sintaxis de Apertura:** Se define encerrando el nombre de la etiqueta entre los caracteres `<` y `>`.
    * *Ejemplo:* `<p>` (Etiqueta de párrafo).
* **Sintaxis de Cierre:** Necesario para la mayoría de etiquetas. Es igual a la de apertura, pero con una barra `/` inmediatamente después del `<`.
    * *Ejemplo:* `</p>`.
* **Etiquetas Vacías (Self-Closing):** Algunas etiquetas no requieren contenido ni cierre (ej. `<br>`, `<img>`).
    * *Ejemplo:* `<br>` (Salto de línea).

#### 1.2. Contenido de la Etiqueta
Es la información que será afectada por la etiqueta. Puede ser texto o, más comúnmente, otras etiquetas anidadas, creando una **estructura jerárquica**.

* *Ejemplo Básico:* `<title>Mi Página Web</title>`
* *Ejemplo Anidado:*
    ```html
    <div id="contenedor">
      <p>Contenido importante.</p>
      <span>Otro elemento.</span>
    </div>
    ```

### 2. Atributos HTML

Los **atributos** son modificadores que se añaden a la etiqueta de apertura para personalizar su comportamiento o proporcionar información adicional.

**Sintaxis:** `atributo="valor"`

* **Ubicación:** Se escriben después del nombre de la etiqueta, separados por espacios, dentro de la etiqueta de apertura y antes del `>`.
* **Recomendación:** Los valores deben ir **siempre** entre comillas dobles.

#### 2.1. Tipos de Atributos (Según su Valor)

| Tipo | Descripción | Ejemplo |
| :--- | :--- | :--- |
| **Conjunto de Valores** | Permiten solo un rango específico de valores predefinidos. | `<audio preload="auto"></audio>` (Valores: `auto`, `metadata`, `none`) |
| **Valores Libres** | Se puede especificar cualquier valor, como rutas o nombres personalizados. | `<audio src="audios/music.mp3"></audio>` |
| **Booleanos** | No requieren valor. Su presencia implica `true` (verdadero) y su omisión implica `false` (falso). | `<audio muted></audio>` |


### 3. Categorías Principales de Etiquetas

HTML posee una colección fija de etiquetas, agrupadas por su función para facilitar la estructura del documento. 

| Categoría | Objetivo | Ejemplos Comunes |
| :--- | :--- | :--- |
| **Textuales** | Formato y estructura de partes de texto. | `<p>`, `<h1>` a `<h6>`, `<strong>`, `<em>` |
| **Agrupación** | Contenedores genéricos o estructuración de bloques de contenido. | `<div>`, `<span>` |
| **Multimedia** | Inserción de contenido audiovisual y relacionado. | `<img>`, `<video>`, `<audio>`, `<source>` |
| **Tablas** | Organización de datos en formato tabular (filas y columnas). | `<table>`, `<tr>`, `<td>`, `<th>` |
| **Formularios** | Elementos para la inserción de datos por parte del usuario. | `<form>`, `<input>`, `<label>`, `<button>` |
| **Interactivas** | Elementos que responden a la interacción directa del usuario. | `<details>`, `<dialog>`, `<summary>` |
| **Semánticas** | Etiquetas con significado estructural específico para mejorar la accesibilidad y SEO. (Variaciones de `<div>`). | `<header>`, `<footer>`, `<main>`, `<article>`, `<section>`, `<nav>` |
| **Scripting** | Integración de código de programación (principalmente JavaScript). | `<script>`, `<noscript>` |


### 4. Comentarios HTML

Los comentarios son fragmentos de texto ignorados por el navegador, utilizados exclusivamente para documentación y explicación del código.

* **Sintaxis:** Se delimitan con `` al final.
* **Función en VS Code:** La combinación de teclas **Ctrl + /** (o **Cmd + /** en Mac) convierte una línea o selección en un comentario de forma automática.

* *Ejemplo:*
    ```html
    <!--Este en un comentario en HTML-->
    ```
