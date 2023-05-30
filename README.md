## Screenshot

![screenshot](https://github.com/bitterteasweetorange/nivm/blob/main/screenshot.png)

## Requirements
- [Neovim 0.8+](https://github.com/neovim/neovim/releases/tag/v0.8.1)
- [Nerd Fonts](https://www.nerdfonts.com/font-downloads)
- [ripgrep](https://github.com/BurntSushi/ripgrep)

## Setup

### Windows
Clone Packer to nvim-data folder
 > git clone https://github.com/wbthomason/packer.nvim "$env:LOCALAPPDATA\nvim-data\site\pack\packer\start\packer.nvim"

Clone this repo to C:\Users\[username]\AppData\Local\nvim

Open nvim in developer console (VS2022 Developer Command Prompt or equivalent).  This is needed the first time to create symlinks.
> nvim

Run packer install
> :PackerInstall
and wait for all packages to install.

Quit nvim
> :q!

Reopen nvim and you should see some Mason lsp configuration tasks completing.  Hit Enter

Some additional tasks such as TreeSitter installations may run in the background, wait for these to complete.

Restart nvim again and you should be good to go.