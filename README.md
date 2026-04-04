# Cisco-Packet-Tracer-project-02-SOHO-Network-Lab-Server-Laptop-3-PCs-Cisco-Switch-

I’m excited to share a clean, fundamental networking project – a SOHO (Small Office / Home Office) network built in Cisco Packet Tracer. The topology includes a Cisco 2960‑24TT switch, a server (Server0), a laptop (Laptop0), and three desktop PCs (PC0, PC1, PC2).

![image alt](https://github.com/Sameera54321/Multi-Switch-LAN-with-Servers-PCs-Cisco-2960-Switches-Packet-Tracer-/blob/main/21.png?raw=true)

## 📌 Summary

SOHO Network Lab is a Cisco Packet Tracer simulation that models a small office or home office environment. The topology includes:

    1 switch – Cisco 2960‑24TT (Switch0)

    1 server – Server0 (can provide DHCP, DNS, web, or file services)

    1 laptop – Laptop0 (wireless or wired, depending on configuration)

    3 desktop PCs – PC0, PC1, PC2

### Typical IP addressing :

| Device | IP Address | Subnet Mask | Default Gateway |
| :--- | :--- | :--- | :--- |
| Server0 | 192.168.1.10 | 255.255.255.0 | 192.168.1.1 |
| Laptop0 | 192.168.1.11 | 255.255.255.0 | 192.168.1.1 |
| PC0 | 192.168.1.12 | 255.255.255.0 | 192.168.1.1 |
| PC1 | 192.168.1.13 | 255.255.255.0 | 192.168.1.1 |
| PC2 | 192.168.1.14 | 255.255.255.0 | 192.168.1.1 |

(If no router is present, all devices must be in the same subnet. A router can be added for external connectivity.)

### Key configurations:

    Switch – basic settings (hostname, management IP optional)

    Server – enable DHCP to automatically assign IPs to clients, or set static IPs on all devices

    Clients – test connectivity to server (ping, web browser, FTP)

### Verification:
ping 192.168.1.10 from any PC/laptop should succeed if all are in the same subnet and switch is correctly connected.

## ✨ Features

    ✅ 1 Cisco 2960 switch – Layer 2 connectivity

    ✅ 1 server – can run DHCP, DNS, HTTP, FTP

    ✅ 1 laptop + 3 PCs – multiple client devices

    ✅ Full Packet Tracer file (.pkt) – ready to open and experiment

    ✅ Documentation – IP plan, switch config, server setup

## 🛠️ Built With

    Cisco Packet Tracer – version 8.x

    CLI – switch and server configurations

## 🤝 Contributing

Contributions are welcome! To extend this lab:

    Fork the repository.

    Add a router for inter‑VLAN routing or internet access.

    Implement VLANs to separate traffic (e.g., guest Wi‑Fi).

    Configure port security and SSH on the switch.

    Add a wireless access point for the laptop.

    Open a pull request with a clear description.

## 📜 License

Distributed under the MIT License. See the LICENSE file for more information.
Free to use, modify, and share for educational purposes.
