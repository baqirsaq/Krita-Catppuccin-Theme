<h3 align="center">Catppuccin for <a href="https://github.com/KDE/krita">Krita</a></h3>

<p align="center">
  This port of <a href="https://github.com/catppuccin/">Catppuccin</a> for Krita.
</p>
<p align="center">
  <a href="https://github.com/baqirsaq/Krita-Catppuccin-Theme/stargazers">
    <img src="https://img.shields.io/github/stars/baqirsaq/Krita-Catppuccin-Theme?colorA=363a4f&colorB=b7bdf8&style=for-the-badge" alt="Stars Badge">
  </a>
  <a href="https://github.com/baqirsaq/Krita-Catppuccin-Theme/issues">
    <img src="https://img.shields.io/github/issues/baqirsaq/Krita-Catppuccin-Theme?colorA=363a4f&colorB=f5a97f&style=for-the-badge" alt="Issues Badge">
  </a>
  <a href="https://github.com/baqirsaq/Krita-Catppuccin-Theme/contributors">
    <img src="https://img.shields.io/github/contributors/baqirsaq/Krita-Catppuccin-Theme?colorA=363a4f&colorB=a6da95&style=for-the-badge" alt="Contributors Badge">
  </a>
</p>
<p align="center">
  <img src="https://github.com/baqirsaq/Krita-Catppuccin-Theme/blob/0895d68e99981c15ef802b03f15faff5ed66a989/Preview/banner.png"/>
</p>

----

## Previews

<details>
<summary>🌻 Latte</summary>
<img src="https://github.com/baqirsaq/Krita-Catppuccin-Theme/blob/0895d68e99981c15ef802b03f15faff5ed66a989/Preview/Latte.png"/>
</details>
<details>
<summary>🪴 Frappé</summary>
<img src="https://github.com/baqirsaq/Krita-Catppuccin-Theme/blob/0895d68e99981c15ef802b03f15faff5ed66a989/Preview/Frappe.png"/>
</details>
<details>
<summary>🌺 Macchiato</summary>
<img src="https://github.com/baqirsaq/Krita-Catppuccin-Theme/blob/0895d68e99981c15ef802b03f15faff5ed66a989/Preview/Macchiato.png"/>
</details>
<details>
<summary>🌿 Mocha</summary>
<img src="https://github.com/baqirsaq/Krita-Catppuccin-Theme/blob/0895d68e99981c15ef802b03f15faff5ed66a989/Preview/Mocha.png"/>
</details>

## Installation

1. In Krita, look to the menu bar at the very top
2. Select: Settings > Manage Resources
3. With the Manage Resource window open, select the "Open Resource Folder"
4. Look for the "color-schemes" folder
5. Copy and paste the .colors files into the color-schemes folder
6. Restart Krita
7. Then you just need to go to Settings > Themes > Chose your theme
8. Restart Krita and see the theme
> [!IMPORTANT]  
> To change the go to: Canvas Border Colour Settings > Confiure Krita > Display > Canvas Decoration > Canvas Border Colour

## Configuration
There is no `config file` (yet?), therefore you can make a copy of the theme, change the `Name` and `ColorScheme`:
```color
[General]
Name = Catppuccin Mocha 
ColorScheme = Catppuccin-Mocha
```
And then edit the colours:
```color
[General]
Name = Your Edited Name
ColorScheme = Your-Edited-Name
shadeSortColumn = true

[Colors:Button]
BackgroundAlternate = 30,30,46
BackgroundNormal = 30,30,46
ForegroundNormal = 191,187,169
DecorationFocus = 159,71,104 ; Accent colour for focus/decoration
DecorationHover = 159,71,104 ; Accent colour for hover

[Colors:Selection]
BackgroundNormal = 137,180,250
ForegroundNormal = 255,255,255

[Colors:View]
BackgroundAlternate = 35,39,57
BackgroundNormal = 35,39,57
ForegroundActive = 217,216,216
ForegroundNormal = 191,187,169

[Colors:Window]
BackgroundAlternate = 45,45,67
BackgroundNormal = 35,39,57
ForegroundNormal = 191,187,169

[Colors:Tooltip]
BackgroundNormal = 45,45,67
ForegroundNormal = 220,218,217

[Colors:Text]
BackgroundNormal = 35,39,57
ForegroundNormal = 217,216,216
ForegroundInactive = 147,153,178

[Colors:Complementary]
BackgroundNormal = 30,30,46
ForegroundNormal = 217,216,216
DecorationFocus = 159,71,104 ; Accent colour for focus/decoration
DecorationHover = 137,180,250 ; Accent colour for hover
```
 
> [!NOTE]  
> Don't forget to change you theme and restart krita to see the changes!
