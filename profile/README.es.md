<p align="right">Idioma:&emsp;<a href="README.md" style="vertical-align:middle"><img alt="English" src="lang-en-off.svg" align="middle" style="vertical-align:middle"></a> <img alt="Español" src="lang-es-on.svg" align="middle" style="vertical-align:middle"></p>

<p align="center">
  <a href="https://github.com/ADRenaline-Suite">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="wordmark-dark.svg">
      <img alt="ADRenaline" src="wordmark.svg" width="320">
    </picture>
  </a>
</p>

La marca es un chevron. La cola es cian y la punta es ámbar: el trazo sale frío y llega como un destello. La tinta es `#061018`. La marca cuadrada está en [mark.svg](mark.svg).

# ADRenaline

Suite de plugins de agente para el trabajo de software. Cada plugin hace el oficio de una profesión o de un área que varias profesiones comparten. Quien pide un diagrama, una auditoría o un texto lo pide al plugin que lo produce.

Funciona en Cursor y en Claude Code. El plugin está escrito en inglés. El archivo que guarda en el proyecto sigue el idioma de quien lo pide.

En Cursor el comando es corto: `/uml-classes-v2`, `/uiux-wireframe`. En Claude Code lleva el nombre del plugin delante: `/plugin-uml-diagrams:uml-classes-v2`.

## Repositorios

El nombre dice el tipo. Un repositorio nuevo aparece en esta organización sin cambiar esta tabla.

| Empieza por | Es |
| --- | --- |
| `plugin-` | Un plugin de agente. |
| `template-` | Un machote: un proyecto para copiar y arrancar. |
| `base-` | Un proyecto completo de la suite. |

Publicados:

- [plugin-uml-diagrams](https://github.com/ADRenaline-Suite/plugin-uml-diagrams) — Dibuja los diagramas UML 1.5 y UML 2.5.1, cada uno en su notación.
- [plugin-ui-ux-design](https://github.com/ADRenaline-Suite/plugin-ui-ux-design) — Diseña la experiencia y la interfaz, de la tarea al handoff, sin escribir el código.
- [plugin-project-context](https://github.com/ADRenaline-Suite/plugin-project-context) — Deja la foto actual del proyecto y qué plugins de la suite encajan.
- [plugin-software-architect](https://github.com/ADRenaline-Suite/plugin-software-architect) — Evalúa una arquitectura y escribe el 4+1 y el manual arc42.

Cuando se crea el repositorio de un plugin, se añade a esta lista en los dos idiomas, en el mismo cambio.

## Después

Publicar el resto de plugins del catálogo. Agregar machotes y un par de proyectos completos. Un marketplace que liste esos repositorios, sin copiar unos dentro de otros, y un comando por profesión que instale el núcleo con sus áreas.
