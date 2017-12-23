<!-- TITLE: ec -->

#  **`ec [k] [color]`** set color for given key (prompt, offset, ...)


```text
Usage ec[s?] [key][[=| ]fg] [bg]
```


- **`ec`** list all color keys
- **`ec*`** same as above, but using r2 commands
- **`ecd`** set default palette
- **`ecr`** set random palette (see also scr.randpal)
- **`ecs`** show a colorful palette
- **`ecj`** show palette in JSON
- **`ecc [prefix]`** show palette in CSS
- **`eco dark|white`** load white color scheme template
  > _Use eco to see a list of themes_

    - [Themes](/themes)

- **`ecp`** load previous color theme
- **`ecn`** load next color theme

- [ **`ecH[?]`** highlight word or instruction](/options/e/ec/ec_cap_H)

- **`ec prompt red`** change color of prompt
- **`ec prompt red blue`** change color and background of prompt
- **`colors:`** rgb:000, red, green, blue, ...
- **`e scr.rgbcolor=1|0`** for 256 color cube (boolean)
- **`e scr.truecolor=1|0`** for 256 _256_ 256 colors (boolean)
- **`$DATADIR/radare2/cons`** ~/.config/radare2/cons ./