# Kimmo Zhang · 张睿诚

**LLM systems & AI infrastructure** · Computer Science M.S. student at HUST

Agent memory · Inference orchestration · KV cache infrastructure

[Portfolio](https://kimmozag.github.io/Intro4kimmo/#projects) · [Publications](https://kimmozag.github.io/Intro4kimmo/#research) · [Contact](https://kimmozag.github.io/Intro4kimmo/#contact) · [Try the LMCache calculator ↗](https://docs.lmcache.ai/_static/kv_cache_calculator.html)

## Selected work

<details open>
<summary><strong>NeuroMem</strong> · Streaming memory benchmark · ICML 2026, first author</summary>

Built a benchmark that interleaves writes and retrievals to measure how external LLM memory behaves as new information arrives.

[Paper](https://proceedings.mlr.press/v306/zhang26cw.html) · [Run the benchmark](https://github.com/RIDE-Lab/neuromem-bench#getting-started)

</details>

<details>
<summary><strong>SAGE</strong> · Dataflow orchestration · ICML 2026, co-author</summary>

Designed the DataStream API for composing LLM workflows and integrated NeuroMem as a backend for memory services.

[Paper](https://proceedings.mlr.press/v306/liu26co.html) · [Repository](https://github.com/RIDE-Lab/SAGE) · [Memory integration PR](https://github.com/RIDE-Lab/SAGE/pull/1276)

</details>

<details>
<summary><strong>LMCache</strong> · KV cache observability and capacity planning · Tencent internship</summary>

Worked on KV cache observability, trace replay, and capacity planning. Added Hunyuan and DeepSeek model support and fixed calculations in the open-source KV cache calculator.

[Repository](https://github.com/LMCache/LMCache) · [Calculator PR](https://github.com/LMCache/LMCache/pull/2834)

</details>

<details>
<summary><strong>vLLM-HUST</strong> · LLM inference on Ascend</summary>

Worked on model loading and deployment tooling for LLM inference on Ascend hardware.

[Repository](https://github.com/vLLM-HUST/vllm-hust)

</details>

<details>
<summary><strong>CANDOR-Bench</strong> · Streaming vector search · SIGMOD 2026</summary>

Contributed to research on continuous approximate nearest-neighbor search over evolving vector streams.

[Paper](https://doi.org/10.1145/3786630) · [Benchmark code](https://github.com/DataSysResearch/CANDOR-Bench)

</details>
