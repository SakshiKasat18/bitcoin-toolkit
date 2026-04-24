# Bitcoin Transaction Intelligence Toolkit

A system to **understand, construct, and analyze Bitcoin transactions** — built from first principles without relying on external APIs or full nodes.

---

## 🧭 The Journey

This toolkit was built as a progression:

> From decoding a single transaction → to constructing one → to analyzing patterns across the chain.

```text
ChainLens → CoinSmith → Sherlock
Understand → Build → Analyze
```

---

## 🔍 Projects

### 1. ChainLens — Transaction Parser & Visualizer

Parse raw Bitcoin transactions and visualize them in a human-readable format.

* 🔗 GitHub: https://github.com/SakshiKasat18/chain-lens
* 🌐 Live Demo: https://chain-lens-web.vercel.app/

**Highlights:**

* Raw transaction hex → structured JSON
* Fee, vbytes, SegWit savings analysis
* Script decoding (P2PKH, P2WPKH, P2TR, OP_RETURN)
* Interactive UI for exploration

---

### 2. CoinSmith — Transaction Builder

Construct valid Bitcoin transactions from structured inputs.

* 🔗 GitHub: https://github.com/SakshiKasat18/coin-smith
* 🌐 Live Demo: https://coin-smith-web.vercel.app/

**Highlights:**

* UTXO selection and input handling
* Fee estimation and change output logic
* PSBT-style transaction construction
* Multiple transaction-building modes

---

### 3. Sherlock — Chain Analysis Engine

Analyze transaction patterns across the Bitcoin blockchain.

* 🔗 GitHub: https://github.com/SakshiKasat18/sherlock
* 🌐 Live Demo: (deployment coming soon) *

**Highlights:**

* Block file parsing (blk.dat / rev.dat)
* Heuristic-based transaction classification
* Pattern detection (CoinJoin, change outputs, etc.)
* Large-scale transaction analysis

---

## 🧠 What This Demonstrates

* Deep understanding of Bitcoin internals (UTXO model, scripts, SegWit, Taproot)
* Ability to work with raw binary data and protocol-level structures
* Systems thinking across multiple abstraction layers
* Building tools from first principles instead of relying on APIs

---

## ⚙️ Design Philosophy

* No external blockchain APIs
* No reliance on full Bitcoin nodes
* Everything built from raw data and protocol understanding

---

## 🧩 How It Fits Together

Each project solves a different layer of the same system:

* **ChainLens** → Understand transactions
* **CoinSmith** → Build transactions
* **Sherlock** → Analyze transactions at scale

Together, they form a complete **Bitcoin learning and analysis stack**.

---

## 🙌 Acknowledgements

This work was initiated through the Summer of Bitcoin program and extended independently beyond the original challenges into a full system.

---

## 🚀 Future Work

* Privacy-aware coin selection strategies
* Real-time mempool analysis
* Graph-based transaction visualization
* Streaming block processing
