# KDE desktop setup based around Lightly style
![image](https://user-images.githubusercontent.com/43888122/220772500-0cfcf5b8-3d66-42e4-b987-7de3b603796c.png)

## Install required packages

Install [_Lightly_](https://store.kde.org/p/1414190) application style.

Install [_Maia Transparent_](https://store.kde.org/p/1085371) Plasma style.

Install [_Papirus_](https://store.kde.org/p/1166289) icon theme (yaru colors).

Copy _Darkly.colors_ from [here](https://github.com/Luwx/Lightly/blob/73739ab9eb6934ce886d4d237539208556fe8902/Darkly.colors) to `~/.local/share/color-schemes/darkly.colors`.

## KDE setting

1. Set dark theme
2. In `Global Theme -> Application Style` set _Lightly_
3. Setup desired transparency in _Lightly_ settings
4. In `Global Theme -> Plasma Style` set _Maia Transparent_
5. In `Global Theme -> Colors` set _Darkly_
6. In `Global Theme -> Window Decorations` set _Lightly_
7. In `Global Theme -> Icons` set _Papirus-Dark_

## Setup terminal transparency

In _yakuake_ or _konsole_ profile setting, go to `Apperance` and edit _Breeze_ color scheme. Turn on `Blur background` and set up desired background transparency.

This will be enough for _konsole_ but _yakuake_ needs additional steps. In order to apply blur background for Yakuake, edit the `~/.config/yakuakerc` file:

```
[Appearance]
Blur=true
Translucency=true
```

## Beautify terminal

According to [this tutorial](https://youtu.be/iaXQdyHRL8M).
