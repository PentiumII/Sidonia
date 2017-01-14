Sidonia
------
###### Sidonia version 1.0.0
![Screenshot](https://cloud.githubusercontent.com/assets/11221489/21751568/1c03564e-d57e-11e6-80f7-dff0337bf1ac.png)

![Screenshot](https://cloud.githubusercontent.com/assets/11221489/21748307/92f35fbc-d536-11e6-95a6-7416c31046df.png)

:bulb: Have you ever been visually assaulted or "triggered" by a colorscheme? :rage1: If so, welcome to your safe space! :godmode: In the spirit of minimalism and other great low color syntax colorschemes, Sidonia attempts to help create a simple yet effective color balance without any visual interference. A single color is used for ALL syntax keywords, making it easier for you to read and scan thru large blocks of code without distraction. Normal text is few shades brighter, making a subtle separation between your keywords with that of syntax. Crimson is used for PreProccesors, and Numbers, allowing you to easily spot function expressions, and numerals nestled in your code. Strings are the opposite color, also making it easy to identify.


:rocket: Setup 
---------------
#### 24 Bit Color Setup ( Recommended )

If you have a GUI Vim or a 24-bit terminal with Vim 8, add this to your vimrc:
```VimL
set termguicolors
colorscheme sidonia
```
Not sure if your terminal supports 24 bit colorschemes? Check out this list: [Truecolor Supported Terminals ](https://gist.github.com/XVilka/8346728)

#### ASCII Setup

If you do not have Vim8 you can still run sidonia in full color. You will need to use the sidonia terminal theme in conjunction with the sidonia.vim colorscheme. Essentially this method works similar to the Base-16 colorschemes in that vim will target the terminal colors ( 0 - 15 ). 

```VimL
colorscheme sidonia
```

There are a few ways to install sidonia. The first option is by using your favorite vim package manager and the second is by manual download.

:open_file_folder: Installation
-----------------------------------------

###### Package Manager Option

| Manager          | Location        | Setup                                                                      |
|------------------|-----------------|----------------------------------------------------------------------------|
| Vundle           | add to .vimrc:  | `Plugin 'alessandroyorba/sidonia'`                                         |
| NeoBundle        | add to .vimrc:  | `NeoBundle 'alessandroyorba/sidonia'`                                      |
| VimPlug          | add to .vimrc:  | `Plug 'alessandroyorba/sidonia'`                                           |
| Pathogen         | from terminal:  | `cd ~/.vim/bundle && \ git clone git://github.com/alessandroyorba/sidonia` |

###### Download Option
Download the .zip and copy `sidonia.vim` to `~/.vim/colors` (on Windows `<your-vim-dir>\vimfiles\colors`). Or for global accessibility, `/usr/share/vim/vimfiles/colors`.


:octopus: Related
-------
Feedback, issues or suggestions?. Open an Issue [Sidonia Issues](https://github.com/AlessandroYorba/Sidonia/issues)! Also, if you like Sidonia you might want to check out some of the other Vim themes that I'm working on:

Alduin
[![alduinPalette](https://cloud.githubusercontent.com/assets/11221489/21751570/20af614c-d57e-11e6-8813-fb6037702fc2.png)](https://github.com/AlessandroYorba/Alduin)

Despacio
[![despacioPalette](https://cloud.githubusercontent.com/assets/11221489/21751571/23d80d1a-d57e-11e6-9923-02ba2f2f820d.png)](https://github.com/AlessandroYorba/Despacio)

Sierra
[![sierraPalette](https://cloud.githubusercontent.com/assets/11221489/21751572/27670d8c-d57e-11e6-8465-b4f272d3117b.png)](https://github.com/AlessandroYorba/Sierra)
