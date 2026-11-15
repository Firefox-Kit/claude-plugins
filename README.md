# Firefox-Kit Claude plugins

Plugin marketplace for Claude Code and Cowork, maintained by Firefox-Kit.

## Plugins

| Plugin | Version | Source |
|---|---|---|
| prompt-improver | 0.7.0 | [Firefox-Kit/claude-code-prompt-improver](https://github.com/Firefox-Kit/claude-code-prompt-improver), pinned to the v0.7.0 release commit |

## Install

```bash
claude plugin marketplace add Firefox-Kit/claude-plugins
claude plugin install prompt-improver@firefox-kit
```

## Release policy

Each plugin entry pins a reviewed release with `ref` and a 40-character `sha`.
Changes to `.claude-plugin/marketplace.json` go through pull requests.
