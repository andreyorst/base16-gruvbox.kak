# base16-gruvbox.kak
Base16 Gruvbox Dark Soft variant colorscheme for Kakoune editor. Based on Vim's base16-gruvbox-dark-soft theme.

> ![image](https://user-images.githubusercontent.com/19470159/47956689-84843200-dfb9-11e8-8176-fa09b2b28ace.png)

# Installation

### Via [plug.kak](https://github.com/andreyorst/plug.kak)

```kak
plug "andreyorst/base16-gruvbox.kak" noload do %{
    ln -sf $PWD/colors/base16-gruvbox-dark-soft.kak` $HOME/.config/kak/colors
} config %{
    colorscheme base16-gruvbox-dark-soft
}
```

### Without plugin manager

Place a symbolic link of `base16-gruvbox-dark-soft.kak` to your `colors` folder
