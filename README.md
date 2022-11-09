### Oh My ZSH
follow installation guide on [official site](ohmyz.sh/#install) OR the steps below

1. run the below command to install
```sh
$ sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

2. rename original file in your home directory *.zshrc* to *.zshrc.original*
```sh
$ mv ~/.zshrc ~/.zshrc.original
```

3. download and copy files in this repo `oh-my-zsh/.zshrc` and `oh-my-zsh/.zsh_aliases` to your home directory

4. check content of *.zshrc.pre-oh-my-zsh* ans be sure to copy any path variables or config you have there to the new *.zshrc*  

5. install `zsh-autosuggestions` plugin
```sh
$ git clone https://github.com/zsh-users/zsh-autosuggestions $ZSH_CUSTOM/plugins/zsh-autosuggestions
```

6. install `zsh-syntax-highlighting` plugin
```sh
$ git clone https://github.com/zsh-users/zsh-syntax-highlighting $ZSH_CUSTOM/plugins/zsh-syntax-highlighting
```

7. restart shell session

### Node and NVM
install nvm
```sh
$ curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.2/install.sh | bash
```
