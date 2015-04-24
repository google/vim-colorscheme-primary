## Primary
#### A Vim color scheme based on Google's colors

### Screenshots

![Light mode](/screenshots/light.png?raw=true)
![Dark mode](/screenshots/dark.png?raw=true)


### Installation

Download primary.vim (in the colors folder) and copy it into your .vim/colors
directory.

To set Primary as your default color scheme, add these lines to your .vimrc
file:
```
  syntax enable
  set t_Co=256
  set background=light
  colorscheme primary
```
To use Primary in dark mode, change the third line to `set background=dark`.

For more detailed instructions, see doc/primary.txt.


*Disclaimer: This is not an official Google product (experimental or otherwise),
it is just code that happens to be owned by Google.*
