# oneui-rom-guide-mtk
A small guide for creating custom oneui roms, for mtk (Huaqin or WingTech) based samsung phones (requires unlocked bootloader and/or root)
## Extracting
First things first, you need to extract the mtk firmware. You could use tools like [mtk auth bypass](https://androidfilehost.com/?fid=17825722713688280402) in order to extract it into .imgs.
Then, you would need a tool like [simg2img](https://github.com/KinglyWayne/simg2img_win) in order to extract the super image, then [erofs tools](https://xdaforums.com/t/tool-win-erofs-utils-for-cygwin64.4565233/) for .img extracting.
Last but not least, you can use [ChonDoe Flasher](https://androidfilehost.com/?fid=17248734326145717662) or fastbootd in order to flash the modified .img files onto the device.

## Tweaks

### Debloating
Removing apps and such, better performance / less features.
Bookmarks:
* [el0xren's Debloat guide](https://github.com/el0xren/Samsung_Additional_Features/tree/debloat)

### General
General tweaks.
Bookmarks:
* [Samsung A23 Flagship Feature Tool](https://github.com/mrx7014/AFFT), although for exynos, it might be useful.
* [Samsung M23 Hidden Mods](https://github.com/Aflaungos/M23-Hidden-Mods), although for snapdragon, it might be useful.

### CSC Features
Country specific feature tweaks.
Bookmarks:
* [el0xren's CSC Features guide](https://github.com/el0xren/Samsung_Additional_Features/tree/cscfeature)

### floating-feature.xml
Various/General oneui features, edit in vendor/etc/floating_feature.xml or system/etc/floating_feature.xml.
Bookmarks:
* [el0xren's Floating Features guide](https://github.com/el0xren/Samsung_Additional_Features/tree/floatingfeature)

### Camera Features
Mediatek devices do not use a camera-feature.xml file, so basically you cannot add more/hidden features for the camera app.
What you could do, however, is mod the apk file directly. Application modding is out of this scope however.
Bookmarks:
* [Smiley9000s wing camera mod](https://github.com/smiley9000/android_vendor_samsung_wing-camera)


## Useful Telegram Chats
Might find useful info, worth to check out.
Bookmarks:
* [Samsung Galaxy A05 Development](https://t.me/samsung_galaxy_a05_a055f_a055m)
* [physwizz stuff](https://t.me/physwizz2)
* [FlameOS Development Group](https://t.me/FlameOSGroup)
* [Board Archive](https://t.me/BoardKangs)
