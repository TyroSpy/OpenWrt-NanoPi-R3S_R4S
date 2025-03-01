# OpenWrt-NanoPi-R3S_R4S
## Modifications:

* Patches for REALTEK_PHY driver (R4S only - fixed unitialized LAN port after reboot)
* Increase rootfs size to 1024MB
* dnsmasq-full instead dnsmasq
* syslog-ng instead logd
* Enable Dropbear support ecdsa keys

## Following additional packages integrates:

* kmod-fs-exfat
* kmod-fs-ext4
* kmod-fs-f2fs
* kmod-fs-ntfs3
* kmod-usb-storage-uas
* kmod-usb2
* kmod-usb3
* block-mount
* openssh-server
* openssh-sftp-server
* dnsproxy
* ddns-scripts

### Luci Russian Languages

## After Install you must change openssh server port to avoid conflict with dropbear or remove unnecessary packages

### Firmwares fully support official updates

Big thanks to @anaelorlinski


