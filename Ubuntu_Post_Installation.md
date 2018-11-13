## Ubuntu Post Installation Setup

***

***

### Update the system
> `sudo apt update && sudo apt upgrade`


***

### Install media codecs for full multimedia support
> `sudo apt install ubuntu-restricted-extras`

> `sudo apt install libavcodec-extra`


***

### Install Gnome shell extensions
> `sudo apt install gnome-shell-extensions`

> `sudo apt install chrome-gnome-shell`


***

### Install snap package manager
> `sudo apt install snap`


***

### Install flatpak package manager
> `sudo apt install flatpak`

> `sudo apt install gnome-software-plugin-flatpak`

> `flatpak remote-add --if-not-exists flathub https://flathub.org/repo/flathub.flatpakrepo`


***

### Install Gnome Tweak Tool
> `sudo apt install gnome-tweak-tool`


***

### Set click to Minimize
> `gsettings set org.gnome.shell.extensions.dash-to-dock click-action 'minimize'`


***

### Set Templates (Right click > Add New Document)
> `cd ~`

> `touch Text_File.txt Python_File.py Java_File.java JS_File.js HTML_File.html CSS_File.css PHP_File.php MarkDown_File.md`


***

### Install communitheme
> `sudo snap install communitheme`


***

### Install flat-remix theme
> `sudo add-apt-repository ppa:daniruiz/flat-remix`

> `sudo apt-get update`

> `sudo apt-get install flat-remix-gnome`


***

### Install flat-remix icons
> `sudo add-apt-repository ppa:daniruiz/flat-remix`

> `sudo apt-get update`

> `sudo apt-get install flat-remix`


***

### Install following gnome shell extensions
* Extensions
* User Themes
* Dash To Panel
* Docker Integration
* Force Quit
* Freon
* IP Finder
* NetSpeed
* Refresh Wifi Connections
* Removable Drive Menu
* Sound Input & Output Device Chooser
* Appfolders Management extension
* Backup Tools

***

### Restart Gnome shell
> Press `Alt + F2` and type `r`, then hit Enter


***

### Clean partial packages
> `sudo apt autoclean`


***

### Cleanup apt-cache
> `sudo apt clean`


***

### Cleanup any unused dependencies
> `sudo apt autoremove`
	
	