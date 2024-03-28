# lI15SO0_Snippets

---

Snippets collection that made by my self.


## Install 

---

### For vim/Neovim

with Lazy.nvim 

``` lua
{ "lI15SO0/lI15SO0_Snippets" }
```

with Packer

``` lua
use "lI15SO0/lI15SO0_Snippets"
```

with vim-plug

```vim
Plug "lI15SO0/lI15SO0_Snippets"
```

with coc.nvim

```vim
:CocInstall https://github.com/lI15SO0/lI15SO0_Snippets
```

## Usage

It should work with any snippet engine that supports loading vscode snippets.

> **Warning** If using LuaSnip, make sure use 
> `require("luasnip.loaders.from_vscode").lazy_load()`
> and add this repo to dependency for LuaSnip,
> make sure LuaSnip has jsregexp compiled.
