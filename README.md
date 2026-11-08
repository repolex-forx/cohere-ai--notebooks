# Repolex Knowledge Graph of cohere-ai/notebooks

RDF knowledge graph data for [cohere-ai/notebooks](https://github.com/cohere-ai/notebooks), parsed by [repolex](https://repolex.ai).

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
rlex download cohere-ai/notebooks
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 62cfb71b3416bca826c5670b77e5d704f742afd9
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 62cfb71b3416bca826c5670b77e5d704f742afd9
│           └── chunk-001.nq.gz
└── blob
    ├── 00b3f02391b516e44a289ea4fdff7f8a3e224e69.nq.gz
    ├── 02a607fd7df605a425ab33712a206c5dd20dde0d.nq.gz
    ├── 081b3ffb16082cddcda594ece134b9352efb6355.nq.gz
    ├── 09c0c30c3e49bc0d414c75f0eea00cf1a46f3b20.nq.gz
    ├── 0ad079e079ab13ba350bf3ce8376292a2cb4b691.nq.gz
    ├── 0cb109e1368f8346af6d37dbd18b759168453f13.nq.gz
    ├── 0d18e1e64926c783cea8be4ced2da8a7bd5d1a43.nq.gz
    ├── 0d7fbadd8266a9dab8a95e64cba2bcf42a63f265.nq.gz
    ├── 0da481c58fc1872563ee837fcb31983e4c752a1d.nq.gz
    ├── 0eb638caf24e93a1eb71ee0eaf97f98979033c15.nq.gz
    ├── 0eccd8372c879813a8bb14a9d6fc4d17660090eb.nq.gz
    ├── 100565663867aabc20eb608b15b96dbc83ad480c.nq.gz
    ├── 11e7107d4ebd7670bc75171c5a4a7a1a44b6f98e.nq.gz
    ├── 128defe650867c7824050df4c5235a426b4d9748.nq.gz
    ├── 1419677aa0aa743dedf27760982d20c98b09bf38.nq.gz
    ├── 15200f313416701f2e21772eb272dd39629c8f33.nq.gz
    ├── 16752f0d1d258576052a754536b0536bdfbeb2de.nq.gz
    ├── 19879d1fd2599703b8117a796cb892aa3f39ce16.nq.gz
    ├── 1a5a68278d599919e99ac841dcc7f7596da5e4ad.nq.gz
    ├── 1bc6d6797f3c969a509a4467649b1fa3d59f35cb.nq.gz
    ├── 1c38a271f7e412b3f5b6b99153d0c4421dcb426e.nq.gz
    ├── 1c6aded64e3c8ffb812e08b1b70b4096c52baf8a.nq.gz
    ├── 1d911c66651fe8482a954dac2e6333574e9adfe4.nq.gz
    ├── 1ef3bb1a9cf945392b5d14acb97a5fcbbdc4d248.nq.gz
    ├── 1fe89905e573a4c00b9eb65d91d456a784f6754c.nq.gz
    ├── 1ffadd776c0387e10e1fa8f2480543ea9a87402e.nq.gz
    ├── 20a77eee475c1a49d2ed91af14fea5cb50ee94bd.nq.gz
    ├── 21f58b225afef0ec14aa67d96c18244f0ec7746e.nq.gz
    ├── 21f87c0097a3b4477781b29a1252900c0c39638a.nq.gz
    ├── 22c890e51d79a94f3a17769f047899af2dca43de.nq.gz
    ├── 22f79610f80e4269e95276dd861a629486460c0c.nq.gz
    ├── 23142ccd9bcbfecf6f7bf965787aab4e461ac6c5.nq.gz
    ├── 232a543fe856e1f1237cfe57cf09152007386efc.nq.gz
    ├── 25d183b1c555560de85df5a0b247420c3ece69c6.nq.gz
    ├── 25ee4e18ecd70405c493cd802a2a2b27c157be04.nq.gz
    ├── 260206d9b165c320b76775681f33d7a39705360b.nq.gz
    ├── 26da7957a27bf0fda0a9e546cfb1d3102bbecdee.nq.gz
    ├── 2766a553547be05467eb435606b221cea9313a47.nq.gz
    ├── 286a42adafa8bc08827fb48616f63cfde919487b.nq.gz
    ├── 29292bfff178b383090a1efbb09bf0d174f53ddc.nq.gz
    ├── 29d31ad1f72a91426a3586a1809619785b5c83d8.nq.gz
    ├── 2a5106c278a197fcf07231f35846bf8f538f988d.nq.gz
    ├── 2a86cb415e2ebd05cc9e847216238be973affc74.nq.gz
    ├── 2b1ca51a41b882ac2c04e9cff90e649551ad5374.nq.gz
    ├── 2b8c76b1e14a37b91fee0f778e94e16465475fcf.nq.gz
    ├── 2befb4b0e55ce25556eab3d9566af4e5db6a2426.nq.gz
    ├── 2d7f28319ee828a8221078064c5e247541475a2c.nq.gz
    ├── 2df969688ca03697535922f73e6a55b34f63b5a0.nq.gz
    ├── 2ed8b58e0593c1b5275b397c7bc1ccb8b48aaa83.nq.gz
    ├── 2f26422d4ac2e3f577c5e816a3195503c1bf90f5.nq.gz
    ├── 2fbc4609760d46f4f4a2112e4e058ca732d46f4e.nq.gz
    ├── 30bebd0e269fbc334bd39c7abc563d5f3c94b31f.nq.gz
    ├── 30f252a2f8c14a2b9dbb527832488ffd945a1fc4.nq.gz
    ├── 323bdda03a00967d3a2389c15ef124f059208993.nq.gz
    ├── 325ea2bfbbe29a9fc6c524175981612b55f29c9e.nq.gz
    ├── 3296642d43eca371509eb509169213fba3182080.nq.gz
    ├── 32a5d6323faab8db30e2c554874f6fd09feb3f7b.nq.gz
    ├── 3304c08a7ad5a98d694cd5a9a67d3320efd20740.nq.gz
    ├── 331d55e1ff7204ee9240f977c05a8258e2f44856.nq.gz
    ├── 3324c76af48454baeee78b1ed072dc1d376dbe73.nq.gz
    ├── 34c4241cbded4279e23b73344391228d392c1d45.nq.gz
    ├── 36980a3c3a580122f8c585729bc865018543c45f.nq.gz
    ├── 384b5935d30b8895fdad533eb36313480590b457.nq.gz
    ├── 391c147ae553bb47188ae5785cbb9742df05769d.nq.gz
    ├── 39395a329ae55420951822f35392b743e987ddc0.nq.gz
    ├── 39f090ec404c5370dca9f32f6f203e27856a9332.nq.gz
    ├── 3b588e1a90314031095a534e55ae25daab17bc31.nq.gz
    ├── 3ba93a719fe2686496b21592d1e64d39ab85cfd3.nq.gz
    ├── 3deabba7998dc79a3b245ff338dae6a74b845f4b.nq.gz
    ├── 3ea43925f567b3859b22ede81ecc0c2163f1dad7.nq.gz
    ├── 3f30daecb78b3a34cbf19a9b96502ee1e5c67b07.nq.gz
    ├── 3ff9d378051dc39cfa17fda9764301fe139fca66.nq.gz
    ├── 40aa44e59cfb22917078e645acd072a6b6434d93.nq.gz
    ├── 413bc08c79d9a3aa5d9e231c4cc31830598f91f0.nq.gz
    ├── 441348795d9e04e906b6a27580b578d9276fca2d.nq.gz
    ├── 4426fe1bf8d2e49c2f6349f595b723d84a056093.nq.gz
    ├── 45410c37a3bd7f06dfe45cd416d77338017f3242.nq.gz
    ├── 456561a1c52f2b844ff6d3c1b3a5966fb133112c.nq.gz
    ├── 457fcbed805e8be6ff38e25c06ffb1c8ddf445dc.nq.gz
    ├── 45b467918b7ab26fcf1187436a2ac6484a0f3968.nq.gz
    ├── 45fc9ef8e31d79049c3716a367a21d9cca6f67f0.nq.gz
    ├── 4685a6303c6046c6df7432a8673f4b4f16545588.nq.gz
    ├── 46d7e8962f7d05e5cf06f711054e8fd22493e165.nq.gz
    ├── 481c6e5fa735c8d987abca6f65b9d9ccd4c9da42.nq.gz
    ├── 49421ebf5f4131ab0bf4da7a36eca2e8a0c3a711.nq.gz
    ├── 4af74a814d4ca216b5f6950e69f2a804b960593b.nq.gz
    ├── 4b44cc8d49ba453d83289d10800415ccfcc0657f.nq.gz
    ├── 4b859eed26aa78f7a39310998a10471c0a2b09c1.nq.gz
    ├── 4d5bdc66d9e65f38be5c29e7a1a58d9008d76c85.nq.gz
    ├── 4d64a28f402e7ec599c2fceb5746d02d0fa795ce.nq.gz
    ├── 4e3c178f8f431b18c50c0783c35dc72aa3aa96c4.nq.gz
    ├── 4f4a139f909f911a35e83d204d43db404250be93.nq.gz
    ├── 500f42b56f81dddf08476bd215da5ba740956df5.nq.gz
    ├── 50f7c6004b8011160ac26d9018a32d676fccec8a.nq.gz
    ├── 514553378b1976148e838c60f5af4a0879e2d0ef.nq.gz
    ├── 517555ab537aaf0491cccc47f43d60c0db22170b.nq.gz
    ├── 52192368758b588576bdc8277d56fd155354567e.nq.gz
    ├── 5289685098a38cf9f24f09709735cc73b85eca75.nq.gz
    ├── 52c7f7b296aacae46769a1b9319c84625b66c3cc.nq.gz
    ├── 52eb00e49312d66a5f6481996e39b25993cfa97b.nq.gz
    ├── 53c77158f45c2ef0202b1697495c1e0dfc9fa683.nq.gz
    ├── 53f10ce12e29ba1ceaadbbc3fdee929cd153bea7.nq.gz
    ├── 550b822e17eca01e4018d8f059e0b27fa242caa2.nq.gz
    ├── 553d7d2173ac8f2c0fe0f1bee2155d3bc0f85315.nq.gz
    ├── 56becd5e60fc91a861c08da28c8126a7d2297da9.nq.gz
    ├── 58dc5753cab49ecb236835439bcb2481487e27c5.nq.gz
    ├── 59efef5387e0b43b4dd3285698ca151066b691c6.nq.gz
    ├── 5a8c5d1fd4dc24f4c37957afe13b6b0e892f9b7a.nq.gz
    ├── 5de54c615f27d29b2197ea5ce0b58010312d5d56.nq.gz
    ├── 5e4ccec5b16d38a7f0b3afb2e10212bd3038f0d4.nq.gz
    ├── 617794f2df55bd0cd952d6aa6852fc02cb17ca3c.nq.gz
    ├── 624547180713244d7e182fd82721914265685322.nq.gz
    ├── 640b437b2506bfdb87d4bce0379661fee363a0e0.nq.gz
    ├── 649708531f7d7526a7c8a4e7afbbe3ee5d220b28.nq.gz
    ├── 64ea475275ce3373415ebbdbd9952a8cce645e62.nq.gz
    ├── 653fcaeceae5ade865abfd9995cfdecf891b9dd7.nq.gz
    ├── 65f2f84ee851734ce2ec032881cc704d12729e64.nq.gz
    ├── 67455aa248ccbc415311b5040cd6f8f81b0bf7fb.nq.gz
    ├── 67b5ae57a12abb2bd8057742d5bc416eed144825.nq.gz
    ├── 67f7de80751df7189d8ca50876d8afad00b805c1.nq.gz
    ├── 68826e8ea8338819afe83788e04ecdc35ba78cf1.nq.gz
    ├── 68bb663b7bbf1cef02a024e6a56a91b294a1dda8.nq.gz
    ├── 6cbdf397bb3a09905c685c0b5c652b3df66ec716.nq.gz
    ├── 6d740e528f9247aae31db763732ab7091027c334.nq.gz
    ├── 6d750c8d1150e05b5e57dc95ff0a0ac35ad3f937.nq.gz
    ├── 6e52895a8c669600adc7e12aac4b589e430f4cf0.nq.gz
    ├── 6e9e596ceca05293407a18193c28939e8407cac2.nq.gz
    ├── 6f87be10f139db7955d0252ab20ef2513e2ce31b.nq.gz
    ├── 7122890a0d8c32ad44b732c74f0cab2afd5bf155.nq.gz
    ├── 72a3d266fd66f1df21a037618d56f2d0f9e04d9a.nq.gz
    ├── 72c791d2e830333439e80a69dd49b17f4e06978e.nq.gz
    ├── 72e4c94ead81e601fafdf4b172d9fbeee1f1cc6b.nq.gz
    ├── 785b641f01755f4b980c773c2467deadcb52a16d.nq.gz
    ├── 78d6f3cdab41404b6429626e951166ccd3393ef4.nq.gz
    ├── 7b8c3a39074017543d0e7fdc5099a6bf29268be1.nq.gz
    ├── 7bc5cacf8668932baefd5939c54dac2ea68b6a1b.nq.gz
    ├── 7bc672ff11aa7001bd9f9f63c21465e8be08147b.nq.gz
    ├── 7c3dd31324bda5d93b91ad8412d830d4a526317d.nq.gz
    ├── 7cfdd8c1bedcc7a849c5bef81c75d342f9d598d7.nq.gz
    ├── 7e1ceca9375a494942b12eb27fa3afafe7769323.nq.gz
    ├── 7e9d6a5dd8123699ff477a1139f3c5e360674248.nq.gz
    ├── 7f2b3c1a8d4006715595ab13694bedc3ce645c10.nq.gz
    ├── 80d1d1f6bcb408ead0f6ee7b43d5cb329222972a.nq.gz
    ├── 813467c65125e34498ddb80d4aee01b1e1def256.nq.gz
    ├── 83ac30179dd9b342d9b42185d2806c20ea5ff805.nq.gz
    ├── 853acadf611d871d9eb47321cadb0bd50bff9306.nq.gz
    ├── 85c4941f2a648f562fae82f7d3d666272f768ec7.nq.gz
    ├── 86ff5d6144e22a64289171ad3c1774756e336da1.nq.gz
    ├── 8756dec6ad1638f78b2582c64d78092ead233a68.nq.gz
    ├── 877384ec7e80d44c8f08a18563fd0234ba6095ef.nq.gz
    ├── 8826352307c19a837ea48cec18132b07136101b9.nq.gz
    ├── 88fc33628f883f5568abc788619be761b19dff88.nq.gz
    ├── 8939671ebb94f611e560b38220a428fdf12f4d9d.nq.gz
    ├── 8c9e76cc1f83978432fd3969138aa60b57bb673b.nq.gz
    ├── 8cb41a57acea17704d5dd54fb7e7cdc581d68fe0.nq.gz
    ├── 8cb7b6d58f8b12bab0e393254e2cee8562b108fa.nq.gz
    ├── 8dff6a2816d7b9470e6cbb655b17fed3e17cc92d.nq.gz
    ├── 8e3a6d041d3bc6a1a0910627a0a43901b8671b10.nq.gz
    ├── 911fe2c3a9846611475968cd669aabea92258a44.nq.gz
    ├── 9543b7a20e2452b4d76fc81e9bc83d5d2073f045.nq.gz
    ├── 9765fff87b5acb0bb6c1c2a9a7339a5d3df558b0.nq.gz
    ├── 97acc18bce301209e8cb1c7847a03f03259b546a.nq.gz
    ├── 9a86a0e3c5a766ae13e005d2153a81ccaf0249c2.nq.gz
    ├── 9d9bd02220f9ad7da40564af5e990603bd07e718.nq.gz
    ├── 9e98aa66bc85b9760ee5fe9c452173ed3bc5b9ee.nq.gz
    ├── 9f4f0288ed09420e0311ddd372cfa9a2b267778b.nq.gz
    ├── 9faad3a3a53c6b5f97f24ec6f45ed45d37d950ff.nq.gz
    ├── a101134069e8c03475b4ebb42ea081757a44f3a8.nq.gz
    ├── a415698aacb57cca7dc0328bc872039b4405248e.nq.gz
    ├── a63d1bcd9a8f9686e106b6ee28451042af7abd6a.nq.gz
    ├── a6b078a841087ca11f124407308bac712151f272.nq.gz
    ├── a7072f645c461b659eb4f658c9562d0e73d9fb96.nq.gz
    ├── a783f9ae3debcfdefa92d27c893491e86a69fc04.nq.gz
    ├── a83b310a229e09a6cb0209846719ef85b3caac01.nq.gz
    ├── a90234521446f4f1434c755d044466437883b2b8.nq.gz
    ├── a92b7e00bebfa086418c852b91044456c7a83c5e.nq.gz
    ├── a9536b70cca3fac8fa1287a872fba089ffe66474.nq.gz
    ├── a989f5c1d535a6eff3e0cd9a739e65f91d8b65a3.nq.gz
    ├── aa57f4cb1e56554f7205b9bffd2801850f830857.nq.gz
    ├── ab58c786ac2be0749aa90d381e6b191082b37728.nq.gz
    ├── b05dc972e18c005150860dac1f393df8949fe0a8.nq.gz
    ├── b0cb4561f2c531ba46551eb3e21bc30b22ca7404.nq.gz
    ├── b25cfeadc2bc0c5ffb0e8d4917f0493e9ed93e3c.nq.gz
    ├── b28dd40794a519e57e118afbd55d08b69a9c6148.nq.gz
    ├── b53cb4e3c569681acd77689b021db3ebcc3e4853.nq.gz
    ├── b9ad11e4db0c2058e34cf594f3dcb021ba2232ed.nq.gz
    ├── ba84a639221cb33ffd89cc4972a9bbb19e6f9a45.nq.gz
    ├── bb09502c3231077289cd65c533fb5265abf16880.nq.gz
    ├── bd80d942b01c79f6dc0a6276c8bd8cbed41938dc.nq.gz
    ├── bfab03168ba2b62b57ad7e34c961a41150f6c9b3.nq.gz
    ├── c2c1dfec84bdd63f08eff7ebc65fa59d03de801a.nq.gz
    ├── c34151b8ce85aa446b9879043262469f888ca08f.nq.gz
    ├── c43580d015a3780fa4e28961b6dd9b2291378829.nq.gz
    ├── c48eb43f076bf2b3ecb026b9f38f6a24e4823521.nq.gz
    ├── c59e61ef596cb5c3aadb3597da184e53cc168fe9.nq.gz
    ├── c8f000a62cc0e670556e1e134810b5a16fb2fcb4.nq.gz
    ├── ca1e39233bc5d6671b26643be7195af969797b02.nq.gz
    └── ca829474dd4787bf8d6aa97d5e25de698123aba1.nq.gz

7 directories, 200 files
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

[cohere-ai/notebooks](https://github.com/cohere-ai/notebooks)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
