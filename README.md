```
       _                                 _            _       _       _            _
__   _(_)_ __ ___        _ __ ___   __ _| |_ ___ _ __(_) __ _| |     | |_ __ _ ___| |_ _   _
\ \ / / | '_ ` _ \ _____| '_ ` _ \ / _` | __/ _ \ '__| |/ _` | |_____| __/ _` / __| __| | | |
 \ V /| | | | | | |_____| | | | | | (_| | ||  __/ |  | | (_| | |_____| || (_| \__ \ |_| |_| |
  \_/ |_|_| |_| |_|     |_| |_| |_|\__,_|\__\___|_|  |_|\__,_|_|      \__\__,_|___/\__|\__, |
                                                                                       |___/
```

# vim-material-tasty

Based on [hzchirs's vim-material](https://github.com/hzchirs/vim-material)
, an [equinusocio's Material Theme](https://github.com/equinusocio/vsc-material-theme) port
for vim.

_Tastiness inspired by [patstockwell's vim-monokai-tasty](https://github.com/patstockwell/vim-monokai-tasty)_.

**Note:** support true color terminal and gvim only

Screenshot
------------

**Dark**
![Dark](https://imgur.com/xfGYwwc.jpg)

**Light**
![Light](https://user-images.githubusercontent.com/4735528/42131913-8c1b0d68-7d3f-11e8-935a-4c10181127d9.png)

**Palenight**
![Palenight](https://user-images.githubusercontent.com/4735528/42134016-056046f4-7d66-11e8-9ea0-c96a59a5b7b0.png)

**Oceanic**
![Oceanic](https://user-images.githubusercontent.com/4735528/47250634-6ebe2b00-d457-11e8-92d7-dabb871f60f1.png)

Installation
------------

* [vim-plug](https://github.com/junegunn/vim-plug)
```vim
Plug 'ahaasler/vim-material-tasty'

" Dark
set background=dark
colorscheme vim-material-tasty

" Palenight
let g:material_style='palenight'
set background=dark
colorscheme vim-material-tasty

" Oceanic
let g:material_style='oceanic'
set background=dark
colorscheme vim-material-tasty

" Light
set background=light
colorscheme vim-material-tasty
```

### Airline
Colorscheme also include an [Airline](https://github.com/vim-airline/vim-airline) theme

```vim
let g:airline_theme='material'
```

License
---

MIT

Copyright for portions of project vim-material-tasty are held by Chris Hung, 2017
as part of project vim-material. All other copyright for project vim-material-tasty
are held by Adrian Haasler García, 2019.
