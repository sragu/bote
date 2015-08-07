IPerf
-------

https://github.com/esnet/iperf

iperf for a collective report on network statistics between 2 systems.

With NetCat 
-----

on the recieving manchine:

`nc -vvlnp 12345 >/dev/null`

And the client can pipe a gigabyte of zeros through dd over the nc tunnel.

`dd if=/dev/zero bs=1M count=1K | nc -vvn 10.10.0.2 12345`
