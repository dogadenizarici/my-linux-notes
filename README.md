Creating bootable linux USB flash drive using dd

```
sudo dd if=isoFileHere of=/dev/sdX status=progress bs=4M oflag=sync
```
