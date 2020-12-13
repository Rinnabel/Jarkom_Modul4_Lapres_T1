# Lapres Modul 3 Jarkom 2020 - T1  
`"Repository dibuat untuk memenuhi tugas praktikum mata kuliah komunikasi data dan jaringan komputer tahun 2020."`  
  
Anggota:  
**Adeela Nurul Fadhila** `[05311840000001]` [@Rinnabel](https://github.com/Rinnabel)  
**Muhammad Ilya Asha Soegondo** `[05311840000010]` [@ilyaasha24](https://github.com/ilyaasha24/)  

Asisten:  
**Arino Jenynof** `[05111740000096]`  

Penguji: 
**I Gede Agung Krisna Pamungkas** `[5111740000135]`

KELOMPOK	NID TUNTAP		NID DMZ
T1		10.151.72.68/30		10.151.73.136/29

JARKOM PRAKTIKUM MODUL 4 SHIFT VLSM CPT FULL VERSION ENHANCED EDITION

Subnet	Size	Size			Mask
Name	Needed	Given	Address			Description 		Assignable Range	 Broadcast
A5	2021	2046	192.168.0.0	/21	255.255.248.0	192.168.0.1	- 192.168.7.254	 192.168.7.255
A1	1001	1022	192.168.8.0	/22	255.255.252.0	192.168.8.1	- 192.168.11.254 192.168.11.255
A13	721	1022	192.168.12.0	/22	255.255.252.0	192.168.12.1	- 192.168.15.254 192.168.15.255
A4	701	1022	192.168.16.0	/22	255.255.252.0	192.168.16.1	- 192.168.19.254 192.168.19.255
A10	521	1022	192.168.20.0	/22	255.255.252.0	192.168.20.1	- 192.168.23.254 192.168.23.255
A8	502	510	192.168.24.0	/23	255.255.254.0	192.168.24.1	- 192.168.25.254 192.168.25.255
A12	252	254	192.168.26.0	/24	255.255.255.0	192.168.26.1	- 192.168.26.254 192.168.26.255
A6	101	126	192.168.27.0	/25	255.255.255.128	192.168.27.1	- 192.168.27.126 192.168.27.127
A9	13	14	192.168.27.128	/28	255.255.255.240	192.168.27.129	- 192.168.27.142 192.168.27.143
A11	2	2	192.168.27.144	/30	255.255.255.252	192.168.27.145	- 192.168.27.146 192.168.27.147
A2	2	2	192.168.27.148	/30	255.255.255.252	192.168.27.149	- 192.168.27.150 192.168.27.151
A3	2	2	192.168.27.152	/30	255.255.255.252	192.168.27.153	- 192.168.27.154 192.168.27.155
A7	2	2	192.168.27.156	/30	255.255.255.252	192.168.27.157	- 192.168.27.158 192.168.27.159
[SUM]	5841				/19	

192.168.0.0/19
├───192.168.0.0/20
│   ├───192.168.0.0/21[A5]
│   └───192.168.8.0/21
│       ├───192.168.8.0/22[A1]
│       └───192.168.12.0/22[A13]
└───192.168.16.0/20
    ├───192.168.16.0/21
    │   ├───192.168.16.0/22[A4]
    │   └───192.168.20.0/22[A10]
    └───192.168.24.0/21
        ├───192.168.24.0/22
        │   ├───192.168.24.0/23[A8]
        │   └───192.168.26.0/23
        │       ├───192.168.26.0/24[A12]
        │       └───192.168.27.0/24
        │           ├───192.168.27.0/25[A6]
        │           └───192.168.27.128/25
        │               ├───192.168.27.128/26
        │               │   ├───192.168.27.128/27
        │               │   │   ├───192.168.27.128/28[A9]
        │               │   │   └───192.168.27.144/28
        │               │   │       ├───192.168.27.144/29
        │               │   │       │   ├───192.168.27.144/30[A11]
        │               │   │       │   └───192.168.27.148/30[A2]
        │               │   │       └───192.168.27.152/29
        │               │   │           ├───192.168.27.152/30[A3]
        │               │   │           └───192.168.27.156/30[A7]
        │               │   └───192.168.27.160/27
        │               └───192.168.27.192/26
        └───192.168.28.0/22
		
JARKOM PRAKTIKUM MODUL 4 SHIFT CIDR UML FULL VERSION ENHANCED EDITION

Subnet	Size	Size			Mask
Name	Needed	Given	Address			Description 		Assignable Range	 Broadcast
A13	721	1022	192.168.0.0	/22	255.255.252.0	192.168.0.1    - 192.168.3.254	 192.168.3.255
A12	252	254	192.168.4.0	/24	255.255.255.0	192.168.4.1    - 192.168.4.254	 192.168.4.255
A11	2	2	192.168.8.0	/30	255.255.255.252	192.168.8.1    - 192.168.8.2	 192.168.8.3
A9	13	14	192.168.16.0	/28	255.255.255.240	192.168.16.1   - 192.168.16.14	 192.168.16.15
A8	502	510	192.168.18.0	/23	255.255.254.0	192.168.18.1   - 192.168.19.254	 192.168.19.255
A10	521	1022	192.168.20.0	/22	255.255.252.0	192.168.20.1   - 192.168.23.254	 192.168.23.255
A7	2	2	192.168.32.0	/30	255.255.255.252	192.168.32.1   - 192.168.32.2	 192.168.32.3
A1	1001	1022	192.168.64.0	/22	255.255.252.0	192.168.64.1   - 192.168.67.254	 192.168.67.255
A5	2021	2046	192.168.128.0	/21	255.255.248.0	192.168.128.1  - 192.168.135.254 192.168.135.255
A6	101	126	192.168.136.0	/25	255.255.255.128	192.168.136.1  - 192.168.136.126 192.168.136.127
A3	2	2	192.168.144.0	/30	255.255.255.252	192.168.144.1  - 192.168.144.2	 192.168.144.3
A4	701	1022	192.168.160.0	/22	255.255.252.0	192.168.160.1  - 192.168.163.254 192.168.163.255
A2	2	2	192.168.192.0	/30	255.255.255.252	192.168.192.1  - 192.168.192.2	 192.168.192.3

192.168.0.0/16
├───192.168.0.0/17
│   ├───192.168.0.0/18
│   │   ├───192.168.0.0/19
│   │   │   ├───192.168.0.0/20
│   │   │   │   ├───192.168.0.0/21
│   │   │   │   │   ├───192.168.0.0/22[A13]
│   │   │   │   │   └───192.168.4.0/24[A12]
│   │   │   │   └───192.168.8.0/30[A11]
│   │   │   └───192.168.16.0/21
│   │   │       ├───192.168.16.0/22
│   │   │       │   ├───192.168.16.0/28[A9]
│   │   │       │   └───192.168.18.0/23[A8]
│   │   │       └───192.168.20.0/22[A10]
│   │   └───192.168.32.0/30[A7]
│   └───192.168.64.0/22[A1]
└───192.168.128.0/17
    ├───192.168.128.0/18
    │   ├───192.168.128.0/19
    │   │   ├───192.168.128.0/20
	│   │   │   ├───192.168.128.0/21[A5]
	│   │   │   └───192.168.136.0/25[A6]
	│   │   └───192.168.144.0/30[A3]
    │   └───192.168.160.0/22[A4]
    └───192.168.192.0/30[A2]

IFCONFIG UML PRO PLUS M1 GAMING EDITION RE:REMASTERED SPECIAL EDITION
                                   #Router
-----------------------------------SURABAYA
auto lo
iface lo inet loopback
#CLOUD
auto eth0
iface eth0 inet static
address 10.151.72.70
netmask 255.255.255.252
gateway 10.151.72.69
#A1
auto eth1
iface eth1 inet static
address 192.168.64.1
netmask 255.255.252.0
#A2
auto eth2
iface eth2 inet static
address 192.168.192.1
netmask 255.255.255.252
#PASURUAN
post-up route add -net 192.168.128.0 netmask 255.255.192.0 gw 192.168.192.2
post-down route del -net 192.168.128.0 netmask 255.255.192.0 gw 192.168.192.2
#A7
auto eth3
iface eth3 inet static
address 192.168.32.1
netmask 255.255.255.252
#BATU
post-up route add -net 192.168.0.0 netmask 255.255.224.0 gw 192.168.32.2
post-down route del -net 192.168.0.0 netmask 255.255.224.0 gw 192.168.32.2
#MALANG
post-up route add -net 10.151.73.136 netmask 255.255.255.252 gw 192.168.32.2
post-down route del -net 10.151.73.136 netmask 255.255.255.252 gw 192.168.32.2
#MOJOKERTO
auto eth4
iface eth4 inet static
address 10.151.73.141
netmask 255.255.255.252

------------------------------------PASURUAN
auto lo
iface lo inet loopback
#A2
auto eth0
iface eth0 inet static
address 192.168.192.2
netmask 255.255.255.252
#WILDCARD
post-up route add -net 0.0.0.0 netmask 0.0.0.0 gw 192.168.192.1
post-down route del -net 0.0.0.0 netmask 0.0.0.0 gw 192.168.192.1
#A3
auto eth1
iface eth1 inet static
address 192.168.144.1
netmask 255.255.255.252
#PROBOLINGGO
post-up route add -net 192.168.128.0 netmask 255.255.224.0 gw 192.168.144.2
post-down route del -net 192.168.128.0 netmask 255.255.224.0 gw 192.168.144.2
#A4
auto eth2
iface eth2 inet static
address 192.168.160.1
netmask 255.255.252.0

-----------------------------------PROBOLINGGO
auto lo
iface lo inet loopback
#A3
auto eth0
iface eth0 inet static
address 192.168.144.2
netmask 255.255.255.252
#WILDCARD
post-up route add -net 0.0.0.0 netmask 0.0.0.0 gw 192.168.144.1
post-down route del -net 0.0.0.0 netmask 0.0.0.0 gw 192.168.144.1
#A5
auto eth1
iface eth1 inet static
address 192.168.128.1
netmask 255.255.248.0
#A6
auto eth2
iface eth2 inet static
address 192.168.136.1
netmask 255.255.255.128

-----------------------------------BATU
auto lo
iface lo inet loopback
#A7
auto eth0
iface eth0 inet static
address 192.168.32.2
netmask 255.255.255.252
#WILDCARD
post-up route add -net 0.0.0.0 netmask 0.0.0.0 gw 192.168.32.1
post-down route del -net 0.0.0.0 netmask 0.0.0.0 gw 192.168.32.1
#A8
auto eth1
iface eth1 inet static
address 192.168.18.1
netmask 255.255.254.0
#MADIUN
post-up route add -net 192.168.16.0 netmask 255.255.255.240 gw 192.168.18.2
post-down route del -net 192.168.16.0 netmask 255.255.255.240 gw 192.168.18.2
#A10
auto eth2
iface eth2 inet static
address 192.168.20.1
netmask 255.255.252.0
#A11
auto eth3
iface eth3 inet static
address 192.168.8.1
netmask 255.255.255.252
#KEDIRI
post-up route add -net 192.168.0.0 netmask 255.255.248.0 gw 192.168.8.2
post-down route del -net 192.168.0.0 netmask 255.255.248.0 gw 192.168.8.2
#MALANG
post-up route add -net 10.151.73.136 netmask 255.255.255.252 gw 192.168.8.2
post-down route del -net 10.151.73.136 netmask 255.255.255.252 gw 192.168.8.2

-----------------------------------MADIUN
auto lo
iface lo inet loopback
#A8
auto eth0
iface eth0 inet static
address 192.168.18.2
netmask 255.255.254.0
#WILDCARD
post-up route add -net 0.0.0.0 netmask 0.0.0.0 gw 192.168.18.1
post-down route del -net 0.0.0.0 netmask 0.0.0.0 gw 192.168.18.1
#A9
auto eth1
iface eth1 inet static
address 192.168.16.1
netmask 255.255.255.240

-----------------------------------KEDIRI
auto lo
iface lo inet loopback
#A11
auto eth0
iface eth0 inet static
address 192.168.8.2
netmask 255.255.255.252
#WILDCARD
post-up route add -net 0.0.0.0 netmask 0.0.0.0 gw 192.168.8.1
post-down route del -net 0.0.0.0 netmask 0.0.0.0 gw 192.168.8.1
#A12
auto eth1
iface eth1 inet static
address 192.168.4.1
netmask 255.255.255.0
#BLITAR
post-up route add -net 192.168.0.0 netmask 255.255.252.0 gw 192.168.4.2
post-down route del -net 192.168.0.0 netmask 255.255.252.0 gw 192.168.4.2
#MALANG
auto eth2
iface eth2 inet static
address 10.151.73.137
netmask 255.255.255.252

-----------------------------------BLITAR
auto lo
iface lo inet loopback
#A12
auto eth0
iface eth0 inet static
address 192.168.4.2
netmask 255.255.255.0
#WILDCARD
post-up route add -net 0.0.0.0 netmask 0.0.0.0 gw 192.168.4.1
post-down route del -net 0.0.0.0 netmask 0.0.0.0 gw 192.168.4.1
#A13
auto eth1
iface eth1 inet static
address 192.168.0.1
netmask 255.255.252.0

                                   # Server
-----------------------------------MOJOKERTO
auto lo
iface lo inet loopback
#SURABAYA
auto eth0
iface eth0 inet static
address 10.151.73.142
netmask 255.255.255.252
gateway 10.151.73.141

-----------------------------------MALANG
auto lo
iface lo inet loopback
#KEDIRI
auto eth0
iface eth0 inet static
address 10.151.73.138
netmask 255.255.255.252
gateway 10.151.73.137

                                   # Client
-----------------------------------SAMPANG
auto lo
iface lo inet loopback
#A1
auto eth0
iface eth0 inet static
address 192.168.64.2
netmask 255.255.252.0
gateway 192.168.64.1

-----------------------------------SIDOARJO
auto lo
iface lo inet loopback
#A4
auto eth0
iface eth0 inet static
address 192.168.160.2
netmask 255.255.252.0
gateway 192.168.160.1

-----------------------------------BANYUWANGI
auto lo
iface lo inet loopback
#A5
auto eth0
iface eth0 inet static
address 192.168.128.3
netmask 255.255.248.0
gateway 192.168.128.1

-----------------------------------JEMBER
auto lo
iface lo inet loopback
#A5
auto eth0
iface eth0 inet static
address 192.168.128.2
netmask 255.255.248.0
gateway 192.168.128.1

-----------------------------------BONDOWOSO
auto lo
iface lo inet loopback
#A6
auto eth0
iface eth0 inet static
address 192.168.136.2
netmask 255.255.255.128
gateway 192.168.136.1

-----------------------------------JOMBANG
auto lo
iface lo inet loopback
#A8
auto eth0
iface eth0 inet static
address 192.168.18.2
netmask 255.255.254.0
gateway 192.168.18.1

-----------------------------------BOJONEGORO
auto lo
iface lo inet loopback
#A9
auto eth0
iface eth0 inet static
address 192.168.16.2
netmask 255.255.255.240
gateway 192.168.16.1

-----------------------------------NGANJUK
auto lo
iface lo inet loopback
#A10
auto eth0
iface eth0 inet static
address 192.168.20.2
netmask 255.255.252.0
gateway 192.168.20.1

-----------------------------------TULUNGAGUNG
auto lo
iface lo inet loopback
#A13
auto eth0
iface eth0 inet static
address 192.168.0.2
netmask 255.255.252.0
gateway 192.168.0.1

-----------------------------------LUMAJANG
auto lo
iface lo inet loopback
#A12
auto eth0
iface eth0 inet static
address 192.168.4.3
netmask 255.255.255.0
gateway 192.168.4.1
