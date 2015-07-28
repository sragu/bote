For disk latency

- https://code.google.com/p/ioping/

ஃ ioping .
4 KiB from . (hfs /dev/disk1): request=1 time=6 us
4 KiB from . (hfs /dev/disk1): request=2 time=43 us
4 KiB from . (hfs /dev/disk1): request=3 time=22 us
4 KiB from . (hfs /dev/disk1): request=4 time=26 us
^C
--- . (hfs /dev/disk1) ioping statistics ---
4 requests completed in 3.77 s, 41.2 k iops, 161.1 MiB/s
min/avg/max/mdev = 6 us / 24 us / 43 us / 13 us


For disk speed, using dd comand:

dd if=/dev/zero of=/tmp/output.img bs=512m count=10 oflag=direct

> copies 5gb of the data to /tmp