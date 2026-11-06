# Repolex Knowledge Graph of ansible-community/ara

RDF knowledge graph data for [ansible-community/ara](https://github.com/ansible-community/ara), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-community/ara
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 8aa994d1e5a254e3994819b2f799c79dbc9f77e6
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 8aa994d1e5a254e3994819b2f799c79dbc9f77e6
│           └── chunk-001.nq.gz
└── blob
    ├── 0113b8c72462d5d20f0d4067298114e0598f863f.nq.gz
    ├── 0131d71cd8aa5c7f2e947845023c22620a489bc8.nq.gz
    ├── 01b12b8390849bfbbbfd6e5d3df35f42f5f5f8b4.nq.gz
    ├── 01fb1a21bd2d3ba143ae29b4d286aa9d14772a3e.nq.gz
    ├── 08a842336121f0f82e9ae53e536c8e35c56eb13c.nq.gz
    ├── 08bebd069bf4b7c322b1aa3755186c13f30aa5ce.nq.gz
    ├── 09a7e89a36a1285d587081ee5f8402f838265c63.nq.gz
    ├── 0a6e6e251a0c76eeb9ae9ceda104b39e809b4b95.nq.gz
    ├── 0ac3a259644716632b464c0834294e12e22b0112.nq.gz
    ├── 0af473e82996b177c902bc1e8be51cfe7047edff.nq.gz
    ├── 0b48c160094cae695d3d778612e83f1f0c984822.nq.gz
    ├── 0b61118cd9f5631bfc7ee0e2cc5126e66a684acd.nq.gz
    ├── 0bddde724605c6c8e6522389028ab27cdeb41df2.nq.gz
    ├── 0c94dcae656c0aff7c80223412786ae203b64256.nq.gz
    ├── 0cc39edf76b0f199454d0544b65c2c6b7af9d0fc.nq.gz
    ├── 0ce89847d6be0a85d6393884df916b67ee790b3b.nq.gz
    ├── 0e88e161ede29e63bd690ae4ec9b383a1c057df2.nq.gz
    ├── 0ee91569bf2b927068f0be1e08f3c607339d4cc2.nq.gz
    ├── 0f4dc65b2e3447e5ef4930f9147753912b970f4d.nq.gz
    ├── 0fcc75ba7e111af60a5151c793395fe9969867d1.nq.gz
    ├── 0fd746ddb3df27b77d04d2e31401f91808b2c937.nq.gz
    ├── 103977d5c5983c4caf3871a3eac4a224d0eb5716.nq.gz
    ├── 11bd2331003adb20fea9702a47a285e1b9dd09c1.nq.gz
    ├── 1225deddcba72f611187bed1376d2ab081e137ab.nq.gz
    ├── 12eb46e675e2c6ec02ed8ff116310f06d2614852.nq.gz
    ├── 13bb45665b60b541ca264bd40144ae9717c6d647.nq.gz
    ├── 15be3be0c49e4cdea659426dab48984105e2b510.nq.gz
    ├── 160a1b597bad9a3a7a05386c3929b483eacaed53.nq.gz
    ├── 16f80e61c863e04eafe75ac3c6ea3eda040a290d.nq.gz
    ├── 17820d1d288138a2e2593726dec08d7f1abdc0b8.nq.gz
    ├── 17d8ffd05953654e3510978c5ca752f9e834e2ae.nq.gz
    ├── 18574b3fe54e99a7c09236f5d2c301e228b68934.nq.gz
    ├── 189f4d2ff23d54b963748a8e033591e3d2d48d83.nq.gz
    ├── 1912e67d66f0ea2620e5b5442afdf249495af6c0.nq.gz
    ├── 1a35d729976b17c9fc76175e602afe6ece17edc7.nq.gz
    ├── 1a47424b08581d54e35ee546267d5000c42acf44.nq.gz
    ├── 1a51259e8170555a9d7228896599c869e6cac6d4.nq.gz
    ├── 1b14f3887a81cf77cae4859cb0aa6f14c8404569.nq.gz
    ├── 1b47697266460171c3b18730e38f468547eb4272.nq.gz
    ├── 1b4a7bdb3c368b45d8783c95bc854c5aa4f8a35d.nq.gz
    ├── 1f0e6950de4215c681e18d7132d3a7476736d7b9.nq.gz
    ├── 21be96a0bea6795dea5696fae6d8642ea512a7ba.nq.gz
    ├── 24d82c455423e77c35f677f87961f22f86209779.nq.gz
    ├── 2679dd66cf7c6a7d6555a9587642692500b162c5.nq.gz
    ├── 26e6475afb72488945d373f19504575995ed2de6.nq.gz
    ├── 27e3e3ab9485ed62e8c93ba592ba69cc2a62fcf9.nq.gz
    ├── 286ecedfa253312d240d3b676dffd1b2f6d10e2e.nq.gz
    ├── 29b9cce670a03ebc33c83956892853326832c6ab.nq.gz
    ├── 29d713cc5909a2de6eb73cbbfbfcba098201adcf.nq.gz
    ├── 2a211200348ef3a8d7d4c5f320d9070099c0edc1.nq.gz
    ├── 2a7d5fd413fe53bb4ae02e8741401ee40d85a3f4.nq.gz
    ├── 2d1670dbb3d4237f85dd38b6ffdc1c29172f0624.nq.gz
    ├── 318f452a5c0bd9c809f51676540847e492fcf25a.nq.gz
    ├── 31dc5589bb1e2688817907beefed9735c69d1cc9.nq.gz
    ├── 32247dcc83b81f7cf280ee34112c0b831f91710f.nq.gz
    ├── 3295cccafdfbba5a4b3c18296c5342706c400f16.nq.gz
    ├── 34648b388a7736ff9e8e7b3e0987932ba26d255d.nq.gz
    ├── 346ee050b4e3feb49b33977c8a936dce5be75a6a.nq.gz
    ├── 34bf0c7664b40bdffc7baf590a6e214078620325.nq.gz
    ├── 34c5963438eb70b041b1638dcb38da3231a3255a.nq.gz
    ├── 3755e79edd75222c0e0b308985c769f57941f263.nq.gz
    ├── 3835b6d7f218c323949f529708e7f209d141472c.nq.gz
    ├── 39455295d169bac5a1d05885cc01d7c25f8994ce.nq.gz
    ├── 39c83b1c24d676459e8fc8acb431d9016e4918cb.nq.gz
    ├── 3a1528f0f62f2b555feffd8a41e15314d33447b4.nq.gz
    ├── 3c1dddf30396e93df28a9474bb3c05e3148b24e2.nq.gz
    ├── 3c964ea927af7cae064565eeb04666af49e155c2.nq.gz
    ├── 3c96e9f87b5ec134b6d3b63834af2f3e0f8bf59e.nq.gz
    ├── 3ccdd89e519e0f597877ed7d2a1d8d17cc7bbcc0.nq.gz
    ├── 3d098e0c877c47800d517ea27da7959f5962c85a.nq.gz
    ├── 3f43dc34a4e9d4c917bed06a5d13edacceb4f124.nq.gz
    ├── 407c0d542d505bdeec6c1154b7fa6951288793ed.nq.gz
    ├── 4158977614440434a914a7a3e7d9ee297fa1e61f.nq.gz
    ├── 428e98765a4988dee139c60cd47a0d5d9102f3cf.nq.gz
    ├── 43a9991625ea7e49e184813be08481aac8c7d63d.nq.gz
    ├── 452a60226ad1560e3b42fa5b76f96166ad99e6fc.nq.gz
    ├── 45e805051aed3bc58b9b674d89313db8434036f3.nq.gz
    ├── 4630f8ea82d49f6ec8206502a01d65e4fb7dff36.nq.gz
    ├── 46b31254b46373d08df427ed2f746f6ec0de1a62.nq.gz
    ├── 4847d9f1bf9cf315ab853cd405981bf617acab74.nq.gz
    ├── 4858afb2da1cd0dcc33e825fd0065c7abbfceaeb.nq.gz
    ├── 49ed0ca86011537f50147c3014eda8e1565459fc.nq.gz
    ├── 4a2621bc41dd99f41fde4592ade7b3aecca63186.nq.gz
    ├── 4cb4a70063f6cc5a40b8c2c5927e24459fb3a7c4.nq.gz
    ├── 4d8c490e1ec1153df2a4d80d1342f1d8820e792d.nq.gz
    ├── 4dc5aac8b83abeeeca7e3b820a2659ef0ffd7d05.nq.gz
    ├── 4dd1b71a5ad17848921e97430cf449c52aa8ed52.nq.gz
    ├── 4e563f407ed2580a92ad4c13b9f096bc840b142d.nq.gz
    ├── 4ef928c3465f193d936dd1b5a4aa828047548bf8.nq.gz
    ├── 501bdca5b80d49d39d7400393d60332747c111d9.nq.gz
    ├── 5074432be5d307736acce62b99580ad960572fee.nq.gz
    ├── 5154ad46e4f140a3c68422b7549653824ddfb23c.nq.gz
    ├── 51bc173758c93b37bd2171fa39106d9ea87a0174.nq.gz
    ├── 52fdc572eb39f0bfd03c55fbf72ca56fd7725f98.nq.gz
    ├── 534ada901e7d94347326e9731ab03a2452c7eaa2.nq.gz
    ├── 53ef0426e2563744ca965eb22ea524fd8af1db5e.nq.gz
    ├── 54ec04105d5f7222a96d3865a6597eae6ef6d118.nq.gz
    ├── 56691e82b170044ecde7d7bf3a2cbda93ba8d572.nq.gz
    ├── 5686a41621581a8e582798e43ba8feb24d8b0033.nq.gz
    ├── 5778a49d2dcb3a68f2dffd7987fc1e5cdec2c2ab.nq.gz
    ├── 586819bc24d473c12966993aa61bb5c2dfbe36e2.nq.gz
    ├── 59435f084443fe299fc8da5dc7b6183cb37caaa4.nq.gz
    ├── 5a428ea2b783b35f8033d87e14002f36c8e36f1b.nq.gz
    ├── 5bad64d870a6486345e17b47db59235513f01927.nq.gz
    ├── 5bccc182bbf15ca82acf175a9a00c22b471760b4.nq.gz
    ├── 5d1ebca8402bf260d0927558381192f3d0cf8249.nq.gz
    ├── 5e3e0b54a096a7f1de54d08361b48337eb974a4a.nq.gz
    ├── 5ec9c7847012c2f0c74f50ec18873b166112f24c.nq.gz
    ├── 5f33d4838204893cfb63a43c85c2ccc9535aa16f.nq.gz
    ├── 6055bd24d826620c48c3b62a947455ab99dedaee.nq.gz
    ├── 60706cba27dcf6420344140eba6e4184d5d8583c.nq.gz
    ├── 6230dd070ca786e715bc5059e8f78a39b89e822c.nq.gz
    ├── 630b698d7be721803169914c9f1a26dcd9ddbc91.nq.gz
    ├── 636b11a75a8fc3f61c9e28c412957a49d90e86c6.nq.gz
    ├── 642402851e0f2065c38a147d4f2e1858f6fa5ace.nq.gz
    ├── 644cac132b0627b6fb5f3daa6bdb1e96e27d7cf7.nq.gz
    ├── 64d316360dddeadfd9cc1844d64909daa57af89f.nq.gz
    ├── 64d6d6738a2ef65ddded29d6d9848f1bc63d4531.nq.gz
    ├── 67e63587b094d57a555c72c5bb837696890c9d4b.nq.gz
    ├── 68deff60aaf520de4753dd0838621f239ce1c420.nq.gz
    ├── 6972464ccc6603db3ae766c9feedd5a53639ccfb.nq.gz
    ├── 6a33cc000157638d0c823e3f1ed15d3f189ae5aa.nq.gz
    ├── 6b6f12f178f5c34940936881fe7b7f8a8638abf7.nq.gz
    ├── 6c9105ee441180373bc8efe516681f304997ac1b.nq.gz
    ├── 6e12a147a6f9e7780d0e62dd2221b1e9d6c88cd5.nq.gz
    ├── 6f73aefbfb433dbd2298d441097ca1d77acbe7be.nq.gz
    ├── 71b130fe21e5541e8c489bba0ede7eeecef6515f.nq.gz
    ├── 72485f4828a12af34b1daf1f2ec1d1ccb10418df.nq.gz
    ├── 73032b0ed8d3881210db8b5cff150fda5b68d907.nq.gz
    ├── 745dbbcadd7ff5f81e76e581b525a738248ff258.nq.gz
    ├── 76b752a7fb71e21b0ea577af95ae77d6de99d01f.nq.gz
    ├── 771111f8e14624db18bc1be9da1a4fb6e23d8fa8.nq.gz
    ├── 77470cb39f05f70a5b709b68304d0756bab75a0d.nq.gz
    ├── 78b90bbec84953b212aa1cc480f6acff4004cc40.nq.gz
    ├── 79918b9fbc745a3b6a0cfb843be24192cafb79e7.nq.gz
    ├── 79c267efbae4c4e6d0c9fef359c7a7fb517177c9.nq.gz
    ├── 7a53054cfe7ec8cf21587724f66d3f1117e18cac.nq.gz
    ├── 7aa587a99bf17ebf312bdd1b6f2dccfad480b5c9.nq.gz
    ├── 7c80fab7de78be3443220d988875ac4479e41764.nq.gz
    ├── 7d11757167f13437ac4dcf92db145fbcb8419cca.nq.gz
    ├── 7e35262e7dfc13598388cee402008d55292f59dd.nq.gz
    ├── 7e4d6f10363ca0d81803c2be57f99246a5787bea.nq.gz
    ├── 7fbac4f1b376f76f4cd5c8a76017e8dd834c75fd.nq.gz
    ├── 81df96f772739b1c36ef5dc3b426e59dac032e38.nq.gz
    ├── 83349c7d615b7cfcd614e37202b7cb4b599d2b36.nq.gz
    ├── 86f9f0708d06aaae78d67ee05a6f452b50611cbb.nq.gz
    ├── 88ce4f926076d998e9b4a2e51ff10143e5ab8a95.nq.gz
    ├── 890cb14e113966e8866768dff49f62c2c3eb232b.nq.gz
    ├── 8c49cb90396c166604c2d2a5c294b12e33014c35.nq.gz
    ├── 8cf05a57602aa725ee3b3959d50ae291fdad155f.nq.gz
    ├── 8d7d43e4f16c025af352fe283f4d5a95f79cb6fc.nq.gz
    ├── 8db09aa19e879e508b24c1c118ceefe21ecd47ee.nq.gz
    ├── 8e2eddedf77d830b14408fcce12bf82a9d145984.nq.gz
    ├── 8fbe5ab8a326df18316a3f34458e747259c94251.nq.gz
    ├── 8ffeeab36273918303d6f94a14da0ec06b636101.nq.gz
    ├── 9086abbae7f09de989c8b4e4d235315139d6cad9.nq.gz
    ├── 9137549dd10d5961c92c79edc524b9740159d648.nq.gz
    ├── 915be09e61fefbbed9d96485eb591834ac2588bb.nq.gz
    ├── 919811867a516bd5c1753dbb6bac806de94898a4.nq.gz
    ├── 936db75ed0b4f3439c08a90aeced69ef3c837af2.nq.gz
    ├── 93df1bcb4dfa70dfcde1a046146f3392b2642c89.nq.gz
    ├── 9948271729d7de595c55240deb221c0f55bccad9.nq.gz
    ├── 998b9d283fab855637afa8d48fbc921e6846089d.nq.gz
    ├── 9a44417fd485e879e233817643a260c6c380b7d7.nq.gz
    ├── 9aef210a0f9f6aa2b818f49adf810a9f5e1d802f.nq.gz
    ├── 9af2f6551a9acb5e367e6c4a8b24bde2d1ad5e17.nq.gz
    ├── 9bbc40d684a85ca08014ef6622e8118afeef25f9.nq.gz
    ├── 9c25eb6a40869c2f3a1285372dddc67d1d074f36.nq.gz
    ├── 9cecc1d4669ee8af2ca727a5d8cde10cd8b2d7cc.nq.gz
    ├── 9e734882154043eaf59e8a92cb6ce1348375bef2.nq.gz
    ├── 9e88a5a3b857110bea1f9d3f09433a4601797b4f.nq.gz
    ├── 9e8b042c268a040977fe56b401248ba928835899.nq.gz
    ├── 9f53275cad307a0c6f99eeea67301e045962abda.nq.gz
    ├── a1b90f3f6e62c4c7464b7af676f169be103a23ee.nq.gz
    ├── a2ef5da6d92d70deb26f08b15343207ebdb86def.nq.gz
    ├── a30193894966fc23c0138827e8d9a83c8843a4b2.nq.gz
    ├── a376a42fd29a01ed58e8f1bcbfbb4962ffe5650d.nq.gz
    ├── a46ed71238dd127ce8fd9c0509c987b865c96718.nq.gz
    ├── a55d08941317f645867eb5297ec1aa917ac57761.nq.gz
    ├── a5a8f3cbf60faa17f43b61208cf4d5f7e282a476.nq.gz
    ├── a5c8045bd245eed305c7817d85832fa879fe26cb.nq.gz
    ├── a80339240c8db7ce33d5657ab3964a63e461f369.nq.gz
    ├── aa09a4deade087a32913cc9cdb986094f994780d.nq.gz
    ├── aa18255901881b9fb8849ab0b601a40d2555d123.nq.gz
    ├── aaec66f95f56aca9d626c12f9a98d47c8359ec85.nq.gz
    ├── acfdc8eead69847b0ea30e9d0440a1f0f77981f3.nq.gz
    ├── ad67a1e6a80fdf736a7799e733c7e620775eec62.nq.gz
    ├── ae03dc7497a60bf3c8e0941592d22a43fd3a9c0c.nq.gz
    ├── b0df8f607d8ad78fcfa55389c0c7f1b73fc56cd4.nq.gz
    ├── b1036464219b9a8d2825af876500044c2ddd9807.nq.gz
    ├── b13f12aea2624d65c1efbeb7aaf7ffbf975c551e.nq.gz
    ├── b1cbba076124c82624a996faa89fc67721abc6a6.nq.gz
    ├── b1fb7366aadc0364a00c75a536ec8a4809aa5c2d.nq.gz
    ├── b442b96a7e7f5f321d7700fe19b5cb639bdbd04f.nq.gz
    ├── b460b1d1f32998906cafb858945a377c12386d5d.nq.gz
    ├── b4ac3cfa27797cf68a0b15acbf8e2bbb681b1928.nq.gz
    ├── b5a8a9222cfda25b7643cc4a27e66426aaf61dd3.nq.gz
    └── b7481ce8c4b0dff6cc8e8a9bf03042f5e3f56e63.nq.gz

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

[ansible-community/ara](https://github.com/ansible-community/ara)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
