# Neovim Cheat Sheet



## Motions

- `gd`             : **G**oto **D**efinition
- `gD`             : **G**oto **D**eclaration
- `gr`             : list **R**eferences of word under cursor
- `<leader>D`      : type **D**efinition of the variable under cursor
- 


## Types informations
- `<leader>D`      : type **D**efinition of the variable under cursor
- `K`              : hover documentation



## Symbols

- `<leader>ds`     : list **D**ocument **S**ymbols
- `<leader>ws`     : list **W**orkspace **S**ymbols
- `<leader>sw`     : fuzzy **S**earch **W**ord under cursor in workspace
- `<leader>sg`     : fuzzy **S**earch **G**rep in workspace


## git

- `<leader>gs`     : **G**it **S**tatus
- `<leader>gb`     : **G**it **B**lame


## File & Buffers

- `<leader>f`       : fuzzy **F**ind file in workspace
- `<C-p>`           : fuzzy **F**ind file in git repository
- `<leader><leader>`: list existing **B**uffers 
- `<leader>?`       : list recently opened files
- `<leader>rn`      : **R**e**N**ame  current buffer
- `<leader>wa`      : **W**orkspace **A**dd folder 
- `<leader>wr`      : **W**orkspace **R**emove folder 
- `<leader>wl`      : **L**ist workspace folders
- `<leader>cl`      : **CL**ose buffer
- `<TAB>`           : next buffer
- `<S-TAB>`         : previous buffer


## File Tree

- `<C-n>`           : display tree
- `<leader>f`       : find file



## Window

- `<leader>v`       : *V*ertical split
- `<leader>h`       : *H*orizontal split


## NeoVim Config

- `<leader>ev`      : open neovim config directory
- `<leader>sv`      : source root init.lua config file



## Help
- `<leader>sh`     : fuzzy **S**earch **H**help
- `<leader>sd`     : **S**earch in **D**iagnostics




## Mason

- `:Mason`         : Run Mason to install/uninstall LSP, DAP, Linters, Formatters
- `:MasonUpdate`   : Update all managed registries


## Packer

- `source ~/.config/nvim/lua/nico/packer.lua`   : source the packer config
- `:PackerSync`     : Perform `PackerUpdate` and then `PackerCompile`
- `PackerCompile`   : Regenerate compiled loader file
- `PackerClean`     : Remove any disabled or unused plugins
- `PackerUpdate`    : Clean, then update and install plugins


