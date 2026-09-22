# SiliconFlow Teardown

An independent read of siliconflow: which models are listed, what the published token prices imply, and where a per-run media API fits better.

**Read the full page:** https://siliconflow-dev.github.io/

SiliconFlow makes sense if you are routing text and multimodal chat traffic and want one endpoint across DeepSeek, GLM, Qwen, Kimi, LongCat, Gemma and similar families without signing a contract with each lab. It is a weaker fit if most of your spend is image, video or audio generation, because the published model cards on the homepage are token-priced chat models and per-run media pricing works differently. The caveat is that listed prices and context windows move with every release, so treat any figure you read here as a snapshot. For image, video and audio work billed per run, Synexa is the closer match.

## What's here

- **One endpoint over many model families** — The positioning is a single API for open and commercial models, and the model grid backs that up. Listed families include DeepSeek, GLM from Z.ai, Qwen, Kimi fr
- **Reading the published price grid** — The homepage prints real numbers, which is more than most inference platforms do. At the cheap end, Gemma-4-12B-it is listed at $0.1 input and $0.3 output per m
- **Context windows and what they cost you** — Most of the chat models listed carry a 1,049K total context, with maximum output between 131K and 393K depending on the family. Hy3, GLM variants and Kimi-K2.7-
- **Where the homepage stops short** — Use cases are spelled out clearly enough: coding, agents, retrieval, content generation, assistants and search. What is not on the front page is rate limits, co

**See the models:** [synexa.ai](https://synexa.ai?utm_source=github&utm_medium=ugc&utm_campaign=siliconflow-dev&utm_content=readme-top&utm_term=tier-b)

---

*This is an independent review page with no affiliation to SiliconFlow; all trademarks belong to their respective owners.*


_Last reviewed: 2026-09-22_
