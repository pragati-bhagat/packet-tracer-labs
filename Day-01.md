# Day 1 - Basic LAN

## Objective

Build a simple LAN using Cisco Packet Tracer.

---

## Network Topology

PC0 ---- Cisco 2960 Switch ---- PC1

---

## Devices Used

- Cisco 2960 Switch
- PC0
- PC1

---

## IP Addressing

| Device | IP Address | Subnet Mask |
|---------|------------|-------------|
| PC0 | 192.168.1.10 | 255.255.255.0 |
| PC1 | 192.168.1.11 | 255.255.255.0 |

---

## Testing

Command:

```bash
ping 192.168.1.11
```

Result:

Successful communication between PC0 and PC1.

---

## Troubleshooting

Changed PC1 IP to:

192.168.2.11

Result:

Ping failed because both devices were on different subnets and there was no router to route traffic.

After changing the IP back to 192.168.1.11, connectivity was restored.

---

## What I Learned

- What is a LAN
- Cisco 2960 Switch
- IPv4 Addressing
- Subnet Mask
- Ping
- Basic Network Troubleshooting
