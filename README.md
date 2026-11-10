# Repolex Knowledge Graph of total-typescript/ts-reset

RDF knowledge graph data for [total-typescript/ts-reset](https://github.com/total-typescript/ts-reset), parsed by [repolex](https://repolex.ai).

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
rlex download total-typescript/ts-reset
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 81b3b2614a32e47948cd4b8d5468879c07c2b361
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 81b3b2614a32e47948cd4b8d5468879c07c2b361
│           └── chunk-001.nq.gz
├── blob
│   ├── 00a804216a856d11ae4c23cfb5e048569e97feae.nq.gz
│   ├── 00a8c4c63e67140b77a93a95615f9393d3e00cf9.nq.gz
│   ├── 024908156a9c3d26af86145f28553eeeeb518e5b.nq.gz
│   ├── 0cecb79f50efebad30aa7b17e076864ef67b4978.nq.gz
│   ├── 0fde5d853d221f589e1ddfb998ec63d21537337e.nq.gz
│   ├── 102598df1629d8dd11dae7c6034aa727de4fa1a5.nq.gz
│   ├── 11eefa3d214c72fed66bc32b3fdcc3f4cfa41342.nq.gz
│   ├── 12752d6fcf5690401461d0b5c3f8c369b00c544c.nq.gz
│   ├── 199bc66ed2048bc6d6fdaceb7b45d8145b01ff31.nq.gz
│   ├── 263461451d85a990a0f755f3785b6537aab83757.nq.gz
│   ├── 2bf541414a3d38c44d9365fdc45f5cacf3064593.nq.gz
│   ├── 2e42001639d65e071081073ffe454eed69df24d2.nq.gz
│   ├── 33830061a603fe2017eadd77ee461005e6f833ea.nq.gz
│   ├── 3630569e6085f529255a519da3d62ba4f44b39da.nq.gz
│   ├── 44588ce229e3c2eec6af49180335b6507b5a20a3.nq.gz
│   ├── 45f1c2766a007197ee08b1a0330ac73041464e66.nq.gz
│   ├── 48dfab6d148542a03a855ee208835b1953a09323.nq.gz
│   ├── 5aab13c76862f9ec355b54e537f6597337d5d2b9.nq.gz
│   ├── 5d9e54a1e1166302f06d4cda2ca09881ca3c7fc2.nq.gz
│   ├── 5e7c11fd644d1c70fab9193da475db7cb75aa4c7.nq.gz
│   ├── 5fb9d67b3c75060a83acd0c8aa1df5b29abe0919.nq.gz
│   ├── 60450445c49a7f0348245c58b1ca55c0f4f01c11.nq.gz
│   ├── 604e896f2582a531c55fda5a90a1558b993fac58.nq.gz
│   ├── 643da9b224ee4f41d6b62baf100fb87caa923aaa.nq.gz
│   ├── 68330b474c0a6c5cc7e374ede282e5a91319eaf0.nq.gz
│   ├── 6946c4d6153441df9f5941a9e6bbb38e425b6b7a.nq.gz
│   ├── 6b35adb16630ae315704115d72962e75e960428d.nq.gz
│   ├── 6bcb811bd8c450d4ee019d92175b89caf27e582d.nq.gz
│   ├── 6f110afe1c8df415f1fa7dbd0bf1856854493765.nq.gz
│   ├── 6f5f2cc48cd8f75b78c13e63378d97ffa80ce1da.nq.gz
│   ├── 71511c15efb44add86813660711eb02bebb97653.nq.gz
│   ├── 83d5ef1c4d152c0a162f2850c1a57f9788c456ab.nq.gz
│   ├── 84b1d08fa39f6c920b708e6e9bff0ba929e8ef1e.nq.gz
│   ├── 874836abb97fb30dad1e7c7178e787a78f1da733.nq.gz
│   ├── 8ff394b7a5c72532293955f68d2ee2d143fb33f0.nq.gz
│   ├── a8683ae4f769a558fe0fd494268a93fa3c317dd9.nq.gz
│   ├── af7b326d4b99f6d22da0af27db28c4fc1d5343b9.nq.gz
│   ├── bc3ea0dc20b28ddbe2b9ae47c1e3ce25d6411b9c.nq.gz
│   ├── c1493c3107b77f21d32a4005869c5eb201b574d6.nq.gz
│   ├── c6306dc41a120651546def68366f7698b750f449.nq.gz
│   ├── cf4d1e445a325f1aa0fb4b2795e996875ef1a300.nq.gz
│   ├── d0b4efea9b0eac5e4b94ba37fe231521b8ffe37c.nq.gz
│   ├── d36ecebb7ed65bd4c1789b51ebee5ac810016704.nq.gz
│   ├── d460ff587689e2b1efb2c97ea2d0b0c7212aa55e.nq.gz
│   ├── daaa12c9bdd3d35fba3222c56cb73ca36adede76.nq.gz
│   ├── dd52159b4e9ff8492dad25264cd353139a6d71c1.nq.gz
│   ├── e03f06e2000257770deb0ac02e626dcb69ea42cd.nq.gz
│   ├── e481fd29e0dee0e4f5312222d9420e29ab0a1ec6.nq.gz
│   ├── e5b6d8d6a67ad0dca8f20117fbfc72e076882d00.nq.gz
│   ├── ef76cce304ce95268037a727a9b55b45b722dde6.nq.gz
│   ├── f4745e5c27efb9f58661880adb5e408eff21af06.nq.gz
│   ├── f60d936d2ef75753ecbc34efbfe229dc46c74e3b.nq.gz
│   ├── fadea1b42164a98903027bf8c024b80c4ac5e706.nq.gz
│   └── fc7ab2c28e7bfe09e30128c3fa93e7ac743bce7b.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 81b3b2614a32e47948cd4b8d5468879c07c2b361.nq.gz
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

[total-typescript/ts-reset](https://github.com/total-typescript/ts-reset)

---
*Parsed on 2026-11-10 by [repolex](https://repolex.ai)*
