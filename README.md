# artberri's Claude Code plugins

A [Claude Code](https://code.claude.com) plugin marketplace with the plugins I write.

## Install

Add the marketplace once:

```sh
claude plugin marketplace add artberri/claude-plugins
```

then install any plugin from it by name:

```sh
claude plugin install sideline@artberri
```

Inside a Claude Code session the same works as `/plugin marketplace add artberri/claude-plugins` and
`/plugin install sideline@artberri`; `/plugin` also lists everything the marketplace offers.

## Plugins

| Plugin                                           | What it does                                                                                                                                      |
| ------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------- |
| [sideline](https://github.com/artberri/sideline) | Declutters Claude Code's conversation: long commands, diffs and tool chatter step aside into a tidy pane with your changes, commits and commands. |
| [artberri](https://github.com/artberri/skills)   | My everyday agent skills: focused, signed commits; pull request review with Open Code Review; and adapting skill templates to a project.          |

Each plugin lives in its own repository, with its documentation and issues there.
