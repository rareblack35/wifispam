# wifispam

This script allows you to spam thousands of WiFi SSIDs.

Notes

This script allows you to generate the number of SSIDs that you want, unless you're using the default word list (1000 SSIDs).
If you are going to use the 4th option I recommend you generate up to ~5000 SSIDs
Some Intel® Hardware In particular Centrino are known to cause problems becuase of the way mdk3 works.

Dependencies

MDK3 sudo apt-get install mdk3: https://github.com/wi-fi-analyzer/mdk3-master

MACCHANGER sudo apt-get install macchanger https://github.com/alobbs/macchanger

PWGEN sudo apt-get install pwgen

Dependencie installation for Arch Linux: sudo pacman -S mdk3 macchanger pwgen


Instalation and usage

1. Download the files git clone https://github.com/rareblack35/wifispam.git

2. Dependencie instalation

2.1 Method 1 run the install.sh file AS ROOT

2.2 Method 2 Manualy add sources and install packages listed above

3. Run the script sudo wifispam.sh


