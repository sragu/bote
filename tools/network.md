IPerf
-------

https://github.com/esnet/iperf

**iperf** for a collective report on network statistics between 2 systems.

With NetCat 
-----

on the receiving machine run:

`nc -vvlnp 12345 >/dev/null`

And then client can pipe a gigabyte of dummy data through dd over the nc tunnel.

`dd if=/dev/zero bs=1M count=1K | nc -vvn 10.10.0.2 12345`

So you can measure how much time it to transfer raw data of given size over network.
