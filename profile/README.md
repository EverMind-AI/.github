<div align="center" id="readme-top">

![banner-gif](https://github.com/user-attachments/assets/2ab7644e-bc6c-43b6-9937-7f13c85ede1e)

<p align="center">
  <a href="https://x.com/evermind"><img src="https://img.shields.io/badge/EverMind-000000?labelColor=gray&style=for-the-badge&logo=x&logoColor=white" alt="X"></a>
  <a href="https://discord.gg/gYep5nQRZJ"><img src="https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fdiscord.com%2Fapi%2Fv10%2Finvites%2FgYep5nQRZJ%3Fwith_counts%3Dtrue&query=%24.approximate_presence_count&suffix=%20online&label=Discord&color=404EED&labelColor=gray&style=for-the-badge&logo=discord&logoColor=white" alt="Discord"></a>
  <a href="https://github.com/EverMind-AI/EverOS/discussions/67"><img src="https://img.shields.io/badge/WeChat-EverMind-07C160?labelColor=gray&style=for-the-badge&logo=wechat&logoColor=white" alt="WeChat"></a>
  <a href="https://github.com/EverMind-AI/EverOS/blob/main/LICENSE"><img src="https://img.shields.io/badge/License-Apache%202.0-2196F3?labelColor=gray&style=for-the-badge" alt="License"></a>
</p>


</div>

<br>

## Repositories

<table>
<tr>
<td width="50%" valign="top">

[![banner-gif](https://github.com/user-attachments/assets/96bf6df0-39e3-4c85-b8a5-240e29136e1b)](https://github.com/EverMind-AI/EverOS)


#### EverOS

Build, evaluate, and integrate long-term memory for self-evolving agents.

[Paper](https://arxiv.org/abs/2601.02163)

</td>
<td width="50%" valign="top">

[![banner-gif](https://github.com/user-attachments/assets/f1c3b962-ae28-405d-acf0-67c153b786fd)](https://github.com/EverMind-AI/MSA)

#### MSA

A scalable, end-to-end trainable latent-memory framework for 100M-token contexts.

[Paper](https://arxiv.org/abs/2603.23516)

</td>
</tr>
</table>

<br>

## Methods

Methods are production-ready memory architectures that give agents persistent, structured long-term memory. Each can be used standalone or composed together depending on your use case.

<table>
<tr>
<td width="50%" valign="top">

![banner-gif](https://github.com/user-attachments/assets/1bbead72-7a6b-4b19-88f2-5bfc8433e3aa)


#### EverCore

A self-organizing memory operating system inspired by biological imprinting. Extracts, structures, and retrieves long-term knowledge from conversations — enabling agents to remember, understand, and continuously evolve.

[Paper](https://arxiv.org/abs/2601.02163) · [Docs](methods/evermemos/)

</td>
<td width="50%" valign="top">

![banner-gif](https://github.com/user-attachments/assets/b63d8735-ea94-4ed6-9c0c-a11b55b1a2a4)

#### HyperMem

A hypergraph-based hierarchical memory architecture that captures high-order associations through hyperedges. Organizes memory into topic, event, and fact layers for coarse-to-fine long-term conversation retrieval. LoCoMo 92.73%.

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

![banner-gif](https://github.com/user-attachments/assets/f6f11c3c-7977-4c3b-8c2b-f7cf13e8f93a)

#### EverMemBench

Three-layer memory quality evaluation: factual recall, applied reasoning, and personalized generalization. Evaluates memory systems and LLMs under a unified standard.

[Paper](https://arxiv.org/abs/2602.01313) · [Dataset](https://huggingface.co/datasets/EverMind-AI/EverMemBench-Dynamic) · [Docs](benchmarks/EverMemBench/)

</td>
<td width="50%" valign="top">

![banner-gif](https://github.com/user-attachments/assets/79fd03fe-cd6d-4b92-88d7-d66886d31799)

#### EvoAgentBench

Agent self-evolution evaluation — not static snapshots, but longitudinal growth curves. Measures transfer efficiency, error avoidance, and skill-hit quality through controlled experiments with and without evolution.

[Docs](benchmarks/EvoAgentBench/)

</td>
</tr>
</table>