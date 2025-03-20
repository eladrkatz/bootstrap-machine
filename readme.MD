

```sh

#zsh
apt install zsh
#ohmyzsh
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

git clone https://github.com/zsh-users/zsh-autosuggestions.git $ZSH_CUSTOM/plugins/zsh-autosuggestions
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git $ZSH_CUSTOM/plugins/zsh-syntax-highlighting

# plugins=(git)
# plugins=(git zsh-autosuggestions zsh-syntax-highlighting)


# nvm
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash\n
source ~/.zshrc
nvm install 22

# docker
curl -fsSL https://get.docker.com -o get-docker.sh
sh get-docker.sh


apt-get install build-essential
```
