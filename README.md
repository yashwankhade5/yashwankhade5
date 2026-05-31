<div align="center">

# Yash Wankhade

### Solana Smart Contract Engineer · Full-Stack · Rust · Anchor

*Turbine3 Accelerated Builder Q2 2026 · Colosseum Hackathon Builder*

[![Twitter](https://img.shields.io/badge/@Yash__Dev1-000000?style=flat&logo=x&logoColor=white)](https://twitter.com/Yash_Dev1)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/your-link)
[![Email](https://img.shields.io/badge/yashwankhade5@gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:yashwankhade5@gmail.com)
[![Location](https://img.shields.io/badge/Maharashtra,_India-gray?style=flat&logo=googlemaps&logoColor=white)](#)

</div>

---

## About Me

I build on **Solana** — smart contracts in Rust/Anchor, backends in TypeScript/Node.js, and full-stack dApps end to end. I care about trustless design, on-chain security, and shipping things that actually work.

Currently in the **Turbine3 Accelerated Builder** cohort (Q2 2026) — an advanced track for high-output Solana developers shipping production-grade projects.

- Submitted to **Colosseum Frontier Hackathon 2025** with HorizonPay (trustless stablecoin payment rail)
- Submitted to **Colosseum Hackathon** with CipherVault (on-chain multisig governance vault)
- Deep in: PDAs, CPIs, SPL tokens, escrow design, idempotency, event-driven backends

---

## Tech Stack

**Blockchain**
`Rust` `Anchor` `Solana Web3.js` `PDAs` `CPIs` `SPL Tokens` `On-chain state design`

**Backend**
`TypeScript` `Node.js` `Express` `WebSocket` `REST APIs` `Prisma ORM` `PostgreSQL` `MongoDB`

**Frontend**
`React` `Next.js` `TailwindCSS` `Wallet Adapter`

**Infra & Tools**
`Docker` `AWS EC2` `Vercel` `Nginx` `CI/CD` `Linux` `Git`

**Security & Auth**
`JWT` `Bcrypt` `Zod` `HMAC` `Idempotency design`

---

## Featured Projects

### [HorizonPay](https://github.com/yourusername/horizonpay) — Trustless Stablecoin Payment Rail on Solana
> *Rust · Anchor · TypeScript · Node.js · Next.js · PostgreSQL · Prisma*

Trustless stablecoin payment infrastructure built end-to-end — Anchor contract, Node.js backend, Next.js checkout frontend.

- On-chain **7-slot circular buffer escrow** in Rust; `advance_escrow()` shared helper called atomically from `pay`, `withdraw`, and `update_withdrawal_amount` instructions
- **Idempotent checkout sessions** via `merchant_id:order_id:amount` key with DB `UNIQUE` constraint; JWT-signed URLs with server-side tx validation before broadcast
- **Event-driven backend**: WebSocket contract listener + 5-minute reconciliation cron; HMAC-signed webhook delivery over raw bytes to prevent JSON key-order mismatches
- 🏆 *Submitted to Colosseum Frontier Hackathon 2025*

---

### [CipherVault](https://github.com/yourusername/ciphervault) — On-chain Multisig Governance & Treasury
> *Rust · Anchor · React · TypeScript · Solana Web3.js*

Full-stack Solana dApp for on-chain governance and treasury management with threshold multi-signature approvals.

- Anchor program with proposal + approval accounts, PDA-based vault authority, CPI for SOL & SPL token transfers
- Governance controls minting and supply decisions
- 🌐 Live on Devnet: [ciphervault-frontend.vercel.app](https://ciphervault-frontend.vercel.app)
- 🏆 *Submitted to Colosseum Hackathon*

---

### [Token Launchpad · Staking · AMM](https://github.com/yourusername/solana-programs)
> *Rust · Anchor · Solana*

Three independent Anchor programs deployed on Solana Devnet:
- **Token Launchpad** — configurable distribution mechanics
- **Staking** — on-chain reward math
- **AMM** — constant-product formula with liquidity pool management

---

### [SolGuard](https://github.com/yourusername/solguard)
> *Rust · Anchor · Solana*

Solana smart contract demonstrating secure account validation and constraint patterns in Anchor — a clean reference for guard logic design.

---

### [High-Concurrency WebSocket Chat Server](https://github.com/yourusername/ws-chat)
> *TypeScript · Node.js · WebSocket*

Event-driven chat server handling **5K–20K concurrent WebSocket connections**. Benchmarked and optimized for vertical scaling under sustained load.

---

### [Payment Backend Clone](https://github.com/yourusername/payment-backend)
> *Node.js · Express · JWT · Bcrypt · Zod · MongoDB*

Production-patterned payment backend: JWT auth, bcrypt password hashing, Zod input validation, idempotent transfer endpoints.

---

## Hackathons & Training

| Program | Year | Details |
|---|---|---|
| 🚀 Turbine3 Accelerated Builder | 2026 (Active) | Advanced cohort for high-output Solana builders |
| 🏆 Colosseum Frontier Hackathon | 2026 | HorizonPay — trustless stablecoin payment rail |
| 🏆 Colosseum Hackathon | 2025 | CipherVault — on-chain multisig governance |
| ⚡ Turbine3 Builder Program | 2025 | 7-week intensive: PDAs, CPIs, SPL, Anchor architecture |
| 🌐 Harkirat Singh Cohort 3.0 | 2025 | Full-stack · Web3 · DevOps (Docker, CI/CD, Nginx, AWS) |

---

## Education

**B.E. Computer Science & Engineering** — SGBAU, Maharashtra  
CGPA: 8.48 / 10 · Graduated 2023

---

<div align="center">

*Open to Solana engineering roles — remote or India-based.*  
**[yashwankhade5@gmail.com](mailto:yashwankhade5@gmail.com) · [+91 82081 09560](tel:+918208109560)**

</div>
