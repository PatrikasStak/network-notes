# network-notes

My notes from learning networking and network automation, from the fundamentals up to BGP, automation and monitoring. Everything is written in my own words, while I learn it.

**Goal:** junior network / infrastructure engineer, ready by February 2027.

## Structure

```
network-notes/
├── 01-fundamentals/     # OSI/TCP-IP, Ethernet, ARP, switching, IPv4/IPv6, subnetting, VLANs, routing
├── 02-linux-networking/ # ip, ss, tcpdump, nftables, network namespaces
├── 03-bgp/              # BGP, peering, transit, IXPs, RPKI
├── 04-automation/       # Python, Ansible, Jinja2, NetBox
├── 05-monitoring/       # Prometheus, Grafana, sFlow, DDoS
├── labs/                # Packet Tracer files, captures (.pcap), lab configs
└── cheatsheets/         # quick-reference commands
```

## Progress

| Phase | Topic | Status |
| --- | --- | --- |
| 1 | Networking fundamentals | 🔄 In progress |
| 1 | Linux networking | ⬜ |
| 2 | BGP + peering | ⬜ |
| 3 | Automation (Python / Ansible / NetBox) | ⬜ |
| 4 | Monitoring + DDoS | ⬜ |

## Projects

| Project | What it shows |
| --- | --- |
| [linux-netns-lab](#) | Routing + NAT between Linux network namespaces |
| [bgp-peering-lab](#) | Multi-AS BGP lab with an IXP route server in containerlab |
| [netbox-to-network](#) | NetBox → Jinja2 → Ansible config pipeline |
| [network-observability-lab](#) | Prometheus/Grafana + sFlow flood detection |

## How I write notes

- One topic per file, written in my own words, not copy-paste
- Every note ends with a **"How I'd explain it in an interview"** section
- Commands I actually ran go in code blocks, with their output where it's useful
- Mistakes and what fixed them go under **"Gotchas"**

## Resources

- [Jeremy's IT Lab: free CCNA course](https://www.youtube.com/@JeremysITLab)
- [subnettingpractice.com](https://subnettingpractice.com)
- [containerlab](https://containerlab.dev) · [FRRouting docs](https://docs.frrouting.org)
- [NetBox docs](https://netboxlabs.com/docs/netbox/) · [Ansible docs](https://docs.ansible.com)
- [Prometheus](https://prometheus.io/docs/) · [Grafana](https://grafana.com/docs/)
- [bgp.he.net](https://bgp.he.net) · [PeeringDB](https://www.peeringdb.com)
