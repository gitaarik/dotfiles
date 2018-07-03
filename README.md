To install the requirements on Ubuntu:

    apt update
    apt upgrade -y
    apt install -y git python-pip python-dev python3-pip python3-dev exuberant-ctags cmake tmux vim silversearcher-ag htop
    pip install powerline-status
    apt-get install fonts-powerline

To set up workspaces for multiple monitors in Gnome, install "GNOME Tweaks". Then execute this command to make the expose on the second monitor only display windows of that workspace:

    gsettings set org.gnome.shell.overrides workspaces-only-on-primary false

More info: http://gregcor.com/2011/05/07/fix-dual-monitors-in-gnome-3-aka-my-workspaces-are-broken/

To get rid of the Dock catching the Super+number keyboard shortcut, in the Keyboard & Mouse menu switch the Overview Shortcut to Right Super and then switch back to Left Super.

To install the requirements on OS X:

    brew install python@2 wget cmake
    pip install powerline-status
