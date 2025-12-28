# EFI-for-dell-inspiron-15-3558
EFI for Dell Inspiron 15 3558 for hackintosh macOS Monterey.  
The above EFI folder also includes kexts for wifi, bluetooth,etc.

Note:- This repo is not going to be maintained any more.

Specs of my Dell inspiron 15 3558 are :-
1. CPU: corei3 5005u
2. RAM: 8GB DDR3L
3. HDD: 500GB
4. GPU: Intel HD Graphics 5500
5. Wifi/Bluetooth: Intel AC3160
6. Sound: Intel Broadwell HDMI Audio

Not working :-
1. Ethernet
2. SD Card slot
3. Sound
4. Bluetooth (Partially working and may need to re-apply the kexts sometimes to get it working)

Sound issue:- I've tried to get the sound working but for some reason the kext doesn't work, the kext I'm using is ```VooDooHDA.kext``` which is made for HDMI audio it works on the previous versions of macOS.
The kext is not included in the EFI folder and you've to apply it in the post installation process.

![Alt text](screenshot.png "screenshot")

🙂 Also a huge thanks to Olarila whos EFI I've used and modified for this computer!
