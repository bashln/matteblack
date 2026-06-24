# Matteblack

Theme for Neovim and WezTerm.

## Estrutura

```
matteblack/
├── nvim/           # Neovim plugin
│   ├── lua/
│   │   └── matteblack/
│   │       ├── colors.lua
│   │       ├── init.lua
│   │       └── ...
│   ├── colors/
│   │   └── matteblack.lua
│   └── README.md
├── wezterm/
│   ├── matteblack.toml
│   └── README.md
└── README.md
```

## Migração

Este repositório foi criado pela fusão de:
- `matteblack.nvim`
- `matteblack.wezterm`

## Uso

### Neovim

Com lazy.nvim:
```lua
{
  "bashln/matteblack",
  config = function()
    vim.cmd("colorscheme matteblack")
  end
}
```

### WezTerm

Copie `wezterm/matteblack.toml` para `~/.config/wezterm/colors/` e selecione `matteblack` no `wezterm.lua`.
