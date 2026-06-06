OSPF Single Area (4 Routers + Multiple Networks)

This lab adds:
--------------------------------
4 routers

Multiple networks

OSPF adjacency

Loopbacks

Verification with show commands

PCs in different networks

IP Addressing Plan
--------------------------------
R1–R2 Link

R1 g0/1: 10.1.12.1/24

R2 g0/1: 10.1.12.2/24

R1–R3 Link

R1 g0/2: 10.1.13.1/24

R3 g0/1: 10.1.13.2/24

R2–R4 Link

R2 g0/2: 10.1.24.2/24

R4 g0/1: 10.1.24.4/24

R3–R4 Link

R3 g0/2: 10.1.34.3/24

R4 g0/2: 10.1.34.4/24

Loopbacks (act as LAN networks)
--------------------------------
R1: 1.1.1.1/32

R2: 2.2.2.2/32

R3: 3.3.3.3/32

R4: 4.4.4.4/32
