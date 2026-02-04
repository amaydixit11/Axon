# Axon

Axon is a serverless, peer-to-peer file sharing system built on ACORDE. It allows users to send large files securely without relying on cloud storage.

No accounts. No servers. No tracking.

## ✨ Features

- Encrypted file transfer
- Content-addressed storage
- Secure invite links
- Expiry-based sharing
- Folder sync
- Version history
- Offline support

## 🏗 Architecture

- Transport: libp2p
- Storage: ACORDE blob store
- Encryption: XChaCha20-Poly1305

## 🚀 Getting Started

```bash
git clone https://github.com/amaydixit11/axon
cd axon
npm install
npm run start
````

## 🔐 Security

* End-to-end encryption
* Device-based authentication
* No centralized metadata

## 📦 Roadmap

* Resume transfers
* Multi-recipient sharing
* Web client
* Mobile app
