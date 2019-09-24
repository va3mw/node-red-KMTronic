# node-red-KMTronic
This is a node-red flow for controlling a KMTronic TCP Web Switch.

This flow requires from the Pallet Manager

Dashboard - node-red-dashboard

Every http request will have to be edited with the
IP address of your KMTronic WEB Switch (not UDP
switch).  Change 192.168.110.12 to the address
of you KMTronic Switch.

Switch 6 is a PTT switch and by pressing it, it will
toggle on Switch 6 for 1 second - you can delete
it if not required

In the initial setup of your KMTRonic switch turn 
off any authetication.  
