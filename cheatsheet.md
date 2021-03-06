# Navigation
- Go to lower/upper pane: `<Ctrl>j`/`<Ctrl>k`
- Go to left/right pane: `<Ctrl>h`/`<Ctrl>l`
- New empty tab: `<Ctrl>t`

# Search
- Next/previous character in current line: `f<char>`/`F<char>`
- Search two characters: `s<char>`

# Files
- Invoke NERDTree: `,e`
  - Open file in vertical/horizontal pane: `s`/`i`
  - File actions: `m`
- Invoke Invoke Ctrlp: `<Ctrl>p`
  - Cycle between file, MRU and buffer modes: `<Ctrl>f`
  - Navigate results list: `<Ctrl>j`/`<Ctrl>k`
  - Open file in new vertical/horizontal split: `<Ctrl>v`/`<Ctrl>x`

# Tags
- Beforehand generate the tags at the project root: `$ ctags -R --python-kinds=-i .`
- Jump to definition: `<Alt-;`
- Jump back from definition: `Alt-.`
- Open definition in vertical/horizontal split: `Alt-,`/`Alt-?`
- Open definition in new tab: `Alt-/`
- Toggle Tagbar: `<F8>`

# Misc
- Toggle invpaste: `<F12>`
- Toggle comment: `,c`
- Enlarge/scrink current pane: `+`/`-`

# Git
- Status: `:Gstatus`
  - Move between files: `<Ctrl>n`/`<Ctrl>p`
  - Stage/unstage file: `-`
  - Start commit: `cc`
  - Save changes `:x`
- Diff: `:Gvdiff`
  - Stage diff: `do` (when stage file in focus)
  - Jump to next/previous diff: `<Ctrl>j`/`<Ctrl>k`
- Commit: `:Gcommit`
