# ADRenaline

Suite de plugins de agente para el trabajo de software. Cada plugin hace el oficio de una profesión o de un área que varias profesiones comparten. Quien pide un diagrama, una auditoría o un texto lo pide al plugin que lo produce.

Funciona en Cursor y en Claude Code. El plugin está escrito en inglés. El archivo que guarda en el proyecto sigue el idioma de quien lo pide.

En Cursor el comando es corto: `/uml-classes-v2`, `/uiux-wireframe`. En Claude Code lleva el nombre del plugin delante: `/plugin-uml-diagrams:uml-classes-v2`.

## Repositorios

El nombre dice el tipo. Un repositorio nuevo aparece en esta organización sin cambiar este texto.

| Empieza por | Es |
| --- | --- |
| `plugin-` | Un plugin de agente. |
| `template-` | Un machote: un proyecto para copiar y arrancar. |
| `base-` | Un proyecto completo de la suite. |

Hoy están publicados [plugin-uml-diagrams](https://github.com/ADRenaline-Suite/plugin-uml-diagrams) y [plugin-ui-ux-design](https://github.com/ADRenaline-Suite/plugin-ui-ux-design).

## Después

Publicar el resto de plugins del catálogo. Agregar machotes y un par de proyectos completos. Un marketplace que liste esos repositorios, sin copiar unos dentro de otros, y un comando por profesión que instale el núcleo con sus áreas.
