<p align="right">Language:&emsp;<img alt="English" src="lang-en-on.svg" align="middle" style="vertical-align:middle"> <a href="README.es.md" style="vertical-align:middle"><img alt="Español" src="lang-es-off.svg" align="middle" style="vertical-align:middle"></a></p>

# ADRenaline

A suite of agent plugins for software work. Each plugin does the job of one profession, or of an area that several professions share. Someone who needs a diagram, an audit, or copy asks the plugin that produces it.

It works in Cursor and in Claude Code. The plugin is written in English. The file it saves in the project follows the language of the person who asked.

In Cursor the command is short: `/uml-classes-v2`, `/uiux-wireframe`. In Claude Code the plugin name comes first: `/plugin-uml-diagrams:uml-classes-v2`.

## Repositories

The name says the type. A new repository shows up in this organization without changing this text.

| Starts with | It is |
| --- | --- |
| `plugin-` | An agent plugin. |
| `template-` | A template: a project to copy and start from. |
| `base-` | A complete project of the suite. |

Published today: [plugin-uml-diagrams](https://github.com/ADRenaline-Suite/plugin-uml-diagrams) and [plugin-ui-ux-design](https://github.com/ADRenaline-Suite/plugin-ui-ux-design).

## Next

Publish the rest of the plugins in the catalog. Add templates and a couple of complete projects. A marketplace that lists those repositories, without copying one inside another, and a command per profession that installs the core with its areas.
