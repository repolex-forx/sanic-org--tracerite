# Repolex Knowledge Graph of sanic-org/tracerite

RDF knowledge graph data for [sanic-org/tracerite](https://github.com/sanic-org/tracerite), parsed by [repolex](https://repolex.ai).

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
rlex download sanic-org/tracerite
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c4080c02d136bbaaad9969f50a1beedaa6695bf1
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── c4080c02d136bbaaad9969f50a1beedaa6695bf1
│           └── chunk-001.nq.gz
├── blob
│   ├── 001634f899898b176c225b362bd7bccfb80cee9c.nq.gz
│   ├── 006ef52851ecc02b2fff756a014bab1ff93493bb.nq.gz
│   ├── 02869d7a9ec515d9c3ccee44d1ee56ff3294b001.nq.gz
│   ├── 050b369cdb227ee2fe18f673a07d4b5893bac911.nq.gz
│   ├── 066b8dffbd91d3127c80f9148732114a74eb3864.nq.gz
│   ├── 0dc0c3de7e236bbd07e28be2086731c957592710.nq.gz
│   ├── 0f76df550cd30dbeb6bd1ff1688e684650d1a1af.nq.gz
│   ├── 0fb8e50fcd29dcb987afe4e40f1bdf8c31e8f18d.nq.gz
│   ├── 1613cdeece5c8b4266322e1e6603944fe1d49591.nq.gz
│   ├── 1a5cf78fb2126d24a14beb8dc41d94959e478d3b.nq.gz
│   ├── 1b9952bacae5096ef08852d09306dbcf7d98e8ee.nq.gz
│   ├── 1bb0ff7ccc9b4a96a2526350f2e030970862cfe7.nq.gz
│   ├── 1ccb1d1896b4858092594c0f28f520a0babea29e.nq.gz
│   ├── 1efd87a69a61bccacd8be0b976e56e24588f4179.nq.gz
│   ├── 2092cc6f74b7cf3d51bafe33c060bdc4fefb455a.nq.gz
│   ├── 249914aecd82e6fabbba2b3b61093a86d6cc17fb.nq.gz
│   ├── 2c411a5d89f474bfc237643f979318767fd5cfae.nq.gz
│   ├── 2d3d236910770dd01cb91a4c9dcd42fbbf639e2d.nq.gz
│   ├── 2dcfa22b73d8d1f8f3844c24301b2bbb8778b887.nq.gz
│   ├── 2f4b53158938fa3f953f0e139622b8e8948c214a.nq.gz
│   ├── 329d808a8f698fcbcfaf0124aa2ae8801c1f8cdc.nq.gz
│   ├── 3473b3218619ffe8caf2e49a252cbaa38cba91af.nq.gz
│   ├── 3eb59cbd077122a39c826b5880488c776fc77b53.nq.gz
│   ├── 3ff364d73835042525c08b1d579d70e6d1ea97fa.nq.gz
│   ├── 42d5ddbff9c3f45ac88f8cc73ae7fe42bf90e340.nq.gz
│   ├── 43f62026517ad988498625d3b9817d14739d826c.nq.gz
│   ├── 495bb7e167f9e5637c85f79303563698141455d9.nq.gz
│   ├── 51a4fad58c0daab27e0c0d7acadf3dc1a4b2f74d.nq.gz
│   ├── 539dc2bdda921af09bd6300f859f69edd58fbd08.nq.gz
│   ├── 54ba9156d3299d2b56cd6cb56dde462702ea2a14.nq.gz
│   ├── 56bc290cc6a0d2461d5c9f30fa8b67ce6ebb55ec.nq.gz
│   ├── 58024787069dfc62675f320cc855c72120c15b4b.nq.gz
│   ├── 5b9f135a58494b4ce49c8ae5a9bb6daa4e9e49b8.nq.gz
│   ├── 5d5d5219377c8ed04814ad935255bada4489842f.nq.gz
│   ├── 5eccb13c9aa0393ab9b2c16b122d04b98b72a62d.nq.gz
│   ├── 5fb1d47b6d483c7af3e2465fe7f839e44ca92302.nq.gz
│   ├── 6288bed86195563c5268af25600e4d2f65ed668c.nq.gz
│   ├── 62d0c6171495c5436712f23b66395bf37ee8a4a2.nq.gz
│   ├── 632e68c08c6544221cff464b6a5ba954363007db.nq.gz
│   ├── 678f5f002d87aac1160e8f0eb80635519b046172.nq.gz
│   ├── 687a2ce8ca57572b4bc70019008bb189aff65d8b.nq.gz
│   ├── 68f02c81228e2d21c9e8b1b50c5c7478df41e276.nq.gz
│   ├── 6a6a6c3f0b7c8aec2c6201e197b151e7c89c2cbd.nq.gz
│   ├── 6ab8cb9dc1f0100845400946a4ae0611953f4beb.nq.gz
│   ├── 6bd97e54f5d332843a7cbbaab0f5993d6d1a63f8.nq.gz
│   ├── 709c59eb6e010ab61dd72e2ece0a0bbdbc9327ce.nq.gz
│   ├── 70c0f72ecd3ec9d2b6e2873bab07f34c054aba34.nq.gz
│   ├── 736210900d78b66020287ed32f996771ad063430.nq.gz
│   ├── 756c29cd4b18524acb6b7622e894e8742d44730a.nq.gz
│   ├── 767d773f4e55f118d7f1d941ca7520ee72b9702b.nq.gz
│   ├── 7c9108f4868c96ddf35ffdaed381ef76c3e1ca4f.nq.gz
│   ├── 7d7a32a0d281b67ea7564ad80d546f29198dfb1a.nq.gz
│   ├── 7ecd8d2cc2886719a1fe7cfd2fbcd6754f17fc0c.nq.gz
│   ├── 825afd32776f6550d2d14799ca533fa325f7c3ab.nq.gz
│   ├── 8672bd22ebc4ad553f1c938a565a06776eb12eb6.nq.gz
│   ├── 86c9518abd1e73f5c44985b7a7650e86488d5901.nq.gz
│   ├── 88a4432b544efff06da340a0c8f73f14886c9fa6.nq.gz
│   ├── 8af6d9d3ce305220428fafb92ffe69311027ebc6.nq.gz
│   ├── 90a56dde874792c25f09e679472c6b8158e770d9.nq.gz
│   ├── 954a1d589d37bbdd0fcc1db6af87678d2c4910f8.nq.gz
│   ├── 95c85d32a064fba03744faac0e3e8266eb44582c.nq.gz
│   ├── 96fa42c0e90134f702c17814e536e663a355854d.nq.gz
│   ├── 9920429f49e6ef44f0d7d62408870c518b7f6991.nq.gz
│   ├── 9a4fe7bacb7363957f39d8265fadb47a73ef920f.nq.gz
│   ├── 9bcbd9935e47d4ddf04f621640f8eb370150c4a8.nq.gz
│   ├── 9f1494524de0d02c0b37973eef85d3b5f3710e81.nq.gz
│   ├── a41993ee390d428a1baa1edf6e9d312ab1bedcb2.nq.gz
│   ├── a4b50f2b41453478c0ddeee6cf53ef39b1ba737e.nq.gz
│   ├── a7bf4f1100f576c5c075d939f9a92fb63b937176.nq.gz
│   ├── aa6d4f96899e0d3e8095af8808546a9c966d4240.nq.gz
│   ├── ac578296dd8451a35ceac63067bdcc1969814ece.nq.gz
│   ├── b3dbff00cd9979ce8009daa72f87fabe1d8f3484.nq.gz
│   ├── b45d2fc48d5534c7516bf925c5a836dc233720ed.nq.gz
│   ├── b573e28b08766b225d97b5e17e13dc4feba8e2c9.nq.gz
│   ├── b6b21b43124a41c2b4e26200fcfc7c146874d1d2.nq.gz
│   ├── c60e9338d7d3847ff41b5bbd59af6758e0ea18e0.nq.gz
│   ├── caec1365c3751afb1dbbf7ce5eabf51e020de7d2.nq.gz
│   ├── cc2a3e97eac811ca9528a7b98a8a9a3dcf3c83e8.nq.gz
│   ├── d4952a72b571fbdb25b434938f0f6444b3b72a43.nq.gz
│   ├── d760b2dab8b254ee33fc2177fd1e5715bd03b0ae.nq.gz
│   ├── d7bfb6741fe5cc146e5a41ea3e4f2d80b49f10ca.nq.gz
│   ├── d9ab1d63475cee255d8fa04ffd20ff95b9a0ad7e.nq.gz
│   ├── d9b423041c7b711f5ed64175c6f35e8c0e956ba5.nq.gz
│   ├── e001fe2bfe004828f1ef58b8178e187e09251b47.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e900eda4eb2ea9b239de05ee23020d682ecb0066.nq.gz
│   ├── f05cfdb76ac91d5ba77c8fb5ffafb26e61abc54a.nq.gz
│   ├── f107bfd74c33a8557420b459b62d709ad93dc5bc.nq.gz
│   ├── f176886bd0ee32f17d925a5c0d68e94741dd17b6.nq.gz
│   ├── f947061dadd3407f5a3f07b69f5be23f1dafaae6.nq.gz
│   ├── fa13f9243cd28a7d64a4a1c750e914d3b9f65d67.nq.gz
│   ├── fcbd32232e8312952ffc780aa358088a64a890d7.nq.gz
│   └── fd4b9944bdf10eb4564b6f213e8a4dd0a7c31ba8.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── c4080c02d136bbaaad9969f50a1beedaa6695bf1.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 101 files
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

[sanic-org/tracerite](https://github.com/sanic-org/tracerite)

---
*Parsed on 2026-10-21 by [repolex](https://repolex.ai)*
