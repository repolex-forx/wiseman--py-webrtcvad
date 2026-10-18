# Repolex Knowledge Graph of wiseman/py-webrtcvad

RDF knowledge graph data for [wiseman/py-webrtcvad](https://github.com/wiseman/py-webrtcvad), parsed by [repolex](https://repolex.ai).

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
rlex download wiseman/py-webrtcvad
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e283ca41df3a84b0e87fb1f5cb9b21580a286b09
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── e283ca41df3a84b0e87fb1f5cb9b21580a286b09
│           └── chunk-001.nq.gz
├── blob
│   ├── 002fcd8d6617059579cad6cd8ae5af99106fbd90.nq.gz
│   ├── 03baf31567e984177e919c173688d691327b7cad.nq.gz
│   ├── 0cb899c47f1205649f2191cf9777ada089a094c6.nq.gz
│   ├── 145395a4cbd4f386422f6f415a2d7a45dc4e8ecf.nq.gz
│   ├── 176270cc5f00638a6689b4d068aaf84880f8098c.nq.gz
│   ├── 17f22389901f6c711e073087f3f9b970b46380b0.nq.gz
│   ├── 2220cc3331ab77a8120a5444a9caa609a422b15e.nq.gz
│   ├── 2d420525bab1c29accf5a144130a4ec5abeddade.nq.gz
│   ├── 32808723330d0d1a33accd4c73e04220558caa2f.nq.gz
│   ├── 3dbef18f5461e87caf4b86ea1c5b2e9aa76f7280.nq.gz
│   ├── 4315b099598afdc8cdf07324c6bba98fff3b8be4.nq.gz
│   ├── 4c796f819776714eae7bb18556b7ef8c7ada4589.nq.gz
│   ├── 55f76641e6ba1f4f073e6ea703dda07fe2f4e26e.nq.gz
│   ├── 5c2512880c81fb0a1f68a3882a30e5843a070f74.nq.gz
│   ├── 6409fbac471cdd6064c01277f27fb6d6194f54da.nq.gz
│   ├── 6b2d11ba336926e06f5d42a21eea839d71326257.nq.gz
│   ├── 6b8aee9a95948b30941f1969cc5864deed5565a6.nq.gz
│   ├── 72bc0f92b16ae748039fd0cbf1f2d05b18b31505.nq.gz
│   ├── 739161afcaf5443c3c733a0117626b72ecc76111.nq.gz
│   ├── 75975bb09b67d8d45c9170dc32deb6453d245e99.nq.gz
│   ├── 77ca12ef0af4c2f7800a434c16f5fd123b50d7bd.nq.gz
│   ├── 7d25e2abe603fa015050703ccc80a011c20e832d.nq.gz
│   ├── 8286ecae7f2bb41db1908bb0eefac9d0bbb235f3.nq.gz
│   ├── 82e3c8b09c3da79389bdced09d826cc6df527a9c.nq.gz
│   ├── 82fba1dac184a59bcfd64b63063fc6b10e694c18.nq.gz
│   ├── 84450667d1a539fe2e4a1182fc30e80b06062a21.nq.gz
│   ├── 8f0cfc06307071670261ef77d1dd64d24e5fc5ab.nq.gz
│   ├── 90fac072d2759c1a86bf659fec00793bdc86a6da.nq.gz
│   ├── 97d5d6ce4e6be3e46b2230494e89c49d98c99a99.nq.gz
│   ├── a2a118064459a81bb217e2559ae62d66e00c9169.nq.gz
│   ├── a9eccfcc94126910187d03dbb41ed3428b30c7c6.nq.gz
│   ├── aac9605d88087ab3e50dc6129c431dc6f31362a5.nq.gz
│   ├── b40050519589d3939463842ce8cb67595560a7a0.nq.gz
│   ├── bb892d40cb310ab21c04b63a978e3c70ff6090fb.nq.gz
│   ├── c51024b9e0d82b34ec9a547b3f4f1894ef7240b7.nq.gz
│   ├── c8bd2dc457a6a9dd2ff452efed0f8cc9218023d3.nq.gz
│   ├── c8d903ebd53312fed6780430f7963b74034d95d8.nq.gz
│   ├── ccbb306d84dbc40d29edbd3e20a1ea7a8599ea43.nq.gz
│   ├── d24b3a5f53752fb6a4b62502f0f6372e9cf6b48f.nq.gz
│   ├── d62eee11439af267b88e70eb4b815dfa132495b5.nq.gz
│   ├── d7c9f2b9afede2a0a86d20bf33c082626de2eade.nq.gz
│   ├── d9661af117cb91d524d4b6991e415bc3841072af.nq.gz
│   ├── d9efdd8e67a055150e227fd388a4e1e4242870b9.nq.gz
│   ├── da56743b67856aa75df0a6b82cbe5dc33ca55b06.nq.gz
│   ├── db2e4a8116977dd6972cb5c5a29f4171453aedb6.nq.gz
│   ├── e1f391d10a49ab66c1f90bbfba049a1fc3e8fe06.nq.gz
│   ├── e575861ed52778e0223fe0b7270361983f0197f1.nq.gz
│   ├── e83f1a698f609e95eba8a0fc399d03d8c218174d.nq.gz
│   ├── eb336f9b75bae54f6a8411bb1d369a63b61442c9.nq.gz
│   ├── efa6a65f0e4551f5c8b0a35a508e7964266518dd.nq.gz
│   ├── f585d34ded3dc4a5b0ae2296ba03027fe6e7bd3a.nq.gz
│   ├── f5bbadf5b78fce8b3557ef7971e7a3bd90ea5e66.nq.gz
│   ├── f79ac9fa63562a918d3e099474e51f0783e83985.nq.gz
│   └── f7d040c62c98592b7676cb09396702d299257f12.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── e283ca41df3a84b0e87fb1f5cb9b21580a286b09.nq.gz
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

[wiseman/py-webrtcvad](https://github.com/wiseman/py-webrtcvad)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
