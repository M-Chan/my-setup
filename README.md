# my-setup
[Vim Setup](#vim-setup) | [Oh My Zsh Setup](#oh-my-zsh-setup) 
 | [Powerlevel10K Setup](#powerlevel10k-setup) | [Python and Pip](#python-and-pip)

## Vim Setup
```
sudo apt install vim
```

## Oh My Zsh Setup
1 - Install Zsh
```
sudo apt install zsh
```

2 - Modify the .bashrc file by adding 'zsh' to the end

3 - Install Ohmyzsh
```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

## Powerlevel10K Setup
1 - Download and install the fonts in the folder 'MesloLGS NF'
2 - Configure the terminal to use this font
3 - Clone the repo
```
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k
```
4 - Modify the .zsrc file and set the following
```
ZSH_THEME="powerlevel10k/powerlevel10k"
```
5 - Go through the interactive setup when opening the terminal for the first time...

- Lean
- Unicode
- 256 colors
- 24-hour format
- Two lines
- Disconnected
- No frame
- Compact
- Many icons
- Concise
- Enable transient prompt
- Verbose instant prompt mode
- Apply changes to ~/.zshrc

## Python and Pip
Install a specific python version from the deadsnakes PPA
```
sudo add-apt-repository ppa:deadsnakes/ppa
sudo apt update
sudo apt install python{VERSION_NO}
```
Modify ~/.zshrc to find pip
```
export PATH="/usr/local/bin:/usr/bin:$PATH"
```

