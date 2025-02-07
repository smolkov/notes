# Linux system tips

## Use tempfs to mount 25% ramdisk

Folgende Zeile in `/etc/fstab`

```
tmpfs /home/sascha/ramdisk tmpfs default,size=25% 0 0
```
