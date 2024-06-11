# Dotfiles

# Requirements
Ensure it is installed

- Git
- Stow

# Installation
Clone dotfiles repo into $HOME directory using Git
```
$ git clone git@github.com/jordyboy/dotfiles.git
```
Go into dotfiles and run the install script

```
$ cd .dotfiles
$ ./install
```
# Dependencies

## Nvim
- Neovim
```
curl -LO https://github.com/neovim/neovim/releases/latest/download/nvim-linux64-tar.gz
sudo tar -C opt -xzf nvim-linux64.tar.gz
```
- ripgrep [telescope]
```
sudo apt install ripgrep
```

## TMUX
- Install tmux
```
sudo apt install tmux
```
- Clone TPM:
```
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```

## oh-my-posh
- Install oh-my-posh
```
curl -s https://ohmyposh.dev/install.sh | bash -s -- -d ~/opt
```
