# Manjaro theme for Midnight Commander

## Installation

- Copy files from ./skins to ~/.local/share/mc/skins
- Copy files from ./config to ~/.config/mc/ (optional)
-
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
