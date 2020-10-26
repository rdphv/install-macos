# Installation et configuration de mon Mac

Poste de travail orienté développement Web (principalement Javascript).

## Installer [Brew](https://brew.sh/)

    /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
    
## Installer [iTerm2](https://www.iterm2.com/)

Permet de remplacer `Terminal` par une console plus efficace

    brew cask install iterm2
    
    # Oh My Zsh - https://ohmyz.sh/#install
    sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"   
    
    # Powerlevel10k - https://github.com/romkatv/powerlevel10k
    git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k
    
    # Set ZSH_THEME="powerlevel10k/powerlevel10k" in ~/.zshrc.
    
    # Redémarrer la console
    
## Installer Bitwarden

    brew cask install bitwarden
    brew install bitwarden-cli

## Installer [Firefox](https://www.mozilla.org/fr/firefox/new/)

    brew cask install firefox
    
    # Ou/et
    
    brew cask install google-chrome
    
## Installer [VS Code](https://code.visualstudio.com/)

    brew cask install visual-studio-code
    
## Installer NodeJS

    brew install nvm
    nvm install node
    brew install yarn
    
## Installer Rust

    brew install rustup-init
    
    # Puis
    rustup-init
    
    # Rust Language Server (utile pour les IDEs et autres outils)
    rustup component add rls rust-analysis rust-src
    
    # Extension Rust pour VSCode
    code --install-extension rust-lang.rust
    
    # Extension pour bien gérer les fichiers TOML
    code --install-extension tamasfe.even-better-toml
    
## Installer Github & Co

    # Github Cli
    brew install gh
    
    # Netlify Cli
    npm install netlify-cli -g
    
    # Zola Site generator en Rust
    brew install zola
    
## Divers

    # VLC
    brew cask install vlc
    
    # Slack
    brew cask install slack
    
    # Permet de remplacer `Apercu` pour lire les PDF et pouvoir les commenter, signer, etc.
    brew cask install adobe-acrobat-reader
    
## Dev

    # AWS CLI
    brew install awscli
