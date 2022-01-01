# SideloadSign
SideloadSign is an IPA signer based on XreSign and built for SideloadStore to sign apps.  this adds the option to sing apps with your apple ID and directly signed on to device simalar to Altstore.  I will release a terminal exec first then a GUI program.  

## Supported Devices
SideloadSign will work on Mac and Linux (no windows support)



### Usage:
```
$ ./xresign.sh -s path -c certificate [-e entitlements] [-p path] [-b identifier]

where:
-s  path to ipa file which you want to sign/resign
-c  signing certificate Common Name from Keychain
-e  new entitlements to change (Optional)
-p  path to mobile provisioning file (Optional)
-b  bundle identifier (Optional)
```
## Credits
big thanks to the XReSign team who made this project.
-Applec0r Dev
-ZDC
