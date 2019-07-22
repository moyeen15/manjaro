## Install Pamac:
Pamac is a graphical package management program that can be used instead of Octopi (Built-in package manager for Manjaro-KDE)

It has built in AUR (Arch User Repository) support.

    sudo pacman -Syu pamac-gtk
	
*Menu -> Preferences -> AUR*
    
Link: https://wiki.manjaro.org/index.php/Pamac
	
## Install yay:
yay is an AUR Helper. It is a great tool for installing packages from Arch User Repository (AUR) 
    
	git clone https://aur.archlinux.org/yay.git

	cd yay

	makepkg -si

After installation you can just search and install any applications using:
	
	yay <Search Term>
