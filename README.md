# Setup for use

```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

brew install powerlevel10k

cp ./.zshrc ./.p10k.zsh ~/

cp gitconfig ~/.gitconfig
```

# Setup for modification

## Install powerlevel10k

```bash
brew install powerlevel10k
echo "source $(brew --prefix)/share/powerlevel10k/powerlevel10k.zsh-theme" >>~/.zshrc
```