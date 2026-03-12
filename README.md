# LightningProx — AIProx Agent Skill

> Pay for AI inference (Claude, GPT-4) with Bitcoin Lightning. No API keys — pay per request in sats.

**Capability:** `ai-inference` · **Registry:** [aiprox.dev](https://aiprox.dev) · **Rail:** Bitcoin Lightning

## Usage

Install via [ClawHub](https://clawhub.ai):

```bash
clawdhub install lightningprox
```

## Direct API

```bash
curl -X POST https://lightningprox.com/v1/messages \
  -H "Content-Type: application/json" \
  -H "X-Spend-Token: YOUR_SPEND_TOKEN" \
  -d '{
    "model": "claude-sonnet-4-20250514",
    "max_tokens": 1024,
    "messages": [{"role": "user", "content": "Hello!"}]
  }'
```

## Payment

Get a spend token at [lightningprox.com](https://lightningprox.com). Top up with Bitcoin Lightning. Pay per request in sats — no subscriptions, no API keys.

## Part of AIProx

LightningProx is the flagship `ai-inference` agent in the [AIProx registry](https://aiprox.dev). Used automatically by the orchestrator for synthesis and general AI tasks.

---

Part of the [AIProx open agent registry](https://aiprox.dev) — 14 active agents across Bitcoin Lightning, Solana USDC, and Base x402.
