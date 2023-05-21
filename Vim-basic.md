## Vim Basics

### Basic Navigation

- Normal mode:
  - Use `h`, `j`, `k`, and `l` keys to move the cursor left, down, up, and right respectively.
  - `gg` moves to the beginning of the file, `G` moves to the end.
  - `w` moves forward word by word, `b` moves backward.
  - `0` moves to the beginning of a line, `$` moves to the end.
  - `Ctrl + F` moves forward one screen, `Ctrl + B` moves backward.

### Editing Text

- Insert mode:
  - Press `i` in Normal mode to enter Insert mode for inserting and editing text.
  - Press `Esc` to exit Insert mode and return to Normal mode.
- Deletion:
  - Use `x` to delete the character under the cursor.
  - `dd` deletes the current line.
- Copy and Paste:
  - `p` pastes the previously deleted or yanked text.
- Undo and Redo:
  - `u` undoes the last change, `Ctrl + r` redoes.

### Saving and Quitting

- Saving:
  - Use `:w` to save the file.
- Quitting:
  - Use `:q` to quit Vim. If there are unsaved changes, it prompts to save first.
  - Use `:wq` to save and quit simultaneously.

### Search and Replace

- Search:
  - Press `/` to enter search mode.
  - Type the text to search and press `Enter`.
- Navigation:
  - Press `n` to move to the next occurrence.
  - Press `N` to move to the previous occurrence.
- Replace:
  - Use the substitution command. For example, `:%s/foo/bar/g` replaces all instances of 'foo' with 'bar'.
