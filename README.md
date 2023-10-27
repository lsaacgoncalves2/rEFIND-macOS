# rEFIND-macOS
How to install rEFIND on macOS.

1st step:
Download the latest release.

2nd step:
Unzip it and copy to an usb stick or you can manually create a partition, with 8GB, and paste to there.
IMPORTANT: Remeber the name you selected to the usb stick or partition. I will use "REFLASH".

3rd step:
Boot the system to recovery mode.

4th step:
Open utilities and then terminal.

5th step:
Type:
```
cd /
ls
cd Volumes
ls
cd REFLASH
ls
cd refind-bin-0.14.0
ls
./refind-install
```

  

6th step:
Reboot.

