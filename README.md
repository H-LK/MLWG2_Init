# MLWG2_Init

Use the OpenWRT Buildroot Tutorial to build your own Image.
https://wiki.openwrt.org/doc/howto/buildroot.exigence


Before step 5 copy `fstab` and `rc.local` to `/init.d` and `/etc` (Create the directories if they does not exist!)
- Copy fstab to /trunk/files/etc/init.d/
- Copy rc.local to  /trunk/files/etc/



The script searches for something like `fhg_mlwg2_v1.0.bin`. Change `rc.local` line 5 and 8 to search for other image files.
