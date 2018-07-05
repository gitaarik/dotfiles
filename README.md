To install the requirements on Ubuntu:

    apt update
    apt upgrade -y
    apt install -y git python-pip python-dev python3-pip python3-dev exuberant-ctags cmake tmux vim silversearcher-ag htop
    pip install powerline-status pipenv flake8
    apt-get install fonts-powerline

To set up workspaces for multiple monitors in Gnome:

    - Install "GNOME Tweaks"
    - Go to "Workspaces"
    - set "Display Handling" to "Workspaces span displays"
    - Then execute the following command to make the expose on the second
      monitor only display windows of that workspace:

          gsettings set org.gnome.shell.overrides workspaces-only-on-primary false

      More info: http://gregcor.com/2011/05/07/fix-dual-monitors-in-gnome-3-aka-my-workspaces-are-broken/

    - Then execute the following command to disable the hotkeys of the GNOME
      Dock, so you can use the keyboard shortcuts for Super + Number to switch
      to the workspaces:

        gsettings set org.gnome.shell.extensions.dash-to-dock hot-keys false

      More info: https://askubuntu.com/questions/968103/disable-the-app-key-supernum-default-functionality-in-ubuntu-17-10

To install the requirements on OS X:

    brew install python@2 wget cmake
    pip install powerline-status
