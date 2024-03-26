### Installation 
To install OMV, OMV-Extras copy and paste this line in the Terminal and press Enter. The installation will take some time, so enjoy the text flying on the screen. 

***The installation process demands sudo utilization.***

To download and execute the script you can use either *wget* or *curl*, feel free to use what you prefer!

*wget script*
####  
```bash
sudo wget -O - https://raw.githubusercontent.com/andikamc/armbian-omv-installer/master/installer?date=$(openssl rand -hex 12) | sudo bash
```

*curl script*
```bash
sudo curl -sSL https://raw.githubusercontent.com/andikamc/armbian-omv-installer/master/installer?date=$(openssl rand -hex 12) | sudo bash
```
