E-hfsc ("enhanced-hfsc") is a bash script for set a working traffic shaping on your network.  
  
    
Assuming your router is linux based, your will be able to get a working voip/interactive/http traffic, with no latency or trouble, also while p2p (torrent,amule,etc) are still on and filling bandwidth.  

It uses hfsc classificator, tc (of course), ifb interfaces, iptables (with connmark).
  
  
A little howto is in file header.

--
You can test your classes and filter using polltc, from [https://github.com/k0smik0/polltc](https://github.com/k0smik0/polltc)
