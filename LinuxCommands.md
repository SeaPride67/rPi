Operation | Command - RASPBIAN/DEBIAN/UBUNTU
--------|-----------------------
Install a package. | sudo apt install <package name>
 Update the package index. | sudo apt update
 Upgrade the packages on your systems. | sudo apt upgrade
 Is nano installed? | dpkg-query -l  \| grep nano
 Is a package containing the string nano available? | apt-cache search nano
 Get more information about a package. | apt-cache show nano, apt-cache policy nano
 Get help. | apt help
 Graceful shutdown. | sudo shutdown -h now
 Graceful reboot. | sudo reboot
 
 
