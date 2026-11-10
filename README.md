# Repolex Knowledge Graph of typelevel/skunk

RDF knowledge graph data for [typelevel/skunk](https://github.com/typelevel/skunk), parsed by [repolex](https://repolex.ai).

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
rlex download typelevel/skunk
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1045d3b2317ed21d7554c92676cc77edb3d1cd18
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 1045d3b2317ed21d7554c92676cc77edb3d1cd18
│           └── chunk-001.nq.gz
└── blob
    ├── 0092898fc7c9b5ba2fede487b4557ef38e692174.nq.gz
    ├── 02c87a6fd30fd612f21665c064d45e09b1643960.nq.gz
    ├── 02d25fce2cdf64abbcab0909802b2f373c2da35f.nq.gz
    ├── 0369c50ec42ce3938ad1607730e15e6b6e3c4553.nq.gz
    ├── 041cb55f98b5fe191c6030f258bdc079406c9b5a.nq.gz
    ├── 0517b219fc6d6c3f34c01a9ee12e24d01e5625e4.nq.gz
    ├── 052d1e7f0a59af1e9f7645b9c218d645c9febf87.nq.gz
    ├── 0612927f33b955a1e446bc4dd982b5e00b4bde2e.nq.gz
    ├── 07018b5140297f22ee6f9f1f40139e2158319378.nq.gz
    ├── 07ae23d9b3f8a2bf6c3838c33bfe7674a2f1c95f.nq.gz
    ├── 07d4d7606ab204c1bf2ef4b57b72ee174e5e5818.nq.gz
    ├── 07e40ae006b5e800d8598db289ebd2c1e7f31a94.nq.gz
    ├── 083fb067d45f1aa0a1e4875fc7c0627b3abeed83.nq.gz
    ├── 08c10fca3ed7537f35653870cc35afce0e337d2d.nq.gz
    ├── 0911685debfde143630767ff30eef3ac92a4f2ff.nq.gz
    ├── 0a1ffeeb168d74beaab86787aaaa426a681d161d.nq.gz
    ├── 0a9abdddd5422d5d280be69a2852780bafbce6e2.nq.gz
    ├── 0dec463990457006955f4c19c93d85595dc65fb4.nq.gz
    ├── 0e2977f1367af5f067bd38fddfd79f5f3a21099f.nq.gz
    ├── 0f5dda3b0ca1bcdf13fac443314f37cd24d9578d.nq.gz
    ├── 10535a92f0f015adf2341fccc29d8cf275f1970a.nq.gz
    ├── 109f253ba61b4090e1c6c68c56baff99927628b1.nq.gz
    ├── 10b3c47bf423773907d337b4874b1ed96e548002.nq.gz
    ├── 1330ed996571c6dd310588f7a1897c3690b70fe5.nq.gz
    ├── 136153ae50f4894e13cf770bec73657e2f966c8e.nq.gz
    ├── 163ee140a3e3e8fdd01cda61c7acf7ee0a2720b5.nq.gz
    ├── 1689ceeb1af8ccd79ff4e8df8cec288d12e009ad.nq.gz
    ├── 16c23d75197873eee9e1a707370f9d4211268594.nq.gz
    ├── 16ce682f5b51b57a2572092bc8224c0ce62dae3a.nq.gz
    ├── 16d65ecc84ebdf013887c7757d077c7b6b44bee6.nq.gz
    ├── 16f5efc7fc483b7800c033d10223719c1425d6c1.nq.gz
    ├── 17c26c91ee41b7d8086633673f9149d8bd0fa3a5.nq.gz
    ├── 180ca4546b403e83893e74284fe291e23a244025.nq.gz
    ├── 190097ccc6d1e8e7e32f4e4263714034cf5cc326.nq.gz
    ├── 19401ed7032edf2e39cc091bd1df31114eee3a92.nq.gz
    ├── 19bd446adaa5048dad6a81cecce27fb39072b271.nq.gz
    ├── 1be50a15f781374dd62e9c0b023a20fa22d8184b.nq.gz
    ├── 1dae6203f8b0eb4b2cdbf5927fd091a6da34c72e.nq.gz
    ├── 1ddb68bde50c9e6648bf167062f78598dc6ad34e.nq.gz
    ├── 1f2a94e7cd0cbbb1bd572db871d76302e4d9d777.nq.gz
    ├── 22072d234914a0679d8bc9e87021c6c2d4b56856.nq.gz
    ├── 2235d68fbe8d3a465ecec13c16a6de47494a3e8e.nq.gz
    ├── 23538a3d74dd0624d1a2a59f00878fbb8e0b340a.nq.gz
    ├── 23573afe0d935a92015971f372b95949d6e9381c.nq.gz
    ├── 23adcad93d75568b374e017efc5e7a3ca83ea41d.nq.gz
    ├── 23c73b981ff294c5f6b5ea09bdc8388729c7089b.nq.gz
    ├── 2427cf97bcdbe98ac4b40cc699cb9c2ab3b9dc8a.nq.gz
    ├── 2539b9a2aa3e602c7101bce265d6bd2353c4c5db.nq.gz
    ├── 26bfc4d5ca6c386440830389cb3a1992c3fcd1fe.nq.gz
    ├── 26d407b0d9e0d1bbc091134963626752b1af772b.nq.gz
    ├── 2794bbc1fb03375bb99999b48ad1b1e7d22522b2.nq.gz
    ├── 27970556338f1bb3d3a8484b37692c05430a0d9d.nq.gz
    ├── 27e4d2e40fc697676b1794313453f6e89bc53234.nq.gz
    ├── 293ab0e089e2361e8b2f91bcb416f3b8bdedab09.nq.gz
    ├── 293b8c91d74cf71662df9a25acc9a77faa45f441.nq.gz
    ├── 2b1363f8695e75e25c4e759a97f67193868decd5.nq.gz
    ├── 2b4ff40815b1311007cfdd8dae272a7d24e880ab.nq.gz
    ├── 2b8c48303553fa631568c2cf38e613d56a77c35d.nq.gz
    ├── 2c10c07bfa6410dea041a6a7f292615eab5aae94.nq.gz
    ├── 2db3c69b47649b7efeaf3d1381be30f6bf0f4352.nq.gz
    ├── 2e4bb113308365afbfcd1894ffe6e5f6b9a96ca7.nq.gz
    ├── 31a65e4b0fd8ced762047c259a36fa56a03226d9.nq.gz
    ├── 335211ed6a7bcfbe6c19f8c07ed800c68377d51e.nq.gz
    ├── 338e8349a577aebbff1dd059c68c653311f960b2.nq.gz
    ├── 33b6350b02af8915f88d1fd612211e59b19deced.nq.gz
    ├── 33f509557ce7f9e48f62bda93732ae444582f02b.nq.gz
    ├── 3481553706c2d0dfbf5ee0eb87715e73f930a1d4.nq.gz
    ├── 34b317e3fab21f3db57dcdf89e252bb41fe16b1b.nq.gz
    ├── 355f6e3baf6e71f200d4b7223459f4fbdbfd550a.nq.gz
    ├── 35a3e694557c9885420f6d5c3d53de219de73f82.nq.gz
    ├── 374aeddf34ee3c46352921c37f7d1e4d4c8b7ceb.nq.gz
    ├── 3750e3417c9c0a8b40f31dabccfd1e83ed2dcd50.nq.gz
    ├── 38463d00c2d9bd3dc77e4b40a0d254a0923ef4b5.nq.gz
    ├── 39607c183ce1cd9f38734fadd7840fa1cdd8e9d4.nq.gz
    ├── 39c0e78dec3d021f19183e2c44a03b4f52c71290.nq.gz
    ├── 3c5dac727e2537fd585082d899d81dc07d9f25ea.nq.gz
    ├── 3d78e5a4a2afb42fd532d8f3c75f8541c0d16863.nq.gz
    ├── 3f0f8877fb0125ce251e0bd9a7c34b6a6ee31ba2.nq.gz
    ├── 40307968870df4f99b7044f592c73624766dacdd.nq.gz
    ├── 403eb06abf6928ef76d036c39faf954907694d0d.nq.gz
    ├── 4063b0180f09842da452d8595d0fecd4e1ac7297.nq.gz
    ├── 414de9e7fbdc76debf6323ec7035bff07a6af077.nq.gz
    ├── 4156c1a3ad85190534d13abd26f7a1c3d83490aa.nq.gz
    ├── 42067a2b618e4b4bb73edf0f2ff80d1b8c61c100.nq.gz
    ├── 42d9e0aa57910c862ddcbb83eb47cb6e1241b89a.nq.gz
    ├── 447da64bba6116f33e4c1e927a4263366065ad5d.nq.gz
    ├── 466161816fcaebe22010af02915a8aad627a6412.nq.gz
    ├── 46667954d0f36a263a9ded64c8006d79ffccbf44.nq.gz
    ├── 475dbf32f1caca400589f11bfa43f440b368116a.nq.gz
    ├── 47f9691eab9bca652aee9351650f8f0d82477d9a.nq.gz
    ├── 48176aa9b832f741325191cce64e1d2f8fa28548.nq.gz
    ├── 4afff577b0cbe7179b835018b388cd80fea95a4e.nq.gz
    ├── 4d6b34c011c43c8559e5910ddd027494010b059d.nq.gz
    ├── 4db4b03d6912c22008b7a57978514a4ca6f66b83.nq.gz
    ├── 4f48e8dc5e9c1f0a9e8a7ed9e012bd5ae7f23b7a.nq.gz
    ├── 4f7f1126280bb7d54451181f9b97e12cb0cd4095.nq.gz
    ├── 4f99fa85692c00875f9e8c67240a2c95b7fe9b47.nq.gz
    ├── 4fabee029819484d9c48b0bd4a3a6f3f3b8dc99b.nq.gz
    ├── 50096e8eb1afa7426aa45b6240e5ea8bf8670b35.nq.gz
    ├── 5101f890b7f9cad4673f1e74e54b8ba9da82d4f8.nq.gz
    ├── 516e0dd107bf260673b8e60b324707fd1fe818c9.nq.gz
    ├── 533cde25e64a960e28e63b050121305a8aebf136.nq.gz
    ├── 53eb8df86eaae1baf17dc2eeb58f5f6551fdc4bd.nq.gz
    ├── 547aaa43e25de692092b602bb308642221a6cd77.nq.gz
    ├── 547eb7fa00aea211f503c15e5b30fa14efdd3f77.nq.gz
    ├── 549fd7237331c0483f10bca8f5b86f91858183bc.nq.gz
    ├── 54f7ca8efa20dcfba285b47dad1b28fa9ec2e924.nq.gz
    ├── 560b00b659bd575280047054f45bde3f0a7d2707.nq.gz
    ├── 57aafff9ef53773799e3c0a29e920e38e6840f17.nq.gz
    ├── 57f5d0f8e76652d97c4ff96b0d3f2f27d8e9c343.nq.gz
    ├── 58a3f67a1b2cc8879d03e84198781f12921ed61a.nq.gz
    ├── 5bb619d1f6b0d8a1fe474c0420db0a6721e978c8.nq.gz
    ├── 5bca2936672d236bc6d47134d9555d6005caf804.nq.gz
    ├── 5be1ad93cbde690f05aa79713423ec261f6f6d6e.nq.gz
    ├── 5c0feca569fb555dba11ea0eb29bed22b30d259a.nq.gz
    ├── 5c1e93b44638f61f69d17050f86453d3b993ab28.nq.gz
    ├── 5c517a785ec4f2b603c3f4b7398e2967d7d9595b.nq.gz
    ├── 5dfee3bb5d7805ec1632e46c96dc1e3e9d9f7db0.nq.gz
    ├── 5e58178d792e96bd7a64971ccc583a7f17ba1c34.nq.gz
    ├── 5f95512a67e6db31304bf4b35d661387b2829ee3.nq.gz
    ├── 60217a6dfd8eb530f27ee380599e90119cc2685c.nq.gz
    ├── 6201f583bf28d88e73e0ff069c3e1ea8596c6e39.nq.gz
    ├── 62ea627866e1d441665a3a82304960761cd8a7bd.nq.gz
    ├── 65714af26f9719b211d790dd378d1344b27642d9.nq.gz
    ├── 657607c02aa10408e50fb9f246f0fbbc10b27e8a.nq.gz
    ├── 658bbde9eaa1599c7d1f88f8acb3e56bd07f81fd.nq.gz
    ├── 65c329141de6479029f62fa0a2897595199dd3cd.nq.gz
    ├── 65c67d0be0b55726689c5711500c6564c0c8b7df.nq.gz
    ├── 66af379ef802b40daf854d964ef1a01f4ec28e2c.nq.gz
    ├── 6777db5a58c44e7a33f8614a1cf86a778b7336ac.nq.gz
    ├── 683b61d8721d171d1f4621308940f80a3bb8c087.nq.gz
    ├── 69758396a636444f222dfb5a24e988a513ff8abe.nq.gz
    ├── 69d67edc0deadfeeee582842e35baa62f81e057d.nq.gz
    ├── 6c0cd611b77e71a681a341bf8edc602456a63561.nq.gz
    ├── 6c1f8fa35c64937d8f7d9ebc4a0ab4700c567e55.nq.gz
    ├── 6c494711ef1d74ce8c1543dc3c4966d60aa1c285.nq.gz
    ├── 6cb89b8bf7f9dfef1098f67b1adf39f4e5fba67f.nq.gz
    ├── 6ef8789f147ae566a3454889f87437dcdf91e0e2.nq.gz
    ├── 6fd9d8ea8882b45a819602cb92247988031e3828.nq.gz
    ├── 71e7cd587cd26d55b14c215fbf077d88f571cecc.nq.gz
    ├── 72b98aa20d0832469589b3142a9f4735d15b34e6.nq.gz
    ├── 72cf11b6015093a2a922a7e52d5a0dd6f5b0155e.nq.gz
    ├── 72dbaaf6b23e0b3fccbb90cf26901ac8a283d878.nq.gz
    ├── 73b00f3f197b1301c1b25639f3bf145f1b85514f.nq.gz
    ├── 74c97d25bce80fb149c8d7675e264b9d82ef1490.nq.gz
    ├── 74cc672e40efe55048896dee1693f9333147e3f9.nq.gz
    ├── 75669b9dbd5d332a2292f8a820b1376a6fbbbb97.nq.gz
    ├── 765b523368940a785430007009663dae71160c3f.nq.gz
    ├── 76fc4f003d1aff576812573677b9bf385add754d.nq.gz
    ├── 7820964c62df0be83674e2ce4ec2a8670d9829fd.nq.gz
    ├── 784d2c9c97a96d1aaab3cb9d09ae2735b78e4926.nq.gz
    ├── 784e27431d195e1a0f158811213c21647ce5d708.nq.gz
    ├── 792d50b2d4bb87e53699aa00072eac0e6c70f738.nq.gz
    ├── 7ad919477c89968d6f4e6a4230d4f8b8d2e68f05.nq.gz
    ├── 7b4517015065aee4c87c8ee034ae099ab9f33405.nq.gz
    ├── 7cd16441015589c11a43c5c292670a9a23cbdab8.nq.gz
    ├── 7cfa8cc629ada6aa94c3abe385b42ffdc8469cd2.nq.gz
    ├── 7db7b0403c85e2f21e68b73cf966a2d23611ecaa.nq.gz
    ├── 7df89cbe500a9a1b67add17421bd69a4d69054bd.nq.gz
    ├── 7dfedc86046e6f8247b76aabff9e58831e87bc64.nq.gz
    ├── 7eda3d8b349e7dbb9cba26eb6d01fa18078b2614.nq.gz
    ├── 7eefce14728c8eabd774df024318313795d59138.nq.gz
    ├── 7f11f0b8ce5b32506fc81ba022e7da3edbdf147d.nq.gz
    ├── 7f2f85612b819dd98d54d311118a2cd36d4eb8f6.nq.gz
    ├── 7f51bce84860e2ee0db3b2e326a0af14bdb5d1cc.nq.gz
    ├── 80c007b34329cfdaf412bd44c95bb6d62678a896.nq.gz
    ├── 8135846f8ca1ec5700c886d2a2e720655b53a5a1.nq.gz
    ├── 817aa53c31914a26d3cc3485cb0253b7139a051b.nq.gz
    ├── 82606372d9575d96b52a7cae77c19e9465eb50c3.nq.gz
    ├── 85b7878865b64691aceb3a5c4e95ec8ccf617d58.nq.gz
    ├── 87fc90de6210fe5ff0339636e453382752235852.nq.gz
    ├── 88213d5eebf0fc5637060b6e39f1ebe711715f17.nq.gz
    ├── 889cfca2006557c6f43fe4b74a71e26b030d34d1.nq.gz
    ├── 88fd4d2cd2e4ef2e906bb5372e7a75f9bb773d1a.nq.gz
    ├── 8b3cbb745c5564e753eb23cdb9a4ff14b3f0e8dd.nq.gz
    ├── 8c27f7f7a404e227a8f473ca205a353b900a092e.nq.gz
    ├── 8c3f4bf2468cf459965c5356981a4dbaf9356165.nq.gz
    ├── 8eae60a9b2c806dc4dd4d209c183eea784c8195b.nq.gz
    ├── 8f65c583eda5e85487966273aec9844b3429900c.nq.gz
    ├── 8f789f9e9da20284a037671a5af5c54d898caf15.nq.gz
    ├── 8f7a63e69d6b512b299eb388613fbdce21c44d4d.nq.gz
    ├── 8fe23d040323e1a2f64b86e8b50afa76414217b8.nq.gz
    ├── 90f5b86662c4a0493b081dc20da3e8e5850444cc.nq.gz
    ├── 90f9e95380781e8a25e8b88fe19791b2637cb67c.nq.gz
    ├── 9233f72bc77913c20b4bab91586f8669ff77d544.nq.gz
    ├── 92abf4504b63bb295237997431f4d973e32436e1.nq.gz
    ├── 92fec87dd38f18599fa024cbf1beafcbc7780a2a.nq.gz
    ├── 968ea63adcc181fb20cc1dd95bedf3c754d93503.nq.gz
    ├── 972e8c9b0ada16d57b49de2d81fef548de17ce2b.nq.gz
    ├── 97979ba469ad5fb6b554d8f7a8437f4f93b8ad82.nq.gz
    ├── 98bb4a5ec2ce59965a800943d868e8d32b668a5a.nq.gz
    ├── 990a6ffe9207dca72e70b3c4d8c4af372b16b0e1.nq.gz
    ├── 9913283be9b4f53194106aaf6af99288261ac663.nq.gz
    ├── 99b9baf07371d4ceffa2261cdc4e825b456a0502.nq.gz
    ├── 9a64191c6bc20c3a6150aac3c9096a8ceae7e7d9.nq.gz
    ├── 9d17a295bd4aa87a0f7e32a994095039d4133d75.nq.gz
    ├── 9f73571ec778291712d75211e64ebc41a586b3c6.nq.gz
    └── 9f982dda81eb8b4345e160049161a0c61b2ff4f4.nq.gz

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

[typelevel/skunk](https://github.com/typelevel/skunk)

---
*Parsed on 2026-11-10 by [repolex](https://repolex.ai)*
