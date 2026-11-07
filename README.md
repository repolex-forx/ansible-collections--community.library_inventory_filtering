# Repolex Knowledge Graph of ansible-collections/community.library_inventory_filtering

RDF knowledge graph data for [ansible-collections/community.library_inventory_filtering](https://github.com/ansible-collections/community.library_inventory_filtering), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-collections/community.library_inventory_filtering
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 90cd245b3acbab4089041f36c5e83dd8081eae4e
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 90cd245b3acbab4089041f36c5e83dd8081eae4e
│           └── chunk-001.nq.gz
├── blob
│   ├── 012065c8539f2bd3e61eecc74acf5a046956de40.nq.gz
│   ├── 0368269772561de77982f7bccb46a3d585e1b57a.nq.gz
│   ├── 107fe125698754beed8efddf473a003bdc2a80d7.nq.gz
│   ├── 1a3e4d8db12545a6c1dca913a69408cfdf8dc641.nq.gz
│   ├── 1d6cf8554ada641c9a963a6f986822bf4be2da9d.nq.gz
│   ├── 200063a8592118460db50166472442410459325d.nq.gz
│   ├── 2348b03c70600d58e9c2b3520840ff4dec52c15a.nq.gz
│   ├── 27c8567cc02a6269bee184eb7e45593d30bee5c6.nq.gz
│   ├── 2eafbdde7039a63ddcb29392156344ba4aef7ccf.nq.gz
│   ├── 36e6e566e8c4d2b800879a1f943ac4ecf11b4e91.nq.gz
│   ├── 38590f2e4ec486212f404e5f1405e69f7ec27db8.nq.gz
│   ├── 44ea037ca4f7a7f1781ab8ced2baca1cf12c072b.nq.gz
│   ├── 4e4af39b1dd602764663f53285ab660c25e14268.nq.gz
│   ├── 535dbe81a5561ef9e4e917490ac9b8477d9f3e82.nq.gz
│   ├── 55abd2207728484142e0d35129b496403b77e853.nq.gz
│   ├── 595d7dc315b3cbf843cd940b9cde55954d9ba7bc.nq.gz
│   ├── 665398d553b012707d0121b0c78a8f295bf77e24.nq.gz
│   ├── 6ebb9d39cf6164d848d4d026c78515c9923a8318.nq.gz
│   ├── 713fda83d3ede6185a6fdc2862cf135d35cc6980.nq.gz
│   ├── 7d5bd454e9ae1e1f1f1a8b5312373fd9a29d38af.nq.gz
│   ├── 7ec436cf233753664494b81fd541b3db6d8a5311.nq.gz
│   ├── 8266e4d8cfa18abf3dc0723cdb4125f034ef8a48.nq.gz
│   ├── 8e398ff231735476276658c72cc5a7c5279f5f92.nq.gz
│   ├── 9436f7263fe2ccfc691c03a136ce3d9bf7bf486a.nq.gz
│   ├── 95dbdc8b2fd4baa31565598926b47df1bfd30fc6.nq.gz
│   ├── a18bb585a766d72753f3e300beddef932baeee26.nq.gz
│   ├── bddb0c0780bd8b0a343fe419a75b80811360fbdc.nq.gz
│   ├── d1b1e8374c201abc72a5a72d5472f6255d788ecf.nq.gz
│   ├── d40ed757f84cd66af5baa33ac83c218dadc71904.nq.gz
│   ├── d642fb8957881441e416c77a274df5ed956f1f19.nq.gz
│   ├── d98835de0c417add87d46a5111d81a3c4a2d9b3d.nq.gz
│   ├── d9a3f7afb587ec588c5ed417c567601b701792f4.nq.gz
│   ├── dbbcb46c22bfcec41d98fe888d5ec586ffa46cea.nq.gz
│   ├── dd16c75ce15f8e7f0421562b221bd3ccfe81501f.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e70c6c4beb154720cdda193514f62b0261c805b4.nq.gz
│   ├── edff8c7685d5f4817c24b0ac7a99e0826bd2cf18.nq.gz
│   ├── f288702d2fa16d3cdf0035b15a9fcbc552cd88e7.nq.gz
│   ├── f71b322d2aabd560774185ebb7c3fec99c47ef3e.nq.gz
│   ├── fe9e93cced9f8b9f590946533d51cd1ab9dc2544.nq.gz
│   └── ff95bb8217b6b64162a2911f958f8c367bebec4c.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 90cd245b3acbab4089041f36c5e83dd8081eae4e.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 49 files
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

[ansible-collections/community.library_inventory_filtering](https://github.com/ansible-collections/community.library_inventory_filtering)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
