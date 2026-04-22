### Hi, I'm Siyuan 👋

MS student at Sun Yat-sen University, Guangzhou. I spend most of my time
pushing tiny multimodal models into places they don't fit — small GPUs,
weird modalities, short context budgets.

What I'm interested in right now:

- 🔬 **small MLLMs** — how much capability can you squeeze into ≤ 3B params
  before something breaks
- 🎙️ **speech tokenizers** for LLM-style modeling — semantic vs. acoustic
  tradeoffs, codec choice, semantic preservation under compression
- 🎯 **honest evaluation** — benchmarks that actually surface where small
  models fail, not just leaderboards for the frontier

A few projects I've been tinkering on:

- [`picovlm`](https://github.com/JUL-404/picovlm) — a compact VLM you can
  pretrain on a single 24 GB card, SigLIP + TinyLlama glued together
- [`speechcodec-arena`](https://github.com/JUL-404/speechcodec-arena) —
  one config → same metrics across EnCodec / DAC / SpeechTokenizer / XCodec
- [`mm-nano-bench`](https://github.com/JUL-404/mm-nano-bench) — eval
  benchmark focused on small VLM failure modes (counting, OCR, spatial)

Usually writing PyTorch. Always happy to chat about anything above.
