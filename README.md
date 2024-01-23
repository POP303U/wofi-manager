<div align="center"> 
<h2> wofi-manager </h2>
Settings menu for my hypr-dots

</div>

## Foreword
This will propably not work without my Hyprland config [hypr-dots](https://github.com/POP303U/hypr-dots).

## Installation

```
git clone https://github.com/POP303U/wofi-manager ~/wofi/wofi-manager
chmod +x ~/wofi/wofi-manager/wofi-manager
sudo cp ~/wofi/wofi-manager/wofi-manager /bin
```

### Hyprland keybinding

```
bind $mainMod, S, exec, wofi-manager "main"
```

### Thanks for the inspiration!

- [rofi+pywal theme switcher](https://dev.to/mafflerbach/theme-switcher-based-on-rofi-and-pywal-4128)
