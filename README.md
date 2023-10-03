# 🚀 nvim-config

## ⚙️ Configuration

- Map leader is set to a space character (`vim.g.mapleader = " "`).

## 🔑 Key Mappings

### 🌟 Normal Mode

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

### ✍️ Insert Mode

- `<C-c>`: Act as if you pressed the Escape key to exit insert mode.

## 📦 Plugins

### Fugitive (Git Integration) 🐙

- `<leader>gs`: Open the Git command-line interface.
- `<leader>p`: Execute a function to push changes.
- `<leader>P`: Execute a function to pull changes and rebase.
- `<leader>t`: Execute a Git push command with options.
- `<leader>gh`: Execute a command to get a specific version from Git diff.
- `<leader>gl`: Execute a command to get a specific version from Git diff.

### Harpoon (Project Navigation) 🌐

- `<leader>a`: Add the current file to Harpoon's project.
- `<C-e>`: Toggle the quick menu for Harpoon.
- `<C-h>`: Navigate to the previous file in Harpoon.
- `<C-t>`: Navigate to the next file in Harpoon.
- `<C-n>`: Navigate to the first file in Harpoon.
- `<C-s>`: Navigate to the last file in Harpoon.

### Language Server Protocol (LSP) 🌐

- `gd`: Go to definition.
- `K`: Show hover information.
- `<leader>vws`: Search for symbols in the workspace.
- `<leader>vd`: Open diagnostic messages in a float window.
- `[d`: Go to the next diagnostic message.
- `]d`: Go to the previous diagnostic message.
- `<leader>vca`: Execute code actions.
- `<leader>vrr`: Find references.
- `<leader>vrn`: Rename symbol.
- `<C-h>` (Insert Mode): Show signature help.

### Refactoring 🛠️

- `<leader>ri` (Visual Mode): Inline variable refactoring.

### Telescope (File Picker) 🔭

- `<leader>pf`: Find files.
- `<C-p>`: Find Git-tracked files.
- `<leader>ps`: Grep string in files.
- `<leader>vh`: Show help tags.

### Trouble (Quickfix List) 🐛

- `<leader>xq`: Toggle the quickfix list.

### Undotree (Undo History) ⏪

- `<leader>u`: Toggle Undotree.

### Zenmode 🧘

- `<leader>zz`: Activate Zenmode.
