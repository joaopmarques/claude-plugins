# claude-plugins

Claude Code plugins by João P. Marques, in one marketplace. The same skills are also listed on [skills.sh](https://www.skills.sh/joaopmarques).

| Plugin | What it does | skills.sh |
|---|---|---|
| [barbeque](https://github.com/joaopmarques/barbeque) | Grills your plan for you, picks the answers, and serves a short plan with a decision log plus sauces and sides. | [![skills.sh](https://www.skills.sh/b/joaopmarques/barbeque)](https://www.skills.sh/joaopmarques/barbeque) |
| [code-review-review](https://github.com/joaopmarques/code-review-review) | Explains a reviewer's PR comments in plain English, judges each one, then fixes, pushes, and replies on "go". | [![skills.sh](https://www.skills.sh/b/joaopmarques/code-review-review)](https://www.skills.sh/joaopmarques/code-review-review) |
| [dial-in](https://github.com/joaopmarques/dial-in) | Puts live controls next to a UI component. You tweak by eye, and Claude writes the values back to source. | [![skills.sh](https://www.skills.sh/b/joaopmarques/dial-in)](https://www.skills.sh/joaopmarques/dial-in) |

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
