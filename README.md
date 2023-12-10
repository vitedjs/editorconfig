# @vited/editorconfig

Recommended EditorConfig for Vited projects

```ini
root = true

[*]
charset = utf-8
end_of_line = lf
indent_size = 2
indent_style = space
insert_final_newline = true
trim_trailing_whitespace = true
quote_type = single
max_line_length = 120
```

If you created your project with vited, this editorconfig should already be included. If not, copy above content into your `.editorconfig` file.

## Single quote

By using single quotes, you press less `Shift` key. It is faster ans healther for your hands.

## Print width 100

Tradional 80-character print width is too narrow for modern screen. Considering the smallest common screen usage:

- 1920x1080 screen with 150% scale, actual width **1280px**
- 2560x1440 screen with splitting, actual with **1280px**

If you use VS Code, with side panel, line numbers, scroll mini-map, your actual code area is about **750px**. If you use 14px font size (default), you can see about **107** characters. So we think **100** should be a good option for most developers.
