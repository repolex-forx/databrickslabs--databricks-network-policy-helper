# Repolex Knowledge Graph of databrickslabs/databricks-network-policy-helper

RDF knowledge graph data for [databrickslabs/databricks-network-policy-helper](https://github.com/databrickslabs/databricks-network-policy-helper), parsed by [repolex](https://repolex.ai).

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
rlex download databrickslabs/databricks-network-policy-helper
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── cc4d847a805f4252278fbe82d162785af7b68959
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── cc4d847a805f4252278fbe82d162785af7b68959
│           └── chunk-001.nq.gz
├── blob
│   ├── 038dcdb7ebc96e1c959769ac89f429fadbbcce9b.nq.gz
│   ├── 0856ac5b5d4fd26232796ff52cefd59a7f8f5192.nq.gz
│   ├── 11bec24817f28e1daa23bf049a4b8b66ae30b0c0.nq.gz
│   ├── 1309ba3254cc26820ab7dc729d392b897d712b06.nq.gz
│   ├── 160b8fd0d13359e0d01b3338da967eeb969ff464.nq.gz
│   ├── 1890e2182709d53a90ebe293b4248976f0b1dec1.nq.gz
│   ├── 1945713f490f752d597776b0940335b2875ad172.nq.gz
│   ├── 1dde0475eadc700d964698bcfbef1b09feb8350d.nq.gz
│   ├── 27e0d8fa529a4a17c23ac3a948000cc3c2b4e88b.nq.gz
│   ├── 28f5a91bcc92bc2067398c491fd4f60027948d9c.nq.gz
│   ├── 31e338f796daecfc16a10ff2cbfbc6ad86995e90.nq.gz
│   ├── 35b2d081125f8ffb14069b8771dba0bf8a2dc242.nq.gz
│   ├── 3639e761e4350c56aeef509bc5806b7ef5a48957.nq.gz
│   ├── 3ab4640f1cb6b57957ce2aafa2864ca632cbd7a0.nq.gz
│   ├── 3d42dad78aafa491f6cee2c14b2a6d16e78d9e50.nq.gz
│   ├── 3db8877d87d2bedfd425a1a3ed0325d3f5af019b.nq.gz
│   ├── 40227eede391c69932dc1e27ba8f15a425ff88a4.nq.gz
│   ├── 457c4905fdce025cad07d59cf9b2f8f648666ab5.nq.gz
│   ├── 509a8245805cc56a834f6685b2538316ea4f8353.nq.gz
│   ├── 55bcffae72bd3fedd6561ade25ee30a5f96c00c6.nq.gz
│   ├── 5a0983ce517d668a1bab81c52c3731dfa94fadc2.nq.gz
│   ├── 68f702d6091df094f478e3edb1f428f52a7d1049.nq.gz
│   ├── 693a603f4d6270b83a460b2ac2d97a9cfd633025.nq.gz
│   ├── 6db72495435b2cc0a8e5b0304a7a5269f732d4fa.nq.gz
│   ├── 70b09f2d0e13c667aa44c036832ad739785844d1.nq.gz
│   ├── 739c9f2289750bdb550d696faa45713dff8cbbba.nq.gz
│   ├── 75db3f9db02c6a673abded998f38e63aad8f7fb3.nq.gz
│   ├── 769511f333fd68974b6666a2badc40db568eaa7c.nq.gz
│   ├── 79fdb6e2febb6088346bbb6fa86fc623d0cd8ed5.nq.gz
│   ├── 7c46df567be47ce7d79ea8ff3693ce11ff74aac4.nq.gz
│   ├── 7e2ee1e5e2a8e55d4ac5f7f03f0432d9f1a82b24.nq.gz
│   ├── 7ebc84caf484eef32b11ec438f19202698d7b628.nq.gz
│   ├── 829f77227e105fefdac7b48bfc935268615472c6.nq.gz
│   ├── 87cfbdf6d101089bdef0a1176feece575886d074.nq.gz
│   ├── 935d45f464787575265cad5ebee4b26cc22e68ec.nq.gz
│   ├── 9546fd55fa3d580ddcd358fa952f6f017ecbca8b.nq.gz
│   ├── 962a93ec97c07f2c0eaf473049c92ef5b83d1d24.nq.gz
│   ├── 963a64997442a5343ae484e402c0555bb2ec0d7e.nq.gz
│   ├── a15ca2d185039969f3b2de12b801dea4e047fc95.nq.gz
│   ├── a48c176f4dd17f99ca4d21304ebf081f9870055d.nq.gz
│   ├── a5737455de4dee6ce89bdbb388702ca38192a7f2.nq.gz
│   ├── a5b2a1d67696ea2e69ba73cd8e62b1fddd69e7c7.nq.gz
│   ├── abc0440a6bf347ac6ef01ee0d4740350d5e3dddc.nq.gz
│   ├── b02c715858e204b488336e8a206f34f11fa7151e.nq.gz
│   ├── bc97c5847c3465d0e752a080430d3c8eb321c389.nq.gz
│   ├── be62bb167df3ee24f4586fa3458df728de0a0010.nq.gz
│   ├── c2af5c32d0d546d149140d9eb87b0a3e7ddd464b.nq.gz
│   ├── c5c14899e692acd5ac5821fe1ccc2edcff4dcfef.nq.gz
│   ├── caa173f6c4734c935bd737a2ac66f6f9a976d685.nq.gz
│   ├── cca9c3e6c704b96cd0c8c457eed765fc56957f4e.nq.gz
│   ├── d3f1b884fa672dc01e4776b22cc20c5ba35719ff.nq.gz
│   ├── d66f9600e337a0669425163dbf5d602461cbfb29.nq.gz
│   ├── d72520a4e1019ef1c9614b7a5e11201f6b7d187c.nq.gz
│   ├── d968bdf46d0a5e266b9c2d240c63d8027da49bc6.nq.gz
│   ├── dc2a68f265b0a60a518149e09e9c2196ab60b6e4.nq.gz
│   ├── e8a64fe1a3c6c9958ecb34f53219112220be51aa.nq.gz
│   ├── e96d476b1cec7ebd74ce050490b9fe8d75e9c33f.nq.gz
│   ├── ea4079820d8108f7635a586b3a18b7716afe4606.nq.gz
│   ├── f27e09f446eb3b862709194ac56a5ea09a0c1d90.nq.gz
│   ├── f4499d128fdf68aefa9c3cd8c5192f7d87e8cda4.nq.gz
│   ├── f5cbdeb6c5086c83e79393f8b2bac3f969a04d02.nq.gz
│   ├── fd8ccc6de369b845a32ee4d5ad3d8aa841574f27.nq.gz
│   └── ff7141801ec4ba6fb377bcd2b65736020dff5be9.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── cc4d847a805f4252278fbe82d162785af7b68959.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 70 files
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

[databrickslabs/databricks-network-policy-helper](https://github.com/databrickslabs/databricks-network-policy-helper)

---
*Parsed on 2026-10-28 by [repolex](https://repolex.ai)*
