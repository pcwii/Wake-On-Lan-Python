Wake-On-Lan-Python
==================

wol.py is A small Python script to allow the sending of a WOL Magic packet so that LAN clients can be remotely switched on from another machine on the same subnet. Rather than needing to know the MAC address of the desired machine, the script allows you to specify by hostname, so long as that host is included in the configuration file.


Usage
-------

> wol.py \[hostname\]

or

> wol.py list



Configuration File
--------------------

The configuration file is just a basic INI file, containing one section per host;

> \[General\]
>
> broadcast=192.168.1.255
>
> \[Computer\]
>
> mac=00:13:0d:e4:60:61
>
> \[Server\]
>
> mac=AB:13:0d:e4:88:42
>
