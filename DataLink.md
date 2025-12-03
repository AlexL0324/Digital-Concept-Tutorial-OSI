# Layer 2: Data Link Layer

## What It Is:
**The local mail carrier.**
If the Network Layer is the postal system that gets mail between cities, the Data Link Layer is the **local mail carrier** who delivers mail to specific houses on your street. It handles communication **within the same local network**.
---

### Real World Example:
**Delivering mail in your neighborhood:**
- **Mail truck on your street** = Data Link Layer
- **Putting mail in correct mailbox** = Data Link Layer
- **Checking for damaged letters** = Data Link Layer

---

### Key Player: The Switch
- **Switch** = Apartment building mail sorter
- Uses **MAC addresses** (like 00:1A:2B:3C:4D:5E)
- Only works **within same network**
- Delivers to **specific devices**

---

### What It Does:
1. **Physical Addressing**: Uses MAC addresses to identify devices
2. **Local Delivery**: Gets data to specific devices on the same network
3. **Error Detection**: Checks for errors in received frames
4. **Access Control**: Manages who can transmit on shared media

This layer creates a **reliable link** between two directly connected devices.

---

### Simple Test:
Is data being delivered to **specific device on same network** using **MAC addresses**?  
✅ That's the Data Link Layer.

The Data Link Layer is divided into two sublayers:

### 1. LLC (Logical Link Control) - Upper Sublayer
- Talks to the Network Layer above
- Manages frame synchronization, flow control, error checking

### 2. MAC (Media Access Control) - Lower Sublayer
- Talks to the Physical Layer below
- Handles physical addressing (MAC addresses)
- Controls access to shared media (Ethernet, Wi-Fi)

---

## MAC Addresses: The Physical ID

- **48-bit unique identifier** (e.g., 00:1A:2B:3C:4D:5E)
- Burned into network interface card (NIC) at factory
- **First 24 bits**: Manufacturer ID (OUI)
- **Last 24 bits**: Unique device ID
- Like a car's VIN number - unique to each device

### MAC vs. IP Addresses:
- **MAC**: Physical, permanent, Layer 2, local network only
- **IP**: Logical, changeable, Layer 3, works across networks
---

**Next:** Finally, the actual physical transmission.
➡️ [Layer 1: Physical Layer](Physical.md)

**Previous:** [Layer 3: Network Layer](Network.md)  
[Back to Home](README.md)
