# Repolex Knowledge Graph of pydantic/logfire-js

RDF knowledge graph data for [pydantic/logfire-js](https://github.com/pydantic/logfire-js), parsed by [repolex](https://repolex.ai).

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
rlex download pydantic/logfire-js
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 95eca241f7849627751f175768cdcdcf57f6c527
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 95eca241f7849627751f175768cdcdcf57f6c527
│           └── chunk-001.nq.gz
└── blob
    ├── 0024f467942588255b692161b88320c6fb219930.nq.gz
    ├── 004145cddf3f9db91b57b9cb596683c8eb420862.nq.gz
    ├── 010e968c6ffb0d7cfcce97dec750e64e03e327ba.nq.gz
    ├── 0173f6131ef6a0cb749e344c959d86d3d05b41cf.nq.gz
    ├── 02ca9640678f957645b265d83862179057cb03b1.nq.gz
    ├── 033223c087a7060a7dbba80f2dfe5b07a8bdd38e.nq.gz
    ├── 0475bc2789588f04583ed32ebb3af464dcc053f1.nq.gz
    ├── 048b922b631dcbaf4867044a06055beb16224f25.nq.gz
    ├── 04a90f6340a3550d1bb4a8e90b971fed5532ef9a.nq.gz
    ├── 056c42b7d657bbfe65f9015a8a6843550e5f7aad.nq.gz
    ├── 05d992ebee8706ce961d6214295650d8f779c903.nq.gz
    ├── 063f180469bd20f1984326d9bf6d210a85e342b9.nq.gz
    ├── 06ee99d0dd8d8612c76dbe788adbfd5a2aff7eb8.nq.gz
    ├── 0981c7e924447dff63da49d7eaaacc3d0b9e706e.nq.gz
    ├── 09a89802b1dffa286b37cd4c41e338d9924e6ed1.nq.gz
    ├── 0a89773e271c87cfc2ee256e3822f9d2ed5d4054.nq.gz
    ├── 0afdaddbe94298a7c9aece2924df238eee33535a.nq.gz
    ├── 0b522df08d35232227115dbd2dc5257c55fb594f.nq.gz
    ├── 0b806921f3eaf7b09b85bc97ce373fcf2a55edf6.nq.gz
    ├── 0c0d27b16cd15a1bf9aecb1b52da5440e6640fec.nq.gz
    ├── 0c3a60aa34d9dbd6f8e9ca57a0b9510548f78433.nq.gz
    ├── 0c6e5c4cf610ebcb2060ea0cc61ad4d1f59c80ad.nq.gz
    ├── 0c76911097406a77fe682d5ebe3183133d4ecd9a.nq.gz
    ├── 0ceabe91f3022c96f06c3322df5494a6c2668451.nq.gz
    ├── 0cffb0a55ea1de80674b457f0947280cb7ddda3b.nq.gz
    ├── 0d864854e8b7ff288148d41013d0c7765288b95b.nq.gz
    ├── 0e136c1fdb435e377eb23e31892a960042e60e02.nq.gz
    ├── 0e1a5d68ed0ecbe874483b72959fefefa920e951.nq.gz
    ├── 0e3d7ecae550ba13d6be96ffab0a3507d36b8d1f.nq.gz
    ├── 0ef99f580b17652e05f31e04f5e75f837f0b2211.nq.gz
    ├── 0f5850f036128b03dda9de7a1117af13337a09d0.nq.gz
    ├── 0fb20cb7c60af01931eacd9bb82d0d7dadf8eaeb.nq.gz
    ├── 1129f87fd747cf794541652d3d49bc2de5dac1c4.nq.gz
    ├── 12d0f5b5e094a8009b41de6ab8852c279dca879e.nq.gz
    ├── 1300668c7e888b6e49a1659112ceb7ebd0d1255b.nq.gz
    ├── 131711845634c28264543da8e192b7d2b3ebe29a.nq.gz
    ├── 1386f9da44777fddafc6306166b455fbb7af3291.nq.gz
    ├── 13a8af7a7bcac6c2d6292aacf3bf732445eec449.nq.gz
    ├── 14c99fae11e8565d547d18d6fd49b03f2d0e8e83.nq.gz
    ├── 156a7622020b013c0b9f7abeadd96a3add49845a.nq.gz
    ├── 172a52277058818b2d61728f0a82533cdf4b065e.nq.gz
    ├── 194e14597369122823fc2865438312d8bba92059.nq.gz
    ├── 1a0c28d995c1909f0b21b60b43815232f6df2b31.nq.gz
    ├── 1a5f53c130554e39f173562be432a6b2c484157c.nq.gz
    ├── 1b79bb5b4e51d7350418088b7520f3e0b8810922.nq.gz
    ├── 1baceb5965944d30448cd273390eec0489adf8a6.nq.gz
    ├── 1bd81dd42e126877f3058d1bb3283bdf75a20ace.nq.gz
    ├── 1d1c95c282eb7a9d8ef008036055aefe20f67952.nq.gz
    ├── 1e946dbbd1c65f0420776c294931e37be20e7ce9.nq.gz
    ├── 1ebd6bf7bd32f8685e7264a793a6595e4854770e.nq.gz
    ├── 1f731615a46fb03d462705eed11f4c7b65953849.nq.gz
    ├── 1fc89f054aaf6739e3dbe21063d602dc2148f664.nq.gz
    ├── 1fd3f886d8f835e4e70d5ab61924512f66fb3df4.nq.gz
    ├── 1fef872ea3170acafcaa95db1456923650e00ce7.nq.gz
    ├── 201e40abb1ac38b549e6444ca3ae6597cf91cf85.nq.gz
    ├── 203e9256670527ae70c3cc6d28c812d0a122c87f.nq.gz
    ├── 2241fdb8324602efcf3801e03cba635088c2aa28.nq.gz
    ├── 22452699f2ee9f795238e9def2078566227ba34a.nq.gz
    ├── 226e9c045efde5eb79ac9d7338788ac4fe34cada.nq.gz
    ├── 22757e13f29c6f71db20266fa7a44f5770397d85.nq.gz
    ├── 22c2e9aea8c39a5ed5b86c65d154647d0dd85ffd.nq.gz
    ├── 233b72df50817573d2f34c9b909fc40633a3abb0.nq.gz
    ├── 2354b1dc18b85cc66a7f5ddd22e291b49e0b5ab2.nq.gz
    ├── 235f4dee427668bd8631733ef3a9c29ac04247ed.nq.gz
    ├── 2410b4eb3333e96c129a37ab3612ac28077e6c59.nq.gz
    ├── 24204862aa54d8be93e600d59eb7d781e530bb0d.nq.gz
    ├── 25a2f6e80235eabc09bfafe2741cac73b94fa0e5.nq.gz
    ├── 25beb6090a98c547a132b70315eb8c1b71be7acf.nq.gz
    ├── 25da4ae3452acb36feed07dc04811b3da5d9340b.nq.gz
    ├── 26a3cf171b1966a00c1c9a7483d56a7728620310.nq.gz
    ├── 27de95015bfcb4f6a059d52c99b42f3b437e2ed5.nq.gz
    ├── 27eb8d94d505871d6e1cb30a335bbe38fbf942a3.nq.gz
    ├── 285ed8e376668906bf74486d4aa818ac740027d8.nq.gz
    ├── 28ffc6ad30fb9313b57983dfa07c8a6110c71a0c.nq.gz
    ├── 29277aba7509053fa5d65f5197220b7cf3931915.nq.gz
    ├── 29a4f1ed260dcc1e82b35b0b3c7bcd7723e19201.nq.gz
    ├── 29aa648d5c85c881c76ea01fa9aaa0993ee36497.nq.gz
    ├── 29b47f3f8f9d5dfac65958bb292a8ffeb8864296.nq.gz
    ├── 2aeb31870135bd0af097fb281de4089c4d59e655.nq.gz
    ├── 2bca9b19d9659e557eff6659ee22d50e86eaf747.nq.gz
    ├── 2bd69a29649d204f4274b90962fd629429f600df.nq.gz
    ├── 2c07b9c8c1ae48e5df3ca9b03070ad58883ab984.nq.gz
    ├── 2c28043187d7740970b321f39c0fdfe522d8b85a.nq.gz
    ├── 2d4eb89954d004aaa0957640ca3785ceac941381.nq.gz
    ├── 2da9b13a70bcbcb0882dcdffdb4454526b2415bf.nq.gz
    ├── 2e419c443df7378e8650c1c03713692aae5ad7f7.nq.gz
    ├── 2e48d2b6cccca2b385e08ee6e949b6323af83a50.nq.gz
    ├── 2f0ce64db9c03178f978f1ba8364c8bf5439229c.nq.gz
    ├── 2f2f258e4ce982f2601e894ab03b77d15c8fd783.nq.gz
    ├── 2fcab8790d7f5280683239f2cf90a5665763cd60.nq.gz
    ├── 2ff6cbef9730abf1a8dd0657f57afafc583c7aea.nq.gz
    ├── 30185c1b679aea2cf0581942a8747c058d8e4dfd.nq.gz
    ├── 3024ad2995a9f60e468deb576032be67b7126d17.nq.gz
    ├── 3048293d48b6b83e57b8388ed16986e31c90860e.nq.gz
    ├── 305204454e4987141ac134444caa3cf9e7832265.nq.gz
    ├── 30845461adac075a7a2b94c8ecc504fb4c669101.nq.gz
    ├── 30ba50d2238dd996d8233cb51c1cb2deffdd6f6e.nq.gz
    ├── 311d3921d2e21a5d96455e7022f2658d00c2451b.nq.gz
    ├── 32bfafae7cf8b72cd15cc7e50dfc83086a2812c6.nq.gz
    ├── 33d963e716e423c8e7693aed33eefb2eb1709e96.nq.gz
    ├── 344ff94c7e28c013d005f93116260bed1a5522fd.nq.gz
    ├── 34da78707816515324a7f1da03d18ea053a66efd.nq.gz
    ├── 3517fa72ece21d010d6ea8bfc8a0f7ac334435d2.nq.gz
    ├── 3526cbb303c800ad3b779d1dbef2eab33706742c.nq.gz
    ├── 3568ae1f96541cc59542933ba71d59737d748c7f.nq.gz
    ├── 358a1cdbf8e1099013473562e5c92ade3da1309f.nq.gz
    ├── 35fe31dbd772f0c8311fbb16e64f5bc510ba4559.nq.gz
    ├── 366fa78d3662cf30dae9851b7a6001a1a86afad1.nq.gz
    ├── 36b3bebd0ade060f5446b8ce8b93a674fdd57236.nq.gz
    ├── 36d509ae1c64dbeedc2c50c58c1229626e66cd7b.nq.gz
    ├── 36e0de6386c5178fa2b5b54cb8d82856e467be45.nq.gz
    ├── 370ecde4ec34833e7e0fe7cd2c3f9ff5d1057160.nq.gz
    ├── 379911eb78baf80fd19b1ab3b6841dc03bc511aa.nq.gz
    ├── 3826876857c0d40e8e6e8f28f071138356d2bc47.nq.gz
    ├── 3857df7cb13cee490acff9e2819a7a7d46b91338.nq.gz
    ├── 38d1cac90b48916fcdfdb84f9c426ff5dce78c42.nq.gz
    ├── 391969cc1828ec1c4725a098c3f5d650e7eae0d0.nq.gz
    ├── 399f36e2340ec7d630e349fc90a5a121a7b65144.nq.gz
    ├── 39fde1bcf295f8db948023fd1c03112bee78d614.nq.gz
    ├── 3b0fe33c47f106c8008404002730cf4dfb60248f.nq.gz
    ├── 3b2e439056a98587c0fa04a0ef29979f0cb8ccd1.nq.gz
    ├── 3bd3eca0d38d143663e33efb77ac37945509f3a7.nq.gz
    ├── 3be50f2abbd9e68f350a730bf026169a9b9a64b1.nq.gz
    ├── 3c2b54bb8e7d8d8ce82e852a0c45b0de54fb158c.nq.gz
    ├── 3c44f72c7f747df1a620afb34ec33cb93c6eff41.nq.gz
    ├── 3c6895efc14870ce35fec39f9d0f2cb1e156688e.nq.gz
    ├── 3cac35484f7e1738439777731cd0b4f747cf3de7.nq.gz
    ├── 3cb9be7df6dd39d511ba2d54c67643c6c7468c53.nq.gz
    ├── 3d4c4824200b04590f542c38131bd5a5e4af135b.nq.gz
    ├── 3d7ef208421d084f3020dc2216f54e74411ca66c.nq.gz
    ├── 3e7adab2fd8a134abe0f88f08cc87929f11731c3.nq.gz
    ├── 3f1a0d8a8e8579816531a719fa333681f3e1720d.nq.gz
    ├── 3f6e80d4573024e2353277458b9e3e3b9be76b35.nq.gz
    ├── 3f8d5df9512407717f6906aa6a76bdb7d06816eb.nq.gz
    ├── 4110aabc96dac1b0ff15545df1e6fb50bf953b55.nq.gz
    ├── 4156adb943cbb1907842a1ce9ae3e5a5199206a3.nq.gz
    ├── 422ad8bf456d2e911f56754ae3a1dbb5f8cbfe22.nq.gz
    ├── 4288559e6a2c43b6d2d9b54af0fa66b42504edd6.nq.gz
    ├── 4295576e72f9cbc0f8f3a776b2a7437a8ed7450c.nq.gz
    ├── 4440e1144a0bbabc67473b3692a320aba70df207.nq.gz
    ├── 4444287bad00beb248fec57c23bcba967aaf6662.nq.gz
    ├── 4491d5470c055bceb2f58077464bcc67c6f4faea.nq.gz
    ├── 44cab79761322c21cc75229dc93a9c288151a92d.nq.gz
    ├── 44e0690a71baf473c0c3b799cfb54b3bd7c165c7.nq.gz
    ├── 4572b3dcf421624beaef8637a79a7c5824ec7566.nq.gz
    ├── 45ea4a8872cab5d8e0807f556a26df613b9bced0.nq.gz
    ├── 460f43ecd0cfdebac6af34610a3fad174c28999d.nq.gz
    ├── 466d1c8ce2f6bc1a53ea361ead3c10b05b5009ad.nq.gz
    ├── 46d05e98eda2423706dfc70416912b4e0cb15fba.nq.gz
    ├── 47dc3e3d863cfb5727b87d785d09abf9743c0a72.nq.gz
    ├── 48290b59d07ede5435a250ef8f2c24b84264850f.nq.gz
    ├── 4953b6ed77f92bc8121783cbab2b3cc2b08afb18.nq.gz
    ├── 49894084300defa3b298e659537306925f0c81b0.nq.gz
    ├── 49ac92f79a9f50a6972c6f87a8fb6e606157327e.nq.gz
    ├── 4a7525f5526590fade74863f683e60008ba9a986.nq.gz
    ├── 4aa7f3f9d554b25f6515d926280836b6ccbcf298.nq.gz
    ├── 4acc9b3c06ac91fa47e7eb893c7f76da72be6fb7.nq.gz
    ├── 4b74d2b089cdbefe46248c57f2448aa42617b352.nq.gz
    ├── 4cd73a734cc3d77b8bb7f414abd93f9ea2e966cb.nq.gz
    ├── 4dbb63810d3485d86c042f9541dc09237fc4e78f.nq.gz
    ├── 4ddb90efa0d58bfd8853dfef8c358b7630ea0eb0.nq.gz
    ├── 4e0f18459372faf3b36e54a14e66a60e1d53b037.nq.gz
    ├── 4f5edc248c888b86c78b83fb8a88b9f914f7faa0.nq.gz
    ├── 516da61aed52fd939479e5b377b66ba8bff54e75.nq.gz
    ├── 5174b28c565c285e3e312ec5178be64fbeca8398.nq.gz
    ├── 542fe2cb9a97e2e838690391331090cd649d01a3.nq.gz
    ├── 54a27d7155354502117876d7d3ffaff316ba262c.nq.gz
    ├── 54c19f5cb8cfe1ed0b08b449d5618090f0fe1c4c.nq.gz
    ├── 552aa14904d819e60413dab7e520a733548fec28.nq.gz
    ├── 559c90bad1245a95e941c55ac9867d64f102c52e.nq.gz
    ├── 567f17b0d7c7fb662c16d4357dd74830caf2dccb.nq.gz
    ├── 5686f8acffbe7422bcc3856cfffb2a65ef1c017d.nq.gz
    ├── 580a2eb6a61ec9c11e835e26b7af1542ab5c7a1c.nq.gz
    ├── 58722a12da78e9b2df6b73cd5c1862624ebde42a.nq.gz
    ├── 58b66d7971281becc44e1cfc838341ef5709808c.nq.gz
    ├── 58cae508306990b5298770209be93006345f12c7.nq.gz
    ├── 58da68456bbdac29e5b16e2e57c209160a3b6d05.nq.gz
    ├── 590dedca02ea4be6c02395515c7d20a8caa5880e.nq.gz
    ├── 591d3c832416649cc24be4e0c923be4873de5da5.nq.gz
    ├── 5a23a1226bcb62d89d534413b53401d7d543fc64.nq.gz
    ├── 5bd6f664ea5b3d79331efed0178191d4ea18cde9.nq.gz
    ├── 5be4a63fa30cb1f5738aca15bb88f0c026a6bf9f.nq.gz
    ├── 5c0f93cdf83981c3bfbf3caaa59c4f813d77f268.nq.gz
    ├── 5c1604bfd921d1129671901918962523fdb48db3.nq.gz
    ├── 5c6a990005de142cef02cd54b2272a2657f4d4b6.nq.gz
    ├── 5d1869a4d8eafd70aef0e0da798a66ff80409174.nq.gz
    ├── 5d2cf0c0dfd63732100ab8fcf5e19aadcdbf80b8.nq.gz
    ├── 5d301ef083e44a927a83424e5410196473f72043.nq.gz
    ├── 5dd4ad7ddee82e82d14634e0588404e0c4e6f6b3.nq.gz
    ├── 5e282771b43dac21e5c67f436841494804259d98.nq.gz
    ├── 5e28a22d330b371855da41497246987b1d41e2e0.nq.gz
    ├── 5e83c4970e3946c3c9b27eca24ec66b674cee620.nq.gz
    ├── 5ec11bf7853443c53aff322b0dece827c6be2101.nq.gz
    ├── 5ef6a520780202a1d6addd833d800ccb1ecac0bb.nq.gz
    ├── 5f6ab5c1e102370fb74703cd1819b7c43110d34e.nq.gz
    ├── 6036586a08f7a3fac71bab9c6d936e980ca18272.nq.gz
    ├── 60799c9997ea728b1fb646fdd6f20f922469d91d.nq.gz
    └── 611913e8db93b72591a71035927dc8f347330b26.nq.gz

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

[pydantic/logfire-js](https://github.com/pydantic/logfire-js)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
