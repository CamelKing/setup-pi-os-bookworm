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

    * this script will install python3-autopep8 thru apt
    * so that vim does not run into autopep8 not found 
    * error when saving .py files. However, once Python venv
    * is installed and setup, the autopep within the venv would
    * be used instead.

5. Install Python

    cd ~/src/setup-pi-os-bookworm/python
    ./install_python.sh

    * python 3.11 was preinstalled on pi os
    * this installation make use of python venv


6. Install LX Terminal Config file.

    cd ~/src/setup-pi-os-bookworm/lxterminal
    ./install-lxterminal-conf.sh

    * this is totally optional
    * old version of pi os used to store menu as 
    * a text file which has been changed, and that
    * part of the installation has been removed

