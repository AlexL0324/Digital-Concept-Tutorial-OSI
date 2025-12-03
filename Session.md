# Layer 5: Session Layer

## What It Is:
**The connection manager.**
If you think of network communication as a phone call, the Session Layer is the **operator** who sets up the call, maintains the connection, and properly ends the call. It manages the "conversations" between applications.
---

### Real World Example:
**Making a phone call:**
- **Dialing and connecting** = Session Layer
- **Keeping the call alive** = Session Layer
- **Hanging up properly** = Session Layer

---

### What It Does:
1. Starts conversations between apps
2. Keeps them connected
3. Ends them cleanly
4. Can restart if disconnected

---

### Simple Test:
Are apps **starting, maintaining, or ending** a connection?  
✅ That's the Session Layer.

### 1. Session Establishment
Before data can flow, applications need to agree to communicate. The Session Layer handles this "handshake" process.

### 2. Dialog Control
Determines who can talk when:
- **Half-duplex**: Like a walkie-talkie (one talks at a time)
- **Full-duplex**: Like a phone call (both can talk simultaneously)

### 3. Synchronization
Adds "checkpoints" in data transfer:
- If a connection fails, it can resume from the last checkpoint
- Like saving a game - you don't start from the beginning if you lose connection

### 4. Session Termination
Properly ends conversations so resources are freed up.

---

**Next:** Now we need to ensure reliable delivery.
➡️ [Layer 4: Transport Layer](Transport.md)

**Previous:** [Layer 6: Presentation Layer](Presentation.md)  
[Back to Home](README.md)
