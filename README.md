**NOTE**: _This repository is no longer supported or updated by Awake Security / Arista Networks. If you wish to continue to develop this code yourself, we recommend you fork it._

# OSX Cider Bootstrap Files

[Cider](https://github.com/msanders/cider) is a simple wrapper for [Homebrew](http://brew.sh) and [Homebrew Cask](http://caskroom.io). We use Cider to automate the process of installing a standard set of applications and utilities on our OSX Laptops. e.g. Google Chrome, Firefox, iTerm2, virtualbox and vagrant, dropbox, Oracle Java, CLI tools like GnuPG, Go, curl etc. 

## Install HomeBrew, Cask & Cider
Install the Apple xcode command line tools: [Download](https://developer.apple.com/downloads/)  


    $ ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
    $ sudo easy_install pip
    $ brew install caskroom/cask/brew-cask
    $ sudo pip install -U cider

## Clone this repo
    $ git clone https://github.com/awakenetworks/dotfiles ~/.cider
    
## Bootstrap your laptop
    $ cider restore
    
## Change whats installed
1. Fork the [awakenetworks/dotfiles](https://github.com/awakenetworks/dotfiles) repo on github.com
2. Edit the file bootstrap.json in your forked repo.
3. Clone this repo to ~/.cider and run cider restore.

