# Hi, I'm Termaine "TJ" Jenkins (he/him)

Self-taught solo developer in Tampa, FL, running [Sentient Solutions LLC](https://sentientsolutions.dev).
I build desktop apps, serverless backends and indie games, and I test them like I'll be the one on call.
I design and review the work and test it myself. AI coding agents write much of the code from my specs.

**Open to work. Remote preferred.** Contact: [studio@sentientsolutions.dev](mailto:studio@sentientsolutions.dev)

## What I build
- **Game launcher + backend:** an Electron launcher for my game *The Great Circle*. Cloudflare Workers link Steam and Discord accounts and issue Ed25519-signed entitlements. The launcher checks them offline; the game-side check is in progress. Launcher CI is green on Ubuntu and Windows. The opt-in bug-report pipeline (R2 storage, 90-day retention) and developer gating are built and merged, shipping in the next release.
- **ReplyReader (Windows):** a PowerShell tray app that reads new AI chat replies aloud, using local Windows voices or optional cloud voices with the user's own key. Free beta; the exe isn't code-signed yet.
- **ReplyReader (Android):** a Kotlin port, in progress and not released.
- **Unreal Engine games:** *The Great Circle*, an indie game on Steam.

## Featured
| Project | What it shows |
|---|---|
| [Case study: Steam + Discord linking with launcher-verified unlocks](https://sentientsolutions.dev/work/tgc-launcher/) | Architecture, threat model, testing (105 automated tests). Launcher CI is green on Ubuntu and Windows |
| [ReplyReader](https://sentientsolutions.dev/products/replyreader/) | Privacy-first Windows tray app with signed update manifests. Beta; the exe is unsigned |
| [ss-qa-showcase](https://github.com/termainejenkins/ss-qa-showcase) | Read-only Playwright (TypeScript) tests against my live site: smoke, navigation, download links, accessibility. Runs in GitHub Actions |
| [TimeKeeper](https://github.com/termainejenkins/TimeKeeper) | Electron + React always-on-top HUD for time and tasks. Windows release v1.0.4 |
| [SS_GitReporter](https://github.com/termainejenkins/SS_GitReporter) | Watches an Unreal project's git repo and posts change summaries to Discord |

## Tech
**Languages:** TypeScript, JavaScript (Node.js), PowerShell, Kotlin (learning through the Android port), Python, HTML/CSS
**Platforms:** Cloudflare Workers, R2, D1, KV; Electron; Astro; Unreal Engine
**Testing and CI:** Playwright, Vitest, node:test, GitHub Actions
**Security:** Ed25519 signing, AES-256-GCM, OAuth 2.0, salted-hash rate limiting

[Website](https://sentientsolutions.dev) · [LinkedIn](https://linkedin.com/in/termaine-jenkins) · [The Great Circle on Patreon](https://patreon.com/thegreatcircle)
