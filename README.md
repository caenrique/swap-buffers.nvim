Lua plugin to swap buffers easily between split windows

<p align="center">
   <img src="https://i.imgur.com/z3YxA64.gif">
<p>
   
## How to use
   
call the lua function `swap_buffers` giving it on of `h j k l` as a parameter:
   
```vim
nnoremap <C-h> <cmd>lua require('swap-buffers').swap_buffers('h')<CR>
```
   
This will map Ctrl-h to swap the current buffer with the one on the left. The same can be done for right, top and bottom.
   
## Configuration

Default values:

```lua
require('swap-buffers').setup({
  ignore_filetypes = {'NvimTree'}
})
```

## Installation

Using packer.nvim

```lua
require('packer').startup {
  use {"caenrique/swap-buffers.nvim"}
}
```
