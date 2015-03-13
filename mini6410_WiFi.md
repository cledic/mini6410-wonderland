# A quick and dirty way to add WiFi to the Mini6410 board (WEP and WPA). #

You need to download and install a new kernel from the "Download" tab of this site.
http://code.google.com/p/mini6410-wonderland/downloads/detail?name=zImage_n43&can=2&q=#makechanges

I have compiled this kernel from the FriendlyARM source, adding the WiFi capability.
**Use this kernel at your risk!**

Then I download this wpa\_supplicant package from here:
http://www.dengebt.com/wpa_supplicant0.6.10_mini2440_dengebt.tar.gz
(thanks a lot  S.Onur Selamet)
And I _install_ manually the software putting the library files under **/lib** and the executable files under **/usr/sbin**

You can follow this topic for the configuration file setup:
http://www.friendlyarm.net/forum/topic/242

Or you can follow my page written for the mini2440 board:
http://translate.google.it/translate?u=http%3A%2F%2Fcode.google.com%2Fp%2Fmini2440-wonderland%2Fwiki%2FConfigurazioneWiFi&sl=it&tl=en&hl=&ie=UTF-8

It works for me! :-)