```sh
rm -rf ~/.config/nvim
rm -rf ~/.local/state/nvim
rm -rf ~/.local/share/nvim
```

```sh
git clone https://github.com/NvChad/starter ~/.config/nvim && nvim
```
## use the commands in nvim terminal like ":MasonInstallAll"
```sh
MasonInstallAll
```

## install treesitter for languages
```sh
TSInstall <name of the language>
```
## to check available languages
```sh
TSModuleInfo
```

## some important key-bindins
<kbd>space </kbd> + <kbd>ch</kbd>  : cheatsheets of nvim
ctrl + n : open/close file tree
space + ff : find files && esc : close find files
space + h  : horizontal terminal
space + v  : vertical terminal

---
# LSP : Code compeletion
video reference : https://youtu.be/yfAtL6Ji684?si=_BOef_wTIfuMN7ac
https://youtu.be/Mtgo-nP_r8Y?si=gOOwo-vreT9WUUXH

.config>nvim>lua>custom : 