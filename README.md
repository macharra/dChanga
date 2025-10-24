# 🌍 dChanga — Transparent Community Crowdfunding on Hedera

### 🏆 Mission
Empower Kenyan communities to raise funds with verifiable trust, milestone-based payouts, and QR code transparency — no middlemen, no fraud, just impact.

---

## 💡 Problem
Traditional crowdfunding in Africa often faces:
- Lack of **transparency** (funds misuse)
- **Manual record-keeping**
- **Low donor trust**
- No simple way to **verify** campaign authenticity or progress

---

## ✅ Solution
**CrowdfundKE** uses **Hedera Hashgraph** to make community fundraising:
- **Transparent:** Immutable donation records via HCS (Hedera Consensus Service)
- **Accountable:** Milestone-based payouts via Smart Contracts
- **Verifiable:** QR codes link to real campaign data on-chain
- **Inclusive:** Mobile-first UX for WhatsApp/social sharing

---

## ⚙️ Core Architecture

| Feature | Hedera Service | Description |
|----------|----------------|--------------|
| Campaign Creation | Smart Contract Service | Define goal, deadline, payout logic |
| Contribution Logging | Consensus Service (HCS) | Timestamp every donation immutably |
| Campaign Token | Token Service | Optional NFT or token as proof of support |
| QR Code Verification | Frontend + HCS | Scan to verify campaign details and history |
| Milestone-Based Payouts | Smart Contracts | Release funds only when milestones are achieved |
| Flagging + Review | HCS + Smart Contracts | Pause and review suspicious campaigns |

---

## 📱 UX Flow
1. **Create Campaign** → Enter goal, description, deadline  
2. **Generate QR Code** → Share via WhatsApp, posters, or social media  
3. **Contribute** → Scan & send HBAR or stablecoin via wallet  
4. **Track Progress** → See live updates, milestones, and receipts  
5. **Verify** → Campaign details visible on **HashScan** for transparency  

---

## 🧠 Trust Layer
- **Verified Wallets:** Campaign creators link their Hedera wallet to their identity  
- **Endorsements:** Trusted community members co-sign campaigns  
- **QR Scan:** Reveals campaign history and contributions  
- **Flagging System:** Suspicious campaigns paused pending community review  

---

## 🎁 Reward Tiers (Example)
| Tier | Reward |
|------|---------|
| KSh 100 | Thank-you shoutout |
| KSh 500 | Digital badge or NFT |
| KSh 1,000 | Early access to updates |
| KSh 5,000+ | Name/logo on donor wall or physical plaque |
| “Sponsor a desk” or “Fund a water tank” | Tangible local impact |

---

## 🧱 Tech Stack
- **Frontend:** React + TailwindCSS + QR Generator  
- **Backend:** Node.js / Express + Hedera SDK  
- **Smart Contracts:** Solidity (Hedera Smart Contract Service)  
- **Database:** IPFS / JSON store (off-chain campaign metadata)  
- **Wallet Integration:** HashPack / Blade Wallet  

---

## 🧩 Roadmap
### Phase 1 — MVP (for hackathon)
- [x] Campaign creation + contribution flow  
- [x] Immutable donation logging (HCS)  
- [x] QR code verification of campaign data  
- [x] Simple milestone payout contract  

### Phase 2 — Extended Features
- [ ] Token/NFT rewards  
- [ ] Community flagging + voting system  
- [ ] Creator verification via KYC/DAO council  
- [ ] Mobile app / PWA  

---

## 🔗 Verify Transparency
- View campaigns and donations on [HashScan](https://hashscan.io/)
- Verify campaign authenticity by scanning the QR code

---

## 📸 Demo Ideas
- Record a 1–2 min video:  
  “Mary’s Youth Group raising funds for a water tank — donors scan, contribute, and verify on-chain.”
- Show QR scanning, live updates, and milestone payouts.

---

## 🧑‍💻 Team Roles (Suggested)
| Role | Responsibility |
|-------|----------------|
| Smart Contract Dev | Solidity logic for campaign creation and payouts |
| Backend Dev | Integrate HCS, store campaign metadata |
| Frontend Dev | QR code generator, UI, wallet connect |
| Presenter | Demo, storytelling, and impact narrative |

---

## ⚖️ License
MIT License © 2025 dChanga Team

---

## 🤝 Acknowledgments
Built with ❤️ for **Hedera Africa Hackathon 2025**  
Inspired by Kenya’s community-driven giving culture.
