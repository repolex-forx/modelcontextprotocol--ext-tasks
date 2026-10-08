# Repolex Knowledge Graph of modelcontextprotocol/ext-tasks

RDF knowledge graph data for [modelcontextprotocol/ext-tasks](https://github.com/modelcontextprotocol/ext-tasks), parsed by [repolex](https://repolex.ai).

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
rlex download modelcontextprotocol/ext-tasks
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 5246bc3d0253c1c4b09e682f690b7e8b97362500
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 5246bc3d0253c1c4b09e682f690b7e8b97362500.nq.gz
│   └── repolex
│       └── 5246bc3d0253c1c4b09e682f690b7e8b97362500
│           └── chunk-001.nq.gz
├── blob
│   ├── 00208fe39c3c970babb94f99cbda4b34d7f4e557.nq.gz
│   ├── 048f5f38701325d0a34fdbe6fced4d741ca397dc.nq.gz
│   ├── 04f5a9fd1b6e907633a52b1b71509ce5c7da4afa.nq.gz
│   ├── 05f056aec6cc79141ad01f598ae98424eb1752a4.nq.gz
│   ├── 06215f4e5f32f4e86008ca87df4a2e1ba7422f6b.nq.gz
│   ├── 0760147a93132916687100397b2c87cc8b1acfb6.nq.gz
│   ├── 09b34021f4c80d39347fa19467a1596682154fd3.nq.gz
│   ├── 0a471ab527db926df3a0e2e25b0967998183b9c4.nq.gz
│   ├── 113db08fba91fdfd1817db5be20e850d0947d52c.nq.gz
│   ├── 15aa2d9bea4a0b6848796d77cf963066cd1c39dc.nq.gz
│   ├── 170a3f9d019ee9b764253816b35f18dde6f6ccd3.nq.gz
│   ├── 17cdb3dbcc577ce6cca0781e4ecc0dca84cc2c67.nq.gz
│   ├── 192abf4efbfcf0cb9c7c1ea1fa3cafd109a43a0b.nq.gz
│   ├── 19883e23ad19b515b34f17ed96c210fab233e319.nq.gz
│   ├── 1c292e239d4db468f046f85f1fa2631b3a59ae76.nq.gz
│   ├── 1d0ec255bbcc5744264be53bba0e09e7eb8a5615.nq.gz
│   ├── 1da79666df5b06de72c80065e27cafee09038ef7.nq.gz
│   ├── 1f27048fa0251ad24c189811dd6cad621506dc01.nq.gz
│   ├── 2496c99112ffc2c0e13f2ba90c049758b6db5fd4.nq.gz
│   ├── 2715ab00112ac33f4caac91f3bcc2d025b718b33.nq.gz
│   ├── 292adc34ba457838917a0fca33f7fbaf05cc5f49.nq.gz
│   ├── 2cee726ffdc5146eb6548ae166fcd2732af0a1e8.nq.gz
│   ├── 2d6623aaeabf4f2825af0c5dea56b285c68491ba.nq.gz
│   ├── 2d6cfbe6b7dfc9f1174c5ac7137b6c7d736838f6.nq.gz
│   ├── 32a839bf27b0a1d7d50f0ef938a0e94fa32e71cb.nq.gz
│   ├── 402150cd1e6b3369f10f897125f56ec5a1af0c9f.nq.gz
│   ├── 436719dddadb97555b5ce270274dfc4c4e221609.nq.gz
│   ├── 45b9a5d3280198077fa2f85fd22f389914f4b038.nq.gz
│   ├── 45ebd13abf5c0591c5bf4c58da79f8f485dc2995.nq.gz
│   ├── 4f1c2640ca66683cbc6f349a2c01ef5d560b8dc4.nq.gz
│   ├── 51c182d27afdc9f7e9c70e71b2a6d51c04d25ad6.nq.gz
│   ├── 51f7943be001b083a26fdb6596bf5742c96ef6f6.nq.gz
│   ├── 533b9cfa12607f3276ed9f9549c599d69e7b4c55.nq.gz
│   ├── 5580c8d13654db84eb79c4274549004c21cd9036.nq.gz
│   ├── 5932add9d0ea03efc88789d470c0cc81401169d6.nq.gz
│   ├── 59541ba2d438b8699e46785418f0fe793b751c50.nq.gz
│   ├── 5d6a202eacbaab3444f9d0727ce6587598e7e077.nq.gz
│   ├── 5fbf62d21990ba4a2e8b1ab3367fad3a6e88cc7a.nq.gz
│   ├── 60f097b5accc6e4582f57ac7d8c8215a2357202e.nq.gz
│   ├── 6535854d790c8f2a64747521579bfcb47820d1b8.nq.gz
│   ├── 66c7412d2e67a70ba3d62dd5901049c6fdf4066e.nq.gz
│   ├── 67aabfb0c29b48917684883a71c7258c44f2e732.nq.gz
│   ├── 68db664b2fe07db275b4728ba80180a1bda35e6f.nq.gz
│   ├── 6eaed0a9b419d7da71d50a90843a438ab39c700f.nq.gz
│   ├── 70b5fd90dc9f4caf6a690e09b28a7492b0bc0bd9.nq.gz
│   ├── 71c33bd7a2d612093afed71086bac3b9ba270a44.nq.gz
│   ├── 73e2c1540e47f3d775e0c4689928876c281166b6.nq.gz
│   ├── 74f454eaf5d3ef444c9c556c962f459c607dfe81.nq.gz
│   ├── 764e4b0b7dab103bbfdf8fe2336e66b1222c7b30.nq.gz
│   ├── 7fc45ac6403426116b3c9a0186ce5aba22118557.nq.gz
│   ├── 808c3cbfe021b6b52d3887fc6275d759f89b03b5.nq.gz
│   ├── 83721348b21415bc1cda345305f21d17b9de95e2.nq.gz
│   ├── 876801ff68223045ef6bcbebe915f84a656dfc86.nq.gz
│   ├── 8791751ecd854d0409dccfb0d8cd34c2c9d6e475.nq.gz
│   ├── 910c2f7b2244bcea4d2ddded260d2c816adf6c55.nq.gz
│   ├── 919ddef07936892f74d222585790926807c7b175.nq.gz
│   ├── 91ec5eb65285c6d0162778694cfedb453e4eb8df.nq.gz
│   ├── 974d3204bfb3c0c15d837dcd239dcce57a003706.nq.gz
│   ├── 9c48a276a8cb6efbfca84f5b31e3387a041e1fe6.nq.gz
│   ├── a035a69e5414d31bcde0a172a4ed8ba26fc5c046.nq.gz
│   ├── a9411de2b2f0b7f30255836930832eb9153ce7c1.nq.gz
│   ├── a9d1405f76db71fc0eb152c8c68cb526648db771.nq.gz
│   ├── ae847ff6d9cdd6c3e1300cfa6584201c8e3edfef.nq.gz
│   ├── ae877d51a7c0b29616f316dd1e4ffc63f4e50a8d.nq.gz
│   ├── b10c6366378be48f20f7f0eb36f282c8bdd2e298.nq.gz
│   ├── b62e93a0e57ce45270335f99581a9571423a6941.nq.gz
│   ├── b6f6bffc1c19698d75a2ce3b69525ae0c3bfb8b8.nq.gz
│   ├── b71f450be219df877cfbe592ec5d7c084ae6ccd3.nq.gz
│   ├── b86ebbb6fdd7ee73851e4940c2ae512fa6c35082.nq.gz
│   ├── bb467a3203568a853bf2a59bb7232602c9a9941e.nq.gz
│   ├── bbd8c42a217aaa8eed35e5d98c57bb8ed5ec1988.nq.gz
│   ├── bd4059f09a34d2bd8971b42a6bccea43b67aa348.nq.gz
│   ├── c1252748200977eb4b1ce12b661911bfb8a11168.nq.gz
│   ├── c12de5137f3a8b28f6639f24167cc0c049277d9f.nq.gz
│   ├── c7e50be4be7809547446db68241cfe9017acbadf.nq.gz
│   ├── c83e9d0d21c87aa84f2720065b78ab38e4562340.nq.gz
│   ├── c875436e52997ba8c2870c77193c65d767c61067.nq.gz
│   ├── cf9c8c84c7a811db9d04b7f6cd09c7713916136a.nq.gz
│   ├── cfcef76d2244bdabad34e671a483f770978dc15e.nq.gz
│   ├── d3e5b95a3cd085d14f6c460da0d74de7e376ac4c.nq.gz
│   ├── d6bb35eaca7149d6bc2af6b0197111e76cf0706c.nq.gz
│   ├── d8e352d886c370d2e9c7b350fb6944534842efa2.nq.gz
│   ├── e6f480e9b7b99a6625f8b61e8caeae81e11975d5.nq.gz
│   ├── ea988aae05f4bfbb84d70937b2ef7049247e9b91.nq.gz
│   ├── efa4168ae51f3b15375d2d9e74bc68320056bf28.nq.gz
│   ├── f821c002988b391c4c9ae1a02736a9ab97297435.nq.gz
│   ├── f9e1cccaeb0ac6b050f3245a8e4fc3836a831e9a.nq.gz
│   ├── f9f50cb47644cd0e9c0ea43e254f5fe75826ec30.nq.gz
│   ├── fb14f7089d20b51f831c10a7644dbf3e6e1d6c56.nq.gz
│   └── fe59bc5522b0fc0eb4dcad3fe1c28b3e23e5b120.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 5246bc3d0253c1c4b09e682f690b7e8b97362500.nq.gz
├── filetree
│   └── 5246bc3d0253c1c4b09e682f690b7e8b97362500.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 100 files
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

[modelcontextprotocol/ext-tasks](https://github.com/modelcontextprotocol/ext-tasks)

---
*Parsed on 2026-10-08 by [repolex](https://repolex.ai)*
