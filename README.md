# Preferred Development Environment

1. [Homebrew](https://brew.sh/) - `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`
1. [1Password](https://www.1password.com) - `brew install --cask 1password`
1. Chrome - `brew install --cask google-chrome`
1. [iTerm2](https://iterm2.com/) - `brew install --cask iterm2`
   * Set color theme to 'Solarized Dark'
1. Git - `brew install git`
1. [GitHub CLI](https://cli.github.com/) - `brew install gh`
   * [Generate and add SSH keys to account](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)
1. ZSH - `brew install zsh`
   * [Oh My ZSH](https://github.com/ohmyzsh/ohmyzsh)
      * `sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"`
   * [PowerLevel10K theme](https://github.com/romkatv/powerlevel10k#oh-my-zsh)
      * `git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k`
      * `open ~/.zshrc` and set `ZSH_THEME="powerlevel10k/powerlevel10k"`
      * `source ~/.zshrc` and run PowerLevel10K wizard to install fonts
   * [ZSH Auto-completions](https://github.com/zsh-users/zsh-autosuggestions/blob/master/INSTALL.md#oh-my-zsh)
      * `git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions`
      * `open ~/.zshrc` and set `plugins=(zsh-autosuggestions)`. `source ~/.zshrc`
   * [Syntax Highlighting](https://gist.github.com/kevin-smets/8568070#syntax-highlighting)
1. [VSCode](https://code.visualstudio.com/Download) - `brew install --cask visual-studio-code`
   * [Add the `code` command to your PATH](https://code.visualstudio.com/docs/setup/mac#_launching-from-the-command-line)
   * [Update integrated terminal font](https://gist.github.com/kevin-smets/8568070#visual-studio-code-config) - Set `terminal.integrated.fontFamily` to `MesloLGS NF`
1. [Spectacle](https://www.spectacleapp.com/) - `brew install --cask spectacle`
1. [Docker Desktop](https://www.docker.com/products/docker-desktop) - `brew install --cask docker`
1. [Table Plus](https://tableplus.com/) - `brew install --cask tableplus`
1. [Firefox](https://www.mozilla.org/en-US/firefox/new/) - `brew install --cask firefox`
1. [Postman](https://www.postman.com/) - `brew install --cask postman`
1. [Spotify](https://www.spotify.com) - `brew install --cask spotify`

---

## Miscellaneous & Errata

### Github Integration
1. [Add SSH Keys to GitHub](https://docs.github.com/en/free-pro-team@latest/github/authenticating-to-github/connecting-to-github-with-ssh)