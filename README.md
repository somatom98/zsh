# ZSH

## Installation

### zsh
```sh
# Fedora
sudo dnf isntall zsh

# Ubuntu
sudo apt install zsh

# Configure zsh as default terminal
chsh -s $(which zsh)
```

### ohmyzsh

[Wiki](https://github.com/ohmyzsh/ohmyzsh/wiki)
```sh
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

### powerlevel10k

[Wiki](https://github.com/romkatv/powerlevel10k)
```sh
# clone powerlevel10k
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k

# download fonts (you need to install them)
wget https://github.com/somatom98/zsh/raw/main/fonts/MesloLGS%20NF%20Bold%20Italic.ttf
wget https://github.com/somatom98/zsh/raw/main/fonts/MesloLGS%20NF%20Bold.ttf
wget https://github.com/somatom98/zsh/raw/main/fonts/MesloLGS%20NF%20Italic.ttf
wget https://github.com/somatom98/zsh/raw/main/fonts/MesloLGS%20NF%20Regular.ttf

# clone zsh-autosuggestion
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions

# clone configuration
wget https://raw.githubusercontent.com/somatom98/zsh/main/.zshrc -P ~/
wget https://raw.githubusercontent.com/somatom98/zsh/main/.p10k.zsh -P ~/
```


