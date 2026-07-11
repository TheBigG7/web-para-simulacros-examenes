# Simulacro de Examen

Aplicación web interactiva desarrollada para la realización de simulacros de exámenes con diversos formatos de preguntas.

## Descripción del Proyecto

Este proyecto es una herramienta cliente-lado (*front-end*) que permite a los usuarios poner a prueba sus conocimientos mediante un cuestionario dinámico. El banco de preguntas está estructurado para soportar múltiples tipologías de evaluación, permitiendo una experiencia de aprendizaje versátil.

## Características Técnicas

* **Tipos de preguntas soportadas:**
    * Selección múltiple.
    * Verdadero/Falso.
    * Selección múltiple con múltiples respuestas correctas.
    * Emparejamiento (*matching*).
    * Ordenamiento (*ordering*) mediante *drag and drop*.
    * Completar espacios en blanco (*fill-in-the-blank*).
    * Completar tablas.
* **Tecnologías:**
    * HTML5
    * CSS3
    * JavaScript (ES6+)
* **Funcionalidades:**
    * Evaluación inmediata de respuestas.
    * Visualización de la solución correcta tras la comprobación.
    * Contador de progreso en tiempo real.
    * Interfaz responsiva y adaptada a distintos dispositivos.

## Estructura del Repositorio

* `index.html`: Estructura principal y marcado semántico del examen.
* `style.css`: Hojas de estilo que definen la interfaz, los colores y los estados visuales (acierto/error).
* `script.js`: Lógica del examen, gestión del estado de las preguntas y manejo de eventos.

## Uso

1. Clona este repositorio en tu equipo local.
2. Abre el archivo `index.html` en cualquier navegador web moderno.
3. Haz clic en el botón **"Empezar"** para iniciar el simulacro de preguntas.

---
*Nota: Este proyecto fue desarrollado para entornos académicos utilizando lógica de manipulación del DOM nativa, sin dependencias externas.*
