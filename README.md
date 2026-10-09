# athleteOS-marketplace

The `athleteOS-plugins` marketplace: the catalog of Claude Code plugins for AthleteOS work. The catalog is `.claude-plugin/marketplace.json`; each plugin lives in a repository of its own.

## Add it

```text
/plugin marketplace add lgerard314/athleteOS-marketplace
```

This repository and the plugin repository are public, so no access needs granting.

## Plugins

| Plugin | Install | Repository | What it does |
|---|---|---|---|
| `aos-ppt-design` | `/plugin install aos-ppt-design@athleteOS-plugins` | `lgerard314/aOS-ppt-design` | AthleteOS brand design guidelines for PowerPoint slides, with the logo and font files |

## Changing the catalog

To list another plugin, add an entry to `plugins` in `.claude-plugin/marketplace.json` and a row to the table above, and raise the marketplace's `version`. A plugin's own version is set in that plugin's `.claude-plugin/plugin.json`, not here.
