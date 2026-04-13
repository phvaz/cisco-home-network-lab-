# cisco-home-network-lab-
Simulation of a home network using Cisco Packet Tracer, covering wired and wireless connectivity, DHCP configuration, router setup via GUI, and WPA2-secured Wi-Fi. The project demonstrates fundamental networking concepts such as IP addressing, default gateway, DNS resolution, and device connectivity validation.

# Home Network Configuration Lab (Cisco Packet Tracer)

## Overview

This project simulates the design and configuration of a small home network using Cisco Packet Tracer.  
The objective was to implement a fully functional wired and wireless network with internet connectivity, DHCP configuration, and secure Wi-Fi access.

The scenario is based on a residential environment where multiple devices must communicate locally and access external networks securely.

---

## Objectives

- Connect end devices using appropriate cabling (coaxial and Ethernet)
- Configure a home wireless router via GUI
- Set up DHCP with limited client allocation
- Configure wireless LAN (SSID and WPA2 security)
- Validate network connectivity and internet access

---

## Network Topology

The network consists of:

- Cable Modem (ISP connection)
- Cable Splitter (TV and internet distribution)
- Home Wireless Router (central network device)
- Wired hosts (Office PC and Bedroom PC)
- Wireless client (Laptop)

### Logical Flow
Internet → Cable Modem → Home Router → End Devices (wired & wireless)

---

## Key Configurations

### 1. Physical Connectivity
- Coaxial cable used between ISP, splitter, modem, and TV
- Ethernet (Copper Straight-Through) used for LAN connections

---

### 2. Router Configuration (DHCP & Security)

- DHCP enabled on router
- Maximum DHCP users limited to **10 devices**
- Default administrator credentials replaced with:

Username: admin
Password: MyPassword1!


---

### 3. Wireless LAN Configuration

- SSID: `MyHome`
- Security: WPA2-Personal
- Passphrase: `MyPassPhrase1!`

---

## Connectivity Tests

The following validations were performed:

- Office PC → Internet access verified via `skillsforall.srv`
- Laptop → Wireless connection successful (SSID MyHome)
- Bedroom PC → DHCP configuration + internet access confirmed

---

## Key Concepts Demonstrated

- DHCP (Dynamic Host Configuration Protocol)
- Default Gateway routing
- DNS resolution
- LAN vs WLAN architecture
- Wireless security (WPA2)
- Network troubleshooting in simulated environments

---

## Screenshots

> Insert screenshots here for visual validation:

- Network topology overview
- DHCP configuration screen
- Wireless security setup
- Successful connectivity test

---

## File

- `lab-natsumi-home-network.pka` → Packet Tracer activity file containing full configuration

---

## Conclusion

This lab demonstrates the successful implementation of a secure and functional home network, integrating wired and wireless connectivity with proper DHCP configuration and internet access validation.

All devices were successfully connected and able to access external network resources.
