![](docs/images/twrp-home.png)
![](docs/images/twrp-backup.png)

##### Team Win Recovery Project 3.x, or twrp3 for short, is a custom recovery built with ease of use and customization in mind. Its a fully touch driven user interface no more volume rocker or power buttons to mash. The GUI is also fully XML driven and completely theme-able. You can change just about every aspect of the look and feel.

    * Your warranty is now void.
    * I am not responsible for bricked devices, dead SD cards,
    * thermonuclear war, or your getting fired because the alarm app failed. Please
    * do some research if you have any concerns about features included in this ROM
    * before flashing it! YOU are choosing to make these modifications, and if
    * you point the finger at me for messing up your device, I will laugh at you.

Supported Models
-------------
Galaxy S22 Ultra (Snapdragon): S908E, S908N and S9080.

Download & Guide
-------------
                
1. Unlock your bootloader.
2. Downloads for Galaxy S22 Ultra (Snapdragon): [b0q](https://www.androidfilehost.com/?w=files&flid=334554)
3. Reboot to download mode
4. Uncheck auto reboot in Odin and flash TWRP in AP slot and [vbmeta_disabled.tar](https://github.com/afaneh92/android_device_samsung_b0q/raw/github.io/docs/vbmeta_disabled.tar) in USERDATA slot.
5. Hold volume down and power until the screen goes black then immediately switch to holding volume up and power to reboot into TWRP.
6. Disable encryption:
    - Go to Advanced > Terminal, type: multidisabler.​
    - If vendor complain about free space left on device, will attempt to resize vendor. and it ask to " - Run multidisabler again!."​
    - Type: multidisabler again. will see " - Finished." when done.​
    - Go back to Wipe > format data, and type "yes" to confirm.​
    - Reboot to recovery.​
7. Reboot to TWRP
8. Flash latest permissive [kernel](https://www.androidfilehost.com/?w=files&flid=334556) in twrp.
9. Flash magisk (Optional)
10. Reboot to system, Enjoy.
                
Support
-------------
Live support is available via #twrp on Freenode with your IRC client or just [click this link](http://webchat.freenode.net/?channels=twrp).

[Telegram group](https://t.me/+Vnl6QSa5Ru84OTM8)

Bugs
-------------
- Encryption not fully working.
     

Thanks
-------------
* TWRP team
* @ianmacd for multidisabler.
* @Dan_FFM (David Dean) for helping with convert readonly f2fs vendor to readwrite.
* Donators.

Sources
-------------
[Kernel tree](https://github.com/afaneh92/android_kernel_samsung_sm8450)

[Device tree](https://github.com/afaneh92/android_device_samsung_b0q)

Changelog
-------------
[GitHub History](https://github.com/afaneh92/android_device_samsung_b0q/commits/android-12.1)
