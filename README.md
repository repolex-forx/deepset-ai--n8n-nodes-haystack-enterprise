# Repolex Knowledge Graph of deepset-ai/n8n-nodes-haystack-enterprise

RDF knowledge graph data for [deepset-ai/n8n-nodes-haystack-enterprise](https://github.com/deepset-ai/n8n-nodes-haystack-enterprise), parsed by [repolex](https://repolex.ai).

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
rlex download deepset-ai/n8n-nodes-haystack-enterprise
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c680d36e90b3075081fcedac04f49f1f4132c60d
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── c680d36e90b3075081fcedac04f49f1f4132c60d
│           └── chunk-001.nq.gz
├── blob
│   ├── 072d9bc3c039c456ebaf20e8c661486f521fcd54.nq.gz
│   ├── 0bfd8d6427bd3adfa7f3634db75a83a3fbe34b91.nq.gz
│   ├── 1116a5df27182e8d3c56eef786d90b13a9f54588.nq.gz
│   ├── 116dd3dcb129d07e586bdedda9cebea67690d6d3.nq.gz
│   ├── 1a87835042105b6459dcfaa9c747cf6b03d5c5f5.nq.gz
│   ├── 1e2b56e5c490e8512a67a674420b9d7b8498c521.nq.gz
│   ├── 2250c629d36ed546fcaaa1022cd0eeb9b9d97cd9.nq.gz
│   ├── 226ff143cfd752b6baa6033e07fbb0d8172f60b7.nq.gz
│   ├── 244103cd7170d7a990c07f95f691d2bef59b022b.nq.gz
│   ├── 2d1f099b973d14c42e9f92524e467da48b0f3e3d.nq.gz
│   ├── 320c107b3e5f0e08a9b443602d4063fb7c71cd33.nq.gz
│   ├── 36ef7c6311c69018ab3238e8f8e12ea213db1acb.nq.gz
│   ├── 43c994c2d3617f947bcb5adf1933e21dabe46bb5.nq.gz
│   ├── 4b4382e88edca1d50024941c9f6446fc924de2e4.nq.gz
│   ├── 4f0ce0c80d671edcfe71d9f505873bf0374f1ed8.nq.gz
│   ├── 517f553458130f98bbc082c9573a86e07d6886e8.nq.gz
│   ├── 53b47cf4863957fda96824b81072d7d4f9fdd600.nq.gz
│   ├── 591937c28f1a04c8a9ea61702dbed5afc4a7e789.nq.gz
│   ├── 664680e273ceeb1787a62330f16deb5a75d9539e.nq.gz
│   ├── 68ab62ba0c9e2b550a50c441921f39ce30f6a2ae.nq.gz
│   ├── 78914bab3e0319c5672d148607fe5c8d1e835964.nq.gz
│   ├── 93584ae39e957dc1c33e12ad38b5f74261d87f11.nq.gz
│   ├── 93f33e9e4ce300d8c84bf4203d33e44f858e105b.nq.gz
│   ├── 9568c7971cf591771021a50ab88a04551549725b.nq.gz
│   ├── a3802082c4a20dd1923cda887531a2749e6f40ee.nq.gz
│   ├── a81a95a24cfb10f41a33af87ec2d25ff872b7c27.nq.gz
│   ├── a9681b0c5699e4df491d0910c7382c3daa14db9e.nq.gz
│   ├── aa4f3f5e62691ad2c720a09d4d52dd9cd1d294ee.nq.gz
│   ├── ad811a0baf0e5f4edfda048832211e85e36f4742.nq.gz
│   ├── adc4e1a7b2eb1d0ebd503456272e1d06c395ff34.nq.gz
│   ├── ae866d7f8b71a2a1b3faee4750bc789e72494f79.nq.gz
│   ├── b50c6b7a3c347ab391c3b3450a1fcfb4ab4b9912.nq.gz
│   ├── b777a0ffe04d7a89437ea67317b60d7748eb6b8e.nq.gz
│   ├── be498f91f82b3735b2bc11647a97147ed0f836d4.nq.gz
│   ├── bf506a6c3007c7067679fe0412490edc6e62fa9f.nq.gz
│   ├── c0e4a7ce3e102a5b444e71df508a86039581c820.nq.gz
│   ├── c45a7a6fb59c95fcdb4fb6256bdc3d070b06f0a3.nq.gz
│   ├── ca818682fee4fbd8cec7f85ae47bc74981a78c64.nq.gz
│   ├── d5332e8910bac581464d520eba95ab84fddd56af.nq.gz
│   ├── d821623cc27e2ac7f631c85e0b6811bfc041a145.nq.gz
│   ├── da77319485347c0a3424f0ffef08534ac8c19f90.nq.gz
│   ├── daa9eeb407742386f57cd45a78c1bc780644cae2.nq.gz
│   ├── dfb5577342ce5bbbbbd2292f801e14d0937c132f.nq.gz
│   ├── e0c5dff4bdcb5d379c2d4d6f3362f868625a4287.nq.gz
│   ├── e155e929aca174374a599cba27c5d411e14180ee.nq.gz
│   ├── e9dafeb81a20c648c63fe3dfec2fed938f5ada34.nq.gz
│   ├── eca762add242006b69ae1313f88afa6eb07e6803.nq.gz
│   ├── ecfdb42624c5130e2dedcabca4c8bd2611d93eae.nq.gz
│   ├── ef83fc83d8a28db24f1179b1aaa3a61f62fa1db8.nq.gz
│   ├── f05d111b60eda9deba038af8a8d6341791639fa9.nq.gz
│   ├── f138b9d73f1278a0baba28382366f3bcc1d2306a.nq.gz
│   ├── f6008ac0b501714dee73b5cde96ff7f0f4445a72.nq.gz
│   ├── f6b53fc4a1d4e5cb029d38db5ba04aa3cf0e909f.nq.gz
│   ├── f993a89d9eef85721fbe03c7c9feb6dd77e2c80e.nq.gz
│   └── fea027d522743cc384c2bef9952d2b8ff9cc2340.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── c680d36e90b3075081fcedac04f49f1f4132c60d.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 62 files
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

[deepset-ai/n8n-nodes-haystack-enterprise](https://github.com/deepset-ai/n8n-nodes-haystack-enterprise)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
