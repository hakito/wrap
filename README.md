# wrap
This set of script will build a minimized kernel and debootstrap Ubuntu for the PC Engines Wrap board.

# Installation
* Clone this repository on your Ubuntu machine.
* Optional: Adapt the build.config file
* Optional: Adapt other config files
* Open a terminal and go to the repo path
* Insert your compact flash card and unmount it if it has been mounted automatically
* Execute "sudo scripts/build /dev/sdX" (sdX should be the real name of your compact flash card)
* Insert the compact flash card into your wrap board and power it up. If you have a serial console attached you should see the boot process and get a login screen.
* You can login as user "wrap" with password "wrap" (if you didn't change it in the config)
* If you don't have a serial console, you should be able to SSH to the board if you connected it to eth0 (that's the one next to the power input). The IP address is retrieved via DHCP.

