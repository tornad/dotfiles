Dotfiles
===

# Install
Installer homebrew (https://brew.sh/index_fr)
````bash

/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
````
XCODE
````bash
xcode-select --install

````

Les dotfiles
````bash
cd && \
  git clone https://github.com/tornad/dotfiles.git dotfiles &&
  make all
````

My dev env
