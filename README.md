# MyNvim

My neovim config. pywal colors, lazy.nvim, and not much else in the way.

<p align="center">
  <img src="images/nvim-default.png" width="32%">
  <img src="images/nvim-glass.png" width="32%">
  <img src="images/nvim-zen.png" width="32%">
</p>
<p align="center">
  <img src="images/nvim1.png" width="32%">
  <img src="images/nvim2.png" width="32%">
  <img src="images/nvim3.png" width="32%">
</p>

## Install

```sh
git clone https://github.com/elifouts/MyNvim ~/.config/nvim
nvim
```

Plugins install themselves on first launch.

## Needs

- neovim 0.12+
- git (plugins and lazy.nvim install themselves on first launch)
- a nerd font

Optional, for the parts that use them:

- [pywal16](https://github.com/eylles/pywal16): colors from your wallpaper. Without it the theme is tokyonight, and `:ThemeFileGruvbox`, `:ThemeFileNord`... still work
- ripgrep: live grep
- fd: folder picker
- tree-sitter-cli + a C compiler: syntax parsers install automatically when you open a file
- node / npm: some language servers, copilot
- lazygit: `<leader>gg`

## What's in it

- **ui**: alpha dashboard, lualine, noice, which-key
- **files**: neo-tree, telescope
- **code**: lsp + mason, nvim-cmp, luasnip, treesitter, gitsigns
- **ai**: copilot, copilot chat
- **themes**: pywal, tokyonight, gruvbox, kanagawa, catppuccin, rose-pine, nord, everforest, onedark
- **extra**: markview, typr

Leader is `space`. Keybinds are in [KEYBINDS.md](KEYBINDS.md).

Part of my [Dotfiles](https://github.com/elifouts/Dotfiles).
