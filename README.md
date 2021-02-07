# Fix Atheros WiFi AR9565 MacOs BigSur (Hackintosh)

##Support

if you like my work, please support me in <br>
https://www.buymeacoffee.com/iamelse <br>
https://saweria.co/iamelse

## Preparation

1. Download all kext
2. Download PropeTree you can download from here https://github.com/corpnewt/ProperTree

When all done, just follow step below


## Step 

1. Put all kext in OC/Kext
2. Enable those kext in opencore app configurator (in kernel tab)
3. Open ProperTree.command with terminal make sure you mount your EFI partition first
4. Click File -> Open (Cmd + O)
5. Open your config.plist from EFI folder
6. Click File -> OC Clean Snapshot (Cmd + Shift + R)
7. Save then reboot your machine


## Note

You will get 1 signal bar only, but all working fine. Actually better you replace your card with the supported one or use wifi dongle instead. <br>
I'm using OpenCore 0.6.4



## Resource

https://www.insanelymac.com/forum/files/file/1008-io80211family-modif/?_fromLogin=1


## Thanks to

Hackintosh Lover Forum <br>
Didin Wahyudin guy who guided me how to use this :)
