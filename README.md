<img src="header.svg" alt="Yair Etziony: infrastructure, kernels, agents." width="100%">

I got interested in networks, went off to study history and philosophy, and somehow ended up spending 30 years working with infrastructure. These subjects have started to converge.

I'm interested in what sits underneath the abstractions: Linux kernels, execution, isolation, authority, and evidence. Especially now that the thing operating a computer isn't necessarily a person.

I founded [False Systems](https://false-systems.com) to explore some of these problems. I like systems whose behaviour can be examined independently, and tools that are reasonably clear about what they cannot do.

## Tools for working with coding agents

Most of my code is now written with agents. These are the four small tools I use to do that every day, open and MIT licensed. Each works alone; together they take a change from an agent's first prompt to main, checked and reviewed by a second agent.

<img src="loop.svg" alt="A piece of work moves through five steps: start, check, review, land, deploy. toimija starts it, sykli does the other four, ohjaa holds what agents know, and vessa counts what agents used." width="100%">

| Tool | What it does |
|---|---|
| **[toimija](https://github.com/false-systems/toimija)** | Starts a coding agent with the facts of the repository, and shows who is working where. |
| **[sykli](https://github.com/false-systems/sykli)** | Runs the checks you declare and keeps proof. A second agent reviews the change before it reaches main. |
| **[ohjaa](https://github.com/false-systems/ohjaa)** | Holds what your agents are told: decisions, lessons, facts. Anyone proposes; a person decides. |
| **[vessa](https://github.com/false-systems/vessa)** | Counts what your agents used, from the records they leave on disk. |

Start with [Your first loop](https://github.com/false-systems/toimija/blob/main/docs/first-loop.md): one change, through all four.

## Linux and the kernel

- **[Syvä](https://github.com/false-systems/syva)**: workload confinement through eBPF and BPF-LSM, without replacing the container runtime.
- **[Tapio](https://github.com/false-systems/tapio)**: turning selected Linux kernel failures into structured evidence.

There's also **Valvo**, a research project asking a more fundamental question: what would it take for Linux to have coherent, first-class security domains? Identity, file-descriptor authority, inheritance, revocation, and the uncomfortable gaps between existing mechanisms.

Some of this work is practical engineering. Some of it is research. Occasionally the research explains why the practical engineering is harder than expected.

## Language models

- **[Vaisto](https://github.com/yairfalse/vaisto)**: typed operations and pipelines for working with language models, meant to outlive the models that run them.

## Sound

I compose music and build some of the instruments I play it with.

- **[Aste](https://github.com/yairfalse/aste)**: a family of six audio instruments with original DSP, restrained industrial interfaces and unusually strict real-time testing: a hard mastering compressor, an equalizer with nonlinear bands, a programmed-current synthesizer, a tape-inspired memory instrument, a generative rhythm instrument and a playable reverb. Working prototypes, not released yet.
- **[Soiva](https://github.com/yairfalse/soiva)**: live coding music on the BEAM. Patterns are processes, and everything can be morphed while it plays.

Earlier instruments: [Endurance](https://github.com/yairfalse/endurance), [Inversion](https://github.com/yairfalse/inversion), [Radiance](https://github.com/yairfalse/radiance) and [Enforcement](https://github.com/yairfalse/enforcement).

## Elsewhere

I'm a Claude Ambassador, chair the CD Foundation Ambassador cohort, and help organize infrastructure and open-source communities in Berlin. I remain interested in the history of technology, and have a particular affection for old operating systems.

**I build my own containers because I can.**

<sub>[false-systems.com](https://false-systems.com) · Berlin · computing as craft</sub>
