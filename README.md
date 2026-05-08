# Small Enterprise Network with Routing

## 📌 Description

This project is a network simulation built using Cisco Packet Tracer.

The goal was to create a small enterprise network composed of multiple subnets communicating through a router.

This project helped me practice:
- IPv4 addressing
- subnetting
- Cisco router configuration
- inter-subnet routing
- network troubleshooting

---

## 🛠️ Technologies and Tools

- Cisco Packet Tracer
- Cisco IOS CLI
- IPv4
- Subnetting
- Basic static routing

---

## 🌐 Network Topology

The network includes:
- 1 router
- 2 switches
- multiple PCs
- 2 subnets

### Subnets Used

| Network | Address |
|---|---|
| Network A | 192.168.1.0/25 |
| Network B | 192.168.1.128/25 |

---

## ⚙️ Router Configuration

### Interface G0/0

```bash
ip address 192.168.1.1 255.255.255.128
no shutdown```

###Interface G0/1

```bash
ip address 192.168.1.129 255.255.255.128
no shutdown```

##🧪 Tests Performed

###✔️ Interface Verification

```bash
show ip interface brief```

###✔️ Connectivity Test

```bash
ping```

##Screenshots

Network screenshots and test results are available in the screenshots folder.
##📚 Skills Practiced

- Subnetting
- Cisco network configuration
- Network troubleshooting
- Communication analysis
- Understanding gateway behavior

##🚀 Author

Project created by Emmanuel as part of his networking and cybersecurity learning journey.
