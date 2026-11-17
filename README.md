# Orbition Bot

**Versi:** 1.0.0 · **Harga:** Rp 100.000 (~$6) · **Kontak pembelian:** [@rmndkyl](https://t.me/rmndkyl)

Script otomasi Orbition Bot untuk workflow LYID.

## Kebutuhan

| Item | Detail |
|---|---|
| Runtime | Node.js 18+ |
| Wallet | EVM / sesuai chain proyek (kamu sendiri) |
| Proxy | opsional (1 proxy per akun) |
| Captcha | tidak perlu |
| Akses | akun proyek yang kamu kelola sendiri |

## Pembayaran

E-Wallet: DANA / GoPay / ShopeePay · Bank: BCA / Seabank · Crypto: contact for wallet address.
Pembeli menghubungi [@rmndkyl](https://t.me/rmndkyl), kirim bukti transfer, lalu terima license key.

---

Auto bot for Orbition Network airdrop — AI Mining + Quest Completion.

🌐 **Website:** https://airdrop.orbition.network

## Features
- Google OAuth PKCE authentication (stored token, auto-refresh)
- EVM wallet auto-linking
- AI Mining start
- Auto-complete all quests (9 quests, ~3700 OBN total)
- Multi-wallet support (12 wallets)
- Proxy support (Monosans / Private / None)
- Interactive menu + `--daily` flag for auto-run
- Token persistence (tokens.json)

## Setup
```bash
npm install
node index.js
```

## First Run
1. Bot shows Google OAuth URL
2. Open URL in browser, login with Google
3. Copy the full callback URL after redirect
4. Paste into bot terminal
5. Token saved to tokens.json for future runs

## Daily Mode
```bash
node index.js --daily
```
Skips menu, runs Mining + All Quests automatically.
Requires valid token in tokens.json from previous manual login.

## Referral

## Contact
- Telegram: @rmndkyl
- Channel: @layerairdrop
- Group: @layerairdropdiskusi

## Disclaimer
Free and open source script by Layer Airdrop ID (LYID).

## 💰 Harga

| Lisensi | Harga | Fitur |
|---------|-------|-------|
| **Single** | Rp 100.000 / ~$6 | 1 device, lifetime |
| **Bundle (3 bot)** | Rp 100.000 / ~$16 | Pilih 3 bot, hemat 20% |
| **Pro (semua bot)** | Rp 100.000 / ~$70 | Semua bot + update, hemat 30% |

**Cara beli:** Chat [@OG_LYID_bot](https://t.me/OG_LYID_bot) di Telegram → /buy

**Bayar pakai:**
- 🇮🇩 DANA / GoPay / ShopeePay / BCA / Seabank
- 🌐 Crypto (USDT/SOL/ETH)

## 🔧 Troubleshooting

| Masalah | Solusi |
|---------|--------|
| `Cannot find module` | Jalankan `npm install` di folder bot |
| `insufficient balance` | Pastikan wallet punya cukup token untuk gas |
| `429 Too Many Requests` | Tunggu 30-60 detik, bot auto-retry |
| Bot diam/tidak jalan | Cek `config.json` — pastikan API key valid |
| License invalid | Chat [@OG_LYID_bot](https://t.me/OG_LYID_bot) → /verify |

**Butuh bantuan?** Join [Discord](https://discord.gg/ZK2NVkfSNn) atau chat [@layerairdrop](https://t.me/layerairdrop)
