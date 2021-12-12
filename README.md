# dotfiles

![image](https://user-images.githubusercontent.com/7318997/145733886-129e2c9b-0ec5-451b-b051-8326ec7bfefa.png)

This is my hyper-minimal CLI setup. **Here's what it accomplishes:**
1. Swaps base Terminal app for `iTerm 2`
2. Color palette upgrade
3. File-type syntax highlighting
4. Swaps base ls and ll commands for `Exa`
5. Adds `powerlevel10k` for upgraded prompt <sup>†</sup>
6. Adds line numbers and other helpful goodies to vim editor

## Setup
### Download iTerm 2
https://iterm2.com/downloads.html

### Clone the solarized/light repo
https://github.com/altercation/solarized

### Create a new "Profile" in iTerm and assign the color palette "Solarized Light"
More details on how to do this coming soon...

### Download Homebrew
https://brew.sh/

### Install Exa via Brew
https://the.exa.website/install/macos

### Install P10K via Brew
https://github.com/romkatv/powerlevel10k#homebrew

### Clone the contents of this repo and place the files in root directory
You should have these hidden files in your `~/` directory:
- .vimrc
- .zshrc
- .p10k.zsh




---


<sup>†</sup> _More details on p10k:_
- Adds current git branch details to prompt
- Adds useful icons and colors to prompt
- Upgrades font from default
