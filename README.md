# [Manage VIM plugins with _pathogen_ and `git submodule`](http://vimcasts.org/episodes/synchronizing-plugins-with-git-submodules-and-pathogen/)

## HOWTO setup VIM environment on another machine with this repo
```sh
git clone https://github.com/royling/dotvim.git ~/.vim
cd ~/.vim
ln -s ~/.vim/vimrc ~/.vimrc
git submodule update --init
```

### Update all plugins
`git submodule foreach git pull origin master`
