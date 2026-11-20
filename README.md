# 9DEVS

Discord token & email-verified account generator powered by 9Captcha.

## Features

- **Token Generation** — Request-based Discord account creation with full fingerprint spoofing
- **Email Verification** — 7 mail providers: DuckMail, CyberTemp, TempMail.lol, Hotmail007, Zeus, Draxono, Mailcow
- **Humanizer Engine** — Auto-sets display name, bio, pronouns, avatar, and HypeSquad
- **Utility Tools** — Includes Server Joiner, Auth Joiner, Token Checker, Token Onliner, and Proxy Checker
- **Proxy Rotation** — Auto-cycles proxies with IP burn detection
- **9Captcha Solver** — Extension or Request 
- **WebSocket Keepalive** — Maintains gateway presence to prevent instant disable

## Quick Start

```
pip install -r requirements.txt
python start.py
```

## Config

Edit `config.json` or use the Settings menu in `start.py`:

- **9Captcha API Key** — Get yours at [9captcha.pridesmp.fun](https://9captcha.pridesmp.fun)
- **Mail Services** — Toggle providers on/off, set API keys/passwords
- **Solver Mode** — Extension (proxyless OK) or Request (requires residential proxies)
- **Threads** — Concurrent generation count
- **Humanizer** — Enable/disable profile customization

## Proxies

Add to `input/proxies.txt` in `user:pass@ip:port` or `ip:port` format.
U can try using https://dataimpulse.com/?aff=371700 for proxies its good (Not Sponsered)

> **Note:** Request solver requires quality residential proxies. Datacenter IPs are blocked by Discord.
> Extension solver works proxyless.

## 9Captcha API

Get your key at [9captcha.pridesmp.fun](https://9captcha.pridesmp.fun)

## Disclaimer & Terms of Service

This tool is created for educational, development, and security testing purposes only. The developer (**MineX**) and any associated organizations or contributors are **not responsible** for any misuse, damage, bans, or unlawful actions conducted with this software. The end user accepts full and sole responsibility for all actions taken. By downloading, accessing, or running this repository, you explicitly accept and agree to these terms and rules.
