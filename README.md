# nvim_setting

my procedures follows the site below:
https://jdhao.github.io/2018/12/24/centos_nvim_install_use_guide_en/

1. Download neovim app image
https://github.com/neovim/neovim/releases

2. Place app and set `PATH`

3. Place init.vim file under `~/.config/nvim`

4. Install VIM-Plug
```
curl -fLo ~/.local/share/nvim/site/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
```

5. Start NVIM and PlugInstall

6. Install pynvim and jedi for autocompleting python 
```
pip install pynvim
pip install jedi
```

7. Install clang package for autocompleting c
```
apt-get install clang
```

8. Find the libclang.so file path and headers path and include them in the init.vim

----
Reference.
https://jdhao.github.io/2018/12/24/centos_nvim_install_use_guide_en/
https://github.com/deoplete-plugins/deoplete-clang
https://www.reddit.com/r/neovim/comments/49z356/cant_make_deoplete_work_with_deopleteclang/
