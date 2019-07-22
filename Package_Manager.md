## Update your System:

	sudo pacman -Syu
	
## Change Time and Date Language:
   *Settings -> Locale -> English*
   
## Install Pamac:
Pamac is a graphical package management program that can be used instead of Octopi (Built-in package manager for Manjaro-KDE)

It has built in AUR (Arch User Repository) support.

    sudo pacman -Syu pamac-gtk
	
*Menu -> Preferences -> AUR*
    
Link: https://wiki.manjaro.org/index.php/Pamac
	
## Install yay:
    
	git clone https://aur.archlinux.org/yay.git

	cd yay

	makepkg -si

After installation you can just search and install any applications
yay <Search Term>
