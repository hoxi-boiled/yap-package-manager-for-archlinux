# yap-package-manager-for-archlinux
YAP - It’s a merger of AUR and pacman into a single package manager.

how it work - sudo yap install package
>> Searching for package in official Arch repositories...
>> Not found in pacman, trying AUR...
 -> No AUR package found for package
 -> no package found for targets

HOW TO RUN YAP - sudo curl -L https://github.com/hoxi-boiled/yap-package-manager-for-archlinux/releases/download/YAP/yap.sh -o /usr/local/bin/yap && sudo chmod +x /usr/local/bin/yap

to install - sudo yap install package_name

to remove - sudo yap remove package_name
