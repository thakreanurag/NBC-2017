```
Last login: Thu Feb  9 08:12:40 2017 from c18n2.netwebdel.com
[root@fs2client01 ~]# mount -t nfs 10.10.10.234:/storage/disk1/nfs_share nfs
[root@fs2client01 ~]# df -h
Filesystem                             Size  Used Avail Use% Mounted on
/dev/sda2                               99G  3.7G   90G   4% /
devtmpfs                               2.0G     0  2.0G   0% /dev
tmpfs                                  2.0G     0  2.0G   0% /dev/shm
tmpfs                                  2.0G   17M  2.0G   1% /run
tmpfs                                  2.0G     0  2.0G   0% /sys/fs/cgroup
/dev/sda1                              976M  115M  794M  13% /boot
tmpfs                                  396M     0  396M   0% /run/user/0
10.10.10.234:/storage/disk1/nfs_share   30G   32M   30G   1% /root/nfs
```