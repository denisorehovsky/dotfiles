
Git
===


### Installation

Make sure to install the latest git release (arch linux):

```bash
$ pacman -S git
```

### Configuration

Load up my git configuration. It includes user.name and user.email defaults:

```bash
$ ln -s ~/.dotfiles/git/.gitconfig.global ~/.gitconfig
```

You should enter your own name and email:

```bash
git config --global user.name  "Your Name"
git config --global user.email "your@email.address"
```

### Aliases

If you're using my dotfiles (including my .zshrc), these will get automatically loaded, or you can load them manually by putting this in your shell-rc file:


```bash
source ~/.dotfiles/git/aliases.sh
```
