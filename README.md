# phileserve
A simple and minimal ArchlinuxARM based USB NAS distribution for embedded boards. 

Features:

- samba server enabled by default serving the attached USB disks (user/pass is nash/nash) 
- NFS server
- minidlna server
- transmission torrent client (with web interface)
- ssh/sftp server enabled by default 
- automatic mounting of multiple usb disks (ext3, ext4, fat32, ntfs, hfs) using udevil
- external disks spinning down option with hd-idle or hdparm

