========================================================================
CCNP ENTERPRISE NETWORK SIMULATION - ADVANCED ROUTING LAB
========================================================================

1. PROJECT OVERVIEW
------------------------------------------------------------------------
This project simulates a large-scale Enterprise Network designed to practice 
advanced routing techniques within the CCNP curriculum. The system connects 
multiple branch sites to a Core backbone and simulates Internet connectivity 
through multi-homed ISPs.

Key technologies and protocols implemented:
- Interior Gateway Protocols (IGP): OSPF Multi-Area, EIGRP, RIPv2.
- Exterior Gateway Protocol (EGP): BGP (Multi-homed ISP connection).
- Routing Optimization: Route Redistribution, OSPF Stub/Totally Stub/NSSA Areas.
- Connectivity & Redundancy: GRE Tunneling, HSRP (High Availability).

2. FILE LIST AND DESCRIPTIONS
------------------------------------------------------------------------
Below are the details of the files included in this project folder:

[+] Diagram.png
    -> Network Topology Map.
       Provides a visual overview of the entire system, including routing Zones 
       (Areas) and protocols used at each Site (Middle, Upper, Right, Bottom, Left).

[+] IP table.pdf
    -> IP Addressing Plan.
       A comprehensive document listing Interfaces, IP Addresses, Subnet Masks, 
       and Gateways for all 17 Routers in the system. Use this for reference 
       during configuration.

[+] Network_Implementation_Plan.pdf
    -> Step-by-Step Implementation Guide.
       Detailed instructions following a 5-phase deployment process:
       - Phase 1: Basic Connectivity (L1/L2).
       - Phase 2: IGP Setup (OSPF, EIGRP, RIP).
       - Phase 3: Redistribution, GRE Tunnel & Optimization.
       - Phase 4: BGP Architecture.
       - Phase 5: HSRP & Redundancy.

[+] Config.txt
    -> Full Configuration Script (CLI).
       Contains the complete, standard configuration commands for every device 
       (R1 to R17). The code is optimized and includes necessary fixes for 
       GRE Tunnel stability and Routing Loops. Ready to copy/paste.

[+] EVE-NG.zip
    -> Lab Source File (UNETLAB export).
       This is the source file to import into your EVE-NG (or PNETLab) server 
       to replicate the exact environment shown in the Diagram.

3. QUICK START GUIDE
------------------------------------------------------------------------
1. Import the 'EVE-NG.zip' file into your EVE-NG server.
2. Refer to 'Diagram.png' and 'IP table.pdf' to understand the addressing scheme.
3. Use 'Config.txt' to apply configurations to the Routers.
4. Read 'Network_Implementation_Plan.pdf' to understand the design logic and 
   verification steps.

========================================================================
Thank you for checking out this project.

Hope it helpful :)