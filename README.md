<!--TODO: configure php-->
# NeoVim configuration

Just my attempt to create the perfect IDE for myself.

Now it supports only C/C++ and Python (however you can customize it as you need using mason and [lsp-config.lua](https://github.com/asskicker54/nvim-config/blob/main/lua/config/plugins/lsp-config.lua)).

## Instalation

Clone the repo:

```bash
git clone https://github.com/asskicker54/nvim-config.git
```

Find nvim folder:

- Linux: ~/.config/nvim/
- Windows: C:\Users\user_name\AppData\Local\nvim

Place the files inside nvim directory this way:

```bash
nvim/
├── README.md
├── init.lua
└── lua/
    └── config/
        ├── core/
        │   ├──...
        ├── lazy.lua
        └── plugins/
            ├──...
```

Open nvim and it will install everything!😎

