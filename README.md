# vim_etc
All about install vim, installation of plugins to display vim with colors, autocomplete vim to code in php and python 
## Introduction
Yes, you know? I am lazzy! I do not like to change the coding evirement each time because of there limitation and there advantage!
That why I chose Vim and its plugin to do everything I need. You can be low at the beginning with Vim but with the time, when you are familiar with Vim, you will see that it will be awsome !
## Requirement
Git
Python >= 2.7 because of the plugins autocomplete for python is compatible with python >=2.7
## Installation
### Vim installation :
```
sudo apt-get install vim
```
### .vimrc
Get the file vimrc_example to your machine. Go to /home folder, open a file .vimrc and copy all the contents in .vimrc_example to your .vimrc
```
cp download_folder/vimrc_example ~/.vimrc
```
### donwload vundle 
See more : https://github.com/VundleVim/Vundle.vim#quick-start
```
git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim
```
### download vim-colorschemes
See more : https://github.com/flazz/vim-colorschemes#installation
```
git clone https://github.com/flazz/vim-colorschemes.git ~/.vim
mkdir ~/.vim/colors
cp ~/.vim/bundle/colorschemes/colors/* ~/.vim/colors
```
### download plugin phpcomplete
See more : https://github.com/shawncplus/phpcomplete.vim
```
cd ~/.vim/bundle
git clone git://github.com/shawncplus/phpcomplete.vim.git
```
### installation all plugin
In fact, in the .vimrc file, I put some plugin of colors, autocomplete of python and php that I choosed, so you do not need to do yourself. Just run vim and run :PluginInstall command
If you want another colors you can change it in .vimrc
