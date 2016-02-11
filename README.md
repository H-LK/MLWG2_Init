# MLWG2_Init

Use the OpenWRT Buildroot Tutorial to build your own Image.
https://wiki.openwrt.org/doc/howto/buildroot.exigence


- Before step 5 copy `files` to `trunk`.
- Create directory /files/mnt/sda1

```
*@* ~/openwrt/trunk $ ls
bin          docs                include        min.config.old  target
BSDmakefile  feeds               key-build      package         tmp
build_dir    feeds.conf.default  key-build.pub  README          toolchain
config       files      <------         LICENSE        rules.mk        tools
Config.in    full.config         Makefile       scripts
dl           full.config.old     min.config     staging_dir
```




The script searches for something like `fhg_mlwg2_v1.0.bin`. Change `rc.local` line 5 and 8 to search for other image files.
