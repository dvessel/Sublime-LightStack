Personal Sublime Text theme.

![Screen Shot](https://raw.github.com/dvessel/dvessel-theme/master/screen-shot.png)

### Suggested Packages:

- [Soda Theme](http://buymeasoda.github.io/soda-theme/)
- [GitGutter](https://github.com/jisaacks/GitGutter)
- [SublimeLinter](https://github.com/SublimeLinter/SublimeLinter)


### Suggested Settings:

Font: [Anonymous Pro](http://www.marksimonson.com/fonts/view/anonymous-pro)

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
  "theme": "Soda Light.sublime-theme",
}
```

`@file Packages/User/Find Results.sublime-settings`

```json
{
  "gutter": false,
  "indent_guide_options": [],
  "margin": 10,
}
```

`@file Packages/User/SublimeLinter.sublime-settings`

```json
{
  "sublimelinter_mark_style": "outline"
}
```
