# v2raylimiter

limit the number of users who can simultaneously connect to the server for each port

## Installation
first install requirments  
`git`  
`lnav`  
`gawk`
for example in debian or ubuntu  
```bash
apt install git lnav gawk
```
then run this commands

```bash
git clone https://github.com/lovelypablo/v2raylimiter
cd v2raylimiter
./install -i
```
use `sudo ./install -i` if you are not root.  
## Uninstallation
to uninstall v2raylimiter you have to just run installation script with "-r" option  
or from scratch  
```bash
git clone https://github.com/lovelypablo/v2raylimiter
cd v2raylimiter
./install -r
```
use `sudo ./install -r` if you are not root.
## Usage

```bash
USAGE: v2raylimiter [ -r|--run ] 				run userlimiter
		   [ -c|--clear-iptables ] 			clear iptable rules created by userlimiter
		   [ -h|--help ] 				show this help page
		   [ -l|--list-ports ]				show list of ports and their info
		   [ -L|--live-list-ports ]			show live list of ports and their info
		   [ -a|--add-port PORT:LIMITRATE ]		add new port with format PORT:LIMITRATE
		   [ -d|--delete-port PORT ]			delete an existing port from list
		   [ -n|--change-limitrate PORT:LIMITRATE ]	change limitrate of a port with format PORT:LIMITRATE
```

## Some words
i hope you don't use this script for selling vpn to people.  
instead you can teach them how to run vpn servers by themselves.  
and feel free to use this script in your projects.
## License

[GPL v3](https://www.gnu.org/licenses/gpl-3.0.en.html)
