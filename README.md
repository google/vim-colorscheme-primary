## Primary
##### A Vim color scheme based on Google's colors
  
#### Screenshots

![Light mode](/screenshots/light.png?raw=true)
![Dark mode](/screenshots/dark.png?raw=true)


#### Installation

Install using your favorite plugin manager.

To install using Vundle, add the following to your vimrc:
```vim
Plugin google/vim-colorscheme-primary
```

To set Primary as your default color scheme, add these lines to your .vimrc:
```vim
syntax enable
set t_Co=256
set background=light
colorscheme primary
```
For dark mode, use `set background=dark` instead:
```vim
syntax enable
set t_Co=256
set background=dark
colorscheme primary
```

See doc/colorscheme-primary.txt for detailed instructions and additional
options.

#### Happy Google-inspired coding!  

*Disclaimer: This is not an official Google product (experimental or otherwise),
it is just code that happens to be owned by Google.*
