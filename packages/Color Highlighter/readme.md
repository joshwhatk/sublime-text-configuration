[Home](https://github.com/joshwhatk/sublime-text-configuration) - [Customizations](/customizations) - [Packages](/packages) - [Themes](/themes)

# Color Highlighter Settings

[Github](https://github.com/Monnoroch/ColorHighlighter)

This will ensure that the colors show as a filled box around the text.

**ColorHighlighter.sublime-settings**:

```
{
  "search_colors_in": {
    "all_content": {
      "enabled": true,
      "color_highlighters": {
        "color_scheme": {
          "enabled": true,
          "highlight_style": "filled"
        },
        "gutter_icons": {
          "enabled": true,
          "icon_style": "circle"
        },
        "phantoms": {
          "enabled": false,
          "style": "right",
          "length": 2
        }
      }
    }
  }
}

```
