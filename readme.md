Home - [Customizations](/customizations) - [Packages](/packages) - [Themes](/themes)

# Sublime Text Configuration

This will document and provide files concerning my ideal Sublime Text 3 installation, including [customizations](/customizations), [packages](/packages), [themes](/themes), and configuration.

**Preferences.sublime-settings**:

```
{
  "ignored_packages":
  [
    "Markdown",
    "Vintage"
  ],
  "color_scheme": "Packages/User/Themes/pastel (SL).tmTheme",
  "word_wrap": true,
  "font_face": "Fira Code Light",
  "font_size": 20,
  "line_padding_top": 2,
  "line_padding_bottom": 2,
  "tab_size": 2,
  "detect_indentation": true,
  "translate_tabs_to_spaces": true,
  "trim_trailing_white_space_on_save": true,
  "ensure_newline_at_eof_on_save": true,
  "indent_to_bracket": true,
  "highlight_line": true,
  "draw_minimap_border": true,
  "highlight_modified_tabs": true,
  "match_brackets": true,
  "match_brackets_angle": true,
  "match_brackets_braces": true,
  "match_brackets_content": true,
  "match_brackets_square": true,
  "scroll_past_end": true,
  "show_panel_on_build": false,
}
```

**Default (OSX).sublime-keymap**:

```
[
  { "keys": ["super+v"], "command": "paste_and_indent" },
  { "keys": ["super+shift+alt+c"], "command": "find_use"},
  {
    "keys": ["alt+up"],
    "command": "run_macro_file",
    "args": {"file": "Packages/User/quick_cursor/move_3_lines_up.sublime-macro"}
  },
  {
    "keys": ["alt+down"],
    "command": "run_macro_file",
    "args": {"file": "Packages/User/quick_cursor/move_3_lines_down.sublime-macro"}
  },
  {
    "keys": ["alt+shift+up"],
    "command": "run_macro_file",
    "args": {"file": "Packages/User/quick_cursor/extend_3_lines_up.sublime-macro"}
  },
  {
    "keys": ["alt+shift+down"],
    "command": "run_macro_file",
    "args": {"file": "Packages/User/quick_cursor/extend_3_lines_down.sublime-macro"}
  },
  { "keys": ["super+alt+up"], "command": "inc_dec_value", "args": { "action": "inc_min" } },
  { "keys": ["super+alt+down"], "command": "inc_dec_value", "args": { "action": "dec_min" } }
]
```
