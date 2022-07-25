# polybar-sequoia-theme

Sequoia theme for polybar

**Top bar**
![bar-top](https://user-images.githubusercontent.com/43127622/180820536-660883d3-aab5-4c56-bfc7-4b8a8fccee03.png)

**Bottom bar**
![bar-bottom](https://user-images.githubusercontent.com/43127622/180820545-83d57d8b-3c00-4adb-be82-c43bbc54af46.png)

## User settings

### [module/launcher]

When the launcher module is left-clicked, the script is executed.
This settings uses `~/.config/rofi/bin/launcher_misc`.

```ini:config.ini
[module/launcher]
; Change to your launcher script.
click-left = ~/.config/rofi/bin/launcher_misc &
```

### [module/sysmenu]

When the sysmenu module is left-clicked, the script is executed.
This settings uses `~/.config/rofi/bin/powermenu`.

```ini:config.ini
[module/sysmenu]
; Change to your launcher script.
click-left = ~/.config/rofi/bin/powermenu &
```
