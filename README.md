# DATA-CENTER

Case study of a data center network architecture (ENSEEIHT, *Réseaux locaux* course, 2025).

The report (`RL.pdf`, in French) describes each layer, its role, protocols, link speeds and MTU:
- **Border routers** – BGP peering with ISPs, 100–400 Gbps uplinks
- **Core switches** – redundant backbone, jumbo frames (MTU 9000)
- **Aggregation / access switches** – server connectivity
- **Web tier** – public-facing HTTP/HTTPS servers and proxies
- **Application tier** – business apps and APIs on isolated VLANs / subnets
