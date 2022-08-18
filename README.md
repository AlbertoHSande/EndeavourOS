# EndeavourOS
Just a compilation of various tweaks for my Alienware Aurora Ryzen Edition

# Mount second disk as a folder for Steam games
cd / && sudo makdir GAMES  
sudo vi /etc/fstab  
/dev/sdx* /GAMES ext4 defaults,nofail 0 0  

# Add support for Xbox Series Controller
git clone https://github.com/atar-axis/xpadneo.git  
cd xpadneo  
sudo ./install.sh  
sudo bluetoothctl  

# Stop KDE indexing files
balooctl suspend  
balooctl disable  
