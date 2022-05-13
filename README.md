# Installation

Linux
```bash
sh -c "$(curl -fsLS chezmoi.io/get)" -- init --apply matt-bozz
```

Windows (Powershell as administrator)
```bash

# dependencies
choco install curl
choco install git

# install chezmoi
choco install chezmoi
chezmoi init --apply matt-bozz

# probably have to rename ~/.vimrc -> ~/_vimrc
git clone https://github.com/VundleVim/Vundle.vim.git ~/vimfiles/bundle/Vundle.vim

```

