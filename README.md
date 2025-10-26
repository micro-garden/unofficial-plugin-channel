# Micro Garden - Unofficial Plugin Channel for Micro

This is an unofficial plugin channel for the
[micro](https://micro-editor.github.io/) text editor.
By adding this channel to your plugin sources, you can easily install several
unofficial plugins developed by
[Micro Garden](https://github.com/micro-garden) team.

## Installation

To add this plugin channel, edit your `settings.json` file while preserving
proper JSON format.
This file is typically located at `~/.config/micro/settings.json`.

Add (or append) the following to the `"pluginchannels"` list:

```json
{
    "pluginchannels": [
        "https://raw.githubusercontent.com/micro-editor/plugin-channel/master/channel.json",
        "https://raw.githubusercontent.com/micro-garden/unofficial-plugin-channel/master/channel.json"
    ]
}
```

To install a plugin from this channel (for example, `colorswitcher`), open
`micro` and run:

```
plugin install colorswitcher
```

## Plugins

| Code Name         | Name                     | Description                                                                               | Link                                                    |
| ----------------- | ------------------------ | ----------------------------------------------------------------------------------------- | ------------------------------------------------------- |
| `colorswitcher`   | Color Switcher           | Easily cycle through color schemes using keyboard shortcuts or commands.                  | https://github.com/micro-garden/colorswitcher-plugin |
| `fmtonsave`       | Format on Save           | Auto-format files on save using formatters like StyLua.                                   | https://github.com/micro-garden/fmtonsave-plugin     |
| `autotheme`       | Auto Theme               | Automatically sets the colorscheme based on syntax (filetype).                            | https://github.com/micro-garden/autotheme-plugin     |
| `colorshuffle`    | Color Shuffle            | Shuffles your theme each time you open a file.                                            | https://github.com/micro-garden/colorshuffle-plugin  |
| `karehacolors`    | Kareha Colors            | A warm and calm color scheme, evoking the feel of fallen leaves.                          | https://github.com/micro-garden/kareha-colorschemes  |
| `diffpatchsyntax` | diff and patch Syntax    | Syntax highlighting for diff and patch files.                                             | https://github.com/micro-garden/diffpatch-syntax     |
| `gtypistsyntax`   | GNU Typist Syntax        | Syntax highlighting for GNU Typist lesson files.                                          | https://github.com/micro-garden/gtypist-syntax       |
| `mdfy`            | MDfy (Markdown-ize)      | Convert a URL under the cursor into a Markdown link.                                      | https://github.com/micro-garden/mdfy-plugin          |
| `toggle`          | Toggle Options           | Adds two commands for toggling boolean configuration options.                             | https://github.com/micro-garden/toggle-plugin        |
| `shout`           | Shell Out                | Run the current line as a shell command and insert the output below.                      | https://github.com/micro-garden/shout-plugin         |
| `openconfig`      | Open Config              | Adds commands to open micro config files like settings.json, bindings.json, and init.lua. | https://github.com/micro-garden/openconfig-plugin    |
| `pushd`           | pushd                    | Provides shell-like pushd, popd, and dirs commands.                                       | https://github.com/micro-garden/pushd-plugin         |
| `mdtblfmt`        | Markdown Table Formatter | Reformats all Markdown tables in the current buffer.                                      | https://github.com/micro-garden/mdtblfmt-plugin      |
| `colorgen`        | Color Generator          | Randomly generates a new 16-color colorscheme each time you run the command.              | https://github.com/micro-garden/colorgen-plugin      |
| `pubcolors`       | Publc Colors             | A public color scheme collection.                                                         | https://github.com/micro-garden/pub-colorschemes     |
| `skk`             | SKK                      | A Japanese input method inspired by the SKK.                                              | https://github.com/micro-garden/skk-plugin           |
| `vi`              | vi                       | Provides a simple vi-style modal editing mode.                                            | https://github.com/micro-garden/vi-plugin            |
| `mtp`             | TextPad Colors           | Mimics TextPad theme                                                                      | https://github.com/micro-garden/textpad-colorschemes |
