# Repolex Knowledge Graph of litestar-org/litestar-vite

RDF knowledge graph data for [litestar-org/litestar-vite](https://github.com/litestar-org/litestar-vite), parsed by [repolex](https://repolex.ai).

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
rlex download litestar-org/litestar-vite
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 5c49ec501d854e337452203b05c300a8e3c5e819
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 5c49ec501d854e337452203b05c300a8e3c5e819
│           └── chunk-001.nq.gz
└── blob
    ├── 0085392bf5ee3dfcf8bd36fc9883d5c5ebe4a732.nq.gz
    ├── 01af8d99edd2666e62b61728c75035cd4db95938.nq.gz
    ├── 01cdb5b1c57c87dff9263d87dbb9493e39882562.nq.gz
    ├── 01d6f4d313bd26cce9c50faf04669dbc2808da6d.nq.gz
    ├── 01dd77f48ee0f20b52e6caa676f636d8e29a4d41.nq.gz
    ├── 026d60c08e87c7e39f79d4ff5c54def8fa359dc7.nq.gz
    ├── 026ec122e9b8731da5243c4896a55289d7edf882.nq.gz
    ├── 03c3be89b41975cda2cc2b69df5ef159b7430079.nq.gz
    ├── 04240c780956e20ae3556a76661191bef555245d.nq.gz
    ├── 049a8319fe7c4890746b29246b6cd9b5da4b8889.nq.gz
    ├── 06174ca4e5f46ca509b4d8054897d6df49cb3f72.nq.gz
    ├── 0680b43f9c6ae05df91c576141f20ed411d07c7d.nq.gz
    ├── 06895b3e25d596bd91d39220872fc6d19bd374cb.nq.gz
    ├── 08217a975496e5964288681a14bc4fa61296d85f.nq.gz
    ├── 096a0a003c55c02e19092ea583e70b84077435cd.nq.gz
    ├── 096ab88781503d8029749b57970321d6764447c5.nq.gz
    ├── 09d877ebee9b2fb5dbff6ae04e26df1ba7f17c8b.nq.gz
    ├── 0a3ad9a66ac1403c3af335b3cdd3830dadf76e01.nq.gz
    ├── 0a527536b0297e34740e12b8b27dc0db26f07ad7.nq.gz
    ├── 0a8573f4af8262853bf6635e8e3eaa5a475d41ad.nq.gz
    ├── 0abd0a54388343e05642c613ed237dc407bb8c39.nq.gz
    ├── 0b32af53c5e011ef3da6b591893e5a6e758f6669.nq.gz
    ├── 0b753bd932a763f78dac3f910770d83cd89de5cf.nq.gz
    ├── 0b7d27a6059b2c17d14e49258d93754d7ee9c13b.nq.gz
    ├── 0b905b00ec08a3aa9afb19e913c6f5e5ead574a6.nq.gz
    ├── 0bf958235ae66e6ab84e0fb89e55aaeb54170eb0.nq.gz
    ├── 0d3ea6ad8edc8b978c5db39b30ccafa47c6cc655.nq.gz
    ├── 0dfd577ba676022926df7a5a1b914dc3c774e3f4.nq.gz
    ├── 0e9ed725dc1aa2e03d6a90dd9a73c66199dfe6fa.nq.gz
    ├── 0eb8b30146a3e5ec5b8b8cd0476bfb89fc9d8051.nq.gz
    ├── 0fd822ec7564e922dde8935692e72cb602119425.nq.gz
    ├── 1007f2359a3ba7159e21aed752604f5c5e0ad494.nq.gz
    ├── 105a609912c8e98208efee9aefd5e0206c337001.nq.gz
    ├── 106c2003f138d236254ef99ab2173f2dc30168ae.nq.gz
    ├── 1083a7d58015902132e04aed057bbc7b6c5a0244.nq.gz
    ├── 10938e84a965f2efe68efe2f1885b70b45b525ae.nq.gz
    ├── 109e33beb97f5951dd4ab4d65d0cb6bc5c7ec873.nq.gz
    ├── 10ab41f1556602dc5d0431c4c7e425ec242dd302.nq.gz
    ├── 118586b8cfdef30cc422357f29e6c0066054c26d.nq.gz
    ├── 11b0921c5a806d0e3839e3deb9db3d4e58142171.nq.gz
    ├── 11f02fe2a0061d6e6e1f271b21da95423b448b32.nq.gz
    ├── 138bfe516bcc0041ebd51519d0ac1c0e79b321da.nq.gz
    ├── 146f9371957e60c3797a45e81490331d9e200052.nq.gz
    ├── 14f1e2733f86d1ecae80166963fb212cf99cd4e2.nq.gz
    ├── 170dfc77bddc4faf60b9a6bfd0fac6daf1ed174b.nq.gz
    ├── 175c754dce53df9731fb3fe956f897d6d24e472f.nq.gz
    ├── 18210873a404a96d9d1789bd9c438cd1bba68be8.nq.gz
    ├── 19ad158ba49b47d63beae9b8b4473db1ff86022b.nq.gz
    ├── 1a9245b5488226d0187def9f3b331fc4115e7f00.nq.gz
    ├── 1af82ffc1a32b8360c49c33b1d453307a0f77ca5.nq.gz
    ├── 1c39827aa2e1c56ab094d23e026b77a54a32e5f3.nq.gz
    ├── 1c8a18f2100f8e38b9da2f657cb19faaa9b80a99.nq.gz
    ├── 1cf1b910a3bf57e54924f70e635879d562cd1219.nq.gz
    ├── 1d08f0703bb1d0c84b6ba46c7604d78cc52ba505.nq.gz
    ├── 1d890107ca51413b41043d866f3d3db328fd6646.nq.gz
    ├── 1e1ee7ee8b2d32c84854d8f25181e546b390a12b.nq.gz
    ├── 1eefb81cc7e89dd5b9916b229ad55f19e65a778b.nq.gz
    ├── 1f031e052c11ad1504a42393836fd6c1531b94d8.nq.gz
    ├── 1f7d93647755ea18d4da413ecffa52c832cf2d80.nq.gz
    ├── 1f8a14d9acdbbabe55578020505dc5dfa91a3185.nq.gz
    ├── 1fc3b8eb6277246741b71d0b10de5e4e652563f5.nq.gz
    ├── 1fc5d6e0d14153fbb7bbd5f51555a104a271ae31.nq.gz
    ├── 1ffef600d959ec9e396d5a260bd3f5b927b2cef8.nq.gz
    ├── 201cc14336a592fa821e7fcd3d3a5d76ff62005b.nq.gz
    ├── 201fce1ee4c67bc47885e109938dab36c9751b29.nq.gz
    ├── 2050e98d38f6af76bc9e51c55a5afb4a35a9ef28.nq.gz
    ├── 20fb9a60ab57d8d8cee65670c6be57088f8a7715.nq.gz
    ├── 20ff94c876036baeb62f499c189f721c9633d9e3.nq.gz
    ├── 22bc37a5ec94a7650baee261165455ad0a3de573.nq.gz
    ├── 22c5317ec6561c57642e19c5634cc6f42fe718a7.nq.gz
    ├── 22fb32fd44576206611cb6891d97feccafd5532e.nq.gz
    ├── 23535e0410da747b6981075c84e196a68c034b52.nq.gz
    ├── 24252cf708b53660358ed0c80c7757bb61e4b996.nq.gz
    ├── 251ac764007568a715da3f18ec06755f31a34080.nq.gz
    ├── 25a7b13a4d7a87501b795afdb1b81ebd9cf6b8c4.nq.gz
    ├── 26b4ff0891b815ae9e384dda7a2c7e860a62efd9.nq.gz
    ├── 276b92cda61649de5885f0da9ba01993728bcb7f.nq.gz
    ├── 276bbd6b1ff4158e3c7911bf15168e2c87d0fbd1.nq.gz
    ├── 279f49d3710a2d11aba1a2b0b61ec3e8f41750ee.nq.gz
    ├── 290436e9c1feb57f63885135ab06e06b9e8bba8c.nq.gz
    ├── 2a2fb98c12cd375293b18bb5462efe5b2d231e22.nq.gz
    ├── 2b314bf07e0d21bb77ae255b875d65e4bab12dfa.nq.gz
    ├── 2b8e73a4e120a5215e93afe567bd38359b05bd79.nq.gz
    ├── 2bc68c444e9a62cace3eda363ddc0d3d540065cd.nq.gz
    ├── 2c005cdc0b81858675aa43fc31a41f49144559fd.nq.gz
    ├── 2c56b5488b799e69e3faeacabd8df5171ae21e7e.nq.gz
    ├── 2c581bfdd2102cbf4248d2289cd4fa03afda140a.nq.gz
    ├── 2d0daf8153464fa02a193e48f6730920e3eee1fd.nq.gz
    ├── 2d13c1ed7efbbe9fa8690aea1f51a9fd0b356279.nq.gz
    ├── 2d6b8f7f2fc6814a35e829b1564f75499485841b.nq.gz
    ├── 2da23832c7fb89d94819d64770f5d58e56f5f18a.nq.gz
    ├── 2ebddee3b0e2c42b61e37d38817281edb54b9e81.nq.gz
    ├── 2edb44ccb89a299d053364768efc770087246f80.nq.gz
    ├── 2f30140cd69a0fa9ec58ba5fe2c9e8d144e5e41d.nq.gz
    ├── 2f3d0c54a4807549e9a7d4a72cb9af0cc0690339.nq.gz
    ├── 2f6f310221dc388a4d76cd237d289ea07e92535b.nq.gz
    ├── 2fee751ae234f16ece576f55ed28cf53753325d2.nq.gz
    ├── 30204ca3246b352c9f350fcb446463b0f3fbb37d.nq.gz
    ├── 31328f8054de43b28eaf0528a0ed2afa195662a0.nq.gz
    ├── 31d9b71956a3c64fc46c0e69be860656bc97e714.nq.gz
    ├── 32b39faac989b10843d47e013fae98ac1d1e7090.nq.gz
    ├── 32d885a4314f3ffe81e4ea634b271c1cbaedba34.nq.gz
    ├── 343ddb0477beb8cf6917803cd184043958f13598.nq.gz
    ├── 34ac969e1932e5302e329f38e6c3b02396a496b6.nq.gz
    ├── 356d09b0573009d9f288614b8c4f809b2062f37c.nq.gz
    ├── 35b91cea3bda4342d020389b8bd2ad7c74f7dccd.nq.gz
    ├── 360c86bed500846ba2c2b804148a5444096373a4.nq.gz
    ├── 364c993a0a256055bd675e1ff7dc501ffe92c16b.nq.gz
    ├── 374b6daeca52ae252ce2d990227c180499fb05cb.nq.gz
    ├── 375c6b33b74ea3d5a563c756700575e27c124e76.nq.gz
    ├── 39a5fff60252a56101d6da7b8c34f645bc5eca82.nq.gz
    ├── 39b0c8774790401555709e5462cac05297564094.nq.gz
    ├── 3a8965b37f0f0f6e1ba312adb0c1ddaed586b8a4.nq.gz
    ├── 3ad683555d7825489a90a1e83744b295930959c8.nq.gz
    ├── 3b38ced719162835698c773c7fe1b6ca29316641.nq.gz
    ├── 3b9ec68f01db38bfa49f2658f23296a4cf2cbc39.nq.gz
    ├── 3c1b071292b62fadb53d9142edb8c49935dce49e.nq.gz
    ├── 3c7918e74b74ea28d5093950bddf0ffaada05ce7.nq.gz
    ├── 3c9bfeb788ccb288599849ed5f8de563d5aedcc1.nq.gz
    ├── 3cd7383f8c0a7ac2c4cbef05b942c64043146d46.nq.gz
    ├── 3d3dcce133f257a3dee0b903af1a56ab71085c0e.nq.gz
    ├── 3d413dd9209fed60977ee3ab36ef977d1e2f54aa.nq.gz
    ├── 3d9e7b5d81ca37e23f0c34f6706378d1972432a5.nq.gz
    ├── 3d9f178727727c17d91943a92278ba59a03a95bc.nq.gz
    ├── 3dc0087e01bf2a89b26ca892619f172caa18fbab.nq.gz
    ├── 3dc1680289e72408efbf1355770db3204f1702f3.nq.gz
    ├── 4078e7476a2eaf5705d327b5c9d459c234c01652.nq.gz
    ├── 408c203069e0483cc08b5c51409f866d35d10338.nq.gz
    ├── 41147b9642473a95a56c4b1ae4d30981a2b6ea1a.nq.gz
    ├── 421c1a44ceafaf8048c8677d8ca5ff0dc717a211.nq.gz
    ├── 427cc3eb5caed125510adf0537e066ff725ec912.nq.gz
    ├── 436900991dba2642a6b8da7e3d488b4d6d47ea77.nq.gz
    ├── 436929d2d038a0316097d588d8439e8e65127d63.nq.gz
    ├── 437a4022336eede9af4ecb2fffc7044d94a641ce.nq.gz
    ├── 439638e150d2b04f1aa89d5692908574a8278fd2.nq.gz
    ├── 43aa44127c2088f44c2aee43a7ef5ef74cee97c3.nq.gz
    ├── 43fca4396e2a3d4518ee8965ce4bf2e0c7fe179d.nq.gz
    ├── 441ec8c13e9624d1b1e1af31c535a2fea3c70caf.nq.gz
    ├── 45ac612f770d3b3eef6d05415da7d31f4e472881.nq.gz
    ├── 45da75d5bb410ec3f3b87f13ad85aa7656785e1f.nq.gz
    ├── 46c16bc22b9a72e68e82a1568dd8ead2c4590e94.nq.gz
    ├── 46dfaf3aba6994dfcd5bca4b8cf2a2dc96dc65bf.nq.gz
    ├── 4798094f4d9f73195d471ee3fcdabcb13787c64b.nq.gz
    ├── 4869e224a64687185c589d5653defb59e7a3cf2e.nq.gz
    ├── 498a4958674fbac4d2dde73c7a2ff90f49ec2b13.nq.gz
    ├── 49aba94bd7997b232a5d3960377da49ade219bc6.nq.gz
    ├── 4a5367b2e9ab46e6c88da67cabae95f206b09d6b.nq.gz
    ├── 4b7089ffa8d1e550fb619bd2e11a5cf90eeda233.nq.gz
    ├── 4b919f61ff578683d253ffb61ce658a7e95112d1.nq.gz
    ├── 4c736117e898a31520b1805066667648614f3821.nq.gz
    ├── 4c957d535e516739f7a256b6093f803735e5cb97.nq.gz
    ├── 4d1581aab4bdcc89a9805d17cc4ad1c69f7b9374.nq.gz
    ├── 4d1c0556b675c15554fa4d3c2ffd8e72bddaa017.nq.gz
    ├── 4d3739dabee54def11fcb5b65bd14c0449d46148.nq.gz
    ├── 4d7e9949a988a39c2b88013a9ed34c31b81a089b.nq.gz
    ├── 4e2a0d55fc7423f460286a9683c890a630d2a0ee.nq.gz
    ├── 4e6bafbb9aecdde371f62f048b6c6c57dacdd1b9.nq.gz
    ├── 4ecb987c2b57609356dd604770609fd5c56e8202.nq.gz
    ├── 4f696fd5459921da524cb2c7da202ec24a476842.nq.gz
    ├── 4fe289ecc621c00621ba7e6b5629e8cdc711c799.nq.gz
    ├── 50195c60c2093a29948b9772d5a2154e5a5d61c5.nq.gz
    ├── 505f5a16310127b3f1367ae3dd8d705608ee0866.nq.gz
    ├── 506338edd0e67ef33892fe641347e6b597400643.nq.gz
    ├── 507fada03277a46006b4121742fee6c2ff268af4.nq.gz
    ├── 509b7e8ff3610dda941748973433d5145a126200.nq.gz
    ├── 50b30246f9d322fe433276749438b3dd78b6040e.nq.gz
    ├── 50b5fd8e521c035e643f913583b408cdc6ad96b1.nq.gz
    ├── 512ca4df3828a101d1211bd8c99fa5a15eba7b34.nq.gz
    ├── 52d03bb758d19e7da696a2a4197dd3ebb3a469bb.nq.gz
    ├── 52e382dc033561d0c500e9b7221a3bfc005ff6a8.nq.gz
    ├── 53238334022f69cd8581ca6f1e359c89031c1cd1.nq.gz
    ├── 5334e0b0372dbbd06548e5db3521b800cf5b719e.nq.gz
    ├── 53568596f157030f70a24e125311b6e797e26bed.nq.gz
    ├── 536325e9dc7353b6163425db3ab5cc37897896f0.nq.gz
    ├── 5488d28914a63f101db3ec1361195159e9ba7b47.nq.gz
    ├── 5569f67f820cdd758fd93d16a818e15171a47190.nq.gz
    ├── 5583317847986dffec4ae954cbc0ca7f2efc797a.nq.gz
    ├── 5616540ef3fa4e325607333962ffc0026a6db89c.nq.gz
    ├── 563c95cec2d478705879f8481ba4d7cb2f75dedb.nq.gz
    ├── 56c30c31a8edf6411aad8915bb4555a7cffd756b.nq.gz
    ├── 5718511a27cf965192ee7d46ed00515f89f43002.nq.gz
    ├── 57f3e7ab47290323cc5d8cb0747812e10783ae88.nq.gz
    ├── 587ca383c75c996ae7ed6377be7c8ba1053430ae.nq.gz
    ├── 587d9c9774462ff9addbf5ab2fb71c8117f57dc5.nq.gz
    ├── 596fdc9e0e853c685e878bed228dad08d5616fd7.nq.gz
    ├── 59f2fd31a608bd71a82f27ea0023dc6708129fa2.nq.gz
    ├── 5b1e80bbe3562851bcb8d7b200c240fdbf7d6470.nq.gz
    ├── 5c23caf84d3d5a52887c86fc14fe7fc6eed1da5e.nq.gz
    ├── 5ccce8f4b20eb4151c0f0b4b667d3d5f8f090c46.nq.gz
    ├── 5d4342822fe886c47522bec34a19f4ebcb1efb9f.nq.gz
    ├── 5d4e87f30f6362b8597dbe54a44aadaffa915763.nq.gz
    ├── 5de1ca01f0ae754bc16714682ce5ebb06034d47f.nq.gz
    ├── 5e71a3f673f0ee2f2d9df37c016506400a758ccb.nq.gz
    ├── 5f08b80b199ca0a2e9ca647aeaf069b2d7714e6f.nq.gz
    ├── 6021aa8e9410fb6b7eee0009bb84d612551c3089.nq.gz
    ├── 60582068e7325e234bba31e86231d144886d7e4d.nq.gz
    ├── 60f249042e1dfaf27a9b88e2b3d390c5761fa4ba.nq.gz
    └── 6102cee2189131948226d901e6882c47e04446bf.nq.gz

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

[litestar-org/litestar-vite](https://github.com/litestar-org/litestar-vite)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
