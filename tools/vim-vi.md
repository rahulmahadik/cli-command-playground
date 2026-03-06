# Vim Commands Cheatsheet

> Vim is a terminal-based text editor. Edit files at the speed of thought with a powerful modal editor.

## Quick Reference

> **Preview** — This is a curated selection of key commands. Explore the full command list with examples, practice exercises, and more on [Command Playground](https://technoscripts.com/command-playground/?utm_source=github&utm_medium=repository&utm_campaign=explore-all).

| Command | Description |
|---------|-------------|
| `hjkl` | Move cursor left, down, up, right |
| `w/b/e` | Move by word forward, back, end |
| `gg/G` | Go to first or last line |
| `0/^/$` | Go to line start, first char, line end |
| `Ctrl+d/u` | Scroll half-page down or up |
| `:line_number` | Jump to a specific line number |
| `f/F/t/T` | Find character forward or backward |
| `gf` | Open file under cursor |
| `i/a/o` | Insert before, after, below cursor |
| `x/X` | Delete character at or before cursor |
| `dd/D` | Delete entire line or to end of line |
| `yy/p/P` | Yank line, paste after or before |
| `u/Ctrl+r` | Undo or redo last change |
| `c/C` | Change text or change to end of line |
| `r/R` | Replace character or enter replace mode |
| `J` | Join the current line with the next |
| `Ctrl+n` | Auto-complete word in insert mode |
| `/pattern` | Search forward for a pattern |
| `n/N` | Repeat search forward or backward |
| `:s/old/new/` | Substitute first match on current line |
| `:%s/old/new/g` | Substitute all matches in file |
| `*/#` | Search word under cursor forward/back |
| `:w` | Save the current file |
| `:q/:q!` | Quit or force quit without saving |
| `:wq/:x/ZZ` | Save and quit the editor |
| `:e filename` | Open a file for editing |
| `:r filename` | Insert file contents at cursor |
| `v/V/Ctrl+v` | Enter visual, line, or block mode |
| `Visual + d/y/c` | Delete, yank, or change selection |
| `Visual Block Insert` | Insert text in block selection |
| `iw/aw` | Select inner or around word |
| `i"/a"` | Select inside or around quotes |
| `i{/a{` | Select inside or around braces |
| `:split/:vsplit` | Split window horizontally or vertically |
| `Ctrl+w commands` | Navigate between split windows |
| `:ls/:bn/:bp` | List, next, or previous buffer |
| `:tabnew/:tabn` | Open new tab or switch tabs |
| `:set nowrap` | Disable line wrapping |
| `:set number` | Show line numbers |
| `\ERROR:g/pattern/` | Search for error patterns in logs |
| `:v/pattern/d` | Delete lines not matching a pattern |
| `view/vim -R` | Open file in read-only mode |
| `:set syntax=` | Set syntax highlighting language |
| `:set filetype=` | Set the file type |
| `:retab` | Convert tabs to spaces or vice versa |
| `:set expandtab` | Use spaces instead of tabs |
| `:sort` | Sort lines in the buffer |
| `q{register}` | Record a macro into a register |
| `"{register}` | Use a specific register |
| `m{mark}/'{mark}` | Set or jump to a named mark |
| `zf/zo/zc` | Create, open, or close a fold |
| `.` | Repeat the last editing command |
| `:normal` | Execute normal mode commands |
| `:!` | Execute an external shell command |
| `vimdiff` | Compare two files side by side |
| `:set spell` | Enable spell checking |
| `q:` | Open the command-line history window |
| `scp://` | Edit remote files via SCP |
| `Field Extraction` | Extract and manipulate text fields |
| `:mksession` | Save the current Vim session |

## Practice & Resources

| Resource | Link |
|----------|------|
| **Practice Vim interactively** | [Open Terminal](https://technoscripts.com/cli/vim-vi/?utm_source=github&utm_medium=repository&utm_campaign=cli-practice) |
| **Download PDF Cheatsheet** | [Get Cheatsheet](https://technoscripts.com/command-playground/cheatsheet/vim-vi-commands/?utm_source=github&utm_medium=repository&utm_campaign=cheatsheet) |
| **Typing Practice** | [Type Vim Commands](https://technoscripts.com/command-playground/typing-practice/vim-vi/?utm_source=github&utm_medium=repository&utm_campaign=typing) |
| **All 105+ CLI Tools** | [Browse Tools Directory](https://technoscripts.com/command-playground/?utm_source=github&utm_medium=repository&utm_campaign=tools-directory) |

---

*Part of the [CLI Commands Cheatsheet](../README.md) collection by [TechnoScripts](https://technoscripts.com/?utm_source=github&utm_medium=repository&utm_campaign=tool-page)*
