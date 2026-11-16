![Kimmo Zhang — LLM Systems & AI Infrastructure](./assets/profile-banner.png)

<p align="center">
  <strong>张睿诚 · Computer Science M.S. student at HUST</strong><br>
  Agent memory · Inference orchestration · KV cache infrastructure
</p>

<p align="center">
  <a href="https://kimmozag.github.io/Intro4kimmo/#projects"><strong>Projects ↗</strong></a>
  &nbsp;·&nbsp;
  <a href="https://kimmozag.github.io/Intro4kimmo/#research"><strong>Publications ↗</strong></a>
  &nbsp;·&nbsp;
  <a href="https://kimmozag.github.io/Intro4kimmo/#contact"><strong>Contact ↗</strong></a>
</p>

## Research & systems

- **NeuroMem** &nbsp; `ICML 2026 · First author`<br>
  Built a benchmark for external LLM memory with interleaved writes and retrievals.<br>
  [Paper](https://proceedings.mlr.press/v306/zhang26cw.html) · [Benchmark code](https://github.com/RIDE-Lab/neuromem-bench)

- **SAGE** &nbsp; `ICML 2026 · Co-author`<br>
  Designed the DataStream API for composing LLM workflows and integrated NeuroMem as a backend for memory services.<br>
  [Paper](https://proceedings.mlr.press/v306/liu26co.html) · [Repository](https://github.com/RIDE-Lab/SAGE) · [Memory integration PR](https://github.com/RIDE-Lab/SAGE/pull/1276)

- **CANDOR-Bench** &nbsp; `SIGMOD 2026`<br>
  Contributed to research on continuous approximate nearest-neighbor search over evolving vector streams.<br>
  [Paper](https://doi.org/10.1145/3786630) · [Benchmark code](https://github.com/DataSysResearch/CANDOR-Bench)

## Inference infrastructure

- **LMCache** &nbsp; `Tencent internship`<br>
  Worked on KV cache observability, trace replay, and capacity planning. Added Hunyuan and DeepSeek model support and fixed calculations in the open-source KV cache calculator.<br>
  [Repository](https://github.com/LMCache/LMCache) · [Calculator PR](https://github.com/LMCache/LMCache/pull/2834)

- **vLLM-HUST**<br>
  Worked on model loading and deployment tooling for LLM inference on Ascend hardware.<br>
  [Repository](https://github.com/vLLM-HUST/vllm-hust)
