# claude-plugins

Claude Code plugins by João P. Marques, in one marketplace.

| Plugin | What it does |
|---|---|
| [barbeque](https://github.com/joaopmarques/barbeque) | Grills your plan for you, picks the answers, and serves a short plan with a decision log plus sauces and sides. |
| [code-review-review](https://github.com/joaopmarques/code-review-review) | Explains a reviewer's PR comments in plain English, judges each one, then fixes, pushes, and replies on "go". |
| [dial-in](https://github.com/joaopmarques/dial-in) | Puts live controls next to a UI component. You tweak by eye, and Claude writes the values back to source. |

## Install

Add the marketplace once (Claude Code 2.1.275 or later):

```bash
claude plugin marketplace add joaopmarques/claude-plugins
```

Then install the plugins you want:

```bash
claude plugin install barbeque@joaopmarques
claude plugin install code-review-review@joaopmarques
claude plugin install dial-in@joaopmarques
```

Inside a session, use `/plugin` and pick the `joaopmarques` marketplace.

## Add a plugin

1. Put the plugin in its own repo, with `.claude-plugin/plugin.json` at the root.
2. Add an entry to `.claude-plugin/marketplace.json` with a `github` source.

## License

MIT. See [LICENSE](LICENSE).
