# HTML: Estructura y Semántica de la Web

HTML (HyperText Markup Language) es el **lenguaje de etiquetas** fundamental que define el **significado y la estructura** del contenido en la web. Permite incluir o hacer referencia a diversos tipos de información.


## La Base del Lenguaje: Las Etiquetas

El documento HTML está formado por **etiquetas** (`<>`), que son la esencia del lenguaje. Cada etiqueta tiene una finalidad específica: **contener información** y asignarle un **significado** a esa información.

Existen muchas etiquetas (`<p>`, `<h1>`, `<a>`, `<img>`, etc.), y cada una posee sus propias características que deben utilizarse según lo requiera el contenido.


## La Importancia de la Semántica

La **semántica** en HTML se refiere a utilizar las etiquetas de manera que el **significado** del contenido esté correctamente **individualizado y estructurado**.

El objetivo principal es lograr la **separación de la presentación del contenido**:

* **Contenido (HTML):** Debe ser claro y comprensible al leer el código, enfocándose **solo en el significado** de la información (por ejemplo, esta es una cabecera, esto es un párrafo, este es un enlace, etc.).
* **Presentación (CSS):** Si se desea cambiar la apariencia (color, tamaño, disposición), esto debe gestionarse por completo en el documento CSS (Cascading Style Sheets).

Al aplicar una buena semántica, se asegura que el documento HTML sea legible, accesible y mantenible.

##  Jerarquía del Documento (Estructura Básica)

Aunque no está explícitamente en el texto, la documentación se beneficia de conocer la estructura jerárquica básica de un documento HTML5.

* **`<!DOCTYPE html>`:** Define el tipo de documento.
* **`<html>`:** Etiqueta raíz que envuelve todo el contenido del documento.
    * **`<head>`:** Contiene metadatos, enlaces a CSS y scripts, y el título de la página (información que no se muestra directamente en el cuerpo del navegador).
        * `<meta>`: Información sobre el documento (codificación, descripción, etc.).
        * `<title>`: El título que aparece en la pestaña del navegador.
    * **`<body>`:** Contiene todo el contenido visible de la página (texto, imágenes, enlaces, etc.).

## Conceptos Clave

| Concepto | Definición |
| :--- | :--- |
| **HTML** | Lenguaje de marcado para la estructura web. |
| **Etiqueta** | Unidad básica de HTML que envuelve contenido y le da significado. |
| **Semántica** | Uso de etiquetas para expresar el significado estructural del contenido. |
| **Separación** | Distinción clara entre el significado (HTML) y la apariencia (CSS). |