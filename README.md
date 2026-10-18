# Repolex Knowledge Graph of miguelgrinberg/python-engineio

RDF knowledge graph data for [miguelgrinberg/python-engineio](https://github.com/miguelgrinberg/python-engineio), parsed by [repolex](https://repolex.ai).

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
rlex download miguelgrinberg/python-engineio
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 740d905780f559aa4ae66f80d2cec401174f80f2
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 740d905780f559aa4ae66f80d2cec401174f80f2
│           └── chunk-001.nq.gz
├── blob
│   ├── 00f535444bc8a49e09f9209590b34879fa55938d.nq.gz
│   ├── 013f4fff18f6b0aa601cefbbd82b059a4185073d.nq.gz
│   ├── 01a42c55a766b2ed2fe348a164cf764ead7b5161.nq.gz
│   ├── 01e7d71438103151864f5dbd59cc783b760d47d2.nq.gz
│   ├── 046fece2cfce6f62fa132007771d591580508f6a.nq.gz
│   ├── 06bf225216577f6e91017615a5dcd3ab17a052f8.nq.gz
│   ├── 075c52d82a4916487c2a927672fef582277425c9.nq.gz
│   ├── 0795ac360a2c93b21d97c0a0bc50beffdca4e8bd.nq.gz
│   ├── 07c392100ab95825a9fc02e4dbf28697d2c60137.nq.gz
│   ├── 08127688ca5e69bcb1a4abdeef61b2b65e073dd9.nq.gz
│   ├── 0943369baa7000d43398144f1f3f945f7cb4b483.nq.gz
│   ├── 0ac52d6202518bc92014069ca6a518a50c9a29dc.nq.gz
│   ├── 0bda74c5ccc126184eec93aabf368d003d947e98.nq.gz
│   ├── 0c9c17182a278a69fccb7953f3e3491887b867ed.nq.gz
│   ├── 0d94aa7de3d720449f26e4466b612a8c80d6be91.nq.gz
│   ├── 0e34fb04b1d2e18cff24c60adf355b2a77d3a3e8.nq.gz
│   ├── 12506f1458c49004ef82480a4f5faa3fcf76146d.nq.gz
│   ├── 15557cd0d1c1e736b1d64a8502ac66a5e22794a7.nq.gz
│   ├── 156cc6b40c3be5fdedcf8b068563db08ba4104f4.nq.gz
│   ├── 16155799c6bb811c0899bdf70528940f33a9d924.nq.gz
│   ├── 185fd0eca145caef5a0b2836b9c77619f1c566eb.nq.gz
│   ├── 1c7e47d3bb80ad3ac59c5fdb1b28f4522567cf0c.nq.gz
│   ├── 1ddd31d28fec4622c9a38fa5af0ac854aac89a38.nq.gz
│   ├── 1eef78d3451081aed46160115ce760e6a4c7ad43.nq.gz
│   ├── 20d13b2aa552e4e78221209bccb89dc4dfc72b54.nq.gz
│   ├── 22beb1f3837e3620f0a0c3f64f67acc33e57a997.nq.gz
│   ├── 250f570e6e94706459402810dd05090ea476a264.nq.gz
│   ├── 25d7efc41a60c3e60a7b7eda45ea833b93d932c1.nq.gz
│   ├── 27f573b87af11e2cbbd9f54eb1ee285a58550146.nq.gz
│   ├── 298ea9e213e8c4c11f0431077510d4e325733c65.nq.gz
│   ├── 2a86527114a7b80716b95563926fe4ea6dcd3246.nq.gz
│   ├── 2af8084c68dffb19ec040cc498aa4bbcf191eeff.nq.gz
│   ├── 307e49ac8d926c4bd2ba2bbd4c3c3bf720ab95b5.nq.gz
│   ├── 32bb4b9dede647a6ebccd7d8b8f15bb31305288e.nq.gz
│   ├── 334c3f16d94c1f40e68555e0689a0c0b87037e39.nq.gz
│   ├── 33dabda4be34082a2a9d207316019ff0cfc4474b.nq.gz
│   ├── 3474eed80bcf0444e5ee0bebaa09907bdfb6f2bb.nq.gz
│   ├── 34ab621b79312e5671b29401e67a67d5cb60c15c.nq.gz
│   ├── 352d4917f3316e2e86e8181f068554184e9dd92e.nq.gz
│   ├── 35d9b22e3cc454791a34f73c942ad36283419189.nq.gz
│   ├── 3b4cd22a46371a288fcd0fc29468c5587cc08df0.nq.gz
│   ├── 3fbce038eda99da087f948ecd0f2368a5351dd6a.nq.gz
│   ├── 407c0820bc1a1ccd0849ccaf972bb0ee7c3d669b.nq.gz
│   ├── 409f366f306d7df5b0b47763a88ce0b4a0c78697.nq.gz
│   ├── 40bb6df876cff55a8ab7aed82c68330053678cfd.nq.gz
│   ├── 417ba26d6afbb716f518f555898e551493ecc134.nq.gz
│   ├── 43121258f8e8785b2d0be6c7690d02a556901fe3.nq.gz
│   ├── 4576cb97ea78d3156dd3a38e2b12d325c0573da2.nq.gz
│   ├── 4919efd8f6a8877745eb3e21528d4a7121d901b8.nq.gz
│   ├── 4b5913f9b01923f2fc54f1b2710c79106e0cf623.nq.gz
│   ├── 4d6a5b8e1f8e72c0fda0730ff25e16f8bb6b089f.nq.gz
│   ├── 4fb52281c47a6efa7243b9b1c11d7c64c5625c48.nq.gz
│   ├── 52729f31ee8335724a14350b9b4d626ac48ace55.nq.gz
│   ├── 5b8ad088b19b23a7487be172729b8375e86131b6.nq.gz
│   ├── 5cbc2b55fe34abf62950df844fa15ae6da42bfc9.nq.gz
│   ├── 6239577c663af635a72b7d38b1787635f5795a30.nq.gz
│   ├── 6361c4de0cea9d4dbb99d3ca483a82ebff9f3060.nq.gz
│   ├── 64e21589e443c0199e0707594239e9cace564b00.nq.gz
│   ├── 6a068fb25db0c8146267d2363ada94fe0ea25b70.nq.gz
│   ├── 6a886f4e4a5426c0a4aefa3f70840d1f032e1a20.nq.gz
│   ├── 72dab64767293f1e4df652e3c528c8133818e10e.nq.gz
│   ├── 738a34ffdc397f2e3c7fdceca934bb8c4eeda704.nq.gz
│   ├── 76ed59d2ad0a61cbc541f8d8299618c056f981dd.nq.gz
│   ├── 775241ba7b0a3a39ab9faa163fd4de1b0a5bb9a1.nq.gz
│   ├── 77c891571971cec0cace3a03ff2dabfbbcf1e8a1.nq.gz
│   ├── 7d717fbd3964319dd8d9fe33a9cec166b9a47527.nq.gz
│   ├── 8024445a8e52e6834320989c08bfcdf6357038ce.nq.gz
│   ├── 8117d6011df333ea87ec0ed8f39c72e1442c4779.nq.gz
│   ├── 828c8cd3cbfd70000af584ae6a2ded4000289e1a.nq.gz
│   ├── 83a968e7e4d1eed3b3fdc0b0b0dd2d74f36d5586.nq.gz
│   ├── 89f4509abf2f416d766af773434c370ee102f19e.nq.gz
│   ├── 8a7c5850e134c5e7578b46c47bc0d941377451b1.nq.gz
│   ├── 90287c7a07a08a4a84d41c5d62e58e88514edac3.nq.gz
│   ├── 91028c46e7c6d30d49014dd516e8d8e7809b27f1.nq.gz
│   ├── 91339c3f4ec1bfb527aa496e26079dec3489873e.nq.gz
│   ├── 94c8d9e89104f86a95eee4f359cbac5580bf3232.nq.gz
│   ├── 955a0f85181024f52e6ab79d36e0d2dc7e433c33.nq.gz
│   ├── 98e70219d8065f3a054e516017a426541811abf7.nq.gz
│   ├── 9c975800e396673f97614201b1e5df15e94d2981.nq.gz
│   ├── 9cddc5129284bcf3934bbf3e2b21c345a7c98265.nq.gz
│   ├── 9db39c65c90231862658c206936e68cd6cc5ff39.nq.gz
│   ├── 9fcf73f0f38ac00cf8c579f023df9d347240fe28.nq.gz
│   ├── a1aa7de14ce99493cf7a48b9dac5a19bc74ff847.nq.gz
│   ├── a2ec1c6bec3a467cb5fa07c1a9732c2cd460b567.nq.gz
│   ├── a451d113b734647154351a7e5b787907f3b5aa6a.nq.gz
│   ├── a82057fed2d2a40bb3172e29b2edc4424b71538a.nq.gz
│   ├── a83a4c06bbf23ded3821df9b0503b894db7f5f5e.nq.gz
│   ├── afce173dbebcd0632ede7d0f22b4eabac5abc034.nq.gz
│   ├── b5ccefc84c094dfd3757d2212caec54d071e34e8.nq.gz
│   ├── b612556834376c16a3b3f0566274c9ac9e960a10.nq.gz
│   ├── b70bccdd5530b40a99b525a1f746a7d6ad132daa.nq.gz
│   ├── c1948eefc811da08625cd6af9cd87705c6f7b335.nq.gz
│   ├── c2133c21d21a38d990fdf5958bc2d251391eea88.nq.gz
│   ├── c22109a5755a6c5ef0c591e9b090bdbefd4364a0.nq.gz
│   ├── c22da207a6633489e937845939e778b9b3796ae4.nq.gz
│   ├── c6ee25fa33c2cd963084963f1b078e5c078eef1d.nq.gz
│   ├── c7aec4c54c0b56735db901a1cb1fe87a68b24ed8.nq.gz
│   ├── cb0fbca9e56ea5f9da5892c5674206e913767b78.nq.gz
│   ├── cee14154fa14cc0e77cb795e0d1ca57b9dda5a43.nq.gz
│   ├── d20bcad97867feeaf6e97b56488363ba660856b7.nq.gz
│   ├── d3b68b9f7a819f873c600f29c6ec67f996460b94.nq.gz
│   ├── d45e33d8b9bd3a6434362543c333cce073d1eec0.nq.gz
│   ├── d9153f2031fbb73fd30e3071b446a5ce1ce7da94.nq.gz
│   ├── dabb778b6d4e8428c3b30c1bd49b8aab257ab487.nq.gz
│   ├── db284a54a2a810b897c93a72a52559017dd9707a.nq.gz
│   ├── dcaef7804080ed6be735017e60ceddc9026d6629.nq.gz
│   ├── e1786d2aace0203d265357f17026d4a722a44998.nq.gz
│   ├── e2f1dac815c25daa2945c7e0a66d07d168a517de.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ec9b3d420b5c0ad4cb9be276aacc5f89ccaab20a.nq.gz
│   ├── ef404893a51e43488bfd2e5bc40cec030407d311.nq.gz
│   ├── f140749d285ceca07e8e82a2c85843d0eddfe078.nq.gz
│   ├── f6ca53682229ee528d417a66197c5e07e2cc671b.nq.gz
│   ├── f6e714c3a59072f23814bf9832a547df7f952017.nq.gz
│   ├── f73f3093ff865c514c6c51f867e35f693487d0d3.nq.gz
│   ├── f995286792db1a4d9919a7ebe9ea45fccda8fbec.nq.gz
│   └── fb0b3e057cb76d0a2265151d31ddfe4c68aa24b5.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 740d905780f559aa4ae66f80d2cec401174f80f2.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 125 files
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

[miguelgrinberg/python-engineio](https://github.com/miguelgrinberg/python-engineio)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
