# Claude Code Plugins Marketplace

A curated marketplace of plugins for [Claude Code](https://docs.anthropic.com/en/docs/claude-code).

## Available Plugins

| Plugin    | Description                                 | Repository                                                                           |
| --------- | ------------------------------------------- | ------------------------------------------------------------------------------------ |
| clipboard | Tools for working with the system clipboard | [claude-plugin-clipboard](https://github.com/martinhjartmyr/claude-plugin-clipboard) |

## Installation

### Add the Marketplace

```bash
claude plugin marketplace add martinhjartmyr/mh-cc-plugins
```

### Install a Plugin

```bash
claude plugin install clipboard@mh-cc-plugins
```

### List Available Plugins

```bash
claude plugin list
```

### Enable Auto-Update

Within Claude Code, use the `/plugin` command to open the plugin manager, then:

1. Select "Marketplaces"
2. Choose "mh-cc-plugins"
3. Enable auto-update

### Uninstall a Plugin

```bash
claude plugin uninstall clipboard
```

### Remove Marketplace

```bash
claude plugin marketplace remove mh-cc-plugins
```

## License

MIT
