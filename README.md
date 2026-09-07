<h1 align="center">Alex Haumer</h1>
<p align="center">Founder of <a href="https://onpack.io">onpack</a> · Rails, GS1 standards and AI-native tooling · Vienna</p>

<p align="center">
  <a href="https://onpack.io"><img src="https://img.shields.io/badge/onpack.io-live-2ea44f?style=flat-square" alt="onpack.io"></a>
  <a href="https://haumer.ai"><img src="https://img.shields.io/badge/haumer.ai-products-blue?style=flat-square" alt="haumer.ai"></a>
  <a href="mailto:ajphaumer@gmail.com"><img src="https://img.shields.io/badge/email-ajphaumer%40gmail.com-lightgrey?style=flat-square" alt="email"></a>
</p>

---

## 📦 onpack.io

**Connects every packaged product to the people holding it.**

A public product page for every SKU, resolved from the GTIN already printed on the pack (GS1 Digital Link), and a unique code inside every unit. Brands get scan analytics, unit-level traceability and campaign activations. Customers get the truth about what they're holding. Plus a straight, sourced answer on what the EU Digital Product Passport actually means for food.

| | |
|---|---|
| **Pack Identity** | One page per product. Canonical GS1 Digital Link URIs (AI 01 / 10 / 17 / 21 / 22), RFC 9264 linkset in the `Link:` header, content negotiation across HTML / JSON-LD / linkset, `/.well-known/gs1resolver`. |
| **Pack Experience** | One code per unit. Scan analytics, traceability, loyalty and campaign activations. |
| **EU rules, answered** | Wine e-labels (Reg. (EU) 2021/2117), PPWR, GS1 Sunrise 2027 and the DPP, explained without the fear-mongering → [onpack.io/rules-en](https://onpack.io/rules-en) |

Verified operator in the EU DPP Registry acceptance environment. Built in Austria for DACH food & drink brands. Ruby on Rails, Hotwire, Hetzner.

## 🧪 haumer.ai

Small, sharp products I run on my own domain.

| Product | What it does | |
|---|---|---|
| 🛡️ **Redact API** | Strips PII (names, IBANs, API keys) from text before it reaches an LLM. Three-layer detection pipeline. | [live](https://redact.haumer.ai) · [code](https://github.com/Haumer/redact-api) |
| ✉️ **Organise Mail** | AI email triage: categorisation, priority surfacing, actionable summaries. | [live](https://mail.haumer.ai) |
| 🌍 **Globetracker** | Real-time global signal aggregation on a 3D globe. Conflict scoring, threat classification, LLM briefs, push alerts. | [live](https://globe.haumer.ai) · [code](https://github.com/Haumer/globe-tracker) |

## 🤖 AI toolkit

Claude Code skills I wrote and use daily. Packaged, downloadable set coming soon.

- **deep-research** — fans out parallel sub-agents over the browser and the web, then renders a sourced, opinionated PDF brief. Not prose, not slop.
- **design-document** — papers, reports, memos and letters as well-typeset PDFs via Typst, APA7 conventions, global document IDs.
- **walkthrough** — annotated live product tours in your own browser: impersonate a user, drive a journey step by step, log every bug hit.
- **gemini** — Gemini from the shell: image generation with reference composition, text, key lookup, output decoding.
- **branchit / shipit** — branch + worktree in one command, then test, merge, deploy and smoke-test prod in another.

Repos I build on and contribute to:

- [bot_lense](https://github.com/Haumer/bot_lense) — turns model outputs into structured, bot-readable agent actions
- [turbo_chat](https://github.com/Haumer/turbo_chat) — minimal, extensible chat scaffold for AI-native interfaces
- [browser-harness](https://github.com/browser-use/browser-harness) — CDP-level browser control for agents
- [langchainrb](https://github.com/patterns-ai-core/langchainrb) · [ruby-sdk (MCP)](https://github.com/modelcontextprotocol/ruby-sdk) — Ruby LLM and Model Context Protocol tooling

## 🎲 Misc

- 🏎️ **F1Elo** — F1 stats, Elo ratings, fantasy leagues and agent-generated race predictions. [f1elo.com](https://f1elo.com) · [code](https://github.com/Haumer/f1)
- 🦐 **Kriller** — a social network where only AI agents post. Humans observe. [kriller.io](https://kriller.io) · [get your agent on it in 5 minutes](https://github.com/Haumer/kriller-starter-kit)
- 🚋 **transit-at** — Austrian public transit delays from the command line, 20 cities. [code](https://github.com/Haumer/transit-at)

<p align="center"><sub>📫 ajphaumer@gmail.com · 🌐 onpack.io · Vienna, working worldwide</sub></p>
