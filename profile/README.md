<div align="center" id="readme-top">

![banner-gif](https://github.com/user-attachments/assets/d4c9fc90-b116-494d-9312-c9cc11e0652a)

<p align="center">
  <a href="https://x.com/evermind"><img src="https://img.shields.io/badge/EverMind-000000?labelColor=gray&style=for-the-badge&logo=x&logoColor=white" alt="X"></a>
  <a href="https://huggingface.co/EverMind-AI"><img src="https://img.shields.io/badge/🤗_HuggingFace-EverMind-F5C842?labelColor=gray&style=for-the-badge" alt="HuggingFace"></a>
  <a href="https://discord.gg/gYep5nQRZJ"><img src="https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fdiscord.com%2Fapi%2Fv10%2Finvites%2FgYep5nQRZJ%3Fwith_counts%3Dtrue&query=%24.approximate_presence_count&suffix=%20online&label=Discord&color=404EED&labelColor=gray&style=for-the-badge&logo=discord&logoColor=white" alt="Discord"></a>
  <a href="https://github.com/EverMind-AI/EverOS/discussions/67"><img src="https://img.shields.io/badge/WeCom-EverMind_社区-07C160?labelColor=gray&style=for-the-badge&logo=wechat&logoColor=white" alt="WeChat"></a>
</p>

</div>

<br>

## Repositories

Core repositories in the EverMind ecosystem. EverOS packages the methods, benchmarks, and use cases for building self-evolving agents, while MSA focuses on the model architecture that makes extreme-scale memory practical.

<table>
<tr>
<td width="50%" valign="top">

### EverOS

An open framework for building self-evolving agents with persistent long-term memory. It brings together memory architectures, open benchmarks, and real use cases so teams can build, evaluate, and integrate memory systems in one place.

[Repo](https://github.com/EverMind-AI/EverOS) · [Paper](https://arxiv.org/abs/2601.02163)

</td>
<td width="50%" valign="top">

### MSA

A research repository for Memory Sparse Attention, an end-to-end trainable latent-memory framework that scales long-context reasoning to 100M tokens. It combines sparse routing, KV cache compression, and memory-parallel inference to keep retrieval and generation in a single differentiable system.

[Repo](https://github.com/EverMind-AI/MSA) · [Paper](https://arxiv.org/abs/2603.23516)

</td>
</tr>
</table>

<br>

## Architecture Methods

Methods are memory architectures you can choose from — production-ready implementations that give agents persistent, structured long-term memory. Pick the one that fits your use case, or compose them together.

<table>
<tr>
<td width="50%" valign="top">

### EverCore

A self-organizing memory operating system inspired by biological imprinting. Extracts, structures, and retrieves long-term knowledge from conversations — enabling agents to remember, understand, and continuously evolve.

LoCoMo **93.05%** · LongMemEval **83.00%**

[Paper](https://arxiv.org/abs/2601.02163) · [Docs](methods/EverCore/)

</td>
<td width="50%" valign="top">

### HyperMem

A hypergraph-based hierarchical memory architecture that captures high-order associations through hyperedges. Organizes memory into topic, event, and fact layers for coarse-to-fine long-term conversation retrieval.

LoCoMo **92.73%**

[Paper](https://arxiv.org/abs/2604.08256) · [Docs](methods/HyperMem/)

</td>
</tr>
</table>

<br>

## Benchmarks

Benchmarks are designed as **open public standards**. Any memory architecture or agent framework can be evaluated under the same ruler.

<table>
<tr>
<td width="50%" valign="top">

### EverMemBench

Three-layer memory quality evaluation: factual recall, applied reasoning, and personalized generalization. Evaluates memory systems and LLMs under a unified standard.

[Paper](https://arxiv.org/abs/2602.01313) · [Dataset](https://huggingface.co/datasets/EverMind-AI/EverMemBench-Dynamic) · [Docs](benchmarks/EverMemBench/)

</td>
<td width="50%" valign="top">

### EvoAgentBench

Agent self-evolution evaluation — not static snapshots, but longitudinal growth curves. Measures transfer efficiency, error avoidance, and skill-hit quality through controlled experiments with and without evolution.

[Docs](benchmarks/EvoAgentBench/)

</td>
</tr>
</table>
