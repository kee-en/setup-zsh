# setup-zsh

### Install ZSH
```shell
sudo apt install zsh
```

### Install Oh-My-Zsh
```shell
curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh | sh; zsh
```

### Change Default Shell
```shell
sudo usermod --shell $(which zsh) <your_username>
```

### Install Zsh Syntax Highlighting
```shell
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
```

### Install Zsh Auto Suggestion
```shell
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
```

### Install Fuzzy Finder
```shell
git clone --depth 1 https://github.com/junegunn/fzf.git ~/.fzf && ~/.fzf/install
```
note:
  - Remember to answer "y" to all question.

### Install Nerd font
(Download)[https://nerdfonts.com/#downloads]

### Install Powerlevel10k
```shell
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k
```
- Set `ZSH_THEME="powerlevel10k/powerlevel10k"` to `~/.zshrc`.
