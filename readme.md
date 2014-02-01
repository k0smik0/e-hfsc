E-hfsc ("enhanced-hfsc") is a bash script for set a working traffic shaping on your network.


Assuming your router is linux based, this script provides a working voip/interactive/http traffic with low latency and no trouble while some p2p (torrent, amule, etc) are also active and fills the network bandwidth.

E-hfsc uses (obviously) hfsc classificator, tc (of course), ifb interfaces, iptables (connmark and layer7):
all is supported by vanilla kernel, except for layer7.  
If your kernel does not provide layer7 modules, rules using l7 matches will be simply ignored.


A little howto is in file header.

--
You can test your classes and filter using polltc, from [https://github.com/k0smik0/polltc](https://github.com/k0smik0/polltc)

