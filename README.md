```
┌──────────────────────────────────────────────────────────┐
│                                                          │
│   yair etziony                                           │
│   infrastructure · berlin · 30 years in the machine room │
│                                                          │
│   founder, false systems                                 │
│   infrastructure for agents as first-class operators     │
│                                                          │
└──────────────────────────────────────────────────────────┘
```

Production infrastructure assumes a human operator. False Systems
assumes the operator is an agent. Every tool in this stack is built
to be read, understood, and operated by software — not just humans.

---

### false systems

**observe**
- [`ahti`](https://github.com/yairfalse/ahti) — causal event graph over infrastructure state `rust`

**act**
- [`sykli`](https://github.com/yairfalse/sykli) — pipeline engine, no yaml `elixir`
- [`nopea`](https://github.com/false-systems/nopea) — continuous delivery with deployment memory `go`
- [`rauha`](https://github.com/yairfalse/rauha) — container runtime with ebpf lsm isolation `rust`
- [`rauta`](https://github.com/yairfalse/rauta) — gateway api proxy `rust`

**connect**
- [`polku`](https://github.com/false-systems/polku) — typed event routing between agents `go`
- [`kerto`](https://github.com/false-systems/kerto) — persistent agent context `go`

**foundations**
- [`vaisto`](https://github.com/false-systems/vaisto) — scheme with hindley-milner types, targeting beam `elixir`
- [`vaisto_bpf`](https://github.com/yairfalse/vaisto_bpf) — s-expression to bpf bytecode compiler `elixir`
- [`ilmari`](https://github.com/yairfalse/ilmari) — kubernetes sdk for go, code-only `go`
- [`seppo`](https://github.com/yairfalse/seppo) — kubernetes sdk for rust `rust`

---

[false-systems.com](https://www.false-systems.com) · [linkedin](https://www.linkedin.com/in/yair-etziony/)
