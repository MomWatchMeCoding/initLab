Asus switch/workroom
====================

* model Asys GigaX 1124+
* serial port 115200/no flow/8n1
* internal ip 192.168.192.8, in vlan 1

Ports
-----

* 1 - pp1/online direct
* 2 - tbc
* 5 - airport
* 6 - pp 12/studio
* 7 - pp 26/aquarium
* 8 - pp 4/ruby room, chernobyl
* 9 - pp 14/lecture hall, TMI
* 10 - pp 15/lecture hall/bench
* 11 - pp 6/lecture hall/door
* 12 - pp 11/studio
* 13 - pp 13/lecture hall
* 14 - pp 22/
* 19 - switch to bob (trunk)
* 20 - doorpi
* 21 - emergency mgmt

Vlans
-----

* 1 - mgmt
	* native/untagged 19
	* untagged 21
* 2 - lan
	* ports 4-18 untagged
	* port 19 tagged
* 5 - onlinedirect
	* port 1 untagged
	* port 19 tagged
* 6 - tbc
	* port 2 untagged
	* port 19 tagged
* 8 - doorpi
	* port 20 untagged
	* port 19 tagged
