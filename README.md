# Today I Learned Front-end Keys by [Diego Aaron Figueroa Campos]

### Wednesday, Apr 21 2021 [Npm Issues in Arch Linux]  

**Install nodejs and npm**  
```zsh
sudo pacman -Sy nodejs
sudo pacman -Sy npm
```

**Uninstall nodejs and npm**  
```zsh
sudo pacman -Rsc -n nodejs
```
**How avoid to use sudo npm ...**  
**npm** has a configuration called prefix. This configuration setting tells **npm** where to install global modules  
```zsh
npm config set prefix ~/.npm
```
**Update your PATH to include ~/.npm/bin in Zsh**  
```zsh
echo 'export PATH="$HOME/.npm/bin:$PATH"' >> ~/.zshrc
source ~/.zshrc
```
