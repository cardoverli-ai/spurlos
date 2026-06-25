# 👻 Spurlos

### *Files without a trace.*

> Ghost-grade P2P file transfer. No servers store your files. No identities required. No traces remain.

---

## 🚀 Live

- **App:** [spurlos.pages.dev](https://spurlos.pages.dev)
- **Signaling:** [cardoverli-spurlos.hf.space](https://cardoverli-spurlos.hf.space)

---

## 🥷 What is Spurlos?

Spurlos is a decentralized, end-to-end encrypted peer-to-peer file sharing application built for true ghost-grade privacy.

- **No servers store files** — files travel directly peer-to-peer via WebRTC
- **No identities required** — users are identified by a 12-word mnemonic they control
- **No traces remain** — the signaling server is ephemeral, RAM-only, zero-log
- **Nothing to hide** — the code is open-source. Security comes from keys, not obscurity

---

## 🔐 Core Features

- 12-word BIP-39 mnemonic identity (Ed25519 keypair)
- AES-256-GCM encryption via native WebCrypto (non-extractable keys)
- ECDH key exchange (P-256)
- OPFS direct-to-disk piping (handles 50GB+ files without RAM crash)
- Adaptive chunk sizing (512KB–4MB)
- SHA-256 integrity verification per chunk
- 6-digit pairing code system (60s TTL, one-time use)
- QR air-gap handshake (planned)
- Light + dark theme with liquid glass aesthetic

---

## 🛡️ Ghost Features

- Duress seed phrase (fake dashboard with dummy files)
- Brute-force self-shredder (3-strike PIN)
- Save Device fingerprint (trusted device badge)
- Decoy traffic injector (defeats timing correlation)
- Self-combusting viewer (auto-shred after N views)
- Dead Man's Switch transfer (auto-release on heartbeat failure)
- Bifurcated Key Escrow (Shamir 2-of-2)
- Acoustic Fingerprint Pairing (ultrasonic)

---

## 🏗️ Tech Stack

- **Frontend:** Next.js 16 + TypeScript + Tailwind CSS 4 + shadcn/ui
- **Crypto:** @noble/curves, @scure/bip39, native WebCrypto API
- **P2P:** WebRTC (native browser API)
- **Signaling:** Bun + WebSocket (Hugging Face Space, zero-log)
- **Hosting:** Cloudflare Pages (frontend) + Hugging Face Space (signaling)

---

## 💜 Support

Spurlos is free, forever. No ads. No tracking. No fiat.

If this tool protects your privacy, fuel it with crypto:
- **BTC:** `bc1q469lctvgrda72vvld3s8r7xh4zyr9hg4ckl9c3`
- **SOL:** `BzSzWw4z1PEXDJ83RPsK5AfXkTAKcGmiaVoPWhoQ8Utp`
- **USDT (TRC-20):** `TUNZPBxT4bbM6dWATafQEhd42Umh1GFEZe`
- **LTC:** `ltc1q2tww65rx786kz0zs3nh3a3nryuhtwpcl60n9wc`

---

## 📄 License

MIT — see [LICENSE](LICENSE)

---

*Spurlos — Disappear your files, not your privacy.*
