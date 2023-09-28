Error1:
welcome to emergency mode centos 7
check file system
$ journalctl -xb
Find /dev/dm-x error //x is number

$ xfs_repair -v -L /dev/dm-x
