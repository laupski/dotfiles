# dotfiles

## Install Powerline fonts first (Powershell (Run as Administrator))
```
git clone https://github.com/powerline/fonts.git --depth=1
Set-ExecutionPolicy Bypass
.\install.ps1
Set-ExecutionPolicy Default
```

## Windows Terminal
https://github.com/microsoft/terminal \
Copy settings.json to Windows Terminal -> Settings -> Open your settings.json file

## zsh (ubuntu install)
```
sudo apt install zsh
chsh -s $(which zsh)
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git $ZSH_CUSTOM/themes/powerlevel10k
```
Copy .zshrc and replace the user inside the file \
Restart the terminal and should prompt the powerlevel10k walkthrough

## Fonts
https://www.nerdfonts.com/

## Inspired by
https://medium.com/@hjgraca/style-your-windows-terminal-and-wsl2-like-a-pro-9a2e1ad4c9d0
https://nickymeuleman.netlify.app/blog/linux-on-windows-wsl2-zsh-docker
