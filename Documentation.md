IP Addressing Table



Chennai Branch



Device| VLAN      | IP Address   | Default Gateway

PC1   | IT (10)   | 192.168.10.11| 192.168.10.1

PC2   | HR (20)   | 192.168.20.11| 192.168.20.1

PC3   | SALES (30)| 192.168.30.11| 192.168.30.1



Coimbatore Branch



Device| VLAN      | IP Address    | Default Gateway

PC4   | IT (10)   | 192.168.110.11| 192.168.110.1

PC5   | HR (20)   | 192.168.120.11| 192.168.120.1

PC6   | SALES (30)| 192.168.130.11| 192.168.130.1



Bangalore Branch



Device| VLAN       | IP Address    | Default Gateway

PC7   | IT (10)    | 192.168.210.11| 192.168.210.1

PC8   | HR (20)    | 192.168.220.11| 192.168.220.1

PC9   | SALES (30) | 192.168.230.11| 192.168.230.1



Router-to-Router Links



Connection| Interface| IP Address

R1 – R2   | R1 G0/1  | 10.0.12.1/30

R1 – R2   | R2 G0/1  | 10.0.12.2/30

R2 – R3   | R2 G0/2  | 10.0.23.1/30

R2 – R3   | R3 G0/1  | 10.0.23.2/30



Subnet Mask: 255.255.255.0 for branch VLANs

Routing Protocol: OSPF

OSPF Area: 0

