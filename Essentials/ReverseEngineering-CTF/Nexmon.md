# Nexmon 101.

An C based patching framework for Wifi chips and enabling monitor mode with radiotap headers / frame injection.

allows to scan and doing following operations on network  packets :
- Monitor Mode : an more efficient version of wireshark but with less energy transfer 
- Monitor Mode with RadioTap headers.
- frame injection : can be an stateless attacks on the wifi ( can either be cryptanalysis  for the wifi wpa3 standards or the simply  ). 


Also it supports most of the Android OS based firmwares . my major writeup will explain the reference implementations  from the diffrent raspPi OS , specially extracting the 

in the patches/ channel check the patches.c and the other helper functions for the 
















##  Tasks : 
- [ ]Getting firmware to be rewritten in Rust , specially the cargo pallets for packaging and implementing some sort of "metasploit for  firmware "

- [ ] 