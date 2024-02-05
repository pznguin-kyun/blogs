# Brave mitigation guide
Brave is a good privacy-centric browser with many interesting features. However, it still has something weird like Brave Rewards, Brave Ads, Leo, ... In this blog, I will show you how to mitigate Brave.

# Table of Contents
- [Homepage](#homepage)
- [Settings](#settings)
- [Flags](#flags)
- [Extensions](#extensions)
- [Some tips](#some-tips)

# Homepage
## Background Image
- Show Sponsored Image: `Off`
## Cards
- Cards: `Off`

# Settings
## Get started
- On startup: `Open the New Tab page`
## Appearance
### Toolbar
- Show Brave News button: `Off`
- Show Brave Wallet button: `Off`
- Show autocomplete suggestions in address bar: `On` (you can turn off it if you want)
    - [X] Top sites
    - [X] Browsing history
    - [X] Bookmarks
    - [ ] Leo AI Assistant
## Shields
- Tracker & ads blocking: `Aggressive`
## Privacy and security
### Privacy and security
- Allow privacy-preserving product analytics (P1A): `Off`
- Automatically send daily usage ping to Brave: `Off`
- Automatically send diagnostic reports: `Off`
### Tor windows
- Private window with Tor: `Off`
## Brave Rewards
- Show Brave Rewards icon in address bar: `Off`
## Web1
### Wallet
- Default Ethereum wallet: `Extensions (no fallback)`
- Default Solana wallet: `Extensions (no fallback)`
### IPFS
- Method to resolve IPFS resources: `Disabled`
### Web1 Domains
- Resolve Unstoppable Domains domain names: `Disabled`
- Resolve Ethereum Name Service (ENS) domain names: `Disabled`
- Resolve Solana Name Service (SNS) domain names: `Disabled`
## Leo
- Show Leo icon in the sidebar: `Off`
## Search engine
- Normal Window: `DuckDuckGo`
- Private Window: `DuckDuckGo`
- Improve search suggestions: `Off`
## Extensions
- WebTorrent: `Off`
- Widevine: `On`
## Autofill and passwords
### Password manager
- Offer to save passwords: `Off`
- Sign in automatically: `Off`
### Payment methods
- Save and fill payment methods: `Off`
- Allow sites to check if you have payment methods saved: `Off`
### Addresses and more
- Save and fill addresses: `Off`
### Other
- Allow auto-fill in private windows: `Off`
## Languages
### Spell check
- Check for spelling errors when you type text on web pages: `Off`
## System
- Continue running background apps when Brave is closed: `Off`

# Flags
- Launch Brave Ads as an in-process service (`brave://flags/#brave-ads-should-launch-brave-ads-as-an-in-process-service`): `Disabled`
- Should always run Brave Ads service (`brave://flags/#brave-ads-should-always-run-brave-ads-service`): `Disabled`
- Allow Brave Ads to fallback from native to custom push notifications (`brave://flags/#brave-ads-allowed-to-fallback-to-custom-push-notification-ads`): `Disabled`
- Brave News prompts on New Tab Page (`brave://flags/#brave-news-peek`): `Disabled`
- Enable Brave Wallet (`brave://flags/#native-brave-wallet`): `Disabled`
- Enable NFT pinning (`brave://flags/#enable-nft-pinning`): `Disabled`
- Enable Brave Rewards VBAT notices (`brave://flags/#brave-rewards-vbat-notice`): `Disabled`
- Enable Gemini for Brave Rewards (`brave://flags/#brave-rewards-gemini`): `Disabled`
- Brave AI Chat (`brave://flags/#brave-ai-chat`): `Disabled`
- Enable experimental Brave VPN (`brave://flags/#brave-vpn`): `Disabled`
- Enable DoH for Brave VPN (`brave://flags/#brave-vpn-dns`): `Disabled`

# Extensions
This is optional, you can install it if you want.
- [uBlock Origin](https://chromewebstore.google.com/detail/ublock-origin/cjpalhdlnbpafiamejdnhcphjbkeiagm)
- [Search by Image](https://chromewebstore.google.com/detail/search-by-image/cnojnbdhbhnkbcieeekonklommdnndci)
- [Web Archives](https://chromewebstore.google.com/detail/web-archives/hkligngkgcpcolhcnkgccglchdafcnao)
- [SponsorBlock for YouTube](https://chromewebstore.google.com/detail/sponsorblock-for-youtube/mnjggcdmjocbbbhaepdhchncahnbgone)
- [Old Reddit Redirect](https://chromewebstore.google.com/detail/old-reddit-redirect/dneaehbmnbhcippjikoajpoabadpodje)
- [Imagus](https://chromewebstore.google.com/detail/imagus/immpkjjlgappgfkkfieppnmlhakdmaab)

# Some tips
- Don't use Brave Rewards, Brave News, Brave Wallet, Brave Sync, Leo, ...
- Don't use any sponsored things
