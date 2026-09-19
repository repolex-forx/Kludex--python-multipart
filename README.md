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
│   │   ├── 293ea342c64328819862259877c0d3b7af4f3734
│   │   │   └── chunk-001.nq.gz
│   │   ├── 3035c45b87a4a1bcb857e17f0ecbc4696ea75e47
│   │   │   └── chunk-001.nq.gz
│   │   ├── 3f7233d02196d3b66cb07be294b17f2425241959
│   │   │   └── chunk-001.nq.gz
│   │   ├── 5b1aed83adadbff1677779cd0df53723cd80a0d6
│   │   │   └── chunk-001.nq.gz
│   │   ├── 616b81e72fe67ce67e332c446513ef89b9d816dc
│   │   │   └── chunk-001.nq.gz
│   │   ├── 6e0a3d89ab78e64356ce7b1eaac4a8993cab39e4
│   │   │   └── chunk-001.nq.gz
│   │   ├── 72e30eabb9ec4440c9b420700bee799953810150
│   │   │   └── chunk-001.nq.gz
│   │   ├── 851a0263fc0052eeecdbee34331bcde2c2967e75
│   │   │   └── chunk-001.nq.gz
│   │   ├── 876406774d9b98c7b3afa24c3a0c901215f87029
│   │   │   └── chunk-001.nq.gz
│   │   ├── 8ce342cd9ac03fe238c24d68cffaf25a7ea0371a
│   │   │   └── chunk-001.nq.gz
│   │   ├── b083cef4d6c68cf036bae1d9c68a986c6e1e3cc4
│   │   │   └── chunk-001.nq.gz
│   │   ├── b7cc76dbb30d647c0eb7288221d08a6520317b7a
│   │   │   └── chunk-001.nq.gz
│   │   ├── bea7bbb2904da8ce39123a845088dc72464eaddf
│   │   │   └── chunk-001.nq.gz
│   │   ├── c4fe4d3cebc08c660e57dd709af1ffa7059b3177
│   │   │   └── chunk-001.nq.gz
│   │   ├── ce85154ff138227654e19d5a47eea6b316bba427
│   │   │   └── chunk-001.nq.gz
│   │   └── e59b6b7b60e9993ead149a15a2ec4db73453fe0a
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 1f72955602445706b5517a6f58a720796ad3d96a.nq.gz
│   │   ├── 293ea342c64328819862259877c0d3b7af4f3734.nq.gz
│   │   ├── 3035c45b87a4a1bcb857e17f0ecbc4696ea75e47.nq.gz
│   │   ├── 3f7233d02196d3b66cb07be294b17f2425241959.nq.gz
│   │   ├── 5b1aed83adadbff1677779cd0df53723cd80a0d6.nq.gz
│   │   ├── 616b81e72fe67ce67e332c446513ef89b9d816dc.nq.gz
│   │   ├── 6e0a3d89ab78e64356ce7b1eaac4a8993cab39e4.nq.gz
│   │   ├── 72e30eabb9ec4440c9b420700bee799953810150.nq.gz
│   │   ├── 851a0263fc0052eeecdbee34331bcde2c2967e75.nq.gz
│   │   ├── 876406774d9b98c7b3afa24c3a0c901215f87029.nq.gz
│   │   ├── 8ce342cd9ac03fe238c24d68cffaf25a7ea0371a.nq.gz
│   │   ├── b083cef4d6c68cf036bae1d9c68a986c6e1e3cc4.nq.gz
│   │   ├── b7cc76dbb30d647c0eb7288221d08a6520317b7a.nq.gz
│   │   ├── bea7bbb2904da8ce39123a845088dc72464eaddf.nq.gz
│   │   ├── c4fe4d3cebc08c660e57dd709af1ffa7059b3177.nq.gz
│   │   ├── ce85154ff138227654e19d5a47eea6b316bba427.nq.gz
│   │   └── e59b6b7b60e9993ead149a15a2ec4db73453fe0a.nq.gz
│   └── repolex
│       ├── 1f72955602445706b5517a6f58a720796ad3d96a
│       │   └── chunk-001.nq.gz
│       ├── 293ea342c64328819862259877c0d3b7af4f3734
│       │   └── chunk-001.nq.gz
│       ├── 3035c45b87a4a1bcb857e17f0ecbc4696ea75e47
│       │   └── chunk-001.nq.gz
│       ├── 3f7233d02196d3b66cb07be294b17f2425241959
│       │   └── chunk-001.nq.gz
│       ├── 5b1aed83adadbff1677779cd0df53723cd80a0d6
│       │   └── chunk-001.nq.gz
│       ├── 616b81e72fe67ce67e332c446513ef89b9d816dc
│       │   └── chunk-001.nq.gz
│       ├── 6e0a3d89ab78e64356ce7b1eaac4a8993cab39e4
│       │   └── chunk-001.nq.gz
│       ├── 72e30eabb9ec4440c9b420700bee799953810150
│       │   └── chunk-001.nq.gz
│       ├── 851a0263fc0052eeecdbee34331bcde2c2967e75
│       │   └── chunk-001.nq.gz
│       ├── 876406774d9b98c7b3afa24c3a0c901215f87029
│       │   └── chunk-001.nq.gz
│       ├── 8ce342cd9ac03fe238c24d68cffaf25a7ea0371a
│       │   └── chunk-001.nq.gz
│       ├── b083cef4d6c68cf036bae1d9c68a986c6e1e3cc4
│       │   └── chunk-001.nq.gz
│       ├── b7cc76dbb30d647c0eb7288221d08a6520317b7a
│       │   └── chunk-001.nq.gz
│       ├── bea7bbb2904da8ce39123a845088dc72464eaddf
│       │   └── chunk-001.nq.gz
│       ├── c4fe4d3cebc08c660e57dd709af1ffa7059b3177
│       │   └── chunk-001.nq.gz
│       ├── ce85154ff138227654e19d5a47eea6b316bba427
│       │   └── chunk-001.nq.gz
│       └── e59b6b7b60e9993ead149a15a2ec4db73453fe0a
│           └── chunk-001.nq.gz
└── blob
    ├── 016e7f7c18c014c059214b0ef09dd1ecf97cb8fd.nq.gz
    ├── 01a907d30efec25154c327ac289612d240c8fc5c.nq.gz
    ├── 0373ae36d13c1a23dc25944f6bc65dcd74d83325.nq.gz
    ├── 0640374d67246cba12bcc183821ab993ac8ba7e4.nq.gz
    ├── 07bf74275643d781d83e7d8c05fbba638ba3b7d3.nq.gz
    ├── 08a70f69527b4f24f66cd24544372654f8225dd9.nq.gz
    ├── 09691a30bdb3ba1090ec543ed562ff916134b920.nq.gz
    ├── 09c08fe056c4f5ceaf9617f9a31fe37ba81474ba.nq.gz
    ├── 0a7646aa49c7ca91590d86f7c48590a6b7756a5b.nq.gz
    ├── 0b6a29429f1db349acd5c3737394527cb16ab2cc.nq.gz
    ├── 0b8e594aaec1ad8829d1bf87fcd3490bed9eb80e.nq.gz
    ├── 0c81daef83de66cd18eeb9c104e08427695efb76.nq.gz
    ├── 0cc251d512eccaecedae6bd308190a8bf543507c.nq.gz
    ├── 0cc4c82ebdf647ffc7d20665cb9cdd35ff91307e.nq.gz
    ├── 0d0ee8cc40d9b509b7b5564a5962a88266252c08.nq.gz
    ├── 0d7ab32e3ff7e747ec8c5e6b17a53c07d5e1bae5.nq.gz
    ├── 0e0db6523c3f09e64ff6ce8b16fba0881d958e0b.nq.gz
    ├── 0f1e87f4392c670d7903c82ec45e6429337b87bc.nq.gz
    ├── 10331505a3b311dad002b8325f20059c50e8b061.nq.gz
    ├── 10fdc25d81cd5e9bec84aa492e7473cee49a1e6a.nq.gz
    ├── 12e4922b7c85cac6bc005fac0a61b4bb8f50c359.nq.gz
    ├── 13495cfe05242b2bd11e039cd5ea3bab96f9a4df.nq.gz
    ├── 13ce9ed0aebfcdc359fb9766ab3030fb77259b4a.nq.gz
    ├── 13fe6fb0a00544184afab3403707e01cd965d186.nq.gz
    ├── 141731f5739d1f98cc8700a02216382bb20224ea.nq.gz
    ├── 141f2a9ff82a89d9e0c23bc7f5ee6fee77a132e5.nq.gz
    ├── 1489b7afd55dc1d926fd24ad8d4ac5463e0865a9.nq.gz
    ├── 158b7e6f062fffb86815561e1b0b9d77a7535db6.nq.gz
    ├── 16db5b3b88abc3e0fb71bf67d403c7d982d5e37d.nq.gz
    ├── 16f7b05cb9567502b1a88e9165c51258f3a441a7.nq.gz
    ├── 17133c91464f4016a1a7f35b629aaf78fd732905.nq.gz
    ├── 1742ebd257d04b8e6c347e840d5ee84e52acd292.nq.gz
    ├── 1881a56d8e0ac93c2ec4e91a24e9c2f3e4936bca.nq.gz
    ├── 18c720f804c6f034cdb1ee02a616cc1e271a4007.nq.gz
    ├── 1a81077afc64ca5d74cb4b5dbe353cf38dd06ec8.nq.gz
    ├── 1c4425e126bf9d02b6a27cb7e7c41bda1b056171.nq.gz
    ├── 1c6df309edc8fd9c5aaa21d4a7fb867dd73ba8ec.nq.gz
    ├── 1c80c489f49e43813f43dbd32fb1421f2d09b915.nq.gz
    ├── 1d9fd4dc080b9653431a3e2b3e646c36c90722b4.nq.gz
    ├── 1df0fd7ed1a56da241d601be9188bf21a7d958d3.nq.gz
    ├── 1f15a78d63ae4679200f4e8d9b03bf9993a5a85b.nq.gz
    ├── 202d977eb4fb333958410fc84e0b5e638a112892.nq.gz
    ├── 20de33eec361afb462db5490aa2b295beae85ffb.nq.gz
    ├── 212af4e68e2b249b2562409708d513a6eebaac11.nq.gz
    ├── 21452ecd53809fb87484ab4bde1619e8fdf1409f.nq.gz
    ├── 218abe48913135099dd8fcbb6195286b6a156289.nq.gz
    ├── 21940b3272894b8d88ca203547b5900305128044.nq.gz
    ├── 221bb71658639c2c56a15b73832790027fc4dd06.nq.gz
    ├── 22531078c5f42c25caf9b218e5128b1ceb0407c6.nq.gz
    ├── 235493e757affb4391c7c290e6ab5c4e6c93a55a.nq.gz
    ├── 23baf788af2febb98bdd6852af69c669f647302c.nq.gz
    ├── 23c0fffbe1f28499e8f4f3b4576bc99b7a3c45f1.nq.gz
    ├── 24b49bfc39a59e9ff3bf69646bc03d28e45dc74b.nq.gz
    ├── 251cc1d8c434a2c1417346b8a75fe2e3d9ad755c.nq.gz
    ├── 2546eafe885de228c4dd8a132267bdf4cbca033f.nq.gz
    ├── 2758d6a76006be21c4de138c121e332dee8beca9.nq.gz
    ├── 28c7ad6be4d4200f6c7a9822e174f40ad4fe5ffa.nq.gz
    ├── 29206ded54f5bff489bd363b188a38f2ba519408.nq.gz
    ├── 294cb9f30f1507a5e072fd8d4e87155866ea558c.nq.gz
    ├── 29dd249da94a7f5f61bda98d93b7072219a1076e.nq.gz
    ├── 2a8e005d5188eb1cac32fbbbb69c19c5eee29192.nq.gz
    ├── 2ae1c4eaf0f086a03a5a254d803bd11fa9b83e17.nq.gz
    ├── 2b4e5f6485db557f200b48aeb75bb8173199a4e7.nq.gz
    ├── 2be283b94146c17afa09e5eea310f2ac55e65670.nq.gz
    ├── 2c6bbfb2480d273233e115abe7eecd929af5fda8.nq.gz
    ├── 2c7faf0ce7db3cb8f3f456a29c4e0c7a7d422d71.nq.gz
    ├── 2d12eb3fb3e8dc0d61f15676073618d71576524c.nq.gz
    ├── 2d423f03c1a44146b9cd7e398517e4236543fd1b.nq.gz
    ├── 2e22812b5e4209ab719f104ac84c904794580d2f.nq.gz
    ├── 303a1bf5015ca5c7374a9bde74dee5e2b205fbe3.nq.gz
    ├── 311105160f1f4f2519ba8265cdf87f8ceadcb80a.nq.gz
    ├── 312194a1ba9975fcaf3ca604bb6ccd983a690a6b.nq.gz
    ├── 3179a9def8f97a24afebbf94502cc23f8077daaf.nq.gz
    ├── 31acdfbf1d69a0a13dcde2742fdeb6ff04e98e7d.nq.gz
    ├── 31bfe77e659554b517ba230553cd4639eb6ebd6f.nq.gz
    ├── 328dd6a4ddcadb365ea13160b5a051851430834b.nq.gz
    ├── 33797fcc82fbb9f76a05779eb51000809d9fca87.nq.gz
    ├── 33f47449c11d241e36c83d7f95d819bbe56e2c8f.nq.gz
    ├── 36815d1980abcf496bf63b0ac93525053111dc79.nq.gz
    ├── 3685246a7e022f2742d72ec5e575848f60051460.nq.gz
    ├── 3a814fbd98f292e07b19a6e3cee93928a427449b.nq.gz
    ├── 3b9cefa8681b865c67b9097aae69fedbb8010020.nq.gz
    ├── 3bf70e2ca7579d0a55033bbb272b810e146f86bc.nq.gz
    ├── 3c60fac02fa653335feb08d9f4a95f1b2b120428.nq.gz
    ├── 3d6f080a11a676ad8e7fb8d228c88465a1b8e222.nq.gz
    ├── 417650cac03d15a510b4829c8de0bf55026d435d.nq.gz
    ├── 41e9e0bb6ecded4b6fd77605a48e856f530fe805.nq.gz
    ├── 42081174d0c85c1e395ab9941304b990af550ed4.nq.gz
    ├── 47c8d6e0352cd9a256322c427814fc674627b9b2.nq.gz
    ├── 48d12a24d7c0fc5322854f5a3e0d8fb48849860d.nq.gz
    ├── 493b783c663c55305c2e6a2154d7ab1bc2ece26b.nq.gz
    ├── 49628503ebcd5c78535235f53bc979d941d964e5.nq.gz
    ├── 4ceafb72ea8b1999d601cd1ad7b94b8e8ef1a48e.nq.gz
    ├── 4e341a2fb4123fffbf36e013965a3c9b41b88b0d.nq.gz
    ├── 4e5b509662cb20572170ee8c8b262a77bb2923c2.nq.gz
    ├── 4eea5b6e69e157060b51050a628a3b259f247296.nq.gz
    ├── 4f24b23c0b48eb05e46f7238001a07881310a5ef.nq.gz
    ├── 50074c8fe98c843d391b6908be14c9cbc1f85359.nq.gz
    ├── 507ba2ce09b373d62fd62e3c6a186f2440a12f57.nq.gz
    ├── 515f4af746c58260313f2286816307a937f50dc7.nq.gz
    ├── 542b462515db7875ea5813c33181870ae06edff7.nq.gz
    ├── 543c299d9b31c13c313a58071b8d375123dade33.nq.gz
    ├── 55c9a802e9174711ae4ea58c060b06617d196f8e.nq.gz
    ├── 56dbb3f5e2df91ef433092939e3c9fe04b7ec158.nq.gz
    ├── 5724e30a4f704821e762730280ef7f58612b7880.nq.gz
    ├── 574ed4c24806008b8a973833e1518188cd3f496c.nq.gz
    ├── 5833d836bf3d107642b22234c8ca6a93176e4a93.nq.gz
    ├── 591718521438f19563bc031de626e1aecfece2cf.nq.gz
    ├── 5a118409520813b083045416201e0feabb3043ae.nq.gz
    ├── 5a2aba810cd3eb3d8fe03c5e4246ba35de53e7ad.nq.gz
    ├── 5a61d836610e017e2114d37e78c7c3329f02fae8.nq.gz
    ├── 5cfacf4f2c30cba51032a02019f5875c2876c861.nq.gz
    ├── 5d59788309257daec3bbd4e3809c5df9fc52cdc5.nq.gz
    ├── 5fc1ec07a7ae63ae6c53e6880a0a9ba9eac73ed5.nq.gz
    ├── 5fd2f41ff90613d44e677d268a3562dd997b8b52.nq.gz
    ├── 63078f718638f0ed366cefe4890ca87e0afe4859.nq.gz
    ├── 66915adb118a1b0dd9cbc49636b3e6f2318d4e42.nq.gz
    ├── 66b6e4c2f3b55b25afd9716f9d3c5afb47b15d4e.nq.gz
    ├── 67f0e5bb403eb5b05821d846190b7b8ea482cc37.nq.gz
    ├── 69a3ed4233dd099d7b0c6bab4df16294c531d06e.nq.gz
    ├── 69f3835c8d87fff650fab6437140e037cce171a8.nq.gz
    ├── 6a0076654c19500d59fb94d6a29ea3d22e04c9d0.nq.gz
    ├── 7346e0321c217b852ed171fb442c4234e1292eef.nq.gz
    ├── 7348c210221ff4c3a6ba816e2b0865ef139759c3.nq.gz
    ├── 73910da97daafdbce805c9dafb61117fc58889b8.nq.gz
    ├── 759bd102114a75acac5195d7ca5399ce6f6a1227.nq.gz
    ├── 7604f3b2a26dc580ddd0a7fe851146b11581e202.nq.gz
    ├── 7690f0860208a7376a8164e304b6b4b943f0b18f.nq.gz
    ├── 78020117992750e43f2e7856e57cef0e6634d8c4.nq.gz
    ├── 786b75d5a3f6e67decc00ace643d640ba1afe675.nq.gz
    ├── 7b4fd5c6c89944a048bada6c9b9ca6d46a27167a.nq.gz
    ├── 7bdc864d1c6dc9fefe99c354ba4a938188e97607.nq.gz
    ├── 7bf567dfc297e9e97c10073b2022efc993e39b93.nq.gz
    ├── 7d343779f8efa51bb200d3147fd4cfc74c0a7694.nq.gz
    ├── 7d97e51b45f0d0125257513833088cfa1d44506a.nq.gz
    ├── 7fbeff71db0e4721293c21f2780ffa8c29900d49.nq.gz
    ├── 7fcd45c2aa72d7351cbf9ce4da7a00b479b3e68b.nq.gz
    ├── 80d5cc0bb961045cbb03268b19f7cd6a182beac7.nq.gz
    ├── 81c8e82ab9b3750035cd57e949ede25133e35ac0.nq.gz
    ├── 81eda7b1f14e3cd41d3a8cc18b57eda93c2765c9.nq.gz
    ├── 82a5787798f332a1a7b2f7e9e81f6e3831b8a753.nq.gz
    ├── 82b56a1e22f5fe912c4a961e14716e3c92321bf8.nq.gz
    ├── 8439954e5813ee83d02f0f13f407166b6099142d.nq.gz
    ├── 845a926a1ae7108dddfb053e698ea01489c060f7.nq.gz
    ├── 8720be85a639437f170836b1a2b5646d5e3d8198.nq.gz
    ├── 88df444566d551c7ab74acd5a6691409473b0279.nq.gz
    ├── 897188d3eea01df0e86e8fa18e3fba6fa3ee8498.nq.gz
    ├── 8b0ccaef68c0c378ca4db28f59d54e445a79968d.nq.gz
    └── 8c12ee4c2e3de3bed36fd2b486e1fc517c4b00a1.nq.gz

40 directories, 200 files
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
