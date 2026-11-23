# Repolex Knowledge Graph of huggingface/xet-core

RDF knowledge graph data for [huggingface/xet-core](https://github.com/huggingface/xet-core), parsed by [repolex](https://repolex.ai).

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
rlex download huggingface/xet-core
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 286e66301212a22fc2cf5ed5f067e5721deb14e5
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 286e66301212a22fc2cf5ed5f067e5721deb14e5.nq.gz
│   └── repolex
│       └── 286e66301212a22fc2cf5ed5f067e5721deb14e5
│           └── chunk-001.nq.gz
└── blob
    ├── 00946b6cdce8a12fafc4901e71e1fb499e1eba0e.nq.gz
    ├── 00c2095cf30bbe8a7c08cab7a6fd98c83ecaa01e.nq.gz
    ├── 01540093953d57c1fb009a9ec9224c46e32bbf79.nq.gz
    ├── 01a52fe6347455d18deaab58f9e8a42325e20049.nq.gz
    ├── 01d706e64ad87fb9751e09952fac357be2e6b281.nq.gz
    ├── 01e479815d21d4712f0609b65f0cb2bf59347a6a.nq.gz
    ├── 022cb73073f80e5b83b958d8b8a4e3ac73716cd8.nq.gz
    ├── 02ab050a163695c2d978ce836b929095e12fd3ac.nq.gz
    ├── 034967f967ca5ecf83b0c9f2b08003917be5968c.nq.gz
    ├── 03bac39584c768b6623732557ba3ba78725a7f45.nq.gz
    ├── 074a7340fd87529ede2df92e3a3b2975e77f8226.nq.gz
    ├── 08502774fdf5a2dda76c0f0bad38c3661b4719a8.nq.gz
    ├── 08a6d2abfdb8b9beba0e1024989cfb49fb7d84e2.nq.gz
    ├── 097eae02868be84a0beb574d4a55b431d4715b91.nq.gz
    ├── 09b9c09c77beda0943e686be557f66f6491cc97f.nq.gz
    ├── 09bd1a1fc253be728c19cfff4f90b40f9ad9e970.nq.gz
    ├── 09f74cb8f446317c0e7947a0dd774fbaae60c054.nq.gz
    ├── 0af8569bb300ce8198585bcb8d2de2fff101bb28.nq.gz
    ├── 0b756e065c84bd34648a9ed6190fc46aacb57fce.nq.gz
    ├── 0d9e878df532399bf3a49a4782bb9ee3319d860d.nq.gz
    ├── 0dd21b74d385cfa46335a2e21334d03e53b3d1ea.nq.gz
    ├── 0ebf3a2e467ce763f5c09c3a11c7e1ef294eff9f.nq.gz
    ├── 0f47c24b6211a2cff2070d6be441cdba486687dc.nq.gz
    ├── 0f9caf03874f14e30bd4bb09e9ad0e262bcee544.nq.gz
    ├── 10fa14c5ab0134436e2ae435138bf921eb477c60.nq.gz
    ├── 16b37bc79b8d0b6804783ac20fb39cf253bc3242.nq.gz
    ├── 17277890a540fe3f4a0b25e2a299114fadc79f3c.nq.gz
    ├── 175d21110375b07a0f93d88859021ce439e8173f.nq.gz
    ├── 1aa26928c5da40b324d6691bacd4f42853ef9a99.nq.gz
    ├── 1abe8ac06f2af93f2e1612df17767d7c684588fb.nq.gz
    ├── 1b5ec8b78e237b5c3b3d812a7c0a6589d0f7161d.nq.gz
    ├── 1bd24a4b2302854dc4e6a73bf072e55d3814abc7.nq.gz
    ├── 1e3ae2632af3f07d23debbc0c242b53addae5bcb.nq.gz
    ├── 1ef277d3f1fd3ec3375912ae96435c0078ebe0e0.nq.gz
    ├── 2074c780b44b6411013b3fe84b5c528ed0818353.nq.gz
    ├── 20a26f36259bb967071c0b1e5bba5e9a2b2c15ad.nq.gz
    ├── 20fe888c30ab44fa877a58de0304f4b5e2a5a5cf.nq.gz
    ├── 210c0257b3715d127d5ab7a55a88c5d0f1200595.nq.gz
    ├── 221fe7e00929acfe6f4a417ba59fb8545aeb4e33.nq.gz
    ├── 2227c3047974643c823484189b189ad6b67243c0.nq.gz
    ├── 230aa56ba2f59493becb171cd64699f32a354bfd.nq.gz
    ├── 23e856f5deeb7f564afc22f2beed54449c2d3afb.nq.gz
    ├── 246de2c8bbcd184289206c066d3017455e0d3e44.nq.gz
    ├── 2690d84aaaf76a31e59e8bb365098305276f0dee.nq.gz
    ├── 27098f167aa02de0f7873d5464b8094ed99061e1.nq.gz
    ├── 2cc9999957f9128f916965a3f2de81775c8786a5.nq.gz
    ├── 2e13752019c42e83cc86080566321e4930fe6323.nq.gz
    ├── 3012ca31190754a030f6e2b661ea6613c72f8d79.nq.gz
    ├── 310fe823f0bfe5235ad67c8bd546cd578ba8a733.nq.gz
    ├── 31806e8d8f4526df6fbd3908b990d265eea15322.nq.gz
    ├── 31aa79387f27e730e33d871925e152e35e428031.nq.gz
    ├── 3228d42dc97f3f8741a7d0a25ffc6f0ace3b2ce5.nq.gz
    ├── 322971a8781090d726c68e5a9653d9f04e371b72.nq.gz
    ├── 3250175b09bd553dad80f34bb5d1745cdc9c2bd2.nq.gz
    ├── 38205157237a2486acfbd486453846e7a01b7441.nq.gz
    ├── 399eab1924e39da570b389b0bef1ca713b3b05c3.nq.gz
    ├── 3b608a3acd3377d0effaed92255de57eab304f81.nq.gz
    ├── 3c0272534123e2e17adb886ff0a2e32fd755ef45.nq.gz
    ├── 3d23c3a0e57d4919c6736275d9d3544b67222afe.nq.gz
    ├── 3ec4d71c0d5a7ce1f341df101d61ff27f9e3469a.nq.gz
    ├── 3f15fa9830373c6f5d26e76793a9c7f5af38bee2.nq.gz
    ├── 3fd8df4435f606e63cfaf3a0bd5a4f4e77bb0388.nq.gz
    ├── 400c6f27de8e18ec9758d34e0308657f9b298f24.nq.gz
    ├── 409997ce767b6f3436a874fdfaa9dbebb5474b6c.nq.gz
    ├── 40af29cf4df81a24436116c1a9abbf533260f209.nq.gz
    ├── 4142082bcb939bbc17985a69ba748491ac6b62a5.nq.gz
    ├── 41f17a8b2ea7b68b8d7485be911001a707682bb6.nq.gz
    ├── 42864265ddcc6a6f892274753630697270cce275.nq.gz
    ├── 43142ff9080b90c15c8689c12367d1f9d4f4c6e8.nq.gz
    ├── 443123034fd62a14d86bd27297431d8578fc47f0.nq.gz
    ├── 498b267a8c7812490d6479839c5577eaaec79d62.nq.gz
    ├── 4a4b2d39891f7ca84a79b6a17e9afde018e0452d.nq.gz
    ├── 4c2edf2986cfeb568c92c5fb48d21aedab0579e8.nq.gz
    ├── 4c44742d545237239a2f640203b3fbef29992bb0.nq.gz
    ├── 4c47f34d8d5fa3e8d02801a16172d4e0e7601017.nq.gz
    ├── 4cd26201d71ccfc57c0db8e5fe0ee8b3697b6ca0.nq.gz
    ├── 4ce688d32b7532862767345f2b991ae856f7d4a8.nq.gz
    ├── 4d5da58424bc72898470eabe63d51382f0665d1f.nq.gz
    ├── 4e924cb6ebdc29d8c44f951e814de4ea8dc00b6b.nq.gz
    ├── 502d4515c6cf20bd413a501ee9e0a46b7c543964.nq.gz
    ├── 5178514a001687c0f029e8568ee67e22cd255f4e.nq.gz
    ├── 520636301cee39f06913974c4c88cc609d30b472.nq.gz
    ├── 532b16bdb6f80587674349b29a2629a6870a557f.nq.gz
    ├── 54a207abee97913204aee44dffea5a479cf1a242.nq.gz
    ├── 54d958b2780d03c964d06fd6dfc7d2df5ccedb1d.nq.gz
    ├── 54fc6f119fbd3f3692e514b5931396df7aaf0547.nq.gz
    ├── 55b670a3e73c95f498d8e1f9c690236ada864101.nq.gz
    ├── 57ab32ebf051a89edba1ae069bc42298a4b0f022.nq.gz
    ├── 594945f930b529d034b86327f26bae60ba6794fb.nq.gz
    ├── 5aba7da4769b8fe988c05176786adb88184de777.nq.gz
    ├── 5be35e9c4caa555ded7b4e4fba2562347e2af609.nq.gz
    ├── 5c0b9a3bfa243cc13a04abbc44edddcddd32fefc.nq.gz
    ├── 5f9f1e2caf0947a4b71411f128a0dd30c14b74e0.nq.gz
    ├── 5fb57441566abad6ed03b0e397cd01782976163a.nq.gz
    ├── 610e8aa60f6f9e0a0e7722ef538d1e9168491889.nq.gz
    ├── 61f916ad208bb2af91f82cf2ffffd3715c3ce66b.nq.gz
    ├── 66a03583eb394ebdf6675ed1075d33ef7a5ec4d3.nq.gz
    ├── 684cc4110b714522e8e30d419fcde7c7dde07e7e.nq.gz
    ├── 693699042b1a8ccf697636d3cd34b200f3a8278b.nq.gz
    ├── 69ebf3324562f3a8cac021d9c32e1c03f23a29d4.nq.gz
    ├── 6b61ce7be5812533877396ca89d0244dd67ea2a8.nq.gz
    ├── 6cbef5c370d8c3486ca85423dd70440c5e0a2aa2.nq.gz
    ├── 6ce2f1f6855d7cc9abeca0ea8d4a23cffd88ef36.nq.gz
    ├── 6efe28fff834a94fbc20cac51fe9cd65ecc78d43.nq.gz
    ├── 6f15841dc09ba91abcf265b33877a419748f8553.nq.gz
    ├── 6f36f338c20b36184d756d95d335b29987d03755.nq.gz
    ├── 6f708672607f314cf229090ad03f0246ab18b8e0.nq.gz
    ├── 6f9b5dd9051cbd95853d074d41bc3b1870c95ee3.nq.gz
    ├── 7041bd8d630b5113a94580544b0ffa23361ab5bc.nq.gz
    ├── 70b5ad32663ce5e3a2ce1ab0490e0a2b8ddb5cb3.nq.gz
    ├── 719b1b82cfa94041feb047a994694176322bb46d.nq.gz
    ├── 71b52f370adf529bf5505ec34bd44ebdfd00244a.nq.gz
    ├── 76219eb72e8524f15c21ec93b9b2592da49b5460.nq.gz
    ├── 764bce89afa983f2d480b8eca595cbb586cf81eb.nq.gz
    ├── 79429b5b98271c5285c90ce44ec737ac28424783.nq.gz
    ├── 7974a6249e43040f8ac079e1f0c7ba3abb61329f.nq.gz
    ├── 7b2f87a52caa0c6c10683acd38a1d40742cf4e7f.nq.gz
    ├── 7c89b61ee84d2ac12b15477524458b21e03464a6.nq.gz
    ├── 7d076b13c0762ba66da1c9c095af413b5e92452f.nq.gz
    ├── 7f4e95c47f8f2f2ab256916a577f52da624df2d8.nq.gz
    ├── 7f621ef20b81a803961682ba56c6522d192d69f9.nq.gz
    ├── 7f77985fabc1ce1232a992d05fc86437dae6e5cb.nq.gz
    ├── 802d556f6e257d69c4d5365d21b1491420e6dcc3.nq.gz
    ├── 822168cfc4a6d3acee9a0346c859cd9e4e8f3c2e.nq.gz
    ├── 82eb90190cfd01dead4bb3a8b257024b5e1524c9.nq.gz
    ├── 88125aa12b9b5fea2598ac499f5243adcc61c45c.nq.gz
    ├── 88a15be6120fdce66263d33c4e3cd9bb9f5605e0.nq.gz
    ├── 8ab61abedc39ceafc8c6d5aa9492f670e69685af.nq.gz
    ├── 8b2ef0f4e7fcbc076ffc637f19f372c8242f5d4d.nq.gz
    ├── 8b58136e52b1dc468ca80f584f3314cf6f0057e0.nq.gz
    ├── 8b5dddbada453837e335c979b40b8878b1d229e9.nq.gz
    ├── 8d0c8c0b2033a98da6e0dfa19f4434e3d46fb879.nq.gz
    ├── 8dc97b9407a78eb284561fb0cd0970fc82c9fb13.nq.gz
    ├── 8ec3fb05c41cbc8d8f4ee7bb78838d809759eb01.nq.gz
    ├── 8eed23f0f2ddedca93925470de1a89d8c699dfb6.nq.gz
    ├── 8fbe57aeb19ad4216a504de3d3071be40e2abc27.nq.gz
    ├── 8fe4ce0e6b00cc71b314249f20c0289c23c8fcc2.nq.gz
    ├── 92970e9576f14dc34c090d1a279fcedec143bdfb.nq.gz
    ├── 92c64cf8d6b88c8a96b317fe21d241bd81a51bf0.nq.gz
    ├── 930bcdcac1cf3a5074218bd5259ec648b010f885.nq.gz
    ├── 932713cb354bcff4065e02326e78a80a666cf08e.nq.gz
    ├── 93aad16fcedbb79d4f4bb22843722a8260378453.nq.gz
    ├── 95525e63a778d44e6a23b37ef287513667b11ea1.nq.gz
    ├── 965b606f331b51d566b46025f9ff311a7aad0c12.nq.gz
    ├── 967a195aa60d92964a30be6dd52a8e8e0169162a.nq.gz
    ├── 9696ec0975ca8b91dc5f92c433fb5284e285a4c9.nq.gz
    ├── 97136017dfab7289ea1330c07734857a8b71ff4f.nq.gz
    ├── 9762d33ec9bfc5c3963694d9c1292c0ed0401f5a.nq.gz
    ├── 97e3b243ba6072ad501f5dd4e033d04557c0f19e.nq.gz
    ├── 9a9d75e098542afe30dea1f8994904d7754680ee.nq.gz
    ├── 9be51434a697eab23341f361457fd7683bdca043.nq.gz
    ├── 9c6ac19c79fe596afb9ad5ce3a491eb94fe005ef.nq.gz
    ├── 9db4f91112add72743df32d1e4cdad158b6776cf.nq.gz
    ├── 9f4676a6e15e8abb63c2137103bce6aff765417f.nq.gz
    ├── 9fce44622049a016eaf4f0605ea7c2ae0fd37c7f.nq.gz
    ├── a02992c4e1f2d17c9022e10b8283cf5317a70726.nq.gz
    ├── a152173058950a82c02b047a5fb66b1d6a7c0c27.nq.gz
    ├── a161cb00e315243d4506c83fb1ee28d2235a0668.nq.gz
    ├── a1d6aaba714cbea9d678d0264a3e6a9a3563ea50.nq.gz
    ├── a1f1762406da31b5c8f73f199c53c916317cfe50.nq.gz
    ├── a1fd29ec14823d8bc4a8d1a2cfe35451580f5118.nq.gz
    ├── a23f26823f3dbeb14cbf689a0721ab66cb02cd3f.nq.gz
    ├── a337d87ac82064d10778300606c34baa8492e78c.nq.gz
    ├── a4c80ab584d956bc12d5e987ed0879ac78e767bf.nq.gz
    ├── a5196d1be8fb59edf8062bef36d3a602e0812139.nq.gz
    ├── a5d7b84a673458d14d9aab082183a1968c2c7492.nq.gz
    ├── a61d4c20bb97821b0ea0d6e29baef0f3a7baa598.nq.gz
    ├── a623d92b44c34acd7adcd1251bbc8be0b4356b24.nq.gz
    ├── a6388f4f31259214553051d3843732f4f4e5654c.nq.gz
    ├── a66116bf1b46a6c9ed20adfe046315ff097be892.nq.gz
    ├── a8308790e0c20c88751230f8ea3e5733d7898a52.nq.gz
    ├── a8c4f74ba800b6f24380e491ae99d35ff97c2e6a.nq.gz
    ├── a9adfa5a90ba3714a2212c4401a758371a270a66.nq.gz
    ├── acbb554d5ceacd47b7b341a82662b0214f339794.nq.gz
    ├── ad46c5d41757ad6025a7a7fe93f6cd6ad31f3b38.nq.gz
    ├── ad84caee53da1a6e8e9672430d29c4b57ecbb967.nq.gz
    ├── ad8a393eaa31d9fc9b407970e712a827778d2ab7.nq.gz
    ├── ae64b6530b3a0f86ec74d0b42301069f11dfa13b.nq.gz
    ├── af5a0c0018b5e9c04b56ac52f21b4d28f48d99ea.nq.gz
    ├── b3aa10bde067d38200f0809c3417f93363d794f3.nq.gz
    ├── b3b0757b3554df2542d102cd2fa1d6afb78ad2ea.nq.gz
    ├── b3b9234ce5c97bbe77793d9406839f63b9acaf7c.nq.gz
    ├── b4b1e9e4ad02e3aa0fc8399350ead6350e8eb49d.nq.gz
    ├── b58d1184a9d43a39c0d95f32453efc78581877d6.nq.gz
    ├── b63543c3a86bd4a87580f4db4e3a4cf3acad18ee.nq.gz
    ├── b77d4e1f9bb7c576d34f6f616860e64e7068fdc8.nq.gz
    ├── b916b7764a7283f91d55cc92eac9e53054c53d79.nq.gz
    ├── b98460fcbe2a0eaa4afc2872ff4da8a6d8f7dde7.nq.gz
    ├── b99f58ad116cca46e9775979046cfe83c0964455.nq.gz
    ├── b9fde52597c6f9e8438366bc31c8aee260c150d6.nq.gz
    ├── ba62a23a941d9a64745d25e1ec653cb62df80c68.nq.gz
    ├── bc2a2a469e3f7fb229a56d008dee443135bfe165.nq.gz
    ├── bca0261a1a844e1d0b90d677dd0b0fc076823b8b.nq.gz
    ├── be274e068a97be6b7338d86ea3752d25ba3c00b5.nq.gz
    ├── bebe4c8873000b8d9b0c6a68cdcd4d1491b5faf1.nq.gz
    ├── bf3c24df298a962971330393e6bc74bae630f821.nq.gz
    └── bff944da82df84492752a1033f00d62870140fda.nq.gz

8 directories, 200 files
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

[huggingface/xet-core](https://github.com/huggingface/xet-core)

---
*Parsed on 2026-11-23 by [repolex](https://repolex.ai)*
