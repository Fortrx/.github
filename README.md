# 🛡️ Welcome to Fortrx

**Post-Quantum-Resistant Double Ratchet + X3DH Secure Communication System**

Welcome to **Fortrx LLC**, an open-source, highly secure end-to-end encrypted messaging engine built to withstand the cryptographic challenges of the post-quantum era. Our system provides seamless, local-first, terminal-based messaging with robust security protocols.

---

## 📦 Our Repositories

The Fortrx ecosystem is primarily divided into two main components:

### [🖥️ Fortrx-Server](https://github.com/Fortrx/Fortrx-Server)
The backbone of the secure communication engine. 
- Facilitates **Post-Quantum-Resistant Double Ratchet** + **X3DH** key exchanges.
- Handles encrypted message routing, user presence, and live delivery.
- **Tech Stack:** Python, Redis (for live delivery/presence), Alembic (DB migrations), Docker.

### [💻 Fortrx-Client](https://github.com/Fortrx/Fortrx-Client)
The encrypted terminal interface for the Fortrx messaging system.
- **End-to-End Encryption:** X3DH / PQXDH-style session bootstrap.
- **Local-First & Offline:** Chat history is stored in a locally encrypted database (SQLCipher) allowing you to read synced conversations without an internet connection.
- **Background Daemon:** Runs silently in the background for inbox sync, live delivery, and WebSocket listening.
- **Tech Stack:** Python 3.11+, SQLCipher.

---

## 🔐 Architecture & Security Model

Fortrx is built with zero-trust principles at its core:
- **Post-Quantum Cryptography (PQC):** Ensures that communications remain secure against "harvest now, decrypt later" attacks utilizing future quantum computers.
- **Double Ratchet Algorithm:** Guarantees **Perfect Forward Secrecy (PFS)** and **Post-Compromise Security (PCS)** by rotating keys after every message exchange.
- **Local Database Encryption:** Private keys, ratchet sessions, and chat histories never leave your device unencrypted.

---

## ⚡ Quick Start

To experience the Fortrx ecosystem, you will need to run the server and connect to it using the client.

### 1. Clone the Projects
```bash
git clone https://github.com/Fortrx/Fortrx-Server.git
git clone https://github.com/Fortrx/Fortrx-Client.git
