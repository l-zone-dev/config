# install homebrew
`/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`

# FIXME add branch for if this is an ubuntu box. want a path for apt install
`/opt/homebrew/bin/brew install zsh tmux neovim`
`sudo apt install zsh tmux neovim`

# install oh-my-zsh
`sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"`

# install tmux package manager and tmux resurrect. Note: prefix + U to update plugins
`git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm`

# type this in terminal if tmux is already running
`tmux source ~/.tmux.conf`

# nvchad setup
see here https://nvchad.com/docs/quickstart/install
`git clone https://github.com/NvChad/NvChad ~/.config/nvim --depth 1 && nvim`
