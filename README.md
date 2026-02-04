# Lens

Lens is an experimental tool for examining how narratives are constructed across different information ecosystems.

It does not verify facts. It does not decide who is right.

Lens focuses on one question only:

**How does the same event become different realities?**

**Try Lens (GPT Store):** https://chatgpt.com/g/g-697f26ee4de08191984b80949cb5aeea-lens

## Access & Model

Lens relies on browsing/search for source retrieval, so it requires an account with access to those capabilities (typically a subscription tier).

For best analytical quality, use the latest reasoning model (at release: **ChatGPT 5.2 Thinking**).

---

## What Lens Does

When given a news link or a topic, Lens:

- Places reports from different information ecosystems side by side
- Analyzes differences in:
  - rhetorical framing
  - time anchors
  - causal attribution
  - authority selection
  - systematic omissions
- Makes visible how these differences shape interpretation

Lens is designed to expose *structure*, not to arbitrate truth.

---

## What Lens Is Not

Lens is **not**:

- a fact-checking system  
- a stance generator  
- a sentiment optimizer  
- a propaganda tool  
- a shortcut to “the correct view”

If your goal is to quickly confirm a position or to win an argument,  

Lens is probably not what you are looking for.

---

## Who Lens Is For

Lens is not built for “more informed” users.

It is built for people who are still willing to question their own understanding.

If you are comfortable with ambiguity,  

if you are curious about how narratives stabilize meaning,  

if you are interested in *how* understanding forms rather than *what* to believe,  

Lens may be useful to you.

---

## How to Use

### Option 1: Use the GPT Agent

Lens is currently available as a GPT agent.

You can:

- paste a news article URL
- or enter a topic (e.g. a geopolitical event)

Lens will attempt to surface contrasting narrative structures and present a structured comparison.

> Note: Lens requires access to full articles to function properly.  

> If a source cannot be accessed, it will be explicitly stated. Lens will try to find a replacement source with similar content.

Native browsing/search can sometimes return only partial text due to paywalls, dynamic rendering, or site restrictions. If full text cannot be accessed, Lens will **replace the source** with a reachable full-text alternative (mirrors, syndications, official releases).

If you run your own setup, you may optionally integrate a trusted full-text reader of your choice to improve retrieval stability. This is an **implementation detail** — the protocol remains the same: **full text, or no analysis**.

---

### Option 2: Fork the Prompt

All prompts, analysis frameworks, and workflows are open.

You are encouraged to:

- inspect the logic
- modify the framework
- build alternative lenses
- adapt it to other languages or contexts

Lens is intended to be forked.

---

## Project Structure

- `README.md` — project overview and usage
- `MANIFESTO.md` — why this project exists
- `ETHOS.md` — boundaries, risks, and strong recommendations
- `/prompts` — core prompt logic
- `/examples` — selected sample analyses (if any)

---

## Transparency and Limits

Lens is open not because it is correct,  

but because it is inspectable.

All outputs are constrained by:

- prompt design
- model weights
- training data
- historical context

Lens is itself a lens.

---

## License

This project is released under an open-source license.

See `LICENSE` for details.

---

## Final Note

Lens is not meant to be a place where you stop.

If using Lens makes you more certain too quickly,  

you are probably using it wrong.

If it makes you pause, hesitate, or re-examine assumptions,  

then it is doing what it was designed to do.