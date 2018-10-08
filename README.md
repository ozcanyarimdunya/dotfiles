# Dotfiles

### Backup all your current dotfiles, this dotfiles will delete them without any warnings.

## Installation

### Automatic Installation
```sh
curl https://raw.githubusercontent.com/yasinuslu/dotfiles/master/download_and_install.sh | sh
```

### Manual Installation
```sh
git clone https://github.com/yasinuslu/dotfiles.git
cd dotfiles
./install.sh
```

## Usage
We use fish, just run `fish`

### Make fish your default shell

- In POSIX compliant shells like `bash` or `zsh`
  
  ```sh
  chsh -s $(which fish)
  ```

- In `fish`
  
  ```sh
  chsh -s (which fish)
  ```

References:
- https://github.com/gpakosz/.tmux
- https://github.com/junegunn/fzf
- https://github.com/SpaceVim/SpaceVim
- https://github.com/icy/pacapt
- https://github.com/asdf-vm/asdf
