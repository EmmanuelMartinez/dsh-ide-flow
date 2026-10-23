# IDE Flow

One install for the DeepSeek Harness Desktop IDE surface:

- **Source control** panel (changes tree, history graph, commit box)
- **Editor** (syntax colours, line numbers, git marks, find/replace, Edit from the preview)
- **Trash** (delete a session into a reversible trash, restore or purge)
- The right **icon rail** (Editor, Source control, Files, Terminal, Trash)

The desktop build this targets ships an older frame without the rail, so this
bundle also replaces the two frame rows that draw and toggle it.

## Install

Plugins → **Add plugin** → enter:

\`\`\`
github:EmmanuelMartinez/dsh-ide-flow#v1.0.0
\`\`\`

Then quit the application (Cmd+Q) and reopen it. The dependencies install with
the bundle; only **IDE Flow** appears in the Plugins list.

## Updating

Plugins do not auto-update: uninstall IDE Flow and install the new tag.
