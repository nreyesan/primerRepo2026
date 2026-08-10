# Herramientas útiles para documentación con Markdown

En las clases anteriores has visto la relevancia de trabajar con Markdown y lo mucho que este lenguaje te puede ayudar para crear una gran documentación. En esta clase lo que veremos son algunos de los muchísimos recursos que puedes utilizar para poder escribir de una gran manera utilizando Markdown de la mejor manera posible. ¡Comencemos!

## Documentación de Markdown

Simplemente, la mejor referencia para conocer todo lo que se puede hacer con Markdown dentro de los documentos, aquí puedes comenzar a leer mucho.

![Markdownpage](https://www.markdownguide.org/assets/images/markdown-mark-white.svg)

## Diagramas Mermaid

Dejando de lado la funcionalidad básica de lo que puedes hacer con los markdown y VS Code podemos dar un paso adelante y utilizar una herramienta que te hará hacer documentos de otro nivel con los diagramas mermaid.

Estos diagramas te permiten diseñar gráficas de muchos niveles y personalizarlas con la complejidad que deseas.

Por ejemplo, gracias a un código similar al siguiente podrás representar el flujo de interacción entre diferentes ramas, muy acorde a nuestro curso ¿no?

```mermaid
%%{init: { "gitGraph": { "branchColors": ["#0000ff", "#ff00ff", "#00cc00"] } }}%%
gitGraph
    commit
    commit
    branch develop
    checkout develop
    commit
    commit
    checkout main
    merge develop
    commit
    commit

