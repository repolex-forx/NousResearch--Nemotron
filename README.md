# Repolex Knowledge Graph of NousResearch/Nemotron

RDF knowledge graph data for [NousResearch/Nemotron](https://github.com/NousResearch/Nemotron), parsed by [repolex](https://repolex.ai).

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
rlex download NousResearch/Nemotron
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 02d6bd036ec364c34dc9f0145413c7fe72a890e6
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 02d6bd036ec364c34dc9f0145413c7fe72a890e6
│           └── chunk-001.nq.gz
└── blob
    ├── 0002cda1f2bf621454fa4597ddde6981305f4067.nq.gz
    ├── 002cd680a5e5a3a86ec7ca2f9fbb43bb851fda5d.nq.gz
    ├── 0075030c14db54b293a7ad38783f07b919563022.nq.gz
    ├── 00a9005c0c66f6c93f8f6ed7dcaabad8717f9ff3.nq.gz
    ├── 0114b818aa896d4f59b90045d2a1866b4230bc49.nq.gz
    ├── 016f64b2bcb252ebf3946a165d2a56513f3cb659.nq.gz
    ├── 023d7aba43b078ef369046f169413eb02652ffbd.nq.gz
    ├── 0303ce06f1f3217f343ad9c5ec58eea621577108.nq.gz
    ├── 037be067a405eaf86cc5b86f1fb091de1c6f31f0.nq.gz
    ├── 03dc5a5334f603a890f75d834b42164ab52fb797.nq.gz
    ├── 04e4c28411e22fe8f5f2707e8bf68ceef60e9db1.nq.gz
    ├── 052a99fe2833636e27407ddcd999a0ccb19e8aef.nq.gz
    ├── 056fa6a9889368f58472cb4221b847ee8df6bc9b.nq.gz
    ├── 05cf44c98996bc3c7891b116ff9cf25b226deb09.nq.gz
    ├── 05d14bf200caeb94836f7e64c5f4b7f2c3ab213c.nq.gz
    ├── 05eb4ae7d423c3bbce0f333846499949f16d478d.nq.gz
    ├── 0696842dfff58e2e0bfd819ef789c5b32b50a5e4.nq.gz
    ├── 070a06322888fdac055fe35387f388d6689f690e.nq.gz
    ├── 0721d078d01e70494bf564e18682ffb830694a32.nq.gz
    ├── 075ccafa01ecb5651c25051961b38da7f001a94b.nq.gz
    ├── 07656f0a38e403b7fac6120921a264b26673b44c.nq.gz
    ├── 07696e8916b773c8af064221213ef95096f692f7.nq.gz
    ├── 0772ea28236c7dd953364ba38723a228ff746dc2.nq.gz
    ├── 07becdd8959fe3a6eb90e78570292eaa482e2c0b.nq.gz
    ├── 081be5b5eccbe582dbc548f57a913586e13549db.nq.gz
    ├── 0a1c94cfd642a7e1e499f6fa6e6cd473f06cfb87.nq.gz
    ├── 0a9eb0d848f77561f23e65d984bf84896afd98eb.nq.gz
    ├── 0ab9a538d8cf369b97209293b7285b64ec357f0f.nq.gz
    ├── 0ba8ae711c84c8fcd5d0fc36e4ff71b5e7f31486.nq.gz
    ├── 0c338aa3bdf3b2a599d185ab00b139847fd70962.nq.gz
    ├── 0c4c0b2d4681b1f32c7ae21a611c946c91b5bc47.nq.gz
    ├── 0c6171986469d18925a5243686d0234ad3afd2aa.nq.gz
    ├── 0ce4072a125ef2fd789394356ebbf1bfd28d1609.nq.gz
    ├── 0cfdd9809aa9796dda5e2dd2d2e4a0c14a48113d.nq.gz
    ├── 0d2f55f274430998f09c6f9b8441fd7207eeefb6.nq.gz
    ├── 0df0f968fd18428a7a35e4a46f1a3e3e2fa9a033.nq.gz
    ├── 0e034b47cead21887e08d4fc8aabc46d4f2decd2.nq.gz
    ├── 0f3c01fe2b8b602884554800f3e905ae43b54e9b.nq.gz
    ├── 0f43291efda8519f43e752df674161764b896141.nq.gz
    ├── 0fa184f8c2dcd3cb69455bd5a4bc8e1278c4ee8f.nq.gz
    ├── 104d306d4d6797d9d96b34177f6e197c726f52bd.nq.gz
    ├── 10623249e13ddf44fb825ac45566c2ff66486b64.nq.gz
    ├── 107a78b383c287b242fe33e44995dc1feeba673e.nq.gz
    ├── 10fcbd20c4c9e7e2c616b009dbfcd9c15914f435.nq.gz
    ├── 113e43e6d4c40fb55793009bc7319a39e888ba0b.nq.gz
    ├── 114d377188b3779ba3723f6fc064f8743f290950.nq.gz
    ├── 12ae97435161e6a9c8f260dd7ff0f76fa8ed796d.nq.gz
    ├── 133601320904137a98aa772934caaab047ed1742.nq.gz
    ├── 13bbd83baf7f05743529e26c02294460d11929cc.nq.gz
    ├── 14367af25a99bcd94a8af8e1d8c9e2f0144a3c61.nq.gz
    ├── 154015214f4c120f30c8453dc7697a3f2b3a9fd3.nq.gz
    ├── 1570b1b9bcf1c48ec10e41d26b2b79826cbd9a62.nq.gz
    ├── 15c616e1c46e4f2b5e0bf477fcefb2150d6f823a.nq.gz
    ├── 17809745c4513eb74fa5a6f32569df25b901edcf.nq.gz
    ├── 191e905af011e7038b3718ea9b56507a443c236f.nq.gz
    ├── 1a2f0ab0399221a90743fe3c10f176e9c5a4f35a.nq.gz
    ├── 1a73759f720f8b600467e011735c208f4102628a.nq.gz
    ├── 1abd23356c5d5a1552c9230f9b6eb0962f7c99d8.nq.gz
    ├── 1b04fc194bdd1bd36d26ef7272536ee26f1c4110.nq.gz
    ├── 1bad05e3f01b5103c94215dbc0a668f40be83c54.nq.gz
    ├── 1c4bab9f2c4b423c172bcd7cbb3c2e000de0d36c.nq.gz
    ├── 1c799bf9d05e8ba2cba5575f8bbe0066061e3bfe.nq.gz
    ├── 1d0f01027a991d7a13f6b83b47181d0088b3b99c.nq.gz
    ├── 1d740e3ae7553aa54ef08a7d6df857e2264d4446.nq.gz
    ├── 1ebe68781d174f0c9efa985139e2aca99aa9b69c.nq.gz
    ├── 1ec6a321508571020879315e5329301b6713fb95.nq.gz
    ├── 205ebec7a1070b123d9cef89e7c7cbad3970c9de.nq.gz
    ├── 20d2a184a08e1a713c45bae4a15769907b1d4517.nq.gz
    ├── 20e4ba0f05da97e028270cd712f968b0f7468b5c.nq.gz
    ├── 212702b342a9e19de526495d07dce426fd89e5e4.nq.gz
    ├── 220e06412599ae746eaaffb35f1ed44e366ef8d3.nq.gz
    ├── 22218f9c1fd71e0c056ca0ca2d3d7f4e347d1de8.nq.gz
    ├── 2261265ce87d215627941654fe7ab376996635b0.nq.gz
    ├── 228c37424c8445a53b02614e8c65e5d4b93add7c.nq.gz
    ├── 24515dcf249a2eccc333d1f11e3ad58c940e9389.nq.gz
    ├── 24a4e6b20b3427bd33f306851355a22732b4f8e2.nq.gz
    ├── 2505feaff042d732eec751cde3532646162eb3a7.nq.gz
    ├── 2538a0bf3fdc15eb20e1e614f26a0a8fd1f47569.nq.gz
    ├── 27e0dd1d07a23731c228605809d3ac3fd6646c7b.nq.gz
    ├── 283a638df9d285628ca32bd673af98fb37793523.nq.gz
    ├── 283b40c0cb22f6e95dca7997f977036a96a336c0.nq.gz
    ├── 284c76d9492e3c055f707d32a48853c8ee4d4549.nq.gz
    ├── 2a1b46b5f0a992662f54181b6dd96bb106dba22e.nq.gz
    ├── 2a31db586ad8517955a6254c395951bda8d152ee.nq.gz
    ├── 2a60658c2fa79ff6e46e784d4711556aae4d09c9.nq.gz
    ├── 2a8e310656eda9beb122eb8a03a64f0a227e3ce6.nq.gz
    ├── 2ad5c21b77eda36c4487308b639cc5c4f7a9674a.nq.gz
    ├── 2b2877e486ff17d7020334f8d1ab968c5a44b4fa.nq.gz
    ├── 2b8cd88b81bd5816a2deadc50113553b26ad6230.nq.gz
    ├── 2be049da77329af8b3cd811a4b18c3c40ce284d2.nq.gz
    ├── 2ccdde0cbae873a86fe5aadc1a03d7934566d243.nq.gz
    ├── 2e54ebc26042c637de61d49c2f6a1a8c503bc1a9.nq.gz
    ├── 2e5710fbee8955112f40863382ea7fb48235d217.nq.gz
    ├── 2eb7a4dd62b5875c29ae7edf8fdce3124ef7dd44.nq.gz
    ├── 2f8471f08834e8289ee938146744794ec03f1d30.nq.gz
    ├── 3002d3cd1f298257735c6772f336c2510d0ecdb2.nq.gz
    ├── 315b72599039a560cfcdf129f7ecb50b043fe739.nq.gz
    ├── 3209e26e3b28a370dbb8c43dac7d10fcaf22c3b5.nq.gz
    ├── 3237e2d816e5e6d6d2c88dee9a601afb464bc2f0.nq.gz
    ├── 32e6a215155784d600b94588658fe830289ebe43.nq.gz
    ├── 3396bc0fd8774b540ec5a74065cf4d442e546b31.nq.gz
    ├── 341a77c5bc66dee5d2ba0edf888f91e5bf225e3c.nq.gz
    ├── 345e525ec318629982be2fd02cd67b309997bbcf.nq.gz
    ├── 34749cdc891a46af286c0a704bd873c1f9790c5e.nq.gz
    ├── 348a0e86a085741bc2162ff43a341c2a5e9aaef7.nq.gz
    ├── 34ef60af46d7811f5dbec6faa145ec07e07c833f.nq.gz
    ├── 39590f49a13e4d4ea3ba880dcb0ab508e2f61879.nq.gz
    ├── 3979a7c7d9e43c2d54f163b6e8d4cbf33d025159.nq.gz
    ├── 3aa472a53bc8f02d080951db7a4b7772d360a968.nq.gz
    ├── 3ac6c41a201ca2dddd762ea1c1e7ad24dff48cec.nq.gz
    ├── 3af9f3d05d7ba59efff3c87ce1bc819ad68c45bb.nq.gz
    ├── 3b5774db4c6b6179c7a77ded7d46ecda098dc2dc.nq.gz
    ├── 3c9af1f3fdad7868318757df34f94843d65c1d86.nq.gz
    ├── 3d16953cef253b1dcd28ff6b3ea4a54198d28a62.nq.gz
    ├── 3d6345e14dd718acb82c8c67f7e1ad8d77a7d350.nq.gz
    ├── 3d6b360070d65e44d7a3f08fdad087b6245a183a.nq.gz
    ├── 3dc07683281d91cefe6fd0514ea7154734050c2b.nq.gz
    ├── 3e709d510552d2c40d1d9f838ceacbf66c7de80b.nq.gz
    ├── 3f19abb7ecb7e777b068aa5fdc3d49c408de80cc.nq.gz
    ├── 4066038c1b64d53ac7ada67ffba6ffe27870ffed.nq.gz
    ├── 40dc4cf5eb7292f4381e2be962f4e4f6c5cd95e1.nq.gz
    ├── 41047851e662ca7dfb7edf2c61769e93b7d3b264.nq.gz
    ├── 410e0cde66f992eb0072fd08c2798b9aaba0973e.nq.gz
    ├── 41546368324080d86b931fc246b5590f6792df6e.nq.gz
    ├── 415f368660d25fdd345c3454fe6835f5d7de8b5b.nq.gz
    ├── 419fffe9ffde5fc98de8b0ebd4d411571b73c470.nq.gz
    ├── 41b205eb039006064820eefa268fe2f5f5eeaba6.nq.gz
    ├── 42045bdb46fbc2b713f794087df3a7afcc5ccf18.nq.gz
    ├── 42357a28bd7d348b2fad06acf74807d8e3272b5a.nq.gz
    ├── 4289c75ee31b650b2aba3593de886df8a70b0bec.nq.gz
    ├── 42df15f4f627a87d8cf1e90e3c33f54551ee1d84.nq.gz
    ├── 43097c7287b85ec33f208aa77d4899fffd863bcc.nq.gz
    ├── 4339121252be12a99aac2a1fbb1c0d7855ba4ba6.nq.gz
    ├── 4362c430ccc478457cac87ffb613e074b82b426a.nq.gz
    ├── 436335142febc4ed83d4d16a84e8b2dfdb5cc0ed.nq.gz
    ├── 445ac879f477cfa095ca89c429e10c97a42cd44c.nq.gz
    ├── 44649170266e8f66aba1fb9ce738676c3ddfd065.nq.gz
    ├── 44974777d9cc708292eeacdff605e139225fca25.nq.gz
    ├── 44d971be048f2de8e681271007062be84c20b3bb.nq.gz
    ├── 44ede962f409521136798b6afbd60b65353fbf45.nq.gz
    ├── 453b684d5d198d49402836fa290c29ffb2b02b5a.nq.gz
    ├── 45ad1cc90051a7e71538a4a990dd8caa5f50dd08.nq.gz
    ├── 462c65fd4214399c559c1cb7c0f926d19d519275.nq.gz
    ├── 463c8c0a924d8d789956451ba1e5f0af934c15a7.nq.gz
    ├── 471026d2ab5b23c5b2e7ecfbcc22754d386c75fd.nq.gz
    ├── 486ec50ef1e0b1ba2ea9661ee0f5cc3dd1251de5.nq.gz
    ├── 48cde28913291216f143d96ad8bba8f192b8ded0.nq.gz
    ├── 499676816b498ff4d6c94ce31f3a6d585ac366bf.nq.gz
    ├── 49b2c6553e7c19a90fac4b16cfd49695287a5ba3.nq.gz
    ├── 49c7b1b0290e03e817367b1cb4e08c127f19f5a5.nq.gz
    ├── 4a28dfa253828c88b4933126e7f00fd24ad1db50.nq.gz
    ├── 4a86bf2f980f39f6d25d36f2e17b99e834832b92.nq.gz
    ├── 4a8eb4e2cfdd760796e5467902517a46dd59ced4.nq.gz
    ├── 4b4c4e9407a224c75b698c5a0921b5af59d9bf61.nq.gz
    ├── 4ca2f6973f329acad0bfb389031e8b3d783ab023.nq.gz
    ├── 4d97c6c912f99247b0ff5b8a9db0027e7937c79a.nq.gz
    ├── 4eefdf3f444c309097dbc0ce74cf7e89839a728f.nq.gz
    ├── 4f7da060741c4841f7536ebc8d1196af71905a3d.nq.gz
    ├── 4f955ecf2d7eb1e5c548d2285d8dbcd64c6eacd8.nq.gz
    ├── 503ab6fee6b3516add8e9c81af351446b4471fa6.nq.gz
    ├── 51ac7651fc8a1e2ebdddf4890f8b357f14774a03.nq.gz
    ├── 525597fbf3021381a7572a70eaf48d3fce816828.nq.gz
    ├── 52be6e91521b2dd7ef1875409bbe19e660b3e45f.nq.gz
    ├── 52e710c8e4306142c7a86ee287e007b4054d587f.nq.gz
    ├── 534ffe7d254fef2bba6352756ad1b3808d62d7f0.nq.gz
    ├── 53895240a755310420043718d185fd22abd54902.nq.gz
    ├── 539332b97dafe12b3ab1bed4e8f2313fdd84b4f4.nq.gz
    ├── 53b6553784e36d1cb7adb27dcdbdfb2499e42641.nq.gz
    ├── 5528630231be7e1ad7a7218c5ed2d6d90d4a448f.nq.gz
    ├── 568a6ab06936fe143c5eadd8081a4997e19e0c6c.nq.gz
    ├── 56eeded8e48ec2a664cec36a92dd2ab958ea6389.nq.gz
    ├── 56f1d27061fe046b737fd27195129e4c35d12797.nq.gz
    ├── 570c7c3c6c44f4541873a52164e4a391e8145a30.nq.gz
    ├── 5712edb4e3db6dc56cbc50dfdfe4dbbef5fb0581.nq.gz
    ├── 5722aa13c44a85353defcc35a81bee2737c9a58c.nq.gz
    ├── 58965d63516f06231b1561fad14c6f7a4c0ea3f9.nq.gz
    ├── 59505d13ae4406b266522951f6fcd44085e0043b.nq.gz
    ├── 595ab8c7ace647dbdbcfa43eeba5cb0dd8c1f61a.nq.gz
    ├── 5a78e7d82760aac7f5e1e87eb5c10b72447840d3.nq.gz
    ├── 5ae03c6425f32625aef2712c4486351000046bb4.nq.gz
    ├── 5b21273ec70cd3d646025be5c532e8950aca55f8.nq.gz
    ├── 5ba480409b5457ec9f32cff884fab13a0251afcc.nq.gz
    ├── 5c44e9744f9d4070555dd79b43cd4e8e36ca7a96.nq.gz
    ├── 5c65ca36b678f2c4e87fff4fe605676ffdc34f54.nq.gz
    ├── 5dc19b1a8b0eeaf31d026d3010bdc809f528937e.nq.gz
    ├── 5e0f0604144263ff0dc65713462f86e4167b3a21.nq.gz
    ├── 5e4efaf6354617ee084d58f83b6b62cc74ef93de.nq.gz
    ├── 5f178d8fd058f6267d3953165158bf943f623451.nq.gz
    ├── 608f5b76d39a9d9158d1ade7c98585136d68a449.nq.gz
    ├── 619ed0d81172e1e72b016d19d6abf0701adaf459.nq.gz
    ├── 61b7339e36012239e200e144c747b86432ce8109.nq.gz
    ├── 61ec1821338055e19b117ba6396ff5c23fb09136.nq.gz
    ├── 62420c2072aef8b36f4f7924d657fb4ae816b7dc.nq.gz
    ├── 627c78cf5157ed62f29b19614db0cc0b0410872b.nq.gz
    ├── 62be5e246e91d9bb6febde854fc00b638149d768.nq.gz
    ├── 62ded9ce1ab62c9c650d0641f0d983ab5d945f00.nq.gz
    ├── 62fb2cc67fe0f4f0c5a5ca73234b304574c6f511.nq.gz
    └── 630b0a80e5af330df6c7da9c7446a3ab22b46c28.nq.gz

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

[NousResearch/Nemotron](https://github.com/NousResearch/Nemotron)

---
*Parsed on 2026-10-09 by [repolex](https://repolex.ai)*
