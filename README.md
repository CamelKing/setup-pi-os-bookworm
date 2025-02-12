# setup-pi-os-bookworm

Installation:


1. Clone setup-pi-os-bookworm to local:

    cd
    mkdir src
    cd src
    git clone https://github.com/CamelKing/setup-pi-os-bookworm
    cd setup-pi-os-bookworm
    ls

2. Install Git.

    * Pi-OS bookworm has git pre-installed,
    * this will install the git completion prompt.
    cd ~/src/setup-pi-os-bookworm/git
    ./install_git.sh

3. Install Bash configuration file and utilities.

    cd ~/src/setup-pi-os-bookworm/bash
    ./install_bash.sh
    cd 
    source ~/.bashrc

4. Install Vim:

    cd ~/src/setup-pi-os-bookworm/vim
    ./install_vim.sh

    run vim once to install/update all plugins

5. 






