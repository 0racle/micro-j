# J support for Micro

[Micro](https://micro-editor.github.io/) syntax file for the [J programming language](https://www.jsoftware.com/).

## Installation

This plugin is not in the official micro plugin channel.
Until that is done, you can either clone the repo, or update your repository settings and install with micro.

### Clone

Simply clone this repo into `~/.config/micro/plug` and restart micro.

### Repository
:s

Add this repo to the `pluginrepos` in `~/.config/micro/settings.json` and restart micro.

```json
{
  "pluginrepos": [
      "https://raw.githubusercontent.com/0racle/micro-j/master/repo.json"
  ]
}
```

In the micro editor press `Ctrl-e` and run command:

```
> plugin install j
```

or run in your shell

```sh
micro -plugin install j
```
