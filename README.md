# 🔐 Menoid — Documentation

> A Private Crypto Wallet for the Multi-Chain World.
>
> [menoid.xyz](https://menoid.xyz)

---

Crypto is multi-chain. Privacy isn't.

Most privacy solutions stay confined to a single ecosystem, so users are forced
to learn a different privacy model every time they switch chains. Menoid is one
wallet with one privacy experience across many chains.

**One wallet. One privacy experience. Multiple chains.**

---

## 📖 Read the docs

### 👉 **[DOCS.md](DOCS.md)**

The full V1 protocol documentation — what Menoid is, and how each part actually
works, section by section.

| Section | What it covers |
|---|---|
| [What is Menoid](DOCS.md#what-is-menoid) | Why privacy matters, Open Mode vs Noid Mode, privacy with accountability, roadmap |
| [Core Vocabulary](DOCS.md#core-vocabulary) | Every term used throughout — notes, commitments, nullifiers, relayers |
| [1. Noid Mode Registration](DOCS.md#1-noid-mode-registration) | One signature → your Noid identity, registered on-chain |
| [2. Overview](DOCS.md#2-overview) | The whole system: one pool, three operations, and the relayer |
| [3. Deposit](DOCS.md#3-deposit) | Open Mode → Noid Mode: public funds become private notes |
| [4. Transfer](DOCS.md#4-transfer) | Private value movement — sender, receiver and amount all hidden |
| [5. Withdraw](DOCS.md#5-withdraw) | Noid Mode → Open Mode: notes burned, funds released |

Each section opens with its diagram, defines its own terms, and explains what
the diagram shows against what the protocol actually does.

---

## 🌍 Open Mode vs 🌑 Noid Mode

Menoid is one wallet with two modes. You choose how visible you want to be.

| | **Open Mode** — public | **Noid Mode** — private |
|---|---|---|
| Balances | Public | Hidden |
| Transfers | Public | Private |
| Swaps | Public | Private |
| Bridges | Public | Private |
| History | Permanently traceable | Untraceable |

Both modes belong to **the same wallet address**. No second wallet, no second
seed phrase, no second address to manage.

---

## 🔑 Privacy with Accountability

Privacy shouldn't force a choice between confidentiality and transparency.
Through **viewing keys**, you can selectively share your activity with trusted
parties — for audits, compliance, or accounting — while everything stays private
by default.

**Privacy as the default. Transparency as a choice.**

---

## 📁 Repository layout

```
.
├── README.md     you are here
├── DOCS.md       the full V1 documentation
└── assets/       diagrams referenced by DOCS.md
```

---

**Menoid — A Private Crypto Wallet.**

[menoid.xyz](https://menoid.xyz)
