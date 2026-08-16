# DACx

> Ephemeral messaging. Honest about what we store.

**Part of DACnetwork.io** | **Version:** 1.5.6 | **Platform:** Android | **Status:** ✅ Beta Live

---

## What is DACx?

DACx is the private communication and identity layer of the DACnetwork ecosystem.

DACx is how DACnetwork members speak to each other — directly, by mutual consent, and ephemerally.

> *Communication must not become an archive. It must remain consent and moment.*

---

## Source Code Status

DACx is currently distributed as a beta application.

This public repository contains:
- Product documentation
- Release information
- Project updates
- APK download via Releases

**The application source code is not currently open-source.**

If you are a developer interested in contributing to DACx, fill in the [Collaboration Form](https://docs.google.com/forms/d/e/1FAIpQLSdBRhcaV6d-CBqXNo0QDP4H6J55wKb8RLkSJJxTlXR7hkDqDg/viewform).

---

## Current Features (Beta v1.5.6)

| Feature | Status | Description |
|---------|--------|-------------|
| xID Identity | ✅ Live | 9-digit network identity — no phone, no email |
| Message requests | ✅ Live | Add by QR or xID; they accept or ignore |
| Ephemeral messages | ✅ Live | Disappear 3 minutes after read/view |
| Solana wallet | ✅ Live | **Devnet.** New accounts create the key on this phone |
| 12-word phrase | ✅ Shown | Shown at signup. **Restore is not available yet** |
| Push notifications | ✅ Live | FCM when the app is closed |
| OTA updates | ✅ Live | Automatic JS/UI updates — no reinstall needed |
| PIN lock | ✅ Live | Required on every app open (4–6 digits) |
| Privacy cover | ✅ Live | App switcher shows only the logo |
| Auto-lock | ✅ Live | Configurable timer (5/15/60 min) |
| Reactions + delete | ✅ Live | Long-press any message |
| Voice calls | ⏸ Hidden | Not offered in the current UI |
| Phrase restore | 📋 Not yet | 12 words are preparation, not recovery |
| $DAC mainnet | 📋 Not yet | Wallet is Devnet SOL only |
| E2EE | 📋 Not yet | Messages pass through DACx servers until they disappear |

---

## Download

👉 **[Download DACx v1.5.6 APK](https://github.com/DAC-web3/dacx/releases/latest)**

Or download from the official website: **[www.dacnetwork.io](https://www.dacnetwork.io)**

**How to install:**
1. Download the APK file
2. Go to Android Settings → Security → Enable "Install unknown apps"
3. Open the APK and install
4. Launch DACx, write down your 12 words, then create your xID
5. Set your PIN and start communicating

Already on **v1.5.6**? Close and reopen the app to receive the latest OTA. No new APK needed.

---

## OTA Updates

Starting from v1.5.6, DACx supports Over-The-Air (OTA) updates.

| Situation | What happens |
|-----------|-------------|
| Install v1.5.6 once | Base installed — OTA ready |
| New JS/UI update released | App updates automatically on next open |
| New native APK released | App shows alert → download new APK |
| Running v1.5.3–1.5.5 | Must install v1.5.6 once first |

**Latest OTA (16 August 2026), runtime 1.5.6:**
- Home: glass header, logo, xID, SOL, QR / card / settings
- Chat: unread fix, composer reset, system back stays in-app
- PIN: one field, 4–6 digits
- QR: full-screen camera; accepts `dacx://add/…` and plain xID
- New accounts: key created on device, 12 words + 3-word confirm
- Wallet badge: **DEVNET** — not $DAC mainnet

**What updates automatically (OTA):**
- UI changes, bug fixes, new screens
- Chat logic, notifications, features

**What requires a new APK:**
- Major native/SDK changes
- New permissions or native modules

---

## How it works

1. **Choose a username and PIN**
2. **Write down 12 words** and confirm 3 of them — DACx cannot recover them
3. **Your xID is created** — 9-digit identity, no phone or email
4. **Add contacts** — scan QR (`dacx://add/…`) or enter an xID; they get a request
5. **Communicate** — messages disappear 3 minutes after being read

Existing accounts (created before this OTA) still sign in with xID + PIN as before.

---

## Wallet — what is true today

- **New accounts:** the Solana key is created on the phone. The server stores only the public address.
- **Network:** Solana **Devnet**. Test SOL only. Not $DAC on mainnet.
- **12 words:** shown once at signup so you can write them down.
- **Restore from those words is not built yet.** If you lose this phone and the local key, the wallet cannot be recovered in-app.
- This is not Phantom-style self-custody until restore exists.

---

## xID — Universal DACnetwork Identity

xID ├─ DACx (messaging + wallet) — LIVE ├─ rutaX (Proof of Activity) — IN DEVELOPMENT ├─ DACmeta (social / VR) — PLANNED └─ DAC Smart Systems (nodes) — RESEARCH

---

## Part of DACnetwork Ecosystem

| Layer | Product | Status |
|-------|---------|--------|
| Activity | rutaX | 🔄 IN DEVELOPMENT |
| Physical | DAC Smart Systems | 🔬 RESEARCH |
| Social | DACmeta | 📋 PLANNED |
| **Communication** | **DACx** | **✅ BETA v1.5.6** |
| Economic | $DAC | ✅ LIVE — Solana Mainnet (not yet inside DACx) |

---

## Roadmap

| Phase | Status | Milestones |
|-------|--------|------------|
| Phase 0 | ✅ Done | MVP, xID identity, Android Beta v1.5.6, OTA updates |
| Phase 1 | 🔄 In progress | 1,000+ xIDs, iOS version, phrase restore, expanded features |
| Phase 2 | 📋 Planned | Mainnet wallet integration, multi-app xID |
| Phase 3 | 📋 Planned | E2EE encryption, $DAC payments in chat |
| Phase 4 | 📋 Planned | DAO governance integration |

---

## Privacy Commitment

- DACx does not collect phone numbers
- DACx does not collect email addresses
- DACx does not sell user data
- DACx does not monetize user behavior
- Messages are **not end-to-end encrypted yet**
- Unread messages are held on DACx servers until they are read, then deleted after 3 minutes
- After that, conversation content is not kept as a permanent archive

---

## Links

- 🌐 [dacnetwork.io](https://dacnetwork.io)
- 🐦 [@DACLabs](https://x.com/DACLabs) on X
- 📁 [Main Repository](https://github.com/DAC-web3/dac-network)
- 🔒 [Security Policy](https://github.com/DAC-web3/dac-network/blob/main/SECURITY.md)

---

*DACx • Asociația DACnetwork Web3 • București, România*
*$DAC is a utility token and does not represent an investment.*
