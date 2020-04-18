# Dotfiles

This repo includes all of my custom dotfiles.

### Installation

```
git clone git://github.com/pmerku/dotfiles.git ~/dotfiles
cd ~/dotfile
./install.sh
```

### Post Installation

Open `.vimrc` and run:

```
:PluginInstall
:source %
```

Then run:

```
cd ~/.vim/bundle/YouCompleteMe
./install.py --all
```

Or you can specify which completitor to use with:
```
--cs-completer `C# support (additionally install MONO)`
--go-completer `Go support (additionally install GO)`
--ts-completer `TypeScript support`
--rust-completer `Rust support`
--java-completer `Java support (additionally install JDK8+)`
```
