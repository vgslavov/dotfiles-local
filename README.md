# Local dotfiles

Get local dotfiles:

```
git clone https://github.com/vgslavov/dotfiles-local.git ~/dotfiles-local
```

Install [Thoughtbot dotfiles](https://github.com/thoughtbot/dotfiles).

On Mac OS X, use Homebrew to install rcm. For Ubuntu, use deb package:

```
wget https://thoughtbot.github.io/rcm/debs/rcm_1.2.3-1_all.deb
sudo dpkg -i rcm_1.2.3-1_all.deb
```

Use rcup (from rcm) to install the files. It will create
symlinks for both Thoughbot and local dotfiles.

Either install [Thoughtbot laptop](https://github.com/thoughtbot/laptop) or
install individual components manually:

```
git clone https://github.com/gmarik/Vundle.vim.git ~/.vim/bundle/Vundle.vim
```

Then force install Vim bundles using Vundle:

```
:BundleInstall!
:BundleList
:h vundle
```
