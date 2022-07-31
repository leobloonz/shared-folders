# shared-folders
```
cd /mnt/hgfs
sudo mkdir hgfs
sudo vim /etc/fstab
ADD: vmhgfs-fuse /mnt/hgfs fuse defaults,allow_other 0 0
sudo reboot now
ls /mnt/hgfs
The Shared Folder you enabled in VMware Fusion Settings will appear
```
