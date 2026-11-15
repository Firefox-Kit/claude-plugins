# Firefox-Kit Claude plugins

Plugin marketplace for Claude Code and Cowork, maintained by Firefox-Kit.

## Plugins

| Plugin | Version | Source |
|---|---|---|
| prompt-improver | 0.7.0 | [Firefox-Kit/claude-code-prompt-improver](https://github.com/Firefox-Kit/claude-code-prompt-improver), pinned to the v0.7.0 release commit |
| diogenes | 1.2.3-fk.1 | [Firefox-Kit/diogenes](https://github.com/Firefox-Kit/diogenes), pinned to commit `2b7279b` on `develop` |
| prompt-architect | 3.5.1 | [Firefox-Kit/prompt-architect](https://github.com/Firefox-Kit/prompt-architect), pinned to commit `6c7a2c7` on `main` |

## Install

Add the marketplace once:

```bash
claude plugin marketplace add Firefox-Kit/claude-plugins
```

Then install the plugins you want:

```bash
claude plugin install prompt-improver@firefox-kit
claude plugin install diogenes@firefox-kit
claude plugin install prompt-architect@firefox-kit
```

## Release policy

Each plugin entry pins a reviewed commit with a 40-character `sha`.
`ref` records the tag or branch that commit was taken from; installs use the `sha`, so later commits on that branch are not picked up until the entry is updated.
Changes to `.claude-plugin/marketplace.json` go through pull requests.
