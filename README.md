# Dotfiles for Mac workflow tools
## Creating symbolic links
> **_NOTE:_** Do not make a symlink to karabiner.json directly. Karabiner-Elements will fail to detect the configuration file update and fail to reload the configuration if karabiner.json is a symbolic link. Symlink the whole `~/.config/karabiner` directory instead.
```bash
ln -s ~/projects/mac-workflow-config/karabiner ~/.config/karabiner
ln -s ~/projects/mac-workflow-config/skhd ~/.config/skhd
ln -s ~/projects/mac-workflow-config/yabi ~/.config/yabai
```
