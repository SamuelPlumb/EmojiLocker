# 🔐 EmojiLocker

EmojiLocker is a **zero-backend, client-side emoji messenger** that encrypts your messages using AES-GCM (256-bit) in the browser and encodes them into a string of emojis for sharing.  
No servers, no accounts — your encryption keys never leave your device.

---

## 🚀 Features

- **Client-Side Encryption** – All encryption/decryption happens in your browser.
- **Emoji-Based Encoding** – Messages are represented as emoji strings for easy sharing.
- **No Backend Required** – Works entirely offline once loaded.
- **Secure by Design** – AES-GCM 256-bit encryption using the Web Crypto API.

---

## 📖 How It Works

1. **Write a message** → EmojiLocker encrypts it with a randomly generated key.
2. **Copy the emoji string** → Send it over any channel (chat, email, social media).
3. **Recipient enters the emoji string + key** → The message is decrypted locally.

---

## 🛠️ Technologies Used

- HTML5, CSS3, JavaScript
- AES-GCM Encryption (Web Crypto API)
- Emoji-based Base64 encoding

---

## 💻 Running Locally

1. **Clone this repository**:
   ```bash
   git clone https://github.com/SamuelPlumb/EmojiLocker.git
