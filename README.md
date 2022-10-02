# Project related to full upgrade

The idea is to have Latest install of Ubuntu Environment with a single script
Download latest image, install it.

## Update repositories
    sudo apt update
## Upgrade
    sudo apt upgrade  
## Autoremove unneeded
    sudo apt autoremove
## Run all 3 above commands in succession twice...
The reason being that after installation everything gets updated
also repos, updaters, some packages become obsolete, just to be sure...


# install git and add
First try to find out version of latest git
# Add the APT REPOSITORY
    sudo add-apt-repository ppa:git-core/ppa
# Update    
    sudo apt update
# Install
    sudo apt install git
# update upgrade ...
    sudo apt update && sudo apt upgrade  && sudo apt autoremove
