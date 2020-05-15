# LINDY-IPower-Stripe-Lite-web-scrapping
A python web-scrapping CLI for the LINDY IPower StripeLITE

##  Reqierments
1.  A valid installation of [Python3](https://www.python.org/)
2.  Installed python3-packages 'requests' & 'bs4'

##  Instalation
1.  Open a comand line interface
1.  Clone this project using `git clone https://github.com/NikBenson/LINDY-IPower-Stripe-Lite-web-scrapping.git`
2.  Navigate in the project folder using `cd LINDY-IPower-Stripe-web-scrapping`
3.  Execute Powerswitch.py with `python3 Powerswitch.py [args]` and replace args for your desire

##  Syntax
### Show all stati
To show all stati use `Poowerswitch.py [IP]` with IP as the devices IP address.
It should print 'on' or 'off' in a own row for each output.
### Show specific status
To show a specific status use `Powerswitch.py [IP] get [outID]` with IP as the devices IP address and outIP as the id of the output on the device starting at 1.
It should print 'on' or 'off'
### Set an output on/off
To set the status of an output use `Powerswitch.py [IP] set [outID] [on/off] [username] [password]` with IP as the devices IP addres, outIP as the id of the output on the device starting at 1, on/off as on for turning the output on and off for turning the output off and username and password as your login data.
It should print 'on' or 'off' to confirm if it worked.
