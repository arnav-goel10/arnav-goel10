# Hey, I'm Arnav 👋

Final-year CS undergrad at the **National University of Singapore**. I like building things that rank, retrieve, or predict, then checking whether the numbers behind them actually hold up.

🔭 **Right now:** an LLM-training final-year project under Assoc Prof Eric Han, extending nanochat through pretraining, supervised fine-tuning, and RL alignment on the NUS SoC GPU cluster.

## 🚀 Stuff I've built

### 🎵 [Music Trend Recommender](https://github.com/arnav-goel10/music-trend-recommender)
Tries to catch songs on the way up. Blends signals from six chart sources, shows exactly *why* each track scored what it did, and uses Gumbel-Top-k sampling so it explores instead of always playing it safe. Scored by replaying weeks in order, so it never gets to peek at the future.

### 📉 [Chronos LINK Forecasting](https://github.com/arnav-goel10/chronos-link-forecasting)
Probabilistic time-series forecasting where the hard part is not the model, it's not lying to yourself. Backward-only feature joins, temporal splits, and quantile metrics that refuse to score misaligned data. 55 tests, including 300 randomised probes that no feature ever leaks in from the future.

### 🎙️ [Whisper for Singaporean English](https://github.com/arnav-goel10/whisper-singapore-english)
LoRA adaptation of whisper-tiny for Singaporean-accented speech. Training 1.4% of a 39M model (540,672 parameters) took it from 66.2% to 23.8% WER, beating zero-shot whisper-small at 6x fewer parameters. Ships the WER harness, not the licensed corpus.

### ⚡ [Select to AI](https://github.com/arnav-goel10/select-to-ai)
Highlight text anywhere, fire it at ChatGPT, Gemini, Claude or Perplexity, or type `ai` in the address bar and it routes sites, questions and tasks. The browser agent plans its work, checks every action actually changed the page, must validate its answer before finishing, and asks before anything irreversible. ~1,000 users and Chrome Web Store **Featured**. Your API keys never leave your browser.

### 📈 [Polymarket Pricing Research](https://github.com/arnav-goel10/polymarket-pricing-research)
Rust playground for prediction-market pricing: order-book reconstruction, lead-lag and order-flow signals, calibration, replay backtests. Strictly paper-only, no live trading.

## 🛠️ Tools of choice

`Python` `Rust` `TypeScript` `Java` `Swift` `SQL`
`PyTorch` `Transformers` `React` `Flask` `Docker` `AWS`

## 💼 Where I've been

- 🤖 **AI engineering** @ iEnergy Digital: safety and compliance agent on AWS with hybrid dense/BM25 retrieval and SQL tools
- 🔧 **Backend** @ NUS IT: three internal platforms, SSO and per-route RBAC, and a sync engine with 167 tests behind it
- 🥽 **Vision Pro research** @ NUS × Apple: a cognitive-assessment app built in the Interactive 3D Design Lab and piloted with stroke patients at NUH, written up for ISMAR 2026 (closed source, since it's clinical research)
- 🧪 **Also fine-tuned** Qwen3-4B with BitFit for insurance-policy reasoning

## 📫 Say hi

[LinkedIn](https://www.linkedin.com/in/arnav10/) · [Email](mailto:arnav@u.nus.edu)
