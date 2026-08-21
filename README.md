# DACx

> Secure messaging. No trace.

**Part of DACnetwork.io** | **Version:** 1.5.6 | **Platform:** Android | **Status:** ✅ Beta Live

---

## What is DACx?

DACx is the private communication and identity layer of the DACnetwork ecosystem.

Ephemeral messaging. Honest about what we store.

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
| Message Requests | ✅ Live | Add by QR or xID; they accept or ignore |
| Ephemeral Messages | ✅ Live | Disappear 3 minutes after read/view |
| Devnet Wallet | ✅ Live | On-device Solana key — 12-word seed phrase |
| Wallet Restore | ✅ Live | Same or new xID, same Solana address |
| DAC Balance | ✅ Live | Devnet DAC (Token-2022) visible in wallet |
| Send DAC / SOL | ✅ Live | Separate tabs in wallet screen |
| Hide Home Balance | ✅ Live | Eye toggle on chip — persists |
| OTA Updates | ✅ Live | Automatic updates — no reinstall needed |
| PIN Vault | ✅ Live | Required on every app open, memory-only |
| Privacy Cover | ✅ Live | App switcher shows only logo |
| Auto-lock | ✅ Live | Configurable timer (5/15/60 min) |
| 24 Reactions | ✅ Live | Long-press any message |
| Delete for Both | ✅ Live | Removes message for both users |
| SVG Icon Set | ✅ Live | Custom stroke icons throughout |
| Identity Avatars | ✅ Live | Color derived from xID |
| Link rutaX | ✅ Live | Settings → Link rutaX — links xID to rutaX |
| Voice Calls | ⏸ Not in current UI | Skipped intentionally |
| $DAC Mainnet | 📋 Not yet | Devnet only |
| E2EE | 📋 Roadmap | Not yet implemented |

---

## Wallet — Important Notes

- **Devnet only** — not mainnet $DAC (`4m9XHiFaZcoUiMxaJH9DbxSXJXuQuXASw3q35hZPjghb`)
- Devnet DAC Mint: `8NeGLu1s8jQjvrtgpTKPMkGg71NKKpwaMthhUSkfLatR`
- Seed phrase never sent to the server
- Sending DAC requires a small amount of Devnet SOL for fees
- Cash-out from rutaX goes to Phantom/Solflare connected in rutaX — not DACx wallet
- Old accounts still use xID + PIN (not seed phrase)

---

## Download

👉 **[Download DACx v1.5.6 APK](https://github.com/DAC-web3/dacx/releases/latest)**

Or download from the official website: **www.dacnetwork.io**

**How to install:**
1. Download the APK file
2. Go to Android Settings → Security → Enable "Install unknown apps"
3. Open the APK and install
4. Launch DACx and create your xID
5. Set your personal PIN and start communicating

---

## OTA Updates

Starting from v1.5.6, DACx supports Over-The-Air (OTA) updates.

| Release | What changed |
|---------|-------------|
| v1.5.6-ota-2 | Devnet DAC wallet, hide Home balance |
| v1.5.6-ota-1 | Security & UI Premium, PIN Vault, 24 reactions |
| v1.5.6 | Base APK — OTA channel enabled |

**How to update:**
Open DACx → Settings → Check for updates → Restart.
Or force-close the app and reopen.

---

## How it works

1. **Create your xID** — 9-digit unique identity, no phone or email
2. **Set your PIN** — personal key, required on every open
3. **Add contacts** — via QR scan or manual xID entry (mutual consent)
4. **Communicate** — messages disappear 3 minutes after being read
5. **Link rutaX** — Settings → Link rutaX to connect your xID

---

## xID — Universal DACnetwork Identity

xID
├─ DACx (messaging + wallet) — LIVE
├─ rutaX (Proof of Activity) — IN DEVELOPMENT
├─ DACmeta (social / VR) — PLANNED
└─ DAC Smart Systems (nodes) — RESEARCH

---

## Part of DACnetwork Ecosystem

| Layer | Product | Status |
|-------|---------|--------|
| Activity | rutaX | 🔄 IN DEVELOPMENT — Devnet API live |
| Physical | DAC Smart Systems | 🔬 RESEARCH |
| Social | DACmeta | 📋 PLANNED |
| **Communication** | **DACx** | **✅ BETA v1.5.6** |
| Economic | $DAC | ✅ LIVE — Solana Mainnet |

---

## Roadmap

| Phase | Status | Milestones |
|-------|--------|------------|
| Phase 0 | ✅ Done | MVP, xID, Android Beta v1.5.6, OTA, Devnet wallet |
| Phase 1 | 🔄 In progress | 1,000+ xIDs, iOS version, expanded features |
| Phase 2 | 📋 Planned | Mainnet wallet integration, multi-app xID |
| Phase 3 | 📋 Planned | E2EE encryption, $DAC payments in chat |
| Phase 4 | 📋 Planned | DAO governance integration |

---

## Privacy Commitment

- DACx does not collect phone numbers
- DACx does not collect email addresses
- DACx does not store conversation content on centralized servers
- DACx does not sell user data
- DACx does not monetize user behavior
- Seed phrase never leaves the device

---

## Links

- 🌐 [dacnetwork.io](https://dacnetwork.io)
- 🐦 [@DACLabs](https://x.com/DACLabs) on X
- 📁 [Main Repository](https://github.com/DAC-web3/dac-network)
- 🔒 [Security Policy](https://github.com/DAC-web3/dac-network/blob/main/SECURITY.md)

---

*DACx • Asociația DACnetwork Web3 • București, România*
*$DAC is a utility token and does not represent an investment.*
*Devnet DAC is not mainnet $DAC.*
