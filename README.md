# Repolex Knowledge Graph of spark-jobserver/spark-jobserver

RDF knowledge graph data for [spark-jobserver/spark-jobserver](https://github.com/spark-jobserver/spark-jobserver), parsed by [repolex](https://repolex.ai).

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
rlex download spark-jobserver/spark-jobserver
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f58280bbe4ecfef110bdf425f5aafccfbaa1bdba
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── f58280bbe4ecfef110bdf425f5aafccfbaa1bdba
│           └── chunk-001.nq.gz
└── blob
    ├── 0051353357a34c0b60031c2a1a6ca46d3c028698.nq.gz
    ├── 012d994b6eba112b2c2c68194ecc55f00b86e363.nq.gz
    ├── 0280bafc8be01ee489f52db2c18a064dae48afe1.nq.gz
    ├── 03f85187e9329cb298a34f38c3c3b3679c1b5a6f.nq.gz
    ├── 0488a49740cc841fa032fc08a9d7da2c231d41fd.nq.gz
    ├── 0551c2c3ac588bfb120f431e5c4d302b90db49fa.nq.gz
    ├── 06ea08a078e46d22a58767f769364f7321dd9c7a.nq.gz
    ├── 06ec53748cf7f73c845612ff838dadca27252dd0.nq.gz
    ├── 09792c384ccd7424004015fd0fc3c25bdfe30970.nq.gz
    ├── 097dbdb2a59f7b441190757d828f7c872ab05ecb.nq.gz
    ├── 0a244dcca80948b51dd9005b052902f85f258f70.nq.gz
    ├── 0b1164ad67623f6eb06d5635ab5dc970ad807d82.nq.gz
    ├── 0b1b3f152729c40e3cd166f6c1a570173d646794.nq.gz
    ├── 0b2bad75523998a22fd8f3b45d697d99e7572829.nq.gz
    ├── 0b2f5c7b340c2d66e8294c284e8db791bb722b71.nq.gz
    ├── 0cd788a58eacedb902c16b62deabf4fdb5dfb8b1.nq.gz
    ├── 0d2d9775393a7531291d21d0d79c2b8ae6917eb3.nq.gz
    ├── 0d73d8ea0711a0ea67f88c9a5d907ea0d147fda7.nq.gz
    ├── 0d9d0e1e72b00f2f39cb23ae0d7d30a865d366eb.nq.gz
    ├── 0e4bbbb2a16f184682cdb9f5f9f334b4a61de689.nq.gz
    ├── 0e91dfb336af68622ad1395bbc3175a853398c27.nq.gz
    ├── 0ec3fa29f95beed2943add3c03b5de8267879e1a.nq.gz
    ├── 0efc21ffc4637ad36a71c55bdbaba824117d7bfc.nq.gz
    ├── 11a8b4a4a4a2e7b7fc3e7418e19cfaacfdd8a2c9.nq.gz
    ├── 11bc4e64a268dc6d5b894654a4d81a1dcb7b739e.nq.gz
    ├── 11da95d0dd51d43339e04fff1b9e02942dbb0d96.nq.gz
    ├── 120d7aa201a7e8fd81fec2b380132f9988c397de.nq.gz
    ├── 13de57bb197f13ff80174d0e703be47f98035182.nq.gz
    ├── 14524e2c07a1289b0f6859cb821c7db3bd0d8e4c.nq.gz
    ├── 15a1641d1ce9d557f4e90c8a144735c535fa5e94.nq.gz
    ├── 16f7bc9ff1a53990df891c80f3c09c52ac04b1a2.nq.gz
    ├── 174258ac8751e6ef3d9f141db7e04b4cdd67466c.nq.gz
    ├── 1794ffc36f6252ce2d18490a80dfb7ba4292dce1.nq.gz
    ├── 181bf5ff5e8b57092777d26ed5e4c155e64219ee.nq.gz
    ├── 18fc6f98670bf79a3dc5ac2c90419485fca60a46.nq.gz
    ├── 19479ba46ff2ccd394d08643dce2ba15aa7a79a7.nq.gz
    ├── 19abbc6365844031dba8d917ebda04c02f05ef13.nq.gz
    ├── 1a1a94b99362120aa6fc42527df71d38639e747e.nq.gz
    ├── 1d233066d7bf3ee1ac8eb96c846280abe29ab567.nq.gz
    ├── 1ec25c860e5e47c74ae08fe3b76719e2b019c60e.nq.gz
    ├── 1ef6b743a87d8f8203d673128c23ba75397999dc.nq.gz
    ├── 221f7a795dbd68ae9c44059be2f9ae36ce4b7aea.nq.gz
    ├── 227bae65b23f5da76a5c574030daf8c60d9fe546.nq.gz
    ├── 228d254e1203f130b904d8898cc5b392e659f77f.nq.gz
    ├── 22c8e5502bd28b86a2826fb2ffb89eeb5b1bd927.nq.gz
    ├── 2864b769586f89e6c93b1a7eda46896af67655dc.nq.gz
    ├── 286c3430bc76b8bde91f83743d9d9f2b638e066a.nq.gz
    ├── 29c78ea57d8eaf3449df4b2d56d5f50d5c443f39.nq.gz
    ├── 2a71e63d94915ef3800e327621b4fea0ff4a1be8.nq.gz
    ├── 2a7942dbfde02ea8be3f6cc2dbe0cca15720e09c.nq.gz
    ├── 2abcf300e3c3ddf10047eab9a1ced56098f1609a.nq.gz
    ├── 2ad94039384e996f05336ca4258a6ff786901c5a.nq.gz
    ├── 2cb8760b2fc3a3af921f941e9d85e9408a006933.nq.gz
    ├── 2cb9787cf770a0283264a3cb2df48dabcb894571.nq.gz
    ├── 2e84f2c9367db4df59199dffd8267e0802f4f5b1.nq.gz
    ├── 2eafe05dfdfcd0d82e5335a2bf02d3205f0f6c56.nq.gz
    ├── 2ef4844a362413528069a89b701faeecdfe40e10.nq.gz
    ├── 2f15b8ee73cdd340109116c71503e21bb0a6e0d3.nq.gz
    ├── 2f9568a519029c953bc7b593fce8a7f36efdb57d.nq.gz
    ├── 2fc3c821ebbf3420e83b174eaaf74e016ae1bca0.nq.gz
    ├── 2fd851a6579d6f06729b464f43e25167e0025a27.nq.gz
    ├── 3024c2575292c5fecc8a3a139bc72018640657af.nq.gz
    ├── 30474e9f36f72f8fda7d1d475000e95357cd0480.nq.gz
    ├── 30ceeab0dc6113667d36ec4cd2880cd4c895ad99.nq.gz
    ├── 310b51b4bf2a3ae3b4678bf4731e30d9a9890bcb.nq.gz
    ├── 31fe36b0d9c4b9e56a237166a25e3372805348b3.nq.gz
    ├── 324c38d2170662bb7deda47636f6680d5e6338bd.nq.gz
    ├── 32fbffc59beb6c4c56a055c55127da2623f0ff00.nq.gz
    ├── 34193e9f6c8e7f64a5842065be85836b36fec952.nq.gz
    ├── 3605c00f509e25ae08e01b3d06de15e14e751a48.nq.gz
    ├── 3628129aaf14607fbf3b5ae4bbca00a1d146c6f4.nq.gz
    ├── 368cbb852a2bd6d375d7ed443720e2f611e575a7.nq.gz
    ├── 37378ebdafdb48bcfccdac28322038c884b3b094.nq.gz
    ├── 373d8a9edf8f90d8b7d3bc9e3fc115fc7612ac35.nq.gz
    ├── 37b2a7ae2f42dc0136a6f6c26f8424f9bcd622f8.nq.gz
    ├── 38523a016b0fb7607c101e7d9736d4daeb1f8a74.nq.gz
    ├── 387b10135df4d9f595092e7a94ecfd0de61d4dbb.nq.gz
    ├── 399e71c79234a7c40e3ec34182129a8d628f332b.nq.gz
    ├── 3a1c898c957cfd3540e06410a6959beac6a58bdd.nq.gz
    ├── 3aecebb81f0a925406eda143650cc52e2db239b8.nq.gz
    ├── 3bb64d81319c67f270176fdcb6d90b175ec86c07.nq.gz
    ├── 3bec63065f3d6e35fea5e59ef53b5300972396bf.nq.gz
    ├── 3cfb1039b6247c9e7e5da5856bdaeccfe26e8720.nq.gz
    ├── 3d4618c2162a08267ee2053ea9bbf75af6ff4279.nq.gz
    ├── 3da65bfd313445d6172e2022e28e2c8a30c08258.nq.gz
    ├── 3f11246e66168c27acda73082d8aafa347f51771.nq.gz
    ├── 3f8f869a53e49dbd1365fff68b730391f453b433.nq.gz
    ├── 3fb22337cf90e3b55f8ab5b28fcd97e940b48a28.nq.gz
    ├── 3fd6ddd4a4191a32e4e0c697c975ef7ae6965ee6.nq.gz
    ├── 40fc2fb6f3e94edd1e2e012f59b51205bfdde627.nq.gz
    ├── 42f4be3bbee25645a9ee2595b39d97f587e7c3ec.nq.gz
    ├── 4381682a39423598cc7d602f1bf53b7466c80621.nq.gz
    ├── 44319fafca9cd7197b1b3bcb3f51074b97ca50df.nq.gz
    ├── 45a0f24391901fda08159c2b35a5fc6f814a7f9c.nq.gz
    ├── 466a52326b66cd3e790f39b8fc4da6c8ab2130ac.nq.gz
    ├── 468cb1f4b2420e789dbf42d275147cd0ae93452f.nq.gz
    ├── 46e8acba96adab0c7c2cbcd16c6f6a4758bc4d08.nq.gz
    ├── 471402d04eb52fde1d26b9da7c4231f95b189771.nq.gz
    ├── 4761618b6637c1408c154c22b595fccf7a9eaa67.nq.gz
    ├── 47820d537dad06df32f679f766f01a3bbd265cbe.nq.gz
    ├── 47d567e29683a324209c11087659cc809c6c1844.nq.gz
    ├── 47ede6325cc5339d3e99d3ba1f41c5124b49c82e.nq.gz
    ├── 48572f421f49fb81beb0d48d76aac66d30f42164.nq.gz
    ├── 49f4826f5becbaeb6a2927758672ebfe43f29c4c.nq.gz
    ├── 4a288e5e75674ccebc238d2fd1f1386a61ef7b73.nq.gz
    ├── 4a2aaef5b3878a11334b5fad1b90e2762e0dc735.nq.gz
    ├── 4a329c838b1ff58946bda95abe43c3947471eeeb.nq.gz
    ├── 4a9c3d51b8c531ecaa060486252c909b4c58eb08.nq.gz
    ├── 4b3a1b97223e3f8470a85156db32aaeffad31132.nq.gz
    ├── 4b544f5c14bb92b9de3c48710ce03665c39805f6.nq.gz
    ├── 4b989de310a294f4314d623dc856c3b8e5ed193b.nq.gz
    ├── 4ba64a13651cfe4186a2bcfbb16b20c2884becab.nq.gz
    ├── 4c5d9f56368c1becfd9ff0503fccc15b6d4bd138.nq.gz
    ├── 4c9ecee8005e69eb4d07fefe96999c95d674bdc9.nq.gz
    ├── 4cbae3ea0964213ecebcdf720244388a8e279b43.nq.gz
    ├── 4d3f9312f336506544a915441e2b632f6debabe7.nq.gz
    ├── 4d6590f99edba0b8905149355e2a196dc8eac6a1.nq.gz
    ├── 4d991dd187a6aafb78c733e46973c18c9755e67f.nq.gz
    ├── 4dc8bc1409713ebf60e97685e501d701db3ce7f9.nq.gz
    ├── 4e46c03d1761392ad9d0b128e6f0c95ea8ed581e.nq.gz
    ├── 4f7fda33137598a13f1a836697770bd857d3baa7.nq.gz
    ├── 4fe556e8a68981d88067e3ec229313503104130c.nq.gz
    ├── 4ff39a197e180722fdb9663a2509dacd3e371d52.nq.gz
    ├── 50169efc9b806287db2e49f9001a3b906facd016.nq.gz
    ├── 502cfb3c8d12c057315d04f7c2a9eeb42f7fdb08.nq.gz
    ├── 50dd4856116c5e68fba6579276b85dc1c41fbf9a.nq.gz
    ├── 5101dd26a67f421776dcea4b92d5f3e9a3463a17.nq.gz
    ├── 51b26118c609d7533d42a5d864b4560cfe016c45.nq.gz
    ├── 5260a23175fa45c10e72c968ff0cc3f93f65556d.nq.gz
    ├── 52ebc3b11658999933759b420afebc5f8b2c19e4.nq.gz
    ├── 532045d250e06a3831047ad198a3b22ed21494b1.nq.gz
    ├── 55713d73ca9eb4598fdad58a6b7798187222c8be.nq.gz
    ├── 57d436eb68af57eb26687f33bd96acaf7d37b065.nq.gz
    ├── 5992016935832f310802725735e87483e315d081.nq.gz
    ├── 5a71f0115147bb6f24b72ad0bf1451974e81dc63.nq.gz
    ├── 5bbb70754b7d3c2ef272d5271f601e73925b2c32.nq.gz
    ├── 5c63b6d983f51ab87596c73223c43164141701d9.nq.gz
    ├── 5c923bac881fad13304b7a68de3824b6b907ca6a.nq.gz
    ├── 5dee6521c96a4dd3e688d1635432828b8e69ce14.nq.gz
    ├── 5e187c0c2be9902ace93f20543f7a1a17c514194.nq.gz
    ├── 5e6775d54c3d115f1b9e51c8642522a93bc4dfda.nq.gz
    ├── 5fb4c18cffe761c683613cf4bd91a31da84f722b.nq.gz
    ├── 600897500865c08386151d758b50a40cc12422af.nq.gz
    ├── 600d09d64ea970223517f61fc7f15be46a483179.nq.gz
    ├── 6054ff7afe4db4aa66d2cef119b16bd591a929e3.nq.gz
    ├── 612baecd1f8b0ce72608dd460a6468f1facfdb2c.nq.gz
    ├── 62cd53a7a0b4f29755e084f25bec781569f5d8e9.nq.gz
    ├── 62d6f1c03d4c7acd3d91c165d6efe3993e67aa83.nq.gz
    ├── 6326eef215c93eaae9992ba7156b27a63b39ce55.nq.gz
    ├── 633b921c5644cc20b82f1c277d9a9472a6ac489d.nq.gz
    ├── 641ea3e1fc1176b7666f5765bd89851a61334d12.nq.gz
    ├── 64435f3949fbe72083be1d976f6affc394e901a7.nq.gz
    ├── 65b8317174debb77eff6eff2e1fd9eeda90bcd86.nq.gz
    ├── 66100fca6ad93ed1abe0287a01251cabc2a354ac.nq.gz
    ├── 661447368e513ea5beeafb47e4150726607db77f.nq.gz
    ├── 6688e299991b5e7580b74c770b072581d809522e.nq.gz
    ├── 67277654a2184c954944e058cd8fef90b2b00726.nq.gz
    ├── 6868479059b21d93cbb467c8f19cb60b8e661f81.nq.gz
    ├── 69525a48c9c99ccd2d5b5415a6927aca3f77be38.nq.gz
    ├── 6a5e2ed30e00214f866759b39373b9b579e9c6ce.nq.gz
    ├── 6b47f834564f6006550ba2957758418215f65a71.nq.gz
    ├── 6ba349782300920d83bd6b411d28370071f1cbd5.nq.gz
    ├── 6bf6fbc73ef2e628b42dffe95073b1162034a648.nq.gz
    ├── 6ca3045e9f64cfa5266538b8c7ab3e35b6766c88.nq.gz
    ├── 6d5d63bb2d51783e03d815b102b4ba0d629a8ea2.nq.gz
    ├── 6e7ce90451c9f4303d1be1bb75d28b3920d4313a.nq.gz
    ├── 6f38ff6c2b4d29993fe7fd63df02500c19d17596.nq.gz
    ├── 7296d84caa22a3f2a3e213f2fa02fa33ca349f19.nq.gz
    ├── 72b434fbefa5b228e912a5e33a89c947100ab220.nq.gz
    ├── 72c13260d84511730598176a74ecc80a9125dac2.nq.gz
    ├── 72c6e124aad33331ae0f1b2d00e3e50bd400e8a6.nq.gz
    ├── 73898f37345a0d4a095359b3307c2e2c03b6ef6b.nq.gz
    ├── 7484d63d4c5711fbadf933d1e5676350b71db60b.nq.gz
    ├── 749dc974c7184a1400959fcf25672d0b7f801978.nq.gz
    ├── 75ce5d4330a53f02df5ce5a961387d504c6cff75.nq.gz
    ├── 761ae7a0231b271efadd2fd8167157d100dd8aea.nq.gz
    ├── 7645474772d136b5e37e89348745c19ef940c40a.nq.gz
    ├── 768932403146be9da3b19ef167aaf5b91d04fda6.nq.gz
    ├── 76c6fc359b06624bad5546f56739ee391b3fdf17.nq.gz
    ├── 77ebcd3c76157ec2afecba531870fb2ce1c5aa3a.nq.gz
    ├── 7896ac56005689a59de1297500a5df01966a8f8a.nq.gz
    ├── 789ea2a5505c9ce748936e2793163b39771f152f.nq.gz
    ├── 78a8f5581f3663121f6dc0824b9b5c80a203f537.nq.gz
    ├── 79bf951662e8b2404a67bcba8e536b7c88462edf.nq.gz
    ├── 79c4a0ef078c5d9e4a554f2bb11d804cf7860a2e.nq.gz
    ├── 7a3a25352452a7f1da4cfeaf7d86512f8ac56bc2.nq.gz
    ├── 7acda6d5f556ae1766873e166fa88e84e6032f9d.nq.gz
    ├── 7baa7db16405610d7ad78c3128789c76e4be43b3.nq.gz
    ├── 7bada3f1d9a827bd3cc78eb23c60c5c3cede0e02.nq.gz
    ├── 7d1163ae5f6999a4421e4b8d09ad0ff6b5551afe.nq.gz
    ├── 7d22fe621873996ff9072c58b25f814a5d9dcca9.nq.gz
    ├── 7d24682fc472de9e6ffce551f8d732a4c7a5b4f5.nq.gz
    ├── 7d88f2d7e825e039bfc247a335b280e8cd17193c.nq.gz
    ├── 7d89c18268a3cc90fca43d98280ebb4e952dbbbd.nq.gz
    ├── 7ecba399a6e60a8e092f5fa9229fe6a3d260d3fd.nq.gz
    ├── 801b0b4797fd99858eb2a5e866fa09002ce17da5.nq.gz
    ├── 808410a4135132785a7096dba2d54ad88c9e0fbb.nq.gz
    └── 80dd6044be6cbf645b211340de5bfdbfa38b813c.nq.gz

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

[spark-jobserver/spark-jobserver](https://github.com/spark-jobserver/spark-jobserver)

---
*Parsed on 2026-11-09 by [repolex](https://repolex.ai)*
