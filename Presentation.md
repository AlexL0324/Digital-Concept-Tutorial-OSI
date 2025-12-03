# Layer 6: Presentation Layer

## What It Is:
**The translator and security guard.**
If the Application Layer is the waiter taking your order, the Presentation Layer is the **translator** who makes sure the kitchen understands what you want. This layer is responsible for how data is **presented** or formatted.

---

### Real World Example:
**Sending a secret note in class:**
- You write the note (Application Layer)
- **Translate it into code** so teacher can't read it = Presentation Layer
- Friend receives it and **decodes it** = Also Presentation Layer

---

### What It Does:
1. **Encryption/Decryption** (like HTTPS lock icon)
2. **Compression** (making files smaller)
3. **Formatting** (JPEG for images, MP3 for audio)
4. **Character Encoding**: Handles different text formats (ASCII, Unicode, etc.)

Think of this layer as the **"universal adapter"** of the network world.
---

### Simple Test:
Is data being **encrypted, compressed, or converted** to a different format?  
✅ That's the Presentation Layer.
- A Windows computer and a Mac might store files differently
- One application might use text, another might use binary
- Different databases might structure data differently

When you see `https://` in your browser:
- Your browser encrypts data at the Presentation Layer
- The web server decrypts it at its Presentation Layer
- This keeps your credit card info, passwords, etc. safe
---

**Next:** Now we need to establish the connection.
➡️ [Layer 5: Session Layer](Session.md)

**Previous:** [Layer 7: Application Layer](Application.md)  
[Back to Home](README.md)
