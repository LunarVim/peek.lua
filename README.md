# peek.lua

## Installation

```lua
use "LunarVim/peek.lua"
```

## Usage

```lua
local opts = { noremap = true, silent = true }
vim.api.nvim_set_keymap("n", "gp", ":lua require('peek').Peek('definition')<CR>", opts)
```
