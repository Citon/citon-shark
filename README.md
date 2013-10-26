Citon Shark - Config snippets and scripts to make Backtrack into a Shark 
-----------------------------------------------------------------------------

A "Shark" is a small, dual NIC, headless system that can be shipped easily
and connected to networks for remote troubleshooting.  The Shark system
features:

 * An automatic phone-home remote access system called URTBOD (Unstoppable
   Reverse Tunnel Backdoor Of Doom)
 * Automatic fight recorder style packet capture on the eth1 (2nd) NIC
   interface
 * Various utility scripts

The core of the system is Backtrack Linux.  (Note that future versions will
target Kali Linux.)  The citon-shark package retrofits an existing Backtrack
installation with the extra setup to make it a Shark.

Scripts are under the scripts/ tree and in the relative subfolders they
should be installed into.
