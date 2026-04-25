## Hey, this is Fortrx 👋
<p align="center">
  <img src="https://raw.githubusercontent.com/Fortrx/.github/main/assets/profile.png" alt="Profile Image" width="100%"/>
<img src="https://api.visitorbadge.io/api/visitors?path=fortrx&countColor=%23f47373&style=for-the-badge" alt="Visitor Count">

Yes, we are building the future of secure communication. **Fortrx** is an open-source, highly secure end-to-end encrypted messaging engine built to withstand the cryptographic challenges of the post-quantum era. We provide seamless, local-first, terminal-based messaging with robust security protocols. 🔐

### 📦 Our Ecosystem

The Fortrx ecosystem is primarily divided into two main components that work together to provide a zero-trust environment:

- [🖥️ Fortrx-Server](https://github.com/Fortrx/Fortrx-Server) - The backbone of the secure communication engine, facilitating **Post-Quantum-Resistant Double Ratchet** + **X3DH** key exchanges.
- [💻 Fortrx-Client](https://github.com/Fortrx/Fortrx-Client) - The encrypted terminal interface, featuring local-first chat history and a background daemon for seamless syncing.

### 🔐 Architecture & Security Model

Fortrx is built with zero-trust principles at its core. See how we protect your data:

- **Post-Quantum Cryptography (PQC):** Ensures that communications remain secure against "harvest now, decrypt later" attacks utilizing future quantum computers. 🛡️
- **Double Ratchet Algorithm:** Guarantees **Perfect Forward Secrecy (PFS)** and **Post-Compromise Security (PCS)** by rotating keys after every message exchange. 🔄
- **Local Database Encryption:** Private keys, ratchet sessions, and chat histories never leave your device unencrypted. 🔒

### 👓 Appendix

We welcome contributions! 🤝 Please check the individual repositories for specific contribution guidelines and issue trackers.

<details> 
	<summary>"Tell me more about the Tech Stack!"</summary>
	<br>
	<ul>
	<li>The <strong>Fortrx-Server</strong> is built using mighty 🔨 open source technologies like <a href="https://fastapi.tiangolo.com/">FastAPI</a>, <a href="https://www.postgresql.org/">PostgreSQL</a>, <a href="https://redis.io/">Redis</a>, and <a href="https://min.io/">MinIO</a>.</li>
		<li>The <strong>Fortrx-Client</strong> utilizes <a href="https://www.python.org/">Python 3.11+</a> and <a href="https://www.zetetic.net/sqlcipher/">SQLCipher</a> for robust local encryption.</li>
	</ul>
</details>

---
<sub>Fortrx is open-source software. Please refer to the individual repositories for licensing details.</sub>
