# Preston Winters

Solo builder. AI memory, consumer products, governance architecture.

The full circle:

```
  Demiurge  ──►  MyKonos  ──►  Ouroboros
  (engine)      (consumer)     (governance)

  How memory     What it       What memory
  should work    feels like    means at scale
```

Open-source the engine, build the consumer product on top, write the governance architecture this technology demands. One thesis across three layers: **personalization belongs to the person.**

---

## Active work

### [Demiurge](https://github.com/Preston2012/demi). The memory engine.

Refusal-first adaptive memory for AI agents. Quality-gated at the write boundary. Surfaces conflicts instead of hiding them. Hash-chain audit log for every read, write, and amendment.

TypeScript, SQLite + sqlite-vec + FTS5, BGE-small ONNX embeddings, SQLCipher encryption-at-rest. Ships as MCP server + REST API. Runs on a $6/mo ARM VPS.

Public benchmarks across 13 evaluations: LOCOMO, BEAM, LongMemEval, CloneMem, MemoryAgentBench, plus an in-house safety suite (FRAME-INJECT, FRAME-SYBIL, FRAME-AUDIT, VAULT) and product-correctness suite (attribution, paraphrase, ECE/Brier, recall@K, stale-memory). Live scorecard in the [demi repo README](https://github.com/Preston2012/demi).

### MyKonos

Personal AI companion built on Demiurge, with BYOK multi-model routing. The memory-active visual primitive lights up the UI when MyKonos pulls something it learned about you, instead of hiding the retrieval behind a black box.

Mobile-first. Live on my phone. First beta tester is reading the Ouroboros draft on it right now.

**Status:** shipping, proprietary. The reference consumer implementation of Memory Sovereignty Principles (below). The engine is open. The product is what it looks like when you actually use it.

### [Ouroboros](https://github.com/Preston2012/ouroboros). Governance architecture for the AI era.

A serious draft proposal for planetary-scale governance designed to compound on behalf of humanity rather than against it. Four layers: personal AI companion, AI representatives trained on each political unit's corpus, a thirteen-member adversarial AI oversight body, and direct human ratification on decisions of consequence.

Currently with trusted readers for v0.7 critique. Targeted release to SSRN, philpapers, Substack. Not social media.

This isn't a side project. It's the reason the engine and the companion exist. Memory, personalization, and AI mediation at scale require governance. Someone has to write the proposal.

---

## Methodology

### [AI Council](https://github.com/Preston2012/ai-council)

Run the same task across Claude, GPT, Gemini, Grok. Reconcile in one pass. Used across every project on this page. 500+ build sessions. 390+ documented rules.

### Memory Sovereignty Principles. Coming next.

A spec doc + benchmark harness for AI memory providers. Ten principles covering local-first, portable export, hard delete with verification, encryption with user-held keys, provenance disclosure, refusal-first injection, no cross-tenant leakage, right to amendment, no silent retraining, open audit log. Scorecard against seven providers including Demiurge.

Drafting now. Will land at [Preston2012/memory-sovereignty-principles](https://github.com/Preston2012/memory-sovereignty-principles).

---

## Shipped products

**StainSlayer** ([Google Play](https://play.google.com/store/apps/details?id=com.mycompany.stainslayerai), [App Store](https://apps.apple.com/us/app/stainslayer-ai/id6757208835)). AI-powered stain removal guidance. Photo + fabric type, returns step-by-step removal instructions tailored to the surface. Standard, Eco, Emergency, and Fun modes. Multi-language responses.

**[Baseline](https://baseline.marketing)** ([showcase](https://github.com/Preston2012/baseline-showcase)). Political intelligence platform. Tracks 100+ public figures across 4 AI providers. Consensus scoring detects bias no single model catches. 28 Flutter screens, 22 Supabase Edge Functions, 5,400+ analyzed statements.

---

## Stack

TypeScript, Dart/Flutter, Python, Supabase/PostgreSQL, SQLite + sqlite-vec, ONNX Runtime, MCP. Claude, GPT, Gemini, Grok, DeepSeek APIs.

## Contact

[baseline.marketing](https://baseline.marketing) · [preston@baseline.marketing](mailto:preston@baseline.marketing) · [LinkedIn](https://linkedin.com/in/prestonwinters)

---

*If you are hiring, building memory infrastructure, or working on AI governance at scale, get in touch.*
