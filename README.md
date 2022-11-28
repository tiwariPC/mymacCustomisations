# mymacCustomisations

## install neovim, details are in neovim-config directory

### install `neovide` to use neovim in GUI

## install tmux, details are in tmux-config directory

## use conda to install packages for data analysis

`brew install miniconda`

### install root from conda-forge

#### inside an environment (I generaly use default env, i.e. base)

`conda config --env --add channnels conda-forge`

`conda install root`

#### inside a new env

`conda create -n myrootenv python=3.7 root -v conda-forge`

`conda activate myrootenv`

`conda  config --env --add channels conda-forge`

#### make macvim a default text editor

`defaults write com.apple.LaunchServices/com.apple.launchservices.secure LSHandlers -array-add '{LSHandlerContentType=public.plain-text;LSHandlerRoleAll=org.vim.MacVim;}'`
Restart the computer to take effect
