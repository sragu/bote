For disk latency
-------------

> ioping 

https://code.google.com/p/ioping/


Measuring disk speed, using dd comand:
------------

`time dd if=/dev/zero of=/tmp/output.img bs=512m count=10 oflag=direct
`
> copies 5gb of the data to /tmp
