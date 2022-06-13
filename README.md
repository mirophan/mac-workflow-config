# Configuration files for Mac workflow tools
## Karabiner
Do not make a symlink to karabiner.json directly. Karabiner-Elements will fail to detect the configuration file update and fail to reload the configuration if karabiner.json is a symbolic link. Symlink the whole `~/.config/karabiner` directory instead.

Example symlink
```bash
ln -s ~/projects/mac-workflow-config/karabiner ~/.config/karabiner
```
