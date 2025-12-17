# Opencore-EFI-For-Asus-X512DA
Opencore Hackintosh EFI for booting macOS on an Asus X512DA laptop

Tested with Sonoma, Wifi kexts are for 14.4+ so change that if you're booting an older version

Make sure you change device info things like serial, rom, model name, etc

Specs:
AMD Ryzen 5 3500U, 12GB DDR4, Radeon Vega 8, 256GB Kingston SSD

Everything I've tested seems to be working completely fine aside from the known and unavoidable bugs of NootedRed - When initially installing remove the kext (from EFI and PLIST) and when you get to the desktop set the wallpaper to a static image. Then add the kext and add it back to the PLIST with CMD+R pointing to your OC folder of the internal drives EFI and save and reboot. You should then have working graphics
