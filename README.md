<img src="assets/banner.svg" alt="mizuki0x. agent infrastructure, Solana protocol engineering, formal verification." width="100%" />

```text
$ covenant audit tail --identity mizuki0x
ok  identity   mizuki0x · protocol engineer · @open-covenant
ok  scope      agent runtimes and audit layers
ok  scope      solana programs (anchor, pinocchio)
ok  scope      formal verification (kani)
ok  scope      payment rails for autonomous agents
ok  anchor     every claim below has a receipt
```

### 証 shō · proof

An operating layer for long-running engineering agents. Rust daemon, signed capabilities, append-only audit, commit-scoped provenance.

<p>
  <a href="https://github.com/open-covenant/covenant">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=open-covenant&repo=covenant&theme=transparent&hide_border=true" alt="open-covenant/covenant" />
  </a>
  <a href="https://github.com/open-covenant/covenant-skill">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=open-covenant&repo=covenant-skill&theme=transparent&hide_border=true" alt="open-covenant/covenant-skill" />
  </a>
</p>

### 絆 kizuna · bonds

Programs and tooling for agents that transact on chain. Escrow, reputation, and dispute flows, plus a CLI for simulating and operating perp markets.

<p>
  <a href="https://github.com/mizuki0x/kamiyo-protocol">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=mizuki0x&repo=kamiyo-protocol&theme=transparent&hide_border=true" alt="mizuki0x/kamiyo-protocol" />
  </a>
  <a href="https://github.com/mizuki0x/percli">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=mizuki0x&repo=percli&theme=transparent&hide_border=true" alt="mizuki0x/percli" />
  </a>
</p>

### 守 mamori · protection

Kani proof harnesses for Solana program invariants, published as [`kamiyo-kani`](https://crates.io/crates/kamiyo-kani). Signature verification for x402-style payments on EVM and SVM.

<p>
  <a href="https://github.com/mizuki0x/kamiyo-kani">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=mizuki0x&repo=kamiyo-kani&theme=transparent&hide_border=true" alt="mizuki0x/kamiyo-kani" />
  </a>
  <a href="https://github.com/mizuki0x/x402-sig-kit">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=mizuki0x&repo=x402-sig-kit&theme=transparent&hide_border=true" alt="mizuki0x/x402-sig-kit" />
  </a>
</p>

### 試 kokoromi · trials

Experiments and one-off studies. The method ships with the results.

<p>
  <a href="https://github.com/mizuki0x/omamori">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=mizuki0x&repo=omamori&theme=transparent&hide_border=true" alt="mizuki0x/omamori" />
  </a>
  <a href="https://github.com/mizuki0x/solana-cu-bench">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=mizuki0x&repo=solana-cu-bench&theme=transparent&hide_border=true" alt="mizuki0x/solana-cu-bench" />
  </a>
</p>

### Receipts

Numbers on this page resolve to something you can run or fetch.

| claim | number | source |
|---|---:|---|
| Rust tests discovered from source in covenant | 2538 | [open-covenant/covenant](https://github.com/open-covenant/covenant) |
| `#[kani::proof]` harnesses in the kamiyo-kani crate | 56 | [proof table](https://github.com/mizuki0x/kamiyo-kani#proof-coverage) |
| entrypoint baseline, pinocchio vs solana-program | 65 vs 787 CU | [RESULTS.md](https://github.com/mizuki0x/solana-cu-bench/blob/main/RESULTS.md) |
| x402-sig-kit tests, green on Node 20 and 22 | 48 | [CI](https://github.com/mizuki0x/x402-sig-kit/actions) |
| omamori charm evaluation inside a Solana instruction | 578 CU | [measured cost](https://github.com/mizuki0x/omamori#measured-cost) |
| whitepaper DOI | 10.5281/zenodo.20134416 | [doi.org](https://doi.org/10.5281/zenodo.20134416) |

### Upstream

Merged work in codebases I don't own.

- [model-checking/kani#4547](https://github.com/model-checking/kani/pull/4547) · SARIF output for GitHub Code Scanning, in AWS's Kani model checker
- [x402-foundation/x402#1108](https://github.com/x402-foundation/x402/pull/1108) · KAMIYO in the x402 ecosystem
- [Swader/x402facilitators#2](https://github.com/Swader/x402facilitators/pull/2) · KAMIYO as a multi-chain payment verification facilitator
- [OOBE-PROTOCOL/synapse-client-sdk#10](https://github.com/OOBE-PROTOCOL/synapse-client-sdk/pull/10) · KAMIYO protocol tools for the Synapse client SDK

### Covenant

Covenant is an operating layer for autonomous engineering agents: identity, permissions, audit.

[opencovenant.org](https://opencovenant.org) · [![DOI](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.20134416-blue)](https://doi.org/10.5281/zenodo.20134416)

---

<p>
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=mizuki0x&theme=transparent&hide_border=true&count_private=true&show_icons=true" alt="GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=mizuki0x&layout=compact&theme=transparent&hide_border=true" alt="Most used languages" />
</p>
