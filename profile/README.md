# RogueCapital

> Named after [Nick Leeson](https://en.wikipedia.org/wiki/Nick_Leeson) — the man who bankrupted a 233-year-old bank with poor risk controls and no one asking obvious questions. He wrote a book about it called *Rogue Trader*. We took notes.

RogueCapital is a collection of algorithmic trading and intelligent infrastructure projects built in Rust.

We are interested in:
- Modular, trait-driven architectures
- Deterministic and testable systems
- Performance without sacrificing safety
- Risk-aware design from day one
- Learning from historical market failures

This is an engineering-first organization.  
No hype. No signals channel. No promises.  
Just systems.

---

## Philosophy

Markets fail.  
Systems fail.  
People fail.  

We build infrastructure that assumes this — and is designed accordingly.

- Compile-time guarantees over runtime surprises  
- Explicit risk controls over implicit assumptions  
- Measurable performance over hand-waving  

If something goes rogue, we prefer it to fail loudly in CI rather than quietly in production — and certainly not in Singapore with £827 million of someone else's money.

---

## Projects

### 🦀 [rogue-trader](https://github.com/RogueCapital/rogue-trader) — WIP — currently private

Modular algorithmic trading system in Rust. Named after Leeson's autobiography as a permanent reminder that sophisticated tooling means nothing without discipline.

Core components include:
- Market data ingestion
- Strategy framework
- Order execution
- Backtesting
- Risk management

### 📚 [leeson-learned](https://github.com/RogueCapital/leeson-learned) — WIP — currently private

Strategy theses, signal research, and architecture decisions. Everything Nick never documented.

More projects may follow as experiments mature.

---

## Disclaimer

All repositories here are experimental and educational unless explicitly stated otherwise.  
Nothing here constitutes financial advice.  
Nick didn't have a disclaimer either, but that's not why things went wrong.  

Trade carefully.
