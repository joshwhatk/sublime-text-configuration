[Home](https://github.com/joshwhatk/sublime-text-configuration) - [Customizations](/customizations) - [Packages](/packages) - [Themes](/themes)

# TrailingSpaces Settings

[Github](https://github.com/SublimeText/TrailingSpaces)

**trailing_spaces.sublime-settings**:

```
{
    "trailing_spaces_highlight_color": "invalid",
    "trailing_spaces_include_current_line" : false,
    "trailing_spaces_modified_lines_only": false,
    "trailing_spaces_trim_on_save": false
}
```

If not kept track of, trailing spaces can get out of hand quickly. With this package, it marks trailing spaces as invalid so that you can easily see them in the document.

I do not use this package to trim trailing white spaces on save because, although trailing spaces are generally bad, in Markdown and some other rare cases, it may be useful to be able to quickly switch it off. Sublime Text has it's own setting for trimming trailing white spaces which can easily be overridden for specific languages or simply turned off.
