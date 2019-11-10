# V syntax highlighting for Kate

WIP syntax highlighting for the [V](https://vlang.io/) language.

## Install

### Linux/Unix
Add `v.xml` symlink (or copy file) to:
`$HOME/.local/share/katepart5/syntax`

### Windows
Copy to `%USERPROFILE%/AppData/Local/org.kde.syntax-highlighting/syntax`. (`%USERPROFILE%` usually expands to `C:\\Users\\user`)

More info on katepart [here](https://docs.kde.org/stable5/en/applications/katepart/highlight.html)

## Usage
Unfortunately files ending in `*.v` is also used by the Verlog language. To make V source files take precedence over Verilog you can go to:
Settings -> Editor Component -> Open / Save -> Modes & Filetypes -> Filetype: "Sources/V -> Priority: 1

For setting a higher priority than Verilog.

![image](https://user-images.githubusercontent.com/768942/68543032-6a421880-03b2-11ea-80cd-8284fa0f030b.png)