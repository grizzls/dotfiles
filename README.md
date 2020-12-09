# dotfiles - My own new Mac setup script

## About

This setup script is for installing some of my preferred Terminal tools, and most of my applications.

### Installation with Curl

To install this script from a brand new Mac (fresh out of the box!) run the following command in terminal:

``` shell
sh -c "$(curl -fsSL https://raw.githubusercontent.com/grizzls/dotfiles/master/.macos)"
```

**Want to know what ```curl -fsSL``` stands for? Checkout this [link](https://explainshell.com/explain?cmd=curl+-fsSL+example.org#).**

If [Xcode Command Line Tools](https://developer.apple.com/library/archive/technotes/tn2339/_index.html#//apple_ref/doc/uid/DTS40014588-CH1-WHAT_IS_THE_COMMAND_LINE_TOOLS_PACKAGE_) is not already installed, you will be prompted to install it after being prompted for ```sudo``` access.

## Mac OS X Modifications

I'm performing the following modfucations to Finder.

### Modify Finder Preferences

#### Show Library Folder in Finder

``` shell
chflags nohidden ~/Library
```

#### Show Hidden Files in Finder

``` shell
defaults write com.apple.finder AppleShowAllFiles YES
```

#### Show all filename extensions in Finder
``` shell
defaults write NSGlobalDomain AppleShowAllExtensions -bool true
```

#### Keep folders on top when sorting by name
``` shell
defaults write com.apple.finder _FXSortFoldersFirst -bool true
```

### Terminal Tools

All of the following are commands that you can enter directly into Terminal or let the script run for you.

Install the following terminal tools:

[Homebrew](https://brew.sh/)
[oh-my-zsh](https://ohmyz.sh/)
[Git](https://git-scm.com/)
[Powerline fonts](https://github.com/powerline/fonts)
[Speedtest-cli](https://github.com/sivel/speedtest-cli)
[openssl](https://www.openssl.org/)
[kubernetes-cli](https://kubernetes.io/)
[helm](https://helm.sh/)
[pyenv](https://github.com/pyenv/pyenv)
[xxenv-latest](https://github.com/momo-lab/xxenv-latest)
[stormssh](https://github.com/emre/storm)
[stormssh-completion](https://github.com/vigo/stormssh-completion)

### Additional Applications

All of the following are commands that you can enter directly into Terminal or let the script run for you.

Install the following applications:

[iTerm2](https://www.iterm2.com/)
[Visual Studio Code](https://code.visualstudio.com/)
[Slack](https://slack.com/)
[1Password](https://1password.com/)
[Google Chrome](https://www.google.com/chrome/)
[google-cloud-sdk](https://cloud.google.com/sdk/)
[Docker](https://www.docker.com/products/docker-desktop)
[Postman](https://www.postman.com/)
[Microsoft Teams](https://teams.microsoft.com/downloads)
[Microsoft Office](https://products.office.com/mac/microsoft-office-for-mac/)
[Macpass](https://macpass.github.io/)
[Zoom](https://www.zoom.us/)
[Plex](https://www.plex.tv/)

### The End