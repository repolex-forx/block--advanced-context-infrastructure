# Repolex Knowledge Graph of block/advanced-context-infrastructure

RDF knowledge graph data for [block/advanced-context-infrastructure](https://github.com/block/advanced-context-infrastructure), parsed by [repolex](https://repolex.ai).

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
rlex download block/advanced-context-infrastructure
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 2954bd8dce87e700daf22055dbad0316af5115fd
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 2954bd8dce87e700daf22055dbad0316af5115fd.nq.gz
│   └── repolex
│       └── 2954bd8dce87e700daf22055dbad0316af5115fd
│           └── chunk-001.nq.gz
├── blob
│   ├── 0040b898c1015056c12dbdde38f4a036dc0013de.nq.gz
│   ├── 09f750517bb7be33841a27742030abdca13489f7.nq.gz
│   ├── 0cd36b87785411419e63903f1e963d510aedc161.nq.gz
│   ├── 0d0682f249d4df8421ae6176576f320947524a55.nq.gz
│   ├── 0eb917ebef3cf405024c33dc10d438213890a383.nq.gz
│   ├── 104eb3bb81f70746e2189807d9ae33cb94dc3149.nq.gz
│   ├── 1303852dea132257f88bee3ccdc2657d18b3b338.nq.gz
│   ├── 1b2f5af8362d535ed67e9424271ef6d0d30b20d3.nq.gz
│   ├── 1e8f0e368cd672c88838bac641d3325f0ae54aca.nq.gz
│   ├── 25b7c25053913f2fa7f2bb5277be4fe5b41c0b8c.nq.gz
│   ├── 26095e5f6ceeacff50a34df1b23928bc878f4283.nq.gz
│   ├── 2b4cb08b26cbc8fdedfac551ab3f3c42a94afcf0.nq.gz
│   ├── 2d25085ab47cb798d0d6cec3cbc299b5b338ef86.nq.gz
│   ├── 2ee6b5654e353fd6d40010ba43275a2d2f5f7a6d.nq.gz
│   ├── 316885f53162b3724d05cf3db13b77d2d6c02fd3.nq.gz
│   ├── 38f522761cb0ec341073b2ae5925e0f6ff1428bc.nq.gz
│   ├── 4243b1c5def5203bb80db822a2c005049317af42.nq.gz
│   ├── 5fa10b34ad72d1baad833fb5c53ca2819074edea.nq.gz
│   ├── 64eb98dc30a6f8b8eec79b05f6fc93c8cee3b75a.nq.gz
│   ├── 6822f76648e8729676f393b14a677ca708abc556.nq.gz
│   ├── 6bccf43368fd7c96d9c659562a5142b8b8cb98a1.nq.gz
│   ├── 6e250c47c15baa8a0ae7964ea76ca31ecc8b0270.nq.gz
│   ├── 71f3d077a93eb5d71f5ec87bb1678a92834a9c50.nq.gz
│   ├── 7a62fc86bb0e8f609bc49642faa3f3a540a1ebdf.nq.gz
│   ├── 817c1d17f9e1599e65890bd80ded2750b5fb234d.nq.gz
│   ├── 862ee3c28647e7a58801a75236855c269c1448ae.nq.gz
│   ├── 8c6f4d2fa5d954fd06bd080e3efa5184568b9d99.nq.gz
│   ├── 8ffef818487555593edafd5eab1ae80945a4d304.nq.gz
│   ├── 9582fc588754f78d9875691a3bd5e674295436b3.nq.gz
│   ├── a3654bd7b252024ba9f76ae6caf853d316ea5471.nq.gz
│   ├── a37ead3383dd86540101a773c98c902bfdd04658.nq.gz
│   ├── a978cf364c513692d9666a5fa4ee938937aea1a7.nq.gz
│   ├── adb744f8c07b1d9fef0a781eadea88cb4b0f2d70.nq.gz
│   ├── ae41e71d3384e97b922b83247d7ff3aa08188d2d.nq.gz
│   ├── bba2961b09719f3d6c1859231821f657dedbb602.nq.gz
│   ├── c18dd8d83ceed1806b50b0aaa46beb7e335fff13.nq.gz
│   ├── c2ddfa0d46d8291d02d3760f2bb18a1254ce4a64.nq.gz
│   ├── c914f22476beb6b22fc91c77afdb80152cfe19a9.nq.gz
│   ├── d77b88d8e52aaae99383991d7b6cac9e6ed63ff5.nq.gz
│   ├── d7e454b95f4de489207229469926689aabd33493.nq.gz
│   ├── dabdba54cbd7ef058d73ec43169c5b8be96884f8.nq.gz
│   ├── dd1f8368ec70a7ab59e1202673d04ee04e2cfc94.nq.gz
│   ├── e42166f096e5818c2db4e1dc088e9f13bbc20f8d.nq.gz
│   ├── e4e38954688711f8ac1b50e72500568554996bee.nq.gz
│   ├── e8f1525672d8b93bf74d03897f5e2e2c438033dd.nq.gz
│   ├── e9a9fb4fb9206b5fe0039c5a434f2c78e2e9aae7.nq.gz
│   ├── ea19ff2438769db3bb193565f35f4a63410f855c.nq.gz
│   ├── ed6697457882645ec295c7b0ec4a9edb4aab4714.nq.gz
│   ├── f84b33c56d965663104d83d0815e10fff5f8a8ee.nq.gz
│   └── fc504f78500eda0f06d9c70076066f4838389f7a.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 2954bd8dce87e700daf22055dbad0316af5115fd.nq.gz
├── issue
│   └── issue.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 58 files
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

[block/advanced-context-infrastructure](https://github.com/block/advanced-context-infrastructure)

---
*Parsed on 2026-10-01 by [repolex](https://repolex.ai)*
