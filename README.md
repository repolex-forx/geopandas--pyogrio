# Repolex Knowledge Graph of geopandas/pyogrio

RDF knowledge graph data for [geopandas/pyogrio](https://github.com/geopandas/pyogrio), parsed by [repolex](https://repolex.ai).

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
rlex download geopandas/pyogrio
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 12efcde31098ec8276d4597f03dbdfbad9826945
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 12efcde31098ec8276d4597f03dbdfbad9826945
│           └── chunk-001.nq.gz
├── blob
│   ├── 01777cca9d00517e0a6584c555cc20d7f99f372e.nq.gz
│   ├── 02845c30b04a72851b858711aed46f61b76a912b.nq.gz
│   ├── 03eba029b098c503cd184d3448a4bf88f8b15f50.nq.gz
│   ├── 0479df892a1e3519dafdac5d4f19afb243d2962d.nq.gz
│   ├── 069dbe07eb3b3136ee3a50491387ef23fdfb74f8.nq.gz
│   ├── 09b6157292edfc7debef186fdc884bd0437851c5.nq.gz
│   ├── 0a03d1c352821b9f59d4156c74521c1bb4f731de.nq.gz
│   ├── 0bb5d69d012fde6a8317f87b55f1e858c9dfc934.nq.gz
│   ├── 0c3b93d66e00fda2bad15c1fa5ba80fffbf6c9dc.nq.gz
│   ├── 12d1763d2417ce13e0e2d3b827993a0811826aa8.nq.gz
│   ├── 17d21fcebdc014ab7bd08d3261636267a1cba74e.nq.gz
│   ├── 1e1fd149ef3c54618407ecbff86aaf1a29ed7ae0.nq.gz
│   ├── 226b0b6eaccf74d548996c6baa357b9b0e38cb4b.nq.gz
│   ├── 28ba8c94a72e18c6335fbbd6ade362706bf5733c.nq.gz
│   ├── 29e03ee469f0ea13ef33487fef7880734c57e07a.nq.gz
│   ├── 3429486d9f91586c99c2b203aaefa55fb4339cd9.nq.gz
│   ├── 34f86c7919421810a89638374a1a47684ea3b346.nq.gz
│   ├── 3788cb7a3c7c2299a2c621c380176b806c9a5118.nq.gz
│   ├── 39d8618221a6fc910a0a3e4c5a4d593e82f2be56.nq.gz
│   ├── 3be3c1fccc97499edbcd60ea7531ab826ab155fb.nq.gz
│   ├── 3e8d670b80f13d803c01abb21eccb38b04baabb2.nq.gz
│   ├── 432c3036117aa5c775ebc697bc7b16c0e8ddfff3.nq.gz
│   ├── 487de5212556fa29581f94e0c7aaf61ac000194f.nq.gz
│   ├── 494ad48ec6b67cd53b106910b6f812b5a14cb187.nq.gz
│   ├── 4aaad1350e65df968e5e82a7570372509873a5a7.nq.gz
│   ├── 4ab6cb4b43d614e92797dc73c1a4dba51a9664af.nq.gz
│   ├── 4cab72d0bf2998eb8a24581864414b7e0e0ae00f.nq.gz
│   ├── 4e37e3aa5faba3e2e6ae6ee4d0b0f0a1fda4323a.nq.gz
│   ├── 51803669d1996b1c7c2cb52539516a7575d2b060.nq.gz
│   ├── 52ef2a8387875984dee42e59174a0e0cc2f6a3bf.nq.gz
│   ├── 5423abbe9066d929bed66a91e4ea2e90534a0b85.nq.gz
│   ├── 5439ba89613ac747c49a0e6944ab57d768d8696c.nq.gz
│   ├── 595a2feae4017b8d76348e4b8e5c19d8710003fa.nq.gz
│   ├── 5ba3f91b2cd7f6dee2bc24303ee73799b5915c31.nq.gz
│   ├── 5c074b98785505cf7f76ba247fd61d65ea4602f4.nq.gz
│   ├── 6247f7e231716482115f34084ac61030743e0715.nq.gz
│   ├── 63b0e6c4abd2118fad8b3d5460b806b0f932c39e.nq.gz
│   ├── 63f6f5e62669a1c85c2b5c60d1bec6a6f9af09f0.nq.gz
│   ├── 670b3ecaa94b47d3108418d23a81b7e350271865.nq.gz
│   ├── 68ac16b2fded5a98754a83f2df571289b877e6f3.nq.gz
│   ├── 769959a636f73654a3170c692273517304ffc9a6.nq.gz
│   ├── 76e8e4b6b0750893717f47a7235b39ba54588337.nq.gz
│   ├── 77d0d9428953660d77606820d8cd2f5cb0d6699b.nq.gz
│   ├── 7b64fd59b39906f841a0e16adec0fa4ae46d6f72.nq.gz
│   ├── 7c674601d4e11479f6f0eae0c37f5bc0807fac09.nq.gz
│   ├── 7e91cab9967d329e78033e54332920e9e3fd19af.nq.gz
│   ├── 85eec9fdf017a9f51f73ba7cbe9986455fd1118e.nq.gz
│   ├── 8624b70867e9c82aa7c18a222da3b01367af7f08.nq.gz
│   ├── 8a22edfee9bf1514af8cecf183e0e994bc40041d.nq.gz
│   ├── 920d498ab4a33e99148e411e00468b0e1ad39ab1.nq.gz
│   ├── 92fec1f9ad9f4301031c220a75d88330b7a40b60.nq.gz
│   ├── 9318e45c7015568100ad4d7a271790fbec966876.nq.gz
│   ├── 974f5be9bc4365a599033688de708e34443b0dcb.nq.gz
│   ├── 99159007fd571f7c6ec8ee754ab0fc6123f52827.nq.gz
│   ├── a30c00a55de19be195abf9e942f6cff93bf0a825.nq.gz
│   ├── a35bd6c2fe1ccf778caf2c24c031420ca0a05547.nq.gz
│   ├── a369df53f2dc3235f2bd5346e0c5f359213d0e58.nq.gz
│   ├── a6d40a7f24e590caa6e0752f97b98fb2adf5ffff.nq.gz
│   ├── a8cc482aad6344018b2fd8c2adf8c802b51de48a.nq.gz
│   ├── a8e1217c114a74b88f10a67c3dbc3aea61224766.nq.gz
│   ├── aa21f419ab8c4a9977b1fde4880818d521c9c230.nq.gz
│   ├── ac27a84869a2cb5b416c12fc1fcf57aa6f626958.nq.gz
│   ├── b00af8ade984c789f9bd77fcca307985fbf5c8a7.nq.gz
│   ├── b3ed01ac895ac3d51cf3313f3a717ba246777d32.nq.gz
│   ├── b5371fcf8083eba98e1dc444b911a459fd343285.nq.gz
│   ├── b9000e6007c5c7d0de0de32008577d18385c07d4.nq.gz
│   ├── b94feff502fac48c398d8466e27b39b6ed2fcb90.nq.gz
│   ├── bb2d05d17932c9ebbec8ab1a307d0fd2f9ab0b58.nq.gz
│   ├── bed8dce4b2fec6933ccd4ee186f2b0e1660112e8.nq.gz
│   ├── bf2d45e92f77a2ddbd9a7f863dcd40039adfdeb4.nq.gz
│   ├── c1521f86bb4dae786d0ba905665b46b2a101e928.nq.gz
│   ├── c2783c15c1a05a4e785e4de78869aedff568683f.nq.gz
│   ├── c3728e0dd6d23d5dca5cf848264b023a3b7e99b5.nq.gz
│   ├── c9ccf36b8c770e3b9033573c71557fe02f9a3a80.nq.gz
│   ├── ca5fddfe0d24dce456249ee9c3f09206c36ffb8f.nq.gz
│   ├── cd3cb469ac3af41dacd44f198fc7d9c5d799914f.nq.gz
│   ├── cd89cb9758e84c59b13399a25325d366af87e4f8.nq.gz
│   ├── d0c3cbf1020d5c292abdedf27627c6abe25e2293.nq.gz
│   ├── d18885a8f4f4bf8210c3817baf2ed8ad580d0d45.nq.gz
│   ├── d4d6082f9ea99ca375bfabb6d840b66b56a849d0.nq.gz
│   ├── d668e90a558b8bd45b214131977dc3744314741f.nq.gz
│   ├── d6f8699865952257531c9fc8eb0ffd6dee062da1.nq.gz
│   ├── d8add95d361f79928850c709ccf99bb8fd2c9fe1.nq.gz
│   ├── dacd08f4479658b078b88545d6969f43756b5b2a.nq.gz
│   ├── db65660f5b1b3a7dbdeee8d406304826633785cb.nq.gz
│   ├── dd8568aa1511f284d54da273ad0818df80f2622f.nq.gz
│   ├── def957a431e9b63bbdb23dc3312c6e725cba31ba.nq.gz
│   ├── e1108ab4be8139ecddc261c0eda4f85fec5d78e4.nq.gz
│   ├── e1cd374f3d02d0e44f64b90884a5769f6309863f.nq.gz
│   ├── e3122de4d303cbb80d86b8dea66bdc4d5e6319f4.nq.gz
│   ├── e64d6c2f7eebe14b174e58e60e82e06419a5a7bf.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e82b3768ef4ff33dd8a81a36bda12b01c1e39e12.nq.gz
│   ├── eebb9710d91074d35f725f4fbcec6de53427fc5a.nq.gz
│   ├── f6c40253a080c71b9abd8c8185adbfa5c50e3bdb.nq.gz
│   ├── f798f46ace4cbf7e75f7e4b1821c8438e97be13c.nq.gz
│   ├── fb76fe20d591491de534e8c70bc8e9502d14ff65.nq.gz
│   └── fd40275a397c246932229d0e54a965dfb23eb46d.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 12efcde31098ec8276d4597f03dbdfbad9826945.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 106 files
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

[geopandas/pyogrio](https://github.com/geopandas/pyogrio)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
