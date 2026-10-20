# Repolex Knowledge Graph of klen/peewee_migrate

RDF knowledge graph data for [klen/peewee_migrate](https://github.com/klen/peewee_migrate), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [rlex](https://github.com/repolex-ai/rlex) query tool:

```bash
cargo install --git https://github.com/repolex-ai/rlex
```

Verify the install:

```bash
rlex --help
```

**rlex is designed to be used primarily by LLMs in a terminal.** Start up your favorite AI assistant and ask it to use rlex. It handles the SPARQL — you just ask questions in plain English.

To load this repo's data:

```bash
rlex download klen/peewee_migrate
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1d089f5eee44b5d4f45fd58616436ed29cb8393c
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 1d089f5eee44b5d4f45fd58616436ed29cb8393c
│           └── chunk-001.nq.gz
├── blob
│   ├── 029c7ca145e323af4163159b5bb4b8c525977221.nq.gz
│   ├── 05f1a35814c978e3c47f5f9839db4f01c000d957.nq.gz
│   ├── 0827d66c1b15e5f4cd4aed8b43901e38c6102b7c.nq.gz
│   ├── 0a6ee958310ca78a98bf4803c291d5898c7fd5b4.nq.gz
│   ├── 11dd12585d364d996451bf0659de84f64b147e86.nq.gz
│   ├── 1b5b8b17e22461525a04cef30db9f8d86b812215.nq.gz
│   ├── 23083ef94d3f223df0a57d34443229fb29f21e11.nq.gz
│   ├── 23c5c150f58bdd129447223d88288e859f8cccb1.nq.gz
│   ├── 29cd1bde99e4fefef3641478f5a312d203f2f096.nq.gz
│   ├── 2d51f8abce5cd7d3ef107f22d3eb85d2b7f82562.nq.gz
│   ├── 3b567ebb4335a39d92ad4a5855cb55357f4489d9.nq.gz
│   ├── 3c5d77a86d58d8618550aa4a30c58d0404336292.nq.gz
│   ├── 3dde510e3fe22a182e0a232c2256be2da9383c7b.nq.gz
│   ├── 3e51b33018a19547c4b1b9aeaf13a5ed208c41dc.nq.gz
│   ├── 40d3699949ac7635b105eb382006cf4e099c6ef5.nq.gz
│   ├── 45eac4b788f76bcc70335bd1a5cc647ddc546602.nq.gz
│   ├── 49b0bd7a70ac2b59898973a794764e50b28b438e.nq.gz
│   ├── 49df105ad2e74da5ef06c9eaa9043061ea2d47d7.nq.gz
│   ├── 55b4d43ea9815e78d5444ac22da4dfbee5f17a83.nq.gz
│   ├── 56c27b221f1591c28ff1f16942bdaf780e8ff5b2.nq.gz
│   ├── 5cc5c746b653c7b0bc54bdca71f33db6393fe596.nq.gz
│   ├── 5dfc7eb7a30ddf5340fa4ad271ff8ea12cff7d20.nq.gz
│   ├── 5f1d5686f3dc12105665875988bbe0b90d32c2bc.nq.gz
│   ├── 61cfb8595cf320973a39276e1278fe85af939e78.nq.gz
│   ├── 666ce2a519fd8f0c3599a11f968422b82612ca92.nq.gz
│   ├── 67f4bb51fc57bf59a944bb3b36f38afbf1a6910f.nq.gz
│   ├── 6a98381d41688ac0ec84b07bfee22efbade669bd.nq.gz
│   ├── 6cbde40b8d3470da60853bf6b37ac0909d84cc47.nq.gz
│   ├── 6ddc8ab85f38771f0d0376f42cf39aab447fecdf.nq.gz
│   ├── 7772a95e23d59a0587daf3154dff4c563d71e3b3.nq.gz
│   ├── 78df056a6afd6b2f7c5a8695635380a19f30acd9.nq.gz
│   ├── 7a3f07ab83552f47a8705fa5d22729a324a2f71a.nq.gz
│   ├── 854a1acfb8756796cf0e954783116a3a06a0e621.nq.gz
│   ├── 8c2ea7417640b2f1ba4eec0e63b12dae5fa025c8.nq.gz
│   ├── 8f9ba978b63e3c658a8e7d748d0fc37c5d1296be.nq.gz
│   ├── 94adf12e80495590028a450b5adf2f3df324d2ae.nq.gz
│   ├── 958812e0e0193f57686788e138119c81fc451153.nq.gz
│   ├── 99e21de7f8cf5704b7fe1f6e5b571396a6186a53.nq.gz
│   ├── 9ec95682eae7c15872be99012836852033f8d152.nq.gz
│   ├── b0b99cc1b1364b2f8b7f19f80e930f9a13677bd1.nq.gz
│   ├── b0ef7a96ff8e7e3772bef391d95ff593bf132f09.nq.gz
│   ├── bda938644a779e4bd2784a4ae851aaa4fb736dd3.nq.gz
│   ├── bfc10ef398aef5c333135b79b37f40cb81aa3ae9.nq.gz
│   ├── c493a1ff14d2de36b846804cace1d3a261c18d86.nq.gz
│   ├── c834bc3db301f80bb3d0d5b9322d8b591dc2c904.nq.gz
│   ├── c8dd3493f90dd88c914c8895e813ec8a8b6badb3.nq.gz
│   ├── ca56a1c488b9698b77cc22070dae7ba59f6e1769.nq.gz
│   ├── ce10b6fee5e677805fa62b60ed4baaa71fda4ff6.nq.gz
│   ├── e669deeabe1654ee8646f5a13a039bacd5cb1745.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e728d03676c20ba87a39556e60b642f5df17ebde.nq.gz
│   ├── e8e25e4ce09ee8d5e9f81939e1dc4ceaabe46e1e.nq.gz
│   ├── f72e17b1b32a1f9586e69d7aa03ff07648bb8fb5.nq.gz
│   └── fe7bdf6384b977562f195aa3ad60e8b70f89dfb3.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 1d089f5eee44b5d4f45fd58616436ed29cb8393c.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 62 files
```

| Directory | What it contains |
|-----------|-----------------|
| `blob/` | Per-file AST graphs, content-addressed by git blob SHA. Each file in the source repo gets its own graph. |
| `aggregate/ast/` | Combined AST graph per parsed commit. Merges all blob graphs for a snapshot of the entire codebase at that point. |
| `aggregate/lsp/` | Language Server Protocol enrichment: resolved symbols, definitions, references, and type information. |
| `aggregate/dataflow/` | Interprocedural data flow edges between functions and modules. |
| `aggregate/repolex/` | Combined graph (AST + LSP + dataflow) per commit. |
| `commit/` | Git commit metadata (author, date, message, parent links). |
| `branch/` | Branch metadata. |
| `tag/` | Tag metadata. |
| `filetree/` | File tree snapshots per commit (which files existed and their blob SHAs). |
| `audit/` | Code architecture and graph audit reports per commit. |

## Source repository

[klen/peewee_migrate](https://github.com/klen/peewee_migrate)

---
*Parsed on 2026-10-20 by [repolex](https://repolex.ai)*
