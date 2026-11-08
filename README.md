# Repolex Knowledge Graph of UKPLab/eacl2026-GritHopper

RDF knowledge graph data for [UKPLab/eacl2026-GritHopper](https://github.com/UKPLab/eacl2026-GritHopper), parsed by [repolex](https://repolex.ai).

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
rlex download UKPLab/eacl2026-GritHopper
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e1c89abca1e7a1154d37f4833bb1f77fdaa54d31
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── e1c89abca1e7a1154d37f4833bb1f77fdaa54d31
│           └── chunk-001.nq.gz
├── blob
│   ├── 004145cddf3f9db91b57b9cb596683c8eb420862.nq.gz
│   ├── 05e726d1b4201bc8c7716d2b058279676582e8c0.nq.gz
│   ├── 0657bc7f4ab95b603239dd31ae337cc518e1fdd4.nq.gz
│   ├── 17456f34638acf80753447f09d944b77761fb71b.nq.gz
│   ├── 1f05013da16e45f62cae38e34143ab145edde634.nq.gz
│   ├── 27d2bdea000260ee3e245cd6285ddb7f75e19fe6.nq.gz
│   ├── 27f4d8ed819888cf2254a053c5359cb60876842a.nq.gz
│   ├── 322aa8d1b51b1f455bc4752a3b379548c0792e79.nq.gz
│   ├── 350fa3ddf769a774aed4a3bded4b290c42ed0adb.nq.gz
│   ├── 36addfd44c560280b1753dec983ad451d0e63c8f.nq.gz
│   ├── 37dfe7fc23cab3c48178f2918e4b0fbee40655e8.nq.gz
│   ├── 3a5dfca52c41bbbeeba6cdc6a7c5b7f7773557bc.nq.gz
│   ├── 494cc7836c7969e6da8d425656bbfa61d6bac81c.nq.gz
│   ├── 4b7992b173f018b7cf03f69211d447f3022f6f9b.nq.gz
│   ├── 5174b28c565c285e3e312ec5178be64fbeca8398.nq.gz
│   ├── 567f17b0d7c7fb662c16d4357dd74830caf2dccb.nq.gz
│   ├── 5ef6a520780202a1d6addd833d800ccb1ecac0bb.nq.gz
│   ├── 61e36849cf7cfa9f1f71b4a3964a4953e3e243d3.nq.gz
│   ├── 63b9cac852f3b3d12d5a6825dca475a4d50841dc.nq.gz
│   ├── 6e94b096efc4374080c3515dccc8f72bf1014a75.nq.gz
│   ├── 77053960334e2e34dc584dea8019925c3b4ccca9.nq.gz
│   ├── 77c6ee654149dea92ce220ee66a1c94920426249.nq.gz
│   ├── 7dc65c551579258ba07cf772b496c431fe96f06d.nq.gz
│   ├── 8ed0da19ee477b34f1bd9c273f5d2541d6dcb774.nq.gz
│   ├── 94a0ec8b1b1e4226fa0f4bd9e853902fff7f6769.nq.gz
│   ├── 95edabb9b415fb1e16cee388fc6d66421646f920.nq.gz
│   ├── af2da28a481f7f28182953dd408420d18f49a258.nq.gz
│   ├── b2b2a44f6ebc70c450043c05a002e7a93ba5d651.nq.gz
│   ├── cb345d7054739f59975e467aa3baf1dae7fe33ea.nq.gz
│   ├── cf2686be4b1d8978530a8c49f57dbaeedb07f180.nq.gz
│   ├── d0c36a8961f45495dfbc9aecfde8ba78c6c87387.nq.gz
│   ├── d0cfcf924dc778c8adf1c471f2d1b4fdcca2d460.nq.gz
│   ├── d2034823261821d5be8b57831e21ffff418735be.nq.gz
│   ├── d52251f8c4a8eee5192725860767486bd5b962fb.nq.gz
│   ├── df519965ee252cb671891f6b638459a0df461c36.nq.gz
│   ├── e215bc4ccf138bbc38ad58ad57e92135484b3c0f.nq.gz
│   ├── e352b388275e40b88b9a843f45eec1ab0d864f8e.nq.gz
│   ├── e646af5150c3df9e7b74e649ef22a9a606822eb3.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ebc1a853b6738d78871573623bf6ee740e0007e4.nq.gz
│   ├── f0bcbef44f605e56c8a832e08effda47042ce6b4.nq.gz
│   ├── f9da000fbaf4aecbbb7767d6f78f3651799c7add.nq.gz
│   └── fb728947c6fa0bdeef8428cc9ffbf0615c26dbba.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── e1c89abca1e7a1154d37f4833bb1f77fdaa54d31.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 51 files
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

[UKPLab/eacl2026-GritHopper](https://github.com/UKPLab/eacl2026-GritHopper)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
