# Source:Snazzy Labs, URL:https://www.youtube.com/feeds/videos.xml?channel_id=UCO2x-p9gg9TLKneXlibGR7w, language:en-US

## Make a Mac Pro for Under $2,000!
 - [https://www.youtube.com/watch?v=l_QPLl81GrY](https://www.youtube.com/watch?v=l_QPLl81GrY)
 - RSS feed: https://www.youtube.com/feeds/videos.xml?channel_id=UCO2x-p9gg9TLKneXlibGR7w
 - date published: 2020-01-25 00:00:00+00:00

Snazzy Labs shows the latest all-AMD Corsair Vengeance 6182 Gaming PC running macOS Catalina using OpenCore. You can make your own too!

Follow me on Instagram - http://instagram.com/snazzyq
Follow me on Byte - snazzy
Support us buying a 5700 XT GPU (or anything else!) - https://geni.us/d3FPlY
Corsair Vengeance 6182 - http://snazzy.fm/hUHON
OpenCore Vanilla Guide - http://snazzy.fm/u2WuW
config.plist Setup Guide - http://snazzy.fm/bc6hB

*INSTALL DEPENDENCIES*
gibMacOS - http://snazzy.fm/m3MQk
SSDTTime - http://snazzy.fm/5Can8
OpenCorePkg - http://snazzy.fm/Ls47P
ProperTree - http://snazzy.fm/hQOyU
patches.plist - http://snazzy.fm/O2x8Q
Needed .efi files - http://snazzy.fm/ZsDcO
Needed .kext files - http://snazzy.fm/c3v9B

*HELP*
General Troubleshooting (more tips below) - http://snazzy.fm/d9RC8
AMD OS X Forums - http://snazzy.fm/WxWTh
AMD OS X Discord http://snazzy.fm/UCzUu

*CORRECTIONS AND SUGGESTIONS*
1. I included the DSDT.aml file by accident—this is not needed
2. I included IntelMausiEthernet.kext. AMD systems only work with 211-AT - http://snazzy.fm/lth41
3. When editing your config.plist file, use the search function in ProperTree to ensure the following: (a) EC SSDT is set as "true," (b) Navi cards require the following boot arguments: [debug=0x100 agdpmod=pikera] (do not include brackets), (c) if you have a black screen after volume selection, make sure ProvideConsoleGOP is set to true.
4. Just about every other problem conceivable can be found here. Read/check it thoroughly.  http://snazzy.fm/d9RC8

Follow me on Twitter - http://twitter.com/snazzyq
Follow me on Instagram - http://instagram.com/snazzyq

Hackintosh machines are often considered unreliable by those who don't know what they're doing or haven't done due diligence on building their own configuration file. In this video tutorial, Snazzy Labs will show you how to make your own AMD hackintosh using the OpenCore bootloader.

