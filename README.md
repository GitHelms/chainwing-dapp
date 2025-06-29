# 🚁 ChainWing DApp

![License: MIT](https://img.shields.io/badge/license-MIT-green.svg)
![Solana](https://img.shields.io/badge/built%20on-Solana-blueviolet)
![Status: MVP](https://img.shields.io/badge/status-MVP--Phase-yellow)

> **ChainWing** is an open-source DApp for decentralized drone services — built with Solana, NFT verification, and tokenized payments via CWT.

---

## 🌍 Vision

We're building a decentralized platform for drone operations.  
Our mission is to enable trustless coordination between project owners and drone pilots — powered by blockchain, automation, and real-world utility.

---

## 🔑 Core Features

- 🪙 **Solana Wallet Login** – secure and fast user onboarding
- 🎖️ **NFT Pilot Certification** – verify licenses, drone type, region & insurance
- 📋 **Mission Board** – clients publish drone jobs, pilots apply via wallet
- 💸 **CWT Payments & Staking** – fast, transparent, and programmable
- 🛠️ **Onboarding Forms** – tailored data capture for clients and pilots
- 🛰️ **Future: DAO governance, autonomous drone hubs, AI agent workflows**

---

## 🧱 Tech Stack

| Layer      | Tools                                        |
|------------|----------------------------------------------|
| Frontend   | Next.js, Tailwind CSS, Wallet Adapter        |
| Backend    | Supabase (PostgreSQL, Auth, Edge Functions)  |
| Blockchain | Solana, Anchor, Metaplex Token Metadata      |
| DevOps     | GitHub Actions, Cloudflare Pages             |

---

## 📦 Project Structure

```bash
chainwing-dapp/
├── frontend/           # Next.js app with wallet login & mission UI
├── backend/            # Supabase logic, schema definitions
├── onchain/            # Solana smart contracts (Anchor)
├── idl/                # Auto-generated Anchor IDLs for frontend integration
├── nft-metadata/       # Pilot NFT metadata (JSON)
├── tokenomics/         # CWT token logic & reward strategy
├── scripts/            # Dev & deployment utilities
├── docs/               # Architecture, vision & planning
└── .github/workflows/  # GitHub Actions for CI/CD
