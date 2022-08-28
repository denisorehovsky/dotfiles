
Git
===


### Installation

Make sure to install the latest git release:

```bash
$ brew install git
```

### Configuration

Load up my git configuration. It includes user.name and user.email defaults and a few aliases:

```bash
$ ln -s ~/.dotfiles/git/.gitconfig.global ~/.gitconfig
```

You should enter your own name and email:

```bash
git config --global user.name  "Your Name"
git config --global user.email "your@email.address"
```
