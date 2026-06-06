# Claude Account Safety Checker

> Free, open-source tool to evaluate your Claude AI usage against Anthropic's official Usage Policies — available in 12 languages.

🔗 **Live tool:** [alphilippo.github.io/claude-safety-checker](https://alphilippo.github.io/claude-safety-checker)

---

## What it does

- **Risk Checker** — select your profile (general user / developer / business) and flag practices that match your usage. Get an instant risk level (low / moderate / high / critical) based on Anthropic's official policies.
- **I'm Banned** — step-by-step appeal process, official statistics from Anthropic's Transparency Hub, and support access by plan.
- **FAQ** — 10 questions sourced directly from Anthropic's Help Center, Usage Policy, and Transparency Hub.
- **Dev system prompt** — generate a ready-to-use system prompt to integrate policy monitoring into your Claude-powered app.

## Languages supported

All 12 languages officially available on [support.claude.com](https://support.claude.com):

`English · Français · Deutsch · Español · Português · Italiano · Русский · Bahasa Indonesia · 日本語 · 한국어 · 简体中文 · 繁體中文`

> **Note:** The appeal steps and FAQ are intentionally kept in English, as the appeal process itself takes place in English on Anthropic's platform (claude.ai/restricted). Native-speaker translations of these sections are welcome via pull request.

## Sources

All content is based on official Anthropic documentation:

- [Anthropic Usage Policy](https://www.anthropic.com/legal/aup) (effective Sept. 15, 2025)
- [Consumer Terms of Service](https://www.anthropic.com/legal/consumer-terms) (effective Oct. 8, 2025)
- [Anthropic Help Center](https://support.claude.com)
- [Anthropic Transparency Hub](https://www.anthropic.com/transparency/platform-security)

## Deploy on GitHub Pages

1. Fork this repository
2. Go to **Settings → Pages**
3. Set source to **Deploy from a branch → main → / (root)**
4. Your tool will be live at `https://[your-username].github.io/claude-safety-checker`

## Contributing

Contributions welcome:
- **Translations** — translate the appeal steps and FAQ into supported languages (see `UI` object in `index.html`)
- **Policy updates** — if Anthropic updates their Usage Policy, open a PR with the relevant changes
- **New risk checks** — suggest additional documented risk factors via issues

## Disclaimer

This tool is **not affiliated with Anthropic**. It is an independent resource built from publicly available official documentation. Always refer to [anthropic.com/legal/aup](https://www.anthropic.com/legal/aup) for the authoritative and up-to-date source.

---

Built by [@alphilippo](https://github.com/alphilippo) · Last updated: June 2026
