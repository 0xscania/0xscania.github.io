# 0xscania.github.io

GitHub Pages home for **scanïa / 0xscania.muse** — crypto enthusiast, developer, creator. Airdrops, testnets, bug fixes, bounties.

Live site (once published): **https://0xscania.github.io/**

> ⚠️ **SECURITY — READ FIRST**
> This site contains **public information only**: public wallet addresses, project descriptions, and faucet links. The seed phrase (mnemonic) and private keys for `0xscania.muse.ai.bw` are **never** in this repo — not in any file, not in git history. They live only in private backup files, offline and in scanïa's private Google Drive folder. Never share them.

## Pages

- `index.html` — hero, motto "DYOR on anything — everything.", projects, wallet preview, faucets preview, about, links, security note
- `wallets.html` — all 12 public addresses of the multi-chain burner wallet `0xscania.muse.ai.bw` (chain + derivation path, copyable), plus the Circle agent wallet on Arc (testnet + mainnet)
- `faucets.html` — free testnet faucets, verified 2026-11-20
- `styles.css` / `script.js` — dark theme, copy-to-clipboard, no external JS dependencies, no tracking

## Deploy (GitHub Pages user site)

This is a user site: the repo must be named exactly `0xscania.github.io` under the `0xscania` account.

```bash
git clone https://github.com/0xscania/0xscania.github.io.git
cd 0xscania.github.io
# edit files, then:
git add -A && git commit -m "Update site" && git push
```

GitHub Pages serves the site from the `main` branch (Settings → Pages → Source: Deploy from a branch, branch `main`, folder `/ (root)`). No build step — plain static HTML/CSS/JS. The `_config.yml` sets the Jekyll theme as a fallback; the static pages work with or without Jekyll processing.

## Source projects

- Burner wallet repo: https://github.com/0xscania/0xscania.muse.ai.bw
- Telegram: https://t.me/s/airdropfind
- Arc testnet explorer: https://explorer.testnet.arc.io/address/0x91963e48ebc021a9f08ca6b50b6f005207d1d8fd
- Arc mainnet explorer: https://explorer.arc.io/address/0xc865a32b3446e46760bf551f0fa9a8476b0a9e03
