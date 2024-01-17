## When you first login to linux you get prompted with a terminal through which you can interact with kernal of linux

 ‘#’ comes for a root user and ‘$’ comes for a normal user which also can be configured on a profile level.

## Filesystems are the way of organizing files in Linux otherwise all of different types of files like user files, config files, network files, data files, log files will be in combined format.

  Different types of filesystem are: ext3,ext4,xfs,etc.

## File system structure in linux and their small description(to see this go to root directory by command "cd /"):
  /boot : Contains file used by boot loader (eg: grub.cfg)
  /root : root user home directory (not root directory i.e. /)
  /dev  : system devices (like disk, drive, keyboard etc)
  /etc  : Configuration files (mostly used)
  /bin->/usr/bin : everyday user commands
  /sbin->/usr/sbin : system/filesystem commands
  /opt : Optional add on application
  /proc : Running Process (Only exist in memory)
  /lib : c programming library files needed by commands and apps 
  /tmp : directory for temporary files
  /home : directory for user
  /var : system logs directory
  /run : System daemons that start very early to store temp run files like PID
  /mnt : to mount external filesystem (eg NFS)
  /media : for cdrom mounts or USB media
