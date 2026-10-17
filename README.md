# Repolex Knowledge Graph of cantools/cantools

RDF knowledge graph data for [cantools/cantools](https://github.com/cantools/cantools), parsed by [repolex](https://repolex.ai).

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
rlex download cantools/cantools
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 8d884136f09f6feccdf243eb35d8da57720c2fe5
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 8d884136f09f6feccdf243eb35d8da57720c2fe5
│           └── chunk-001.nq.gz
└── blob
    ├── 000b1662d956276b3371e35722378f7c9242ceb4.nq.gz
    ├── 009b2be3320c628c42fe2757489d202e9ca25539.nq.gz
    ├── 01f6d77230a5094f912f82da5dea1e1702ad1b7f.nq.gz
    ├── 02af7ca9e8a364faf51608d4a27c02e93e48fc79.nq.gz
    ├── 04739c9f9749d23fb00e3e2a5775304dbaa49f49.nq.gz
    ├── 04b49d7db40fe895bd0a25e30914567a63bdbba0.nq.gz
    ├── 0505eef64c200de3c884158f2c71e15eb48d1af5.nq.gz
    ├── 05e237de0284a70ba20719550e4969cde355cf12.nq.gz
    ├── 06f1759ed127eed54c7ad946bfa2573b7da09180.nq.gz
    ├── 092d317527e644e9b07548f5305505e0c3d9304d.nq.gz
    ├── 0afe2e2074703905fbb71e048b139abeefa8a387.nq.gz
    ├── 0bf3395fbe33a45a73bb7fa5ec2244d21e087136.nq.gz
    ├── 0d82ff893ebb062a0ecb4737e7240841d716bd5f.nq.gz
    ├── 0d90b33cfdca65f755a8c6327be437ff04d38e1c.nq.gz
    ├── 0d9ad2831ba6ac6789b8abeb0400d905bb95790d.nq.gz
    ├── 0e598ae58de9ad332e79fc3e8f9aa64754a44aa1.nq.gz
    ├── 0ed876ed2aaace83343c966416cea21afbaa0cd6.nq.gz
    ├── 0edac3ab1a9a35cf9f09ee919052634a8df2cc38.nq.gz
    ├── 10e2115cbe38715a24c57fa1537e88f7391755a1.nq.gz
    ├── 11991beecf2c471855a97f0f8cdda6834f4d105d.nq.gz
    ├── 11c923517c29f551fdc59766c1d077031632e717.nq.gz
    ├── 12610b63baf68b24542a9bcc1c9cc157c0d6cd54.nq.gz
    ├── 1285bb3952d1f45553880a317d78bfa38b787a2f.nq.gz
    ├── 1374a846a6d434bc1aa70714369ee058fa27db2c.nq.gz
    ├── 13c1d5047cdd74f05d27913c1eb8d44195f7818b.nq.gz
    ├── 14bd6357017cefbe4f9987b8e43434050b664a83.nq.gz
    ├── 15b1bb8b5f9ba5b922d0063dede3cc12077d799b.nq.gz
    ├── 17f3da83c429fbee44fddbad4ae3307c75ae5459.nq.gz
    ├── 183f14c0b978fa510d2d51b507737625a86edd35.nq.gz
    ├── 184db1778877d588d1938756644d3c3c69639da4.nq.gz
    ├── 18af20a9754a8078815799ae26453b20e02ed486.nq.gz
    ├── 1d6662a6bce15e6ad7c4455213711c02189c9101.nq.gz
    ├── 1e28a678e8ec4f9fdf8a83226d847fe7af4941e2.nq.gz
    ├── 2071b7ab529d025e5c51398635fc0a994b5b0679.nq.gz
    ├── 219239234fc9ec9e566e69635c9a45f1a5f6e31d.nq.gz
    ├── 226c9652e33ab602f20743b03f64b883d7b22804.nq.gz
    ├── 22e0f92647f9c49aa0d38b1c2738ccd3a95ca33e.nq.gz
    ├── 23c7f94152025bfe67370aa6ad797891a43900d1.nq.gz
    ├── 23e000916bfc53e35a73c47d6fa0e4fbc07dbb61.nq.gz
    ├── 240d4d0c9888f5a75323f27566a9c0365bb4626f.nq.gz
    ├── 243eb9f7b2be0cfc95b8d7fc8a84e7f3278d5901.nq.gz
    ├── 24fba4aad5aef216909afcfe99897eafbdfddd81.nq.gz
    ├── 25585981d31f06650cfbe54639153c90cb30617e.nq.gz
    ├── 256f61eb1799af55b1daba9d3e65d0d2f5cd185b.nq.gz
    ├── 25a12af084d601993eedbbf73f24d2c1f8e65370.nq.gz
    ├── 25e9ff8b07575897ee16d50cac32883e418d288c.nq.gz
    ├── 265e548d6bda497705c18c685d5a178aba98a27c.nq.gz
    ├── 268c23e29e283a18597bc1c3e145770e0ef44a87.nq.gz
    ├── 28db6b94cb616cb4bdfa5e59eb67a129290908ce.nq.gz
    ├── 29903c40683dabb6f5a58307f39b6c5b825f1167.nq.gz
    ├── 29e47e2e8f68f638f9cd34a66216bd53b0286b4f.nq.gz
    ├── 2a3755dadb7e0a7933a58b89e251551b2cf98806.nq.gz
    ├── 2a617fd691e38e4abccaeaddabcdcf1a8de1303b.nq.gz
    ├── 2c8364f47b49663c047924acbbc55c832ffe2c91.nq.gz
    ├── 2d79b87513b91b68ed252222c3c9fba06be1aaff.nq.gz
    ├── 2e3d058a6db171883a1efd81c11e525f64b5f59b.nq.gz
    ├── 2f3e4aba8a34af2b14081e181edace12792587c0.nq.gz
    ├── 3041e8408580d6433dc1d9d4f7fdc79cd2a9fe4c.nq.gz
    ├── 30889fa3082e00d3d5118a661c8bec14d581db02.nq.gz
    ├── 30daf3702d42238351c6aeef971f2a0dc59f7039.nq.gz
    ├── 32ab678f0390a45b0aa7d8199df7b04f8dccb629.nq.gz
    ├── 32f348a99bb2c968946e5f5db1705300c4274478.nq.gz
    ├── 341d132064e5d33d477ce9415ae9f52e981482a9.nq.gz
    ├── 3497e890fa47ac3a47b20b7c0b909bcff07c245f.nq.gz
    ├── 34c916df94662eda86e7c3b64cd2f9937a5ad867.nq.gz
    ├── 359cd33f8be4b7ba35ee8ae8bbe7a7425cc2f52a.nq.gz
    ├── 365e4bc7ce0c3e62cf0c047139f5c7c87482509c.nq.gz
    ├── 373e534ea094d4c361f8b4825f3d2dccdc72493a.nq.gz
    ├── 377f7e60cdc7c61ec7e51a9a0cb166b991cbae86.nq.gz
    ├── 3839a4713dac63c7a5253cbfd469bca111fd11b8.nq.gz
    ├── 385965f9889e89344ac82ae2480b518e694a1dca.nq.gz
    ├── 38b0606c61e987b533906db2ff0d792d6e046544.nq.gz
    ├── 39bf513cb291661f79272fb5bc8376ee1c945902.nq.gz
    ├── 3ab754d72b95b3ea2669515af9b8e00f44009dd5.nq.gz
    ├── 3ac1d875fb07802df33c9ba00ee3fc31fc8be3cd.nq.gz
    ├── 3b2991da30aa1bd7eff206784373e94f736b9a09.nq.gz
    ├── 3b6749f50665c83900d93f1d8d729acb82a70e94.nq.gz
    ├── 3b97d2f8f3536ea11d73695d876c0e3085b33054.nq.gz
    ├── 3be08263879ecb9f5a10137e50332acd6f00ea55.nq.gz
    ├── 3cb24e8e63fd91e4e1a7e29b93866be5d1afbdb1.nq.gz
    ├── 3d801799d949e23a9f460c38e92b843d6310e22d.nq.gz
    ├── 3e267f56034047fbc5d814d4ac2e5d4e4a29b591.nq.gz
    ├── 3e525df548f0f657b6da2b19e95a4b0dfbb8afb2.nq.gz
    ├── 3e69c4e22abf4bae57bd77eb3c98eb18452364f1.nq.gz
    ├── 4064d0c98823dd530d55a56af6c38c913a4c80b5.nq.gz
    ├── 40f38b7ebdb4aca14aa8e5c2df3deae8fcc951a0.nq.gz
    ├── 424ebd846fa48ac6d81d3b2d64b0e0b3fa67e359.nq.gz
    ├── 43a9fdbfc949b81615e86cd6bb84057b2d508a41.nq.gz
    ├── 43ba567155516447232ead3388a1fad5b80b18b6.nq.gz
    ├── 4446027e6aeead99ab5870a77b20273f0d0ee2f3.nq.gz
    ├── 463aeda502073870c3a27f25a314ddc5ee384865.nq.gz
    ├── 4760e68290f5f546cd23843388ff38ee0dc684f9.nq.gz
    ├── 4783552a7d2caf7babfb685121829684e14a7e41.nq.gz
    ├── 482686cbe5ff2b74afda3b4476b3400cb6ba7f32.nq.gz
    ├── 48cc38cca4878f5407bb2ada3861c05783085dd6.nq.gz
    ├── 494a4e60e495aa179da438d436d240990ef7267c.nq.gz
    ├── 4a5a749e0fd05462680bd1f87dc5eecbcc304d9f.nq.gz
    ├── 4a739a6dcdec099943afbabf12923a79a6e542d7.nq.gz
    ├── 4ceaacb7d2b37860e116188d6a2b16ef7ab3219f.nq.gz
    ├── 4d54f67c4f6231b09c1a61b35fe866f35d7ac22f.nq.gz
    ├── 4e04e2013aaeb7c5bef951df51b3c96e20dee723.nq.gz
    ├── 50c268b3361bfa14b203f7455b08c9e65e38640a.nq.gz
    ├── 511c558287cb844c425c41cf6f2a897ea9c906d1.nq.gz
    ├── 529b27e9cbce3801d10780f8e8e15b06a4e06fb4.nq.gz
    ├── 5323f82f81c28dadf413b7cc3b43c4663b084d20.nq.gz
    ├── 53a265a09778ed4ae43e5ec7e7b6b1f32f6ab60f.nq.gz
    ├── 53b391db49142a4ca2cfbdeff7df75f07db31fb9.nq.gz
    ├── 551d947a7b45f5eb67f8413c13a32aa327dbfb0f.nq.gz
    ├── 58e946db72d9ed97d02d1c7dc9d688f24e654d4d.nq.gz
    ├── 58f6f5d7e232799baff0dd27800cb65a387a1056.nq.gz
    ├── 592fb996641ecbd541513287bb2c37f0b10b58f5.nq.gz
    ├── 59af1288f1fc5f5a6b73b3cba75146f2ec69b464.nq.gz
    ├── 59d05404f35a606fba7f811bcad00c94519e230a.nq.gz
    ├── 5b497d62f65322628d1ff0b98c97b8da9ef454f7.nq.gz
    ├── 5bec2907b6165ebef8771b1931d47b5cf60a6a09.nq.gz
    ├── 5da1df68257212cfbe78c2fa408c79b9dc32369b.nq.gz
    ├── 5e6390274ef18ef10f0ffa8b863538c9cc689557.nq.gz
    ├── 5e76b351e1f2c02c6d0f43027d057d58c19fc67a.nq.gz
    ├── 5f5c83f7b340ccdac84ab9d685f083a9a0916c06.nq.gz
    ├── 5f64d164c439c96b2fb81750b43f172700768eb9.nq.gz
    ├── 5f67ab6ecb7c3224fce997bd19956cbf5357899b.nq.gz
    ├── 5f72b3d91813fd50d6071e1a922f9903a9e3c158.nq.gz
    ├── 604805428564216385c21fffa1be6bef183d2641.nq.gz
    ├── 605fd1f4b308f1804dec2dab748151de0053d92e.nq.gz
    ├── 607df2cb560069f1afdb8ad69b20b4796f6ad7f5.nq.gz
    ├── 60a9cd12a155538b57b7e21313b864b4d53d4894.nq.gz
    ├── 632dc62a09cff0edbd5cbb044c86d2cbb6f3e8d3.nq.gz
    ├── 6401a3b7fcc11f12d93a4769ffc71b38b1d4a8cf.nq.gz
    ├── 6503764b4f65f9e693ff35b4fdf04106059d16f3.nq.gz
    ├── 6507e10578a8a741235f1e3cce30c59624162e98.nq.gz
    ├── 65938ff76344d906237d42ed57ecdbd63f96cb78.nq.gz
    ├── 65e2288e920e014db4cc9ec9749c8c1edb9bfb6b.nq.gz
    ├── 6848d17fa30c3db4f718454060c386d66973a65a.nq.gz
    ├── 684d0b10c052976a9b69699da30b602aa8013fd8.nq.gz
    ├── 6a67ba7f76fc97247a91c0ccd38c95efaf88ef5a.nq.gz
    ├── 6b11aa1f04033527645da8f57f8519be2e635992.nq.gz
    ├── 6c1809c8210dddd81f29a69638f2c50daf82e7e3.nq.gz
    ├── 6cc858265aec87735f1f36f8d87291df9e120162.nq.gz
    ├── 6cd8ac0dd1aa33c52e0c4381c835db856e3694f2.nq.gz
    ├── 6d42110a39142a2420a528a725c124db6f439ecd.nq.gz
    ├── 6dc6a570b8be7858107e96613d5b2c25e3f692ea.nq.gz
    ├── 6ffa585a57a645cba85b366970a789a7fbbf41ab.nq.gz
    ├── 70463c491502f0712ab68cd096f93722d9594bbf.nq.gz
    ├── 70616c48225959b38f83d99ad35211dc7bb30261.nq.gz
    ├── 70d61dadbdd9c1fa65a6bd88a9dc10c715bebfb4.nq.gz
    ├── 71057ac31440b59c7a4327f91a59d933186f5308.nq.gz
    ├── 711f8aa62296591a5b59c4ba0b107b5f44b82956.nq.gz
    ├── 719b3b43786f9acb36f9089f1d85ec385f8b2644.nq.gz
    ├── 7697477c071157e40f9ae2e416cb78a180a58b74.nq.gz
    ├── 774ef4b0ddee7b3edd7c6c820c3db779fc60be5d.nq.gz
    ├── 7c329fea9738bcbe4b79eb272ad52189e04b7040.nq.gz
    ├── 7c6caeba3849c699edf5a995c83b351080b20963.nq.gz
    ├── 7c71507042db4ea93bfc3ddbeb2f1a8fbf8f485e.nq.gz
    ├── 7d2ecabf1b4195a952a01287321eaf333ec9d12f.nq.gz
    ├── 7d4b717ad34e9ef12b12151d47e8cfddc8d010f5.nq.gz
    ├── 7e73cb9d6bff009fac3f8b4410c251cbecef8cba.nq.gz
    ├── 813711d5f4a03dc3bc4b85133575f699dad7cc63.nq.gz
    ├── 815dc3a8ac2065e6dcdeab8383b774368638cb9e.nq.gz
    ├── 83afe068f4616a156f4bc643e669634906363642.nq.gz
    ├── 83c2d185e101ad51444790a52e644090aee832eb.nq.gz
    ├── 870dc8c32c768c4d133a8bbffe8215dca18b496c.nq.gz
    ├── 87b501de1bc6650e7d62f1666e48e823eef89147.nq.gz
    ├── 8844ce7cd4959c8d722899241f5c99847cefc53d.nq.gz
    ├── 8af51a8c887ef220c56d15d4276d94f9f0d9c6c4.nq.gz
    ├── 8b293ac8ad5ca89399eea9104a05a7faf0b2c343.nq.gz
    ├── 8b46eda64f5d2a079961373758d068ec8206404d.nq.gz
    ├── 8c7b09949f2b07beeeda1e201ef5e26bfa525ef9.nq.gz
    ├── 8f06fd0f027da2765b05c35545de048252267971.nq.gz
    ├── 91befd1d627fcac09955f2c5f8fc1a1d5b5680a3.nq.gz
    ├── 91d9b703515186db616d6fc67e19f45b11b6ac24.nq.gz
    ├── 91f1b73c6a18d405b5aef176020e3e71460ca830.nq.gz
    ├── 92625968addd8daf4e71c0bfe6b25351c78b5e74.nq.gz
    ├── 927192aa8435f90396980f7ac6282441417ee993.nq.gz
    ├── 93ac6421ccede65cc3fb497094e4557dddfc16a1.nq.gz
    ├── 940a3b9a0391c03447f2f702bdc606c776ec5f08.nq.gz
    ├── 944c45c222b2dfd4b99cad382ad987bbe57b6667.nq.gz
    ├── 953a47d6e2ede065061196d5c07254a4bddf80aa.nq.gz
    ├── 95cbfc2aef757fa574424862068d2aa412b88dea.nq.gz
    ├── 963fafc29fc6ac7a7a7fe4adecafc9b2088a426d.nq.gz
    ├── 96eba1e7d5dcf6ec7c25d1ce87eac3274ca0d8fc.nq.gz
    ├── 97967273c584e8b1c6e4aa1cfa033ec544d34bca.nq.gz
    ├── 97bc1c07f40d6d88d4df8cd5969f4bf3000b2cf9.nq.gz
    ├── 98614838f098a17e163f2e5f3919bb1ce3995fd6.nq.gz
    ├── 987c22dfdb85b18d7e8fa0cb5885e3f6d798acbb.nq.gz
    ├── 9993b4cb8701288c69fa2cd517f8b8590b1b40ca.nq.gz
    ├── 9a559c5a15190a4d63e1a9132b49e957fa1083d6.nq.gz
    ├── 9c398714a6aa8be50c2fafa8348ebb45550dd01e.nq.gz
    ├── 9d10b919f738bb32defd8a8678cc5ce58a663440.nq.gz
    ├── 9d7970d30a2e1ae9d371d764d6f4e3c85220c387.nq.gz
    ├── 9f23e453c63ee5bb367ba480564f32027c447672.nq.gz
    ├── a024cd48003dad670599c4d140781600872dbe2b.nq.gz
    ├── a1cfb7a3b5a30f35eaef9161cc9366f29dc32a9d.nq.gz
    ├── a27fe74ebd2d492ce433e38c651aa6db64300d1b.nq.gz
    ├── a38a07f3ae3a812b7a8f53fd2fcd2e2bfa9739f8.nq.gz
    ├── a59b2e6e9d6ee104dd0bea5b1b76086606bf7f91.nq.gz
    ├── a5e56fd9574526347506f7ffe4692e7e01a52e36.nq.gz
    ├── a636dee40291c68037d351d7558c717d7a9f4b60.nq.gz
    └── a765c06db9a08b609cd146252c6e00ed7d9a5a74.nq.gz

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

[cantools/cantools](https://github.com/cantools/cantools)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
