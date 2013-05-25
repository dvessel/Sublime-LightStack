Personal Sublime Text theme.

![Screen Shot](https://raw.github.com/dvessel/dvessel-theme/master/screen-shot.png)

### Suggested Additions:

- [Anonymous Pro Font](http://www.marksimonson.com/fonts/view/anonymous-pro)
- [Soda Theme](http://buymeasoda.github.io/soda-theme/)
- [GitGutter](https://github.com/jisaacks/GitGutter)
- [SublimeLinter](https://github.com/SublimeLinter/SublimeLinter)


### Suggested Settings:

`@file Packages/User/Preferences.sublime-settings`

```json
{
  "color_scheme": "Packages/LightStack/LightStack.tmTheme",
  "draw_white_space": "all",
  "font_face": "Anonymous Pro",
  "font_size": 14.0,
  "highlight_line": true,
  "indent_guide_options": [ "draw_active" ],
  "line_padding_top": 4,
  "margin": 0,
  "theme": "Soda Light.sublime-theme"
}
```

`@file Packages/User/Find Results.sublime-settings`

```json
{
  "gutter": false,
  "indent_guide_options": [],
  "margin": 10
}
```

`@file Packages/User/SublimeLinter.sublime-settings`

```json
{
  "sublimelinter_mark_style": "outline"
}
```

### Extras:

This color scheme includes modifications to the Soda Light theme. All you have to do to enable it is to link the `Soda Light.sublime-theme` and `Widget - Soda Light.sublime-settings` file to your `Packages/User` folder.

This is not a hack. It's a supported feature of Sublime Text. More information can be found in the [Soda theme wiki](https://github.com/buymeasoda/soda-theme/wiki/Theme-customisation).

```bash
ln -s ~/Library/Application\ Support/Sublime\ Text\ 2/Packages/LightStack/Soda\ Light/*.sublime-* ~/Library/Application\ Support/Sublime\ Text\ 2/Packages/User/
```
