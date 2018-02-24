# Mac command lines

## [Homerew](https://brew.sh/)

### Install `brew` command line

``` bash
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

## [Cask](https://caskroom.github.io/)

``` bash
brew tap caskroom/cask
brew tap caskroom/fonts
```

### Install Softwares with `cask`

``` bash
# Required
brew cask install cheatsheet
brew cask install cleanmymac
brew cask install command-tab-plus

# Browser
brew cask install brave
brew cask install google-chrome
brew cask install google-chrome-canary
brew cask install firefox
brew cask install firefox-developer-edition
brew cask install opera
brew cask install opera-developer

# Developer
brew cask install visual-studio-code
brew cask install sublime-text
brew cask install docker
brew cask install insomnia
brew cask install postman

# Developer Database
brew cask install datagrip
brew cask install navicat-for-postgresql
brew cask install pgadmin4

# Developer Extra
brew cask install hyper
brew cask install iterm2
brew cask install github
brew cask install gitkraken
brew cask install sourcetree

# Design
brew cask install gimp
brew cask install aseprite
brew cask install magicavoxel

# Game
brew cask install battle-net
brew cask install openemu
brew cask install steam

# Music
brew cask install spotify
brew cask install vlc

# Message
brew cask install messenger
brew cask install franz

# Other
brew cask install bartender
brew cask install virtualbox
brew cask install webtorrent

# Screen Saver
brew cask install fliqlo
brew cask install padbury-clock
```

### Install Font with `cask`

```bash
brew cask install font-fira-code
brew cask install font-source-code-pro
```

## [mas](https://github.com/mas-cli/mas)

``` bash
brew install mas
```

### `mas` singin

``` bash
mas signin mas@example.com
```

or singin with password

``` bash
mas signin mas@example.com "ZdkM4f$gzF;gX3ABXNLf8KcCt.x.np"
```

### Install Softwares with `mas`

``` bash
# Required
mas install 443987910     # 1password
mas install 935235287     # Encrypto
mas install 775737590     # iA Writer
mas install 884952790     # iTranslate
mas install 441258766     # Magnet
mas install 646295438     # RAR Extractor Lite

# Browser
mas install 1077036385    # Fluid Browser

# Design
824171161 Affinity Designer
mas install 863486266     # Autodesk SketchBook
mas install 1289583905    # Pixelmator Pro
mas install 1178074963    # Tayasui Sketches

# Productive
mas install 973134470     # Be Focused
mas install 1018859486    # Countdown
mas install 1017470484    # Next Meeting
mas install 1278508951    # Trello

# Message
mas install 803453959     # Slack
mas install 1176895641    # Spark
mas install 946399090     # Telegram Desktop
mas install 1147396723    # WhatsApp

# Apple
mas install 409183694     # Keynote
mas install 409203825     # Numbers
mas install 409201541     # Pages

# Other
mas install 836505650     # Battery Monitor
mas install 926121450     # Coinverter
mas install 1081413713    # GIF Brewery 3
mas install 748212890     # Memory Cleaner
```