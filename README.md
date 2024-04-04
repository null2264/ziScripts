# ziScripts

Collection of scripts that I personally used.

## Dependencies
- `bc`
- `jq`
- `jo`
- `socat`

## Scripts

### Automation
- `bootstrap`: [WIP] Automatically rice your Arch Linux
- `post-python-upgrade`: Python script that install packages installed on old python install to newer one.
- `zsh-plug-install`: Basically just git clone alias for zsh plugins

### `eww` scripts

> [!WARNING]
> Requires `bc`, `jq`, `jo`, and `socat`!

- `eww-datetime-listener`
- `eww-hyprland-active-workspace-listener`
- `eww-hyprland-workspace-list-listener`
- `eww-launch`: Launch eww, seems to fix odd behaviour when eww being launch by Hyprland's exec-once

### Productivity QoL scripts

> [!WARNING]
> Requires `jq`!

- `dropbox`: Simple dropbox uploader, also able to share file and print the url using `-s` flag.
- `template`: Simple template manager, create a template or copy a template to a destination.
- `todo`: Simple todo list.

### Gaming with WayDroid

> [!CAUTION]
> This scripts uses binary file, compile it yourself if you don't trust it.
>
> Requires `waydroid`!

- `xtmapper-launch`: [WIP] Automatically launch Waydroid and bind XtMapper to Waydroid.
  - `xtmapper-bind`: Bind XtMapper to Waydroid.
  - `bin/xtmapper-client`: Not a script, it's a [fork](https://github.com/null2264/wayland-getevent) of [wayland-getevent](https://github.com/Xtr126/wayland-getevent) to hardcode its window size because resizing it doesn't work on hyprland for me.
- `xqtscrcpy`: Force qtscrcpy to use XWayland.
