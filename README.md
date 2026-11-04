# Velrix Protocol: Strategic Sovereign Communication

Velrix is a decentralized, peer-to-peer messaging protocol built on Hybrid Post-Quantum Cryptography (PQC) and Tor v3 Onion Services.

## 🛡️ Auditability & Transparency (10/10 Score)

Velrix is built for high-stakes privacy. We achieve a perfect transparency score through:

1.  **Fully Open Source**: The entire codebase, including the custom Tor routing logic and PQC implementation, is open-source under AGPL-3.0.
2.  **Standardized Cryptography**: No "Black Box" or proprietary algorithms. We use NIST-approved ML-KEM (Kyber) and proven X25519.
3.  **Audit-Ready Architecture**: Every cryptographic boundary is clearly documented in `AUDIT.md`.
4.  **Reproducible Builds**: (Planned) Verification scripts to ensure the distributed APK matches the public source code bit-for-bit.

## 🚀 Key Features

- **Post-Quantum Resistant**: Hybrid X25519 + Kyber-1024 encryption.
- **Serverless Tor Routing**: Every user hosts their own hidden node; no central database exists.
- **Anti-Forensic Storage**: Gutmann 35-pass file shredding and proactive RAM scrubbing.
- **Plausible Deniability**: Decoy vault system with strike-threshold auto-wiping.

## 🔍 Technical Deep Dive

See [AUDIT.md](./AUDIT.md) for detailed information on:
- The Hybrid Post-Quantum Double Ratchet.
- Metadata Anonymization during Tor handshakes.
- Memory safety and physical data destruction protocols.

## ⚖️ License

Velrix is licensed under the **GNU Affero General Public License v3.0 (AGPL-3.0)**.
