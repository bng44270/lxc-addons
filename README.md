# lxc-addons
a few custom LXC management scripts

## Installation:
1. Determine the location of your existing LXC tools (ex: ```/usr/bin```)  
2. Run ```sudo cp lxc* /usr/bin```  

## Usage:  
1. **lxc-startall** - start all LXC containers on host (if they are not currently running)  
2. **lxc-stopall** - stop all LXC containers on host (if they are currently running)  
3. **lxc-infotab** - display LXC container information in tabular format  
a. To enable refreshing, use ```-r <seconds>``` arguments to specify refresh interval  
5. **lxc-screenui** - open GNU screen for LXC container managment  
a. Creates a summary screen using ```lxc-infotab``` along with a terminal for each container  
b. To specify a custom refresh interval, use ```-r <seconds>``` arguments (default refresh interval is 10 seconds)  
6. **lxc-template** - create a custom Debian-based LXC template with specified packages installed
