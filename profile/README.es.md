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
- [plugin-project-manager](https://github.com/ADRenaline-Suite/plugin-project-manager) — Escribe el caso de uso, la tarea entre repositorios, el reporte de avance, el sprint y el backlog ordenado.
- [plugin-apis](https://github.com/ADRenaline-Suite/plugin-apis) — Escribe el contrato HTTP: operaciones, problem details y la política de versión.
- [plugin-backend](https://github.com/ADRenaline-Suite/plugin-backend) — Escribe el lenguaje, el agregado y el servicio de aplicación.
- [plugin-frontend](https://github.com/ADRenaline-Suite/plugin-frontend) — Implementa una pantalla desde el handoff, con sus estados y el presupuesto de vitales.
- [plugin-qa-engineer](https://github.com/ADRenaline-Suite/plugin-qa-engineer) — Escribe el escenario, el nivel y el tipo de prueba.
- [plugin-security](https://github.com/ADRenaline-Suite/plugin-security) — Clasifica una amenaza y escribe el requisito verificable.
- [plugin-ux-writing](https://github.com/ADRenaline-Suite/plugin-ux-writing) — Escribe los textos de interfaz, la voz y el glosario.
- [plugin-accessibility](https://github.com/ADRenaline-Suite/plugin-accessibility) — Audita contra WCAG 2.2 y escribe el requisito.
- [plugin-documentation](https://github.com/ADRenaline-Suite/plugin-documentation) — Escribe un documento en un tipo Diátaxis.
- [plugin-privacy](https://github.com/ADRenaline-Suite/plugin-privacy) — Registra una actividad de tratamiento, sin elegir la base legal.
- [plugin-action-confirmation](https://github.com/ADRenaline-Suite/plugin-action-confirmation) — Exige la frase allow exacta en este turno antes de una escritura.

Cuando se crea el repositorio de un plugin, se añade a esta lista en los dos idiomas, en el mismo cambio.

## Después

Publicar el resto de plugins del catálogo. Agregar machotes y un par de proyectos completos. Un marketplace que liste esos repositorios, sin copiar unos dentro de otros, y un comando por profesión que instale el núcleo con sus áreas.
