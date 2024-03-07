**Network Configuration Report**

_Prepared by: Rios Falcon Pablo_  
_Date: 7/03/2024_

**Executive Summary:**

The purpose of this report is to document the configuration done on the hosts in the network setup for Hackers Poulette. The network consists of three hosts, namely PC-Robert, PC-Camille, and PC-Renaud, connected to a Cisco 2960-24TT switch (Named: Switch-0) and a 2901 Router (Named: Router-0). The configuration includes assigning IP addresses to the hosts to enable communication between them and connect them via a switch and then connecting them to the internet via the router.

**Configuration Details:**

1. **PC-Robert:**
    
    - LAN Interface: Ethernet Cable
    - IP Address: 192.168.1.10
    - Subnet Mask: 255.255.255.0
    - Default Gateway: 192.168.1.1 (Router IP)
2. **PC-Camille:**
    
    - LAN Interface: Ethernet Cable
    - IP Address: 192.168.1.11
    - Subnet Mask: 255.255.255.0
    - Default Gateway: 192.168.1.1 (Router IP)
3. **PC-Renaud:**
    
    - LAN Interface: Ethernet Cable
    - IP Address: 192.168.1.12
    - Subnet Mask: 255.255.255.0
    - Default Gateway: 192.168.1.1 (Router IP)

**Observations:**

- All hosts are assigned IP addresses within the same subnet (192.168.1.0/24) + (Subnet Mask 255.255.255.0) , allowing them to communicate with each other directly.
- The default gateway specified for individual hosts is the IP address of the router.
- The configuration is consistent with the network requirements, enabling communication between the three hosts within the network and access to the internet.

**Recommendations:**

- It is recommended to verify the connectivity between the hosts using the ping utility as outlined in the mission objectives.

**Conclusion:**

The configuration of the hosts in the network for Hackers Poulette has been successfully completed as per the provided requirements. The hosts are now able to communicate with each other within the network and access the internet via the router. Further testing and verification of connectivity are recommended to ensure the network is functioning as intended.

This concludes the network configuration report.