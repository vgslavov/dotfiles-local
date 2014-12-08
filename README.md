# My dotfiles

## Local dotfiles

1. Get local dotfiles

```
git clone https://github.com/vgslavov/dotfiles-local.git ~/dotfiles-local
```

2. Install [Thoughtbot dotfiles](https://github.com/thoughtbot/dotfiles).
  1. Use Homebrew to install rcup
  2. Use rcup to install files

3. Either install [Thoughtbot laptop](https://github.com/thoughtbot/laptop).

4. Or install individual components manually

```
git clone https://github.com/gmarik/Vundle.vim.git ~/.vim/bundle/Vundle.vim
```

5. Force install Vim bundles using Vundle

```
:BundleInstall!
:BundleList
:h vundle
```
