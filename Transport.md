# Layer 4: Transport Layer

## What It Is:
**The delivery guarantee.**
If data packets were packages being shipped across the country, the Transport Layer would be the **shipping company's quality control**. It ensures packages arrive:
- In the right order
- Without damage
- Not missing any pieces
- At the correct destination
---

### Real World Example:
**Shipping a fragile package:**
- **Tracking number** = Transport Layer
- **Insurance** = Transport Layer
- **"Fragile" sticker** = Transport Layer
- **Confirming delivery** = Transport Layer

---

### Two Main Types:
### TCP (Transmission Control Protocol) - The Careful Courier
- **Connection-oriented**: Establishes connection first (like calling before sending a package)
- **Reliable**: Guarantees delivery with error checking
- **Slower but safer**: Used for web pages, email, file downloads
- **Features**: Acknowledgement system, retransmission if needed

### UDP (User Datagram Protocol) - The Speedy Messenger
- **Connectionless**: Sends data without establishing connection first
- **Unreliable**: No guarantee of delivery
- **Faster**: Used for live video, gaming, VoIP
- **Features**: No acknowledgement, just sends and hopes for the best
---

### Simple Test:
Is data being **checked for errors** or **tracked** for delivery?  
✅ That's the Transport Layer.

### 1. The Transport Layer uses **port numbers** to identify which application should receive data:
- **Web server**: Port 80 (HTTP) or 443 (HTTPS)
- **Email**: Port 25 (SMTP), 110 (POP3), 143 (IMAP)
- **DNS**: Port 53

Think of an apartment building:
- IP Address = Building address
- Port Number = Apartment number

### 2. Segmentation
Large files are broken into smaller **segments** (TCP) or **datagrams** (UDP) for transmission.

### 3. Flow Control
Prevents fast senders from overwhelming slow receivers (like a water faucet controlling flow).

### 4. Error Checking
Uses checksums to detect if data was corrupted during transmission.

---

**Next:** Now we need addresses for delivery.
➡️ [Layer 3: Network Layer](Network.md)

**Previous:** [Layer 5: Session Layer](Session.md)  
[Back to Home](README.md)
