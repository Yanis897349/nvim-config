# nvim-config

## Key Mappings

### Normal Mode

- `<leader>pv`: Open the Ex command-line mode.
- `J` (Visual Mode): Move selected text down by one line and reselect.
- `K` (Visual Mode): Move selected text up by two lines and reselect.
- `J`: Move cursor line down by one line and reposition it at the beginning of the line.
- `<C-d>`: Scroll down and center the cursor line.
- `<C-u>`: Scroll up and center the cursor line.
- `n`: Search for the next occurrence and center the cursor line.
- `N`: Search for the previous occurrence and center the cursor line.
- `<leader>p` (Visual Mode): Delete selected text, paste it before the cursor line, and position the cursor at the beginning of the pasted text.
- `<leader>y` (Normal and Visual Modes): Yank selected text to the system clipboard.
- `<leader>Y` (Normal Mode): Yank the current line to the system clipboard.
- `<leader>d` (Normal and Visual Modes): Delete selected text.
- `Q`: Disabled (mapped to no-operation).
- `<C-f>`: Create a new tmux window named "tmux-sessionizer."
- `<leader>f`: Execute LSP format command.
- `<C-k>` and `<C-j>` (Normal Mode): Navigate through quickfix list.
- `<leader>s`: Initiate search and replace operation on the entire file.
- `<leader>x`: Make the current file executable by running `chmod +x %`.
- `<leader>mr`: Execute the "CellularAutomaton make_it_rain" command.
- `<leader><leader>` (Normal Mode): Source the current file as Vimscript.

### Insert Mode

- `<C-c>`: Act as if you pressed the Escape key to exit insert mode.

## Configuration

- Map leader is set to a space character (`vim.g.mapleader = " "`).
