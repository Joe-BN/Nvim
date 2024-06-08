# Nvim
A simple nvim config folder.

![nvimscreen](https://github.com/Joe-BN/Nvim/assets/128038111/597f8228-4669-4736-9860-76d00c19e296)

Using [lazy.nvim](https://github.com/folke/lazy.nvim) to bring in some useful functionality without making it too complex.

Features include:
+ Tokyonight/Night (theme)
+ Nvim tree (file tree)
+ Nvimtreesitter (syntax highlighting)
+ Barbar (tab spaces)
+ Lualine (Nvim status line)
+ Telescope (fuzzy finder)
(All configured with easy to use keybindings, which you can change as you please)

The font however depends on the one set on your system. 
It must ba a type of Nerd font, they usually look cool and have icons butilt into them.
Check out [NerdFonts](https://www.nerdfonts.com/) and download and configure your nerdfont of choice.
If you dont know how to, check out [how to sutup nerd fonts](https://youtu.be/LJ7CEhnS0OM).


For those new to this:

+ 1st, Install Neovim & git with the package manager of your choice ( mine is pacman, coz I use Arch btw :) ):

```
$ sudo pacman -S neovim
```

and

```
$ sudo pacman -S git
```

+ 2nd, Create the ```nvim/``` folder in your ```.config/``` folder
+ 3rd, ``` cd ``` into ``` ~/.config/nvim ``` and clone the code from my repo from within with:
```
$ git clone https://github.com/Joe-BN/Nvim/config
```

-> Run the following command to unpack all the necessary files into the current directory

```
$ mv Nvim/config/* .
```

-> Run this to delete the ``` Nvim ``` folder gotten from github:
``` 
$ rm -rf Nvim
```

-> When you run ```$ ls``` while in ```nvim/``` it should display this:



when you run ```$ tree nvim``` while inside the ```.config/``` directory, it should display this:

![nvimtree2](https://github.com/Joe-BN/Nvim/assets/128038111/17d26f0c-f854-4e02-a25a-3d9ed3517b32)

Enjoy     : )
