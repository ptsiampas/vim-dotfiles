## Installation:

	git clone git://github.com/ptsiampas/vim-dotfiles.git ~/.vim

### Create symlinks:

	ln -s ~/.vim/vimrc ~/.vimrc
	ln -s ~/.vim/gvimrc ~/.gvimrc

### Switch to the `~/.vim` directory, and fetch submodules:

	cd ~/.vim
	git submodule init
	git submodule update
## Other usefull stuff
### Adding a new submodule (Example putting in fugitive module)
	cd ~/.vim
	mkdir ~/.vim/bundle
	git submodule add http://github.com/tpope/vim-fugitive.git bundle/fugitive
	git add .
	git commit -m "Install Fugitive.vim bundle as a submodule."
