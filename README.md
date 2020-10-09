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
    
## Installer [Firefox](https://www.mozilla.org/fr/firefox/new/)

    brew cask install firefox
    
## Installer [Adobe Acrobat Reader](https://get.adobe.com/fr/reader/otherversions/)

Permet de remplacer `Apercu` pour lire les PDF et pouvoir les commenter, signer, etc.

    brew cask install adobe-acrobat-reader
    
## Installer [Insomnia](https://insomnia.rest/)

    brew cask install insomnia
    
