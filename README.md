# Midnight Commander Config & Skins

GNU Midnight Commander is a visual file manager, licensed under GNU General Public License and therefore qualifies as Free Software. It's a feature rich full-screen text mode application that allows you to copy, move and delete files and whole directory trees, search for files and run commands in the subshell. Internal viewer and editor are included.

[Site Documentation](https://midnight-commander.org/)

## Installation

- Copy files from `./skins` to `~/.local/share/mc/skins`
- Copy files from `./config` to `~/.config/mc` (optional)

## Activating ways

1. Choose the skin through the mc UI with:

```sh
# F9 > Options > Appearance
```

2. Edit `~/.config/mc/ini` and add `skin=onedark`:

```sh
sed -i 's|\(^skin=\).*$|\manjaro|' ~/.config/mc/ini
```

3. Run mc with specific skin:

```sh
mc -S manjaro
```

4. Add `export MC_SKIN=manjaro` to the initialization file of your shell (e.g., `~/.bashrc` or `~/.zshrc`):

```sh
echo "export MC_SKIN=manjaro" >> ~/.zshrc
```

©️ Asapdotid 2024
