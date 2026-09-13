# Mercatura Forum

**We build sovereign infrastructure: chains, wallets, settlement and financial systems that
hold up when the institutions around them cannot.** Cairo-based venture studio; applied R&D in
Web3, AI and robotics.

**Everything in this organisation is open source, and it is being built as the largest
open-source initiative in the MENA region.** The Thebes substrate, its developer tools, the
example applications and the financial products below are all part of the Forum: one body of
work, one licence (Apache 2.0), one team attribution, and every repository meant to be read,
run and built on by anyone.

---

## Thebes: a Layer 1 where the whole application lives on-chain

### 🌐 [thebesprotocol.com](https://thebesprotocol.com): the official site

Distributed cloud hosting for Egypt and the GCC. Everything below runs on it.

Frontend, backend, and data: replicated across every validator, finalized by a
Byzantine quorum, signed under post-quantum certificates on the consensus
critical path. No servers, no cloud bill, nothing to take down.

**Start here, in order:**

| Step | Where | What you get |
| --- | --- | --- |
| 0. Start | **[thebesprotocol.com](https://thebesprotocol.com)** | The product site: what Thebes is, what it costs, and how to put a site on it |
| 1. Understand | [Thebes-Protocol-](https://github.com/Mercatura-Forum/Thebes-Protocol-) | The hub: homepage, technical spec, docs, and small starters (Motoko **and** Rust) |
| 2. See it | [The example library](https://github.com/Mercatura-Forum/Thebes-Protocol-/blob/main/examples/README.md) | Twelve full-stack applications, each one live on-chain: store, chat, CRM, finance, medical imaging, ISO 20022 banking, and more |
| 3. Build | [thebes-sdk](https://github.com/Mercatura-Forum/thebes-sdk) + [thebes-lib](https://github.com/Mercatura-Forum/thebes-lib) | The frontend SDK (`@thebes/sdk`: boundary client, React hooks, passkey gate) and the Motoko backend library (Admin, Users, Pagination, Invoices) |
| 4. Deploy | [thebes-deploy releases](https://github.com/Mercatura-Forum/Thebes-Protocol-/releases) · [CLI guide](https://github.com/Mercatura-Forum/Thebes-Protocol-/blob/main/docs/cli-deploy.md) | One binary. `thebes-deploy deploy` compiles, installs, uploads the frontend, prints the live URL |
| 5. Go further | [digital-asset-exchange](https://github.com/Mercatura-Forum/digital-asset-exchange) | A sovereign DvP exchange: cash, shares, and land titles settling in one indivisible step |

Your users sign in with a **passkey**: no wallets, no seed phrases, no extensions.

## Products built on Thebes

Financial systems that run as smart contracts, each with a provable record, a test battery and an
architecture document. Apache 2.0.

| Repository | What it is |
| --- | --- |
| **[Manticore](https://github.com/Mercatura-Forum/Manticore)** | Core banking and payments: a provable double-entry journal, maker-checker on every money-moving act, ISO 20022 and Mojaloop payments, certified reports |
| **[Solari](https://github.com/Mercatura-Forum/Solari)** | An audit system for audit firms: a hash-chained engagement trail, journal-entry testing, passkey sign-offs, figures a third party can verify |
| **[Tachyon](https://github.com/Mercatura-Forum/Tachyon)** | Delivery-versus-payment settlement: two-phase escrow, both-or-neither settlement, a batch matching engine, certified receipts |

## Also here

- **[ICRC-ME](https://github.com/Menese-Protocol/ICRC-ME)**: a self-indexing ledger standard.
- **[LiteCoin-node](https://github.com/Menese-Protocol/LiteCoin-node)**: a Litecoin full node as a smart contract.
- **[ICP-GPU](https://github.com/Menese-Protocol/ICP-GPU)**: GPU-accelerated cryptography for chain workloads.

---

*Maintained by the Thebes Core Team. Open to contributors: open an issue on the repository concerned.*
