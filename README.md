# Airgeddon
Airgeddon turorial.
Checkout the official website here: https://github.com/v1s1t0r1sh3r3/airgeddon

Airgeddon is a wifi testing tool prebuild into Parrot Security OS.
This tool alows you to test your wifi password hacking skills. This tool is fully automated so actually no skills are necessary here. So be sure to check out de Aircrack tutorial also so you know what this tool does and learn the basics.

# Start the tool.
Before opening the application connect your wifi adapter first.

Open Applications and go to => Pentesting => Wireless testing and open Airgeddon.

This tool needs root privileges so echter your password.
First the tool checks is all the needed applications are installed. Also some optional tools are checked. So as long as the essential tools are there your good to go. Otherwise let Airgeddon install the tools for you or do this yourself.

After a couple of enters Airgeddon needs an interface to work with. 
Select the adapter and enter. (Airgeddon needs alot of enters:)

First let's put the adapter in monitor mode so you can "look" at the networks in the air. (Select 2)

Now select 5 Handshake/PMKID tools menu.
Now select 4 Explore for targets.

This will open an other window that will scan for networks, let it run for a minute and then close it by pressing ctrl-c.
Afterthis a new windows will open and shows you the discoverd networks.
The yellow ones have clients on them to attack. The green once have no clients or at least no clients have been seen yet.
select the number of the network you want to attack and press enter.

On the top of the new screen you see the selected netwerk and other details of this network.
Now select 5 for the PMKID attack or 6 for the handshake caputure.
Let's start with a handshake capture. so select 6.

Airgeddon will validate if everthing is ok and pressent you a menu to select the type of attack.
Option 1 and 2 will try to deauth clients and capture the handshake. In this handshake is the hashed password.
Accept the default values for the time the attack will run. 20sec is the default, and press enter.
Let the application run. It will open 2 screens. One to deauth the clients on the network and one to capture the handshake.

It's possible that you don't capture the handshake, just run in again and again.