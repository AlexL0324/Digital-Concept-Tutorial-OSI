# Layer 3: Network Layer

## What It Is:
**The Internet's postal system.**
If the Transport Layer is like a shipping company that ensures packages arrive safely, the Network Layer is like the **entire postal system** that figures out how to get those packages from one city to another, across different transportation networks.
---

### Real World Example:
**Sending a letter across the country:**
- **Writing address on envelope** = Network Layer
- **Post office sorting** = Network Layer
- **Choosing planes/trucks** = Network Layer

---

### Key Player: The Router
1. **Logical Addressing**: Uses IP addresses to identify devices
2. **Path Determination**: Finds the best route between networks
3. **Routing**: Directs packets along the chosen path
4. **Internetworking**: Connects different networks together

This layer makes the **Internet** possible by connecting millions of separate networks.

---

### What It Does:
1. Uses IP addresses
2. Routes between networks
3. Finds best paths
4. Gets data across the Internet

---

### Simple Test:
Is data moving **between different networks** using **IP addresses**?  
✅ That's the Network Layer.

### 1. IP Addresses
- **Logical addresses** assigned to devices (not physical like MAC addresses)
- Two versions: IPv4 (192.168.1.1) and IPv6 (2001:0db8:85a3::)
- Like your home address in the real world

### 2. Routing
- Routers examine destination IP addresses
- Use routing tables (like road maps) to determine next hop
- Can choose between multiple paths

### 3. Packet Forwarding
- Moving packets from incoming interface to outgoing interface
- Based on routing table decisions

### 4. Fragmentation
- Breaks packets into smaller pieces if needed for different network types
- Reassembles at destination

---

## The Star of Layer 3: The Router

**Routers are Network Layer devices** that:
- Connect different networks together
- Make decisions based on IP addresses
- Maintain routing tables
- Direct traffic between networks

Think of routers as **internet traffic cops** at intersections between networks.
---

**Next:** Now we need local delivery.
➡️ [Layer 2: Data Link Layer](DataLink.md)

**Previous:** [Layer 4: Transport Layer](Transport.md)  
[Back to Home](README.md)
