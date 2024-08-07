# Neovim

## Screenshots

![Preview2](https://github.com/Tanishkshk1/Gamer-vim/blob/main/src-img/240409_13h30m03s_screenshot.png)

![Preview3](https://github.com/Tanishkshk1/Gamer-vim/blob/main/src-img/240409_13h30m40s_screenshot.png)

## Features

- File explorer with [Nvim-tree](https://github.com/nvim-tree/nvim-tree.lua)
- Greeter with [Alpha-nvim](https://github.com/goolord/alpha-nvim)
- Autocompletion with [Cmp](https://github.com/hrsh7th/nvim-cmp)
- Statusline with [Lualine](https://github.com/rebelot/heirline.nvim)
- Fuzzy finding with [Telescope](https://github.com/nvim-telescope/telescope.nvim)
- Syntax highlighting with [Treesitter](https://github.com/nvim-treesitter/nvim-treesitter)

## Prerequisites

- [Nerd Fonts](https://www.nerdfonts.com/font-downloads)
- [Neovim 9.5](https://github.com/neovim/neovim/releases/tag/v0.9.5)

## Installation

#### Make a backup of your current nvim and shared folder

```shell
mv ~/.config/nvim ~/.config/nvim.bak
mv ~/.local/share/nvim ~/.local/share/nvim.bak
```

#### Clone the repository

```shell
git clone https://github.com/Tanishkshk1/Gamer-vim
mv Gamer-vim nvim
mv nvim ~/.config/
```

## Setup

#### Install LSP

Enter `:LspInstall` followed by the name of the server you want to install<br>
Example: `:LspInstall pyright`

#### Install language parser

Enter `:LspInstall` followed by the name of the language you want to install<br>
Example: `:LspInstall python`

#### Manage plugins

Run `:Lazy` to update and clean plugins<br>

## Todo

```

### Improvements
- [ ] Add github copilot Support
  - [ ] Improve the overall Cmp
```

## Credits

Sincere appreciation to the following repositories, plugin authors and the entire neovim community out there that made the development of AstroNvim possible.

- [Plugins](https://astronvim.github.io/acknowledgements#plugins-used-in-astronvim)
- [AstroNvim](https://github.com/AstroNvim/AstroNvim)
- [NvChad](https://github.com/NvChad/NvChad)
- [LunarVim](https://github.com/LunarVim)
- [CosmicVim](https://github.com/CosmicNvim/CosmicNvim)

<div align="center" id="madewithlua">

[![Lua](https://img.shields.io/badge/Made%20with%20Lua-blue.svg?style=for-the-badge&logo=lua)](https://lua.org)

</div>
