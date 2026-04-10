# Repolex Knowledge Graph of prettier/eslint-config-prettier

RDF knowledge graph data for [prettier/eslint-config-prettier](https://github.com/prettier/eslint-config-prettier), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download prettier/eslint-config-prettier
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e2015cd918969a67a31906c9670e09752a87e122
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── e2015cd918969a67a31906c9670e09752a87e122.nq.gz
│   └── repolex
│       └── e2015cd918969a67a31906c9670e09752a87e122
│           └── chunk-001.nq.gz
├── blob
│   ├── 04bddaa58552081e01b5cd0cc0bf8c1807a45538.nq.gz
│   ├── 06798c19f8e7be28c4343ccc577895b46a8da2d4.nq.gz
│   ├── 168d9d2a0cacaf7252308718da0d467f28fad695.nq.gz
│   ├── 175d67a11196bef9cd0e4d8834fb5fa656d9d016.nq.gz
│   ├── 1a28a9040e63ed30be49cba7e0de5d861ff183d8.nq.gz
│   ├── 1b531bada24cb5342102851d53af49dc1653e237.nq.gz
│   ├── 1f2b6d2bf4e83b324ccd29690bd932d82e859498.nq.gz
│   ├── 20073d14d4bdec721da07cffabd5999ff0a8d3e1.nq.gz
│   ├── 239991dfb9136f21977b5e5518011354beea1c9c.nq.gz
│   ├── 345176c3bf4b1c717ec3816dcaa81824a2bd1b50.nq.gz
│   ├── 3dd5ec2e405dffcc5c4d956f990d16558c567470.nq.gz
│   ├── 4b17469e8038a832051611418c2bf8d569f88c44.nq.gz
│   ├── 4b4e0d450ee750bdefb584074e05af78b2bcc583.nq.gz
│   ├── 4cccf922e801e94cf1629801f6c66ca156b1ed30.nq.gz
│   ├── 4d7435aefbf995e99707f29919442c078c2de8cc.nq.gz
│   ├── 5654e898baa3c8d41b28064b0944f144d79973af.nq.gz
│   ├── 67e3824f8b32fead367ebb097e603f8ddb90f77d.nq.gz
│   ├── 69ac40b070c0ad65512f3b233794f75ceb949733.nq.gz
│   ├── 6aa16053b87ed08f9a17e2db7d383802dc45c1be.nq.gz
│   ├── 6b00a4e19383bf9e807258528257bfcd7b34226c.nq.gz
│   ├── 6bde09fd06164a13d6c47d6f64f56e5f394e8e7b.nq.gz
│   ├── 6ee155afe650a108244f9a7a6d2bcac69cf2db2f.nq.gz
│   ├── 786c5f4bb64523e23b4afaa64f69d96473e12804.nq.gz
│   ├── 7c0ee8273c099c86c37cb0e1ac8de986c37adb7a.nq.gz
│   ├── 8962565c04bd8cda13be3c8482b3b2e5d2ce3f85.nq.gz
│   ├── 8ee2f439a2c93ff8c4a720175a3bd995f6c348ac.nq.gz
│   ├── 94d831e8e5534039efe23cb1089791ab777cde33.nq.gz
│   ├── 9aa379a9657133a35b1d46e6f5f16bee7a41d554.nq.gz
│   ├── aac873c4f83ebae977bcf46eff02596efd1cb1e7.nq.gz
│   ├── ae655adceeddf15bd5b8903ec402fe0c5023eeec.nq.gz
│   ├── bd85dd98d139ba4ca9ea8e2501c8cfc3aec0f371.nq.gz
│   ├── c4e4268ba79c1122857a62e4ab794d5ca2e5322e.nq.gz
│   ├── c53e5fb101fd11be943f02b5695f3e41c39eef4a.nq.gz
│   ├── c85565aed125382ba7a600e09f3d721087ada8df.nq.gz
│   ├── d4117d27e9b4f9f7f1688b24d559592278794049.nq.gz
│   ├── d4f39a4e80da233e770d0eaa9d3470e74edc7263.nq.gz
│   ├── d61e61b8aaff2fa78f7b9a7f25d033e8428185c8.nq.gz
│   ├── d99ddd7b3b71e9e2e2a68b20a16e452cc6cbc3cc.nq.gz
│   ├── e025fd476c3da2a3fc5363b49c1d5c879cc6fc85.nq.gz
│   ├── eacad9c16dfc18d2f77b8dc336a779530a3c9127.nq.gz
│   ├── f2ce427e8fd1f23530435527e37a994f98cf7562.nq.gz
│   ├── f7edf8a6593c786f5d451c67cc881ddfc2498dfd.nq.gz
│   ├── fbf4df9598268d3061989e6225d68387eed2d1de.nq.gz
│   └── ff36568ac1e485bad13c9457ab50c85f85b0570a.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── e2015cd918969a67a31906c9670e09752a87e122.nq.gz
├── filetree
│   └── e2015cd918969a67a31906c9670e09752a87e122.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 54 files
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

## Source repository

[prettier/eslint-config-prettier](https://github.com/prettier/eslint-config-prettier)

---
*Parsed on 2026-04-10 by [repolex](https://repolex.ai)*
