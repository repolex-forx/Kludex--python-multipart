# Repolex Knowledge Graph of Kludex/python-multipart

RDF knowledge graph data for [Kludex/python-multipart](https://github.com/Kludex/python-multipart), parsed by [repolex](https://repolex.ai).

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
lexq download Kludex/python-multipart
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 1f72955602445706b5517a6f58a720796ad3d96a
│   │   │   └── chunk-001.nq.gz
│   │   ├── b083cef4d6c68cf036bae1d9c68a986c6e1e3cc4
│   │   │   └── chunk-001.nq.gz
│   │   ├── b7cc76dbb30d647c0eb7288221d08a6520317b7a
│   │   │   └── chunk-001.nq.gz
│   │   ├── bea7bbb2904da8ce39123a845088dc72464eaddf
│   │   │   └── chunk-001.nq.gz
│   │   └── e59b6b7b60e9993ead149a15a2ec4db73453fe0a
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 1f72955602445706b5517a6f58a720796ad3d96a.nq.gz
│   │   ├── b083cef4d6c68cf036bae1d9c68a986c6e1e3cc4.nq.gz
│   │   ├── b7cc76dbb30d647c0eb7288221d08a6520317b7a.nq.gz
│   │   ├── bea7bbb2904da8ce39123a845088dc72464eaddf.nq.gz
│   │   └── e59b6b7b60e9993ead149a15a2ec4db73453fe0a.nq.gz
│   └── repolex
│       ├── 1f72955602445706b5517a6f58a720796ad3d96a
│       │   └── chunk-001.nq.gz
│       ├── b083cef4d6c68cf036bae1d9c68a986c6e1e3cc4
│       │   └── chunk-001.nq.gz
│       ├── b7cc76dbb30d647c0eb7288221d08a6520317b7a
│       │   └── chunk-001.nq.gz
│       ├── bea7bbb2904da8ce39123a845088dc72464eaddf
│       │   └── chunk-001.nq.gz
│       └── e59b6b7b60e9993ead149a15a2ec4db73453fe0a
│           └── chunk-001.nq.gz
├── blob
│   ├── 0373ae36d13c1a23dc25944f6bc65dcd74d83325.nq.gz
│   ├── 08a70f69527b4f24f66cd24544372654f8225dd9.nq.gz
│   ├── 09691a30bdb3ba1090ec543ed562ff916134b920.nq.gz
│   ├── 09c08fe056c4f5ceaf9617f9a31fe37ba81474ba.nq.gz
│   ├── 0b8e594aaec1ad8829d1bf87fcd3490bed9eb80e.nq.gz
│   ├── 0c81daef83de66cd18eeb9c104e08427695efb76.nq.gz
│   ├── 0cc251d512eccaecedae6bd308190a8bf543507c.nq.gz
│   ├── 0cc4c82ebdf647ffc7d20665cb9cdd35ff91307e.nq.gz
│   ├── 0e0db6523c3f09e64ff6ce8b16fba0881d958e0b.nq.gz
│   ├── 0f1e87f4392c670d7903c82ec45e6429337b87bc.nq.gz
│   ├── 10331505a3b311dad002b8325f20059c50e8b061.nq.gz
│   ├── 13495cfe05242b2bd11e039cd5ea3bab96f9a4df.nq.gz
│   ├── 13fe6fb0a00544184afab3403707e01cd965d186.nq.gz
│   ├── 141731f5739d1f98cc8700a02216382bb20224ea.nq.gz
│   ├── 1489b7afd55dc1d926fd24ad8d4ac5463e0865a9.nq.gz
│   ├── 17133c91464f4016a1a7f35b629aaf78fd732905.nq.gz
│   ├── 1c80c489f49e43813f43dbd32fb1421f2d09b915.nq.gz
│   ├── 1d9fd4dc080b9653431a3e2b3e646c36c90722b4.nq.gz
│   ├── 1f15a78d63ae4679200f4e8d9b03bf9993a5a85b.nq.gz
│   ├── 202d977eb4fb333958410fc84e0b5e638a112892.nq.gz
│   ├── 21940b3272894b8d88ca203547b5900305128044.nq.gz
│   ├── 22531078c5f42c25caf9b218e5128b1ceb0407c6.nq.gz
│   ├── 235493e757affb4391c7c290e6ab5c4e6c93a55a.nq.gz
│   ├── 24b49bfc39a59e9ff3bf69646bc03d28e45dc74b.nq.gz
│   ├── 251cc1d8c434a2c1417346b8a75fe2e3d9ad755c.nq.gz
│   ├── 2546eafe885de228c4dd8a132267bdf4cbca033f.nq.gz
│   ├── 2758d6a76006be21c4de138c121e332dee8beca9.nq.gz
│   ├── 294cb9f30f1507a5e072fd8d4e87155866ea558c.nq.gz
│   ├── 29dd249da94a7f5f61bda98d93b7072219a1076e.nq.gz
│   ├── 2a8e005d5188eb1cac32fbbbb69c19c5eee29192.nq.gz
│   ├── 2c6bbfb2480d273233e115abe7eecd929af5fda8.nq.gz
│   ├── 2d423f03c1a44146b9cd7e398517e4236543fd1b.nq.gz
│   ├── 303a1bf5015ca5c7374a9bde74dee5e2b205fbe3.nq.gz
│   ├── 311105160f1f4f2519ba8265cdf87f8ceadcb80a.nq.gz
│   ├── 3179a9def8f97a24afebbf94502cc23f8077daaf.nq.gz
│   ├── 31acdfbf1d69a0a13dcde2742fdeb6ff04e98e7d.nq.gz
│   ├── 31bfe77e659554b517ba230553cd4639eb6ebd6f.nq.gz
│   ├── 328dd6a4ddcadb365ea13160b5a051851430834b.nq.gz
│   ├── 33797fcc82fbb9f76a05779eb51000809d9fca87.nq.gz
│   ├── 36815d1980abcf496bf63b0ac93525053111dc79.nq.gz
│   ├── 3685246a7e022f2742d72ec5e575848f60051460.nq.gz
│   ├── 3bf70e2ca7579d0a55033bbb272b810e146f86bc.nq.gz
│   ├── 3c60fac02fa653335feb08d9f4a95f1b2b120428.nq.gz
│   ├── 41e9e0bb6ecded4b6fd77605a48e856f530fe805.nq.gz
│   ├── 42081174d0c85c1e395ab9941304b990af550ed4.nq.gz
│   ├── 47c8d6e0352cd9a256322c427814fc674627b9b2.nq.gz
│   ├── 48d12a24d7c0fc5322854f5a3e0d8fb48849860d.nq.gz
│   ├── 493b783c663c55305c2e6a2154d7ab1bc2ece26b.nq.gz
│   ├── 49628503ebcd5c78535235f53bc979d941d964e5.nq.gz
│   ├── 4e5b509662cb20572170ee8c8b262a77bb2923c2.nq.gz
│   ├── 4f24b23c0b48eb05e46f7238001a07881310a5ef.nq.gz
│   ├── 507ba2ce09b373d62fd62e3c6a186f2440a12f57.nq.gz
│   ├── 515f4af746c58260313f2286816307a937f50dc7.nq.gz
│   ├── 543c299d9b31c13c313a58071b8d375123dade33.nq.gz
│   ├── 55c9a802e9174711ae4ea58c060b06617d196f8e.nq.gz
│   ├── 574ed4c24806008b8a973833e1518188cd3f496c.nq.gz
│   ├── 591718521438f19563bc031de626e1aecfece2cf.nq.gz
│   ├── 5a118409520813b083045416201e0feabb3043ae.nq.gz
│   ├── 5a61d836610e017e2114d37e78c7c3329f02fae8.nq.gz
│   ├── 5d59788309257daec3bbd4e3809c5df9fc52cdc5.nq.gz
│   ├── 5fc1ec07a7ae63ae6c53e6880a0a9ba9eac73ed5.nq.gz
│   ├── 67f0e5bb403eb5b05821d846190b7b8ea482cc37.nq.gz
│   ├── 6a0076654c19500d59fb94d6a29ea3d22e04c9d0.nq.gz
│   ├── 7346e0321c217b852ed171fb442c4234e1292eef.nq.gz
│   ├── 7348c210221ff4c3a6ba816e2b0865ef139759c3.nq.gz
│   ├── 759bd102114a75acac5195d7ca5399ce6f6a1227.nq.gz
│   ├── 7604f3b2a26dc580ddd0a7fe851146b11581e202.nq.gz
│   ├── 7690f0860208a7376a8164e304b6b4b943f0b18f.nq.gz
│   ├── 786b75d5a3f6e67decc00ace643d640ba1afe675.nq.gz
│   ├── 7bf567dfc297e9e97c10073b2022efc993e39b93.nq.gz
│   ├── 7d97e51b45f0d0125257513833088cfa1d44506a.nq.gz
│   ├── 7fcd45c2aa72d7351cbf9ce4da7a00b479b3e68b.nq.gz
│   ├── 81c8e82ab9b3750035cd57e949ede25133e35ac0.nq.gz
│   ├── 81eda7b1f14e3cd41d3a8cc18b57eda93c2765c9.nq.gz
│   ├── 82a5787798f332a1a7b2f7e9e81f6e3831b8a753.nq.gz
│   ├── 82b56a1e22f5fe912c4a961e14716e3c92321bf8.nq.gz
│   ├── 8720be85a639437f170836b1a2b5646d5e3d8198.nq.gz
│   ├── 8c12ee4c2e3de3bed36fd2b486e1fc517c4b00a1.nq.gz
│   ├── 8c8a694bba5daaafa7b0ad23bfae39e0b5db87fe.nq.gz
│   ├── 8d9c306b1e0fbcf0cb4cc1b4cafb5a272a73c1a0.nq.gz
│   ├── 921637f918c15c11c1ad41c2dc6e09803d0e7542.nq.gz
│   ├── 92652e020173f59b8ab151de7865966e730178f3.nq.gz
│   ├── 99ee6e683f4900b0389ebd4caa140adf42aedcf6.nq.gz
│   ├── 9a3d85411c5a819101a935a8a15f8df3be0c3273.nq.gz
│   ├── 9c9d1e34d2e618eca7c264893d9a00d10a7b160f.nq.gz
│   ├── 9d5f62a65db8ad9d08e14f97ac6c65eb18d518cb.nq.gz
│   ├── 9de1a3be4b5af6a5bb7a0644248025e479728874.nq.gz
│   ├── 9fb3d874dc26eea26235d4911f763416ac729f7e.nq.gz
│   ├── a085714b0311ea1e08ca41cdb08f1363875c6a59.nq.gz
│   ├── a10325fa2168f95cb7b61ab51b81e7da40c6097a.nq.gz
│   ├── a2aa1348afdf08c089d0be278116931ac178104f.nq.gz
│   ├── a6efa7dde3d6ef99a0ce4d70c20b0c3e26ad7c74.nq.gz
│   ├── a7ff1b31fecb2293698544457bd20183e02b9ca4.nq.gz
│   ├── aab37c0983d74c571d4fa0c77e3bbcb1b66c3cae.nq.gz
│   ├── ab339408ecd404e0613193c81369af98cc0b8c9b.nq.gz
│   ├── ab4977b2c0a3658bbd982228d46fd4da0d921cce.nq.gz
│   ├── ae920bf01604a5dd06ecf3cf6c133cc9a3717d2f.nq.gz
│   ├── b13733144abb051f9b7088511ae03d76c91449b0.nq.gz
│   ├── b45190efd8dae23bf7181de1390b0a3b50bfbc0b.nq.gz
│   ├── baff7d52586e8f664e786d3b3666b3b37b0bd9e2.nq.gz
│   ├── c1cab6eecd986cfcd61939f7287605c1068ded9a.nq.gz
│   ├── c4488099481499d8832996888259587997e198ec.nq.gz
│   ├── c4cdfb6694e6feac9e13bdfdec4b803131fdcf5d.nq.gz
│   ├── c83bf51a35a5599abeb22054e93a40e73e6993cf.nq.gz
│   ├── c84bb9954b901649c2b80cdd027020e7bb2c73dd.nq.gz
│   ├── cb2c2d6a8969deaac82eacb234ab864091533d79.nq.gz
│   ├── cc3671f518dd1768a968b8ceb09b286d17840a7e.nq.gz
│   ├── ce92ff43f2be2763a85036f073458de4d10b2813.nq.gz
│   ├── cf07f01dbc06652cd23fd66efbc4f3bfdd2eb362.nq.gz
│   ├── dce491e18a06b9f4dffe6ab7e04d2e72bf92043f.nq.gz
│   ├── dd2fb43245ec25b7cd5c40d440c2d42dab68c8fa.nq.gz
│   ├── de14ae119c9993ae9552ac4b6177276250a57ee7.nq.gz
│   ├── e4265264586f827d7ee24ee95040143d54b10e9d.nq.gz
│   ├── e4b624d3c248ac6b956a75444caf312f965461d1.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e9a5a6cd5824f311094e0342b921394f54cc08f9.nq.gz
│   ├── ecf0140837f2b46479fc7339354c909ebf3ab5b3.nq.gz
│   ├── edf26ebef2b734e7c968d4aeeac502580c23321e.nq.gz
│   ├── efb1b327cd5ece79a226e99c6477c4e5310be349.nq.gz
│   ├── f0356f1dcc9f4d0a5bac2be478e8cc99deeea025.nq.gz
│   ├── f0d80aa2b1d09a32ae47ca981799d0fe081a8292.nq.gz
│   ├── f26a815a41ee24f382986609609f20b25f421170.nq.gz
│   ├── f3dc8346b90aeb3b4e881cba92c7d5a176e9d50a.nq.gz
│   ├── fbf41ad2e57e5ac269fbe210d9809fc39cc67c25.nq.gz
│   ├── fc380cc6cdc7988c507a5c60e552ec4fa4360b72.nq.gz
│   ├── ff493f432d979413ca7e09048585301817f4f566.nq.gz
│   └── ffa4eb78cc87c88bb9b82e97cacfd078a81e1c75.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   ├── 1f72955602445706b5517a6f58a720796ad3d96a.nq.gz
│   ├── b083cef4d6c68cf036bae1d9c68a986c6e1e3cc4.nq.gz
│   ├── b7cc76dbb30d647c0eb7288221d08a6520317b7a.nq.gz
│   ├── bea7bbb2904da8ce39123a845088dc72464eaddf.nq.gz
│   └── e59b6b7b60e9993ead149a15a2ec4db73453fe0a.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

22 directories, 152 files
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

[Kludex/python-multipart](https://github.com/Kludex/python-multipart)

---
*Parsed on 2026-09-19 by [repolex](https://repolex.ai)*
