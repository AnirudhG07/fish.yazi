# fish.yazi

Run Fish <°))>< shell as your default yazi shell.

## Previews

## Requirements

Yazi version 0.2.5 or higher. And of course, fish shell as default shell.

## Installation

```bash
## For linux and MacOS
git clone https://github.com/AnirudhG07/fish.yazi.git ~/.config/yazi/plugins/fish.yazi

## For Windows
git clone https://github.com/AnirudhG07/fish.yazi.git %AppData%\yazi\config\plugins\fish.yazi
```

Windows user's should check the init.lua file to make sure the paths used are correct.

## Usage

Add this to your `keymap.toml` file:

```toml
[[manager.prepend_keymap]]
on = [ ":" ]
run = "plugin fish"
desc = "Fish <°))>< shell"
```

## Acknowldegements

This code is inspired from [zsh.yazi](https://github.com/AnirudhG07/zsh.yazi) and I would like to thank maintainers of sxyazi/yazi for their help and guidance.
