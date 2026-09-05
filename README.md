# Repolex Knowledge Graph of serde-rs/json

RDF knowledge graph data for [serde-rs/json](https://github.com/serde-rs/json), parsed by [repolex](https://repolex.ai).

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
lexq download serde-rs/json
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 4f6dbfac79647d032b0997b5ab73022340c6dab7
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 4f6dbfac79647d032b0997b5ab73022340c6dab7.nq.gz
│   └── repolex
│       └── 4f6dbfac79647d032b0997b5ab73022340c6dab7
│           └── chunk-001.nq.gz
├── blob
│   ├── 03ec1a9a63db12ed6016a4f75f16bac15b9346c8.nq.gz
│   ├── 053f95a29080e58316d7d52011f97fe02424387f.nq.gz
│   ├── 0ba14e22c2987c5ef93945e4d616559b917b5afd.nq.gz
│   ├── 0dfb7315594e3143344c6f6a3f2b8f1c9630e813.nq.gz
│   ├── 10e6e60660d23604b61d0e29ae2b450c053087e3.nq.gz
│   ├── 15662dc507eee6dd39ada97dc5ed1232b765b9a8.nq.gz
│   ├── 1b5ec8b78e237b5c3b3d812a7c0a6589d0f7161d.nq.gz
│   ├── 2148ad520800ac13305401cb2c5507d7fd93a843.nq.gz
│   ├── 226c58cf173315642a99318d666dae232a75fa78.nq.gz
│   ├── 23a6a065ec960a031726c8c26222b0405d4f5851.nq.gz
│   ├── 26e15783a1c6b5eee12cc6292ff321c54c551954.nq.gz
│   ├── 28bb3ee019ff2914e522a00405ad7d38af8574df.nq.gz
│   ├── 2955e4a530c3bcc4bc6a140b42d71c8d71a3156b.nq.gz
│   ├── 29b83a159c51eba955e104801c9035cda0400037.nq.gz
│   ├── 2d434a29cb0f0d428d0e7f0069424af5887f15b8.nq.gz
│   ├── 2df6870dc35c46cb6812da4b121f2ee56bc822f9.nq.gz
│   ├── 2e900f1a1b245a183d70e13a1a6bfd1f9cd4b49b.nq.gz
│   ├── 315bb1545f42e0153b9abc959f253e409a45fe47.nq.gz
│   ├── 31aa79387f27e730e33d871925e152e35e428031.nq.gz
│   ├── 338874ed8f8a83f746232404624956b19883bb23.nq.gz
│   ├── 3d150a1afe7ffa76605dc797e0c345c9e9b6324c.nq.gz
│   ├── 3f3914021435051543fb9201616733fa78e130be.nq.gz
│   ├── 411e8af5d3d33aef1b1bdcd3fc37180fc68937bd.nq.gz
│   ├── 454eaa60654d750964b83ccdb821f3a2efa26f3d.nq.gz
│   ├── 4bc31dc394135fc1aa166b499d5f346bc0abfc2d.nq.gz
│   ├── 4e15da78137bfeca0e64ac20aa116bda5c83e1f7.nq.gz
│   ├── 4fa7eed6dda7ef32d8f5014975399561b8cdfdf8.nq.gz
│   ├── 54c8ddfda40aaab5b8ae29e44cccf97b278a4441.nq.gz
│   ├── 54cbce87c3944aba5fa644ceb629053096fab1d4.nq.gz
│   ├── 5e27de893f91e116d44945bb8aec7685def9d602.nq.gz
│   ├── 5fe38b67929b2886bee2b6df9cddbe6b4da1dc66.nq.gz
│   ├── 63448752271693c605b0da1603bf50c535ebb0b8.nq.gz
│   ├── 69f6ca361fab03b5a099ae1257a159d78fb25ea1.nq.gz
│   ├── 6fec1804096358bc004d7fe1092eba2e7c351d90.nq.gz
│   ├── 70cd7416200fff8ede4e4089e4249aa08e05f1ec.nq.gz
│   ├── 730ecc60a8ae3f6cad9c1d1f56477028683889ef.nq.gz
│   ├── 771aa5287c079ffd992ff9b11b3ea6e29d3c2a8b.nq.gz
│   ├── 77967956cc0dda026402215cdebb84cfddc56c12.nq.gz
│   ├── 7b001100460d589d60be8309e294561ed5a4b711.nq.gz
│   ├── 7b6564dadb467c9b1a4637f170142cfee0ca2db9.nq.gz
│   ├── 7c562f82ddbc395a368ed83d1d14d1ff4b4853a2.nq.gz
│   ├── 7ea17716c3846e57275cb0ee7959ad74d73749ae.nq.gz
│   ├── 7f3a2c6241a58c3e8ad25fe7e6de4660f06e8227.nq.gz
│   ├── 83f18a42d467cf40b70486903dd21c05ff4b4b28.nq.gz
│   ├── 858bd71692131d9cad716fdcbf9128875a850ded.nq.gz
│   ├── 8626eed7f1036cf3244ece6cc6f6cf8f8d9e368d.nq.gz
│   ├── 8818c3e60c4c5e8721f744f41ff546b803db2601.nq.gz
│   ├── 941212b86d6f33c4938849d71150f985b3d60390.nq.gz
│   ├── 942e1c5b263b6c7a49a2cf4b89d168ef88e390f4.nq.gz
│   ├── 96554eac1c37aab55b96ae92bd2703eedca3b665.nq.gz
│   ├── 9792916dcc3068b08d67924167b89648af5cfa44.nq.gz
│   ├── 9beda3ddb1d8dcf2617229916137dca977ad4aa9.nq.gz
│   ├── 9c3b35be60bef7d59a49db6f76af1528037efe38.nq.gz
│   ├── 9dee4a06853c23fe3fa09623d8e6ac5e369e396b.nq.gz
│   ├── 9f77c07299340f234a960c7211e0dcc8b7a54a4a.nq.gz
│   ├── a0bae01e0f44287baea8b05b4c18fa4e2838e097.nq.gz
│   ├── aa3cb25494fb76eaed95f1f892b34f248d2dd958.nq.gz
│   ├── aaf820f07453f164157b6eab970f745ef679ab09.nq.gz
│   ├── aeed4065e97ca82f186216a40a16b97b8faa7567.nq.gz
│   ├── af2c8a6a9747225ca20ad496674877721aabe401.nq.gz
│   ├── b0f0e4bd46ab9ddc202ceb26c82d5b3676ece602.nq.gz
│   ├── b74f4449eff68917bf2f4149e4cb971ce48b8df0.nq.gz
│   ├── b804d8d5704c4b84c740824d0b3647e1e937527e.nq.gz
│   ├── b848e4dbd4015dd4a009ac7220c99aef96d09987.nq.gz
│   ├── bbf4a749bb4b8042c2ac11cb3d938b773a83b134.nq.gz
│   ├── be4dad44d9c7c700d2f530aec22ca34a3e91437f.nq.gz
│   ├── c09fb961085f5fefcfacc7ab4971f49c043c29e7.nq.gz
│   ├── c109ff07dfb868f90a4726db44f3c3c7b3441fe9.nq.gz
│   ├── c87e7e1ed9984f89801157ccf27bc233f901e041.nq.gz
│   ├── d47e88161c949458ca8ca8fd04dd155f6d6b3fde.nq.gz
│   ├── d5e2e84f6ef7b2afd71c27fb1e666b2f11c3573e.nq.gz
│   ├── d5f6466e43102ab76d5959b32e8785d4ff7d0250.nq.gz
│   ├── d93b7b907d8e36e3af2d915ef36dbf5f500cf61b.nq.gz
│   ├── df4b2038cd9e3127c7bd2847357bd90fae2aa6c3.nq.gz
│   ├── dfd35e4a61745cd4b0ff49c8acdba48154a773b5.nq.gz
│   ├── e13df6a8eb3e1a4a9bbf79bd40e614c7f3e9dbfc.nq.gz
│   ├── e19dc62c3b1bd74cfee628a02241cadbd6390cdb.nq.gz
│   ├── e30827453d69b7088bc2179fcd6d944acb9968b1.nq.gz
│   ├── e3d7f1e871040bf6e02bb266ec00a99a05569669.nq.gz
│   ├── e52b1c9b9dbf1f5d7b264e66c412c65ba08c6159.nq.gz
│   ├── e767ea6f7d9324eb92b8283a16b7ce630681f0a8.nq.gz
│   ├── e7d08652e8b0ff7e3e55866ebed4b828c8c7f499.nq.gz
│   ├── e7f1805b1ee9d01cab3001ac45627171464d7a09.nq.gz
│   ├── e9e21997b1aca0707f8749ea13c09aec66c899d2.nq.gz
│   ├── eb8582f5f0f5e472b1add44d51d45e1443e22d55.nq.gz
│   ├── ef5a9fe54d060dd620a24a8027b3adfedb1037bf.nq.gz
│   ├── f4f41cdc5ab8613045046dc35c2c476109343dfd.nq.gz
│   ├── f90d9f74a396254cf8780bdbad5ac500da3eec6b.nq.gz
│   ├── f91e70b249af9340ea341826de05f7c05b09793e.nq.gz
│   └── fa52cedeb26a161db7d3426cad5441afa97bb746.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 4f6dbfac79647d032b0997b5ab73022340c6dab7.nq.gz
├── filetree
│   └── 4f6dbfac79647d032b0997b5ab73022340c6dab7.nq.gz
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

## Source repository

[serde-rs/json](https://github.com/serde-rs/json)

---
*Parsed on 2026-09-05 by [repolex](https://repolex.ai)*
