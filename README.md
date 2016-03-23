# Disable-SIP-for-MBA-USB-Super-Drive

The MacBook Air SuperDrive (MB397G/A) works with MBP (El Capitan ver 10.11.3)

[HT201295 Superdrive not working with El Capitan](https://discussions.apple.com/message/29360321#29360321)    
[How to Disable System Integrity Protection (rootless) in OS X El Capitan](http://osxdaily.com/2015/10/05/disable-rootless-system-integrity-protection-mac-os-x/)    

1) Disable SIP   
2) Find "com.apple.Boot.plist" (/Library/Preferences/SystemConfiguration/)   
3) insert the "mbasd=1" into the "Kernel Flags"   
4) Enable SIP   
