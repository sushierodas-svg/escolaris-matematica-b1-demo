# AGENTS.md

## Propósito del proyecto

Este repositorio contiene objetos digitales HTML para cursos autoguiados del Colegio Escolaris en Canvas LMS.

Cada sección de una lección debe funcionar como un archivo HTML independiente, diseñado para incrustarse en Canvas mediante iframe.

## Regla principal

Modificar únicamente los archivos solicitados. No cambiar estructura, nombres de carpetas, rutas, colores ni contenido que no haya sido pedido explícitamente.

## Tecnología

Usar únicamente:

- HTML
- CSS
- JavaScript puro

No usar frameworks externos.
No usar React.
No usar Bootstrap.
No usar dependencias externas.
No usar drag and drop.

Todas las interacciones deben funcionar por clic o tap.

## Identidad visual Escolaris

Usar esta paleta de colores:

- Naranja quemado: #db6015
- Amarillo dorado: #f7be00
- Azul oscuro: #244b5a
- Rojo ladrillo: #993921
- Fondo azul claro: #f0f8ff
- Blanco: #ffffff

Tipografías permitidas:

- Segoe UI
- Tahoma
- Verdana
- sans-serif

## Organización de lecciones

Cada lección debe tener secciones separadas:

1. lectura-interactiva.html
2. practica-guiada.html
3. practica-owlaris.html
4. proyecto-final.html
5. cierre.html

Cada archivo debe ser independiente, pero puede usar:

- ../../css/styles.css
- ../../js/lesson.js

## Reglas para Canvas iframe

Cada HTML debe:

- Funcionar correctamente dentro de iframe.
- Tener diseño responsivo.
- Evitar scroll horizontal.
- Tener altura visual razonable.
- Cargar correctamente en computadora, tablet, iPad y celular.
- No depender de servidores externos.
- No mostrar errores en consola.

## Reglas pedagógicas

El contenido debe:

- Ser claro para estudiantes de primero básico.
- Explicar antes de preguntar.
- Usar instrucciones breves y accionables.
- Incluir retroalimentación inmediata cuando haya preguntas.
- Usar andamiaje progresivo.
- Incluir metacognición breve cuando corresponda.
- Evitar lenguaje excesivamente infantil.
- Evitar sobrecargar una pantalla con demasiado texto.

## Información que no debe mostrarse al estudiante

No mostrar:

- Fichas internas de trazabilidad.
- Competencias CNB.
- Indicadores CNB.
- Claves internas.
- Notas de QA.
- Comentarios para docentes.
- Advertencias como “no publicar”.
- Información administrativa del documento fuente.

## Reglas para Owlaris

Owlaris puede:

- Dar pistas.
- Hacer preguntas guía.
- Revisar explicaciones.
- Dar retroalimentación.

Owlaris no debe:

- Resolver el proyecto final.
- Dar respuestas completas para copiar.
- Sustituir el trabajo del estudiante.

## Criterios mínimos de QA

Antes de entregar una tarea, verificar:

- Los botones funcionan.
- La navegación funciona.
- No hay texto sobrepuesto.
- No hay claves internas visibles.
- El diseño responde en pantallas pequeñas.
- Las rutas de CSS y JS son correctas.
- El archivo puede abrirse directamente en navegador.
