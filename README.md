Lua plugin to swap buffers easily between split windows

<p align="center">
   <img src="https://i.imgur.com/aufzS5b.gif" width="400">
<p>

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
