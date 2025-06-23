<!--
SEO Keywords: Nexus node Testnet III, Nexus Prover node, how to install Nexus node, Nexus one-click node setup, EasyNode Nexus, Nexus CLI guide
Description: Complete guide to install a Nexus Prover Node on Testnet III using either CLI or EasyNode one-click setup.
-->

# How to Run a Nexus Node on Testnet III – Prover Node Setup with EasyNode

Welcome to the official EasyNode guide to deploy a **Nexus Prover node** on **Testnet III**.

This repository helps developers and node operators quickly set up a Nexus node via:
- ✅ Command-line interface (CLI)
- ✅ One-click setup with [EasyNode](https://app.easy-node.xyz/)

Whether you're asking _“How to install a Nexus node?”_ or looking to contribute compute to the network, this guide is for you.

---

## ⚙️ What is a Nexus Node?

The Nexus Layer 1 blockchain is a decentralized supercomputer designed to power the AI-driven economy. With its zkVM (Zero-Knowledge Virtual Machine), it enables trustless, verifiable, and private execution of smart contracts and autonomous agents.

Running a **Nexus Prover node** helps power this infrastructure — and rewards you with **NEX Points** in Testnet III.

---

## 🚀 Quick Start – One-Click Node with EasyNode

The easiest way to run a Nexus node is to use [EasyNode](https://app.easy-node.xyz/).

### ✅ Benefits:
- No setup required
- Fully managed infrastructure
- Automatic updates
- Dedicated monitoring and dashboards
- Start earning in under 5 minutes

👉 [Deploy your Nexus Prover Node now](https://app.easy-node.xyz/)

---

## 🧪 Manual Setup – CLI Installation (Linux/Ubuntu)

For advanced users, here’s how to install a Nexus node manually.

### 1. Install Dependencies

```
sudo apt update && sudo apt upgrade -y
sudo apt install screen curl build-essential pkg-config libssl-dev git-all protobuf-compiler -y
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
source $HOME/.cargo/env
rustup target add riscv32i-unknown-none-elf
```
2. Download and Run Nexus CLI
```
curl https://cli.nexus.xyz/ | sh
source ~/.bashrc
nexus-network start --node-id <your-node-id>
```
 
💡 Get your node ID from app.nexus.xyz

3. Link Wallet and Register Node
```
nexus-network register-user --wallet-address <your-wallet-address>
nexus-network register-node
```
📊 **Manual Setup vs EasyNode**

> **Manual CLI Setup**: Requires Linux knowledge, takes ~1 hour, self-hosted server, manual updates and setup.  
> **EasyNode One-Click**: Ready in minutes, fully hosted and maintained for you. No server or CLI skills needed.

❓ FAQ
What is Nexus Testnet III?
Testnet III is the latest testing phase of the Nexus network. It introduces enhanced stability, broader access, and new ways to earn NEX Points by contributing compute.

How do I earn NEX Points?
By running a Prover node and linking your wallet to app.nexus.xyz. More computation = more points.

Can I run multiple nodes?
Yes! You can connect multiple devices — desktops, servers, VPS, or browsers — and track them all via one account.

---

🎯 **Ready to launch your Nexus node?**

[👉 Deploy with EasyNode (in under 5 minutes)](https://easy-node.xyz/)

🤝 Join the Community
Need help or want to connect?

[Discord](https://discord.gg/EgpcHSUy5v)
[Twitter/X](https://x.com/easynodexyz)
[Visit EasyNode](https://easy-node.xyz/)
