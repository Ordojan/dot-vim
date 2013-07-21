# Installation:

  git clone git@github.com:Ordojan/dot-vim.git ~/.vim

### Create symlink:

  ln -s ~/.vim/vimrc ~/.vimrc
  
### Setup git submodules:

  git submodule init
  
  git submodule update
  
### Update git submodules:

  git submodule foreach git pull origin master

-----

# Add additional plugins

    git submodule add https://github.com/othree/xml.vim.git bundle/xml
    git add .
    git commit -m "Installed xml.vim bundle as a submodule."
