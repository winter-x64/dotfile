# Helix Editor Configuration

helix is a terminal based txt editor

```toml
theme = "base16_transparent"

[editor]
line-number = "absolute"
mouse = true
true-color = true
bufferline = "multiple"

[editor.cursor-shape]
insert = "bar"
normal = "block"
select = "underline"

[editor.file-picker]
hidden = false

[editor.lsp]
display-messages = true

[editor.indent-guides]
render = false
character = ""

[editor.statusline]
left = ["mode", "spinner"]
center = ["file-name"]
right = ["diagnostics", "selections", "position", "file-encoding", "file-line-ending", "file-type"]
separator = "│"
```
