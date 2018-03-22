# homebrew-therion

Therion is cave surveying software - for details see https://therion.speleo.sk

This repository is hosting homebrew formualae for easy installation and update of Therion on your Mac. Please launch Terminal app and type the following commands.

## Installation

### 1. Install Command Line Tools

`xcode-select --install`

### 2. Install Homebrew - http://brew.sh/

`/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`

Test it:

`brew doctor`

### 3. Get Homebrew-Cask

`brew tap caskroom/cask`

### 4. Install Therion

To install the latest **tested** revision use:

`brew install https://raw.githubusercontent.com/ladislavb/homebrew-therion/master/therion.rb`

If you want to install the latest - bleeding edge version use:

`brew install --HEAD https://raw.githubusercontent.com/ladislavb/homebrew-therion/master/therion.rb`

## Upgrade

Launch Terminal app and type `brew update`