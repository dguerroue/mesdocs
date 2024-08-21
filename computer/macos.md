# Install a Mac

## Install brew
https://brew.sh
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

## Brew packages
``` sh
brew install --cask google-chrome
brew install --cask firefox
brew install --cask enpass
brew install --cask visual-studio-code
brew install --cask raycast
brew install --cask shottr
brew install --cask iterm2
brew install --cask slack
brew install --cask skype
```

### Node 
```sh
brew install nvm
```
**Puis**
``` sh
source $(brew --prefix nvm)/nvm.sh
nvm install node
# OU (par exemple)
nvm install 20.12.1
```

Ajouter dans ~/.zshrc
```sh
source ~/.nvm/nvm.sh
```

## Configurer Enpass

## Se connecter au compte Google

## Générer sa clé SSH pour GitHub

## Se connecter à VsCode

## Terminal OhMyZsh + p10k

### OhMyZsh
https://ohmyz.sh/#install
https://github.com/romkatv/powerlevel10k?tab=readme-ov-file#oh-my-zsh

```sh
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k
brew install powerlevel10k
echo "source $(brew --prefix)/share/powerlevel10k/powerlevel10k.zsh-theme" >>~/.zshrc

# relancer le terminal pour continuer l'installation
```

