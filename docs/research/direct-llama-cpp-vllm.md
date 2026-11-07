# Direct llama.cpp / vLLM

> RESEARCH INCOMPLETE. Public-source bootstrap reviewed 2026-11-07; [#5 control](https://github.com/Homes-That-Behave-Well-LLC/home_steward/issues/5).

## Official documentation

- [llama.cpp](https://github.com/ggml-org/llama.cpp): current `ggml-org` upstream, C/C++ inference,
  quantized GGUF, library/CLI and OpenAI-compatible server.
- [vLLM](https://github.com/vllm-project/vllm): high-throughput serving, OpenAI-compatible API,
  tool/reasoning/structured-output support and multiple accelerator backends.

These are published project capabilities, not executed local benchmarks.
Top-level licenses were not independently re-fetched in this bounded pass; exact version/terms
remain a review item rather than asserting conventional MIT/Apache labels.

## Fit and unknowns

These are inference engines, not full governed household knowledge applications or MCP permission
systems. Wrappers and surrounding services must provide authenticated exposure, scope, retrieval,
source/derived lifecycle, memory, administration, upgrades and recovery.

Compare hardware/backend support, context/model formats, concurrency, quality/latency and coding
workload under explicit configuration. Include Owner integration/security/maintenance time in TCO.
No engine built/installed, model selected or endpoint tested.
