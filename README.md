# Repolex Knowledge Graph of parallel-web/parallel-sdk-python

RDF knowledge graph data for [parallel-web/parallel-sdk-python](https://github.com/parallel-web/parallel-sdk-python), parsed by [repolex](https://repolex.ai).

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
rlex download parallel-web/parallel-sdk-python
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── ee81aa44906d6671dde6a12240968c128b3f1d34
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── ee81aa44906d6671dde6a12240968c128b3f1d34
│           └── chunk-001.nq.gz
└── blob
    ├── 000560281e0d0b78573fd6bbc595714f41d5301f.nq.gz
    ├── 02f9ea761102d2ce5b15a6af7dba17593471bbfe.nq.gz
    ├── 0320bedb4228b902506cfa0d44c43e0b1b392e43.nq.gz
    ├── 03343720f4b49d94b530fc39d8b5e7a8aa18ff4d.nq.gz
    ├── 03544471f0edc62676e751524f05736984fe5ca4.nq.gz
    ├── 03b9ef9fccedca7f2afe8c5bc37360dea2c8297b.nq.gz
    ├── 03e848ef52029db6749289c40a7367d67949b0b7.nq.gz
    ├── 041f47a485dd4573268e82800fdd403b055b1ca4.nq.gz
    ├── 063ee4c26c1258abea24596ce1e610b7cd2ebe20.nq.gz
    ├── 09862884b2987e7822e1cbc4bcdeb5cb28a9639d.nq.gz
    ├── 0c4af4429bab62959be95c421d80c8437db17c04.nq.gz
    ├── 0c7802328d0cd5d830bb224fbb9b548765a9dd18.nq.gz
    ├── 0cf2bd2fd9d04040ba557f3f6658e6c4134d26d4.nq.gz
    ├── 0f239a33c6df82d00988a48777a64ab13449b72f.nq.gz
    ├── 0f396259ab817d8322c6010829a2f2f464b088a2.nq.gz
    ├── 0f57046872c6f2a02597bdb90be0f09ac20fb15e.nq.gz
    ├── 10b2e8f9f8b53d3aa490c80fd5ff868b4a761954.nq.gz
    ├── 112e0fb1420aa35af858354347dd589944815559.nq.gz
    ├── 12db0ec9eec572009ab3f1ce31e7f1f100ae4ab9.nq.gz
    ├── 1388074ab6ef3968f5c1a3635c63972e1dbd65bf.nq.gz
    ├── 1488340b980e8ba01dfaac0b744d9b991351f851.nq.gz
    ├── 14ebe29214b51b8108569017ea3bc8b9a6f023dd.nq.gz
    ├── 14f83c8008364b213b2136e95af6fb905db3a91b.nq.gz
    ├── 15692f8a8f94f7ef79ecc32a5388492f6b3adafc.nq.gz
    ├── 17470204da9826f1621158a3b86be8d343ccf730.nq.gz
    ├── 187abb6b760ead62b7106e26cc326aef8517736d.nq.gz
    ├── 193109f3ad2b3c00e59ad3f41ad32d9f704f5f23.nq.gz
    ├── 1a9d1026cd427f75d2c65de601e39f529ee3cab4.nq.gz
    ├── 1ab16e699786c51ea26941454c19dc0c9cdc4b29.nq.gz
    ├── 1ecb266d443cec72c8683a377152247cd975f3ba.nq.gz
    ├── 226474b2f641dbf69bbc7cc7f4e14275323e63f1.nq.gz
    ├── 24533940a844267d12b643218921f909b375eff8.nq.gz
    ├── 248de45b14d8e838645e99b33ece53fe092a009d.nq.gz
    ├── 25b573de793785e16ee40c3075f389adddddc2f5.nq.gz
    ├── 26d16a90d2406988574d13f8cf01b37be32414ad.nq.gz
    ├── 2a7d4a11a82044a3852cb21fc362ab65c1465c72.nq.gz
    ├── 2aa9d9e788a3721b1dcc9af9d0dbf203509efd29.nq.gz
    ├── 2b08e7ba791510388b80075835df8ee57539afdc.nq.gz
    ├── 2b5cc73d5add0f331ee59034582ca4a3ec4e30a3.nq.gz
    ├── 2c70b299ce498586ae71933a8e7fc8bc40953489.nq.gz
    ├── 300b7fb6f53d54b80167b2f618388ec29194ec39.nq.gz
    ├── 3122909499c2e83167b360d175e3a0865456bf03.nq.gz
    ├── 31ce57e3ec8a5e88dba9fd6c6b81a342d74f61d5.nq.gz
    ├── 335ad6977265ddee0c0703ebd97585310bbbbf71.nq.gz
    ├── 3379cb65bfcf087fd673e95dbdb9fd152c57b826.nq.gz
    ├── 340c91a6d091ae9864ebf0c52c270c5f6b585bb5.nq.gz
    ├── 3772f166507f2ee2249754309f02bc7137238db1.nq.gz
    ├── 39cb8360fa6c1f75dbb4a6d44223c50f3ce96a5b.nq.gz
    ├── 3a507d9b19d7bddc2a57ecd227f79429a946e816.nq.gz
    ├── 3d1284fedd95c7819b7fdcc639b558ccbe6f67bf.nq.gz
    ├── 3d8da813ce85a759248541bba7824c2c8a370fc9.nq.gz
    ├── 3e3f4656d4b5a1335df77c11d79d534ad6f65314.nq.gz
    ├── 3ededc942594690b3f854dd10ce662d2c160508a.nq.gz
    ├── 3f967746499c0884ea3f92cfd4c4f24981401172.nq.gz
    ├── 402e64ecc6c85f20cbc8212ece3d039dfb63d346.nq.gz
    ├── 4127c19c62b7cac54723e7493864b6925c900dde.nq.gz
    ├── 418537103a5e31882963f2593f9f4134ba2179e6.nq.gz
    ├── 43077b246094f0b2ea3a54995d76fe1d320945a1.nq.gz
    ├── 435e52a5703816a14d0f75f861a7fb6f9def4fc6.nq.gz
    ├── 43d6622eef72d7f35c086e0b57198a565222fa1f.nq.gz
    ├── 44aba97e2faf11c4e106023f26ad77bdb3805314.nq.gz
    ├── 44e8fd39abae2cd60d7b269bd686b508335553e0.nq.gz
    ├── 45aaafbebab63a9aeeb295dd651352614983af32.nq.gz
    ├── 46c23ffa614389171506aacaa0ba6f11ddd2c543.nq.gz
    ├── 471d11276bc6fcfff5ae6057af3f735e1b4f1f5e.nq.gz
    ├── 48371cae1ebd7e29160426fbde042a5d887ea063.nq.gz
    ├── 48bfaababfae2db6c322b5602eded4c47553bcf8.nq.gz
    ├── 492ca37bb07dadfd96cabc7a76e2c647833082b1.nq.gz
    ├── 4a0bce9535e65b21eb7a0ecc6e37bdf5c1951f34.nq.gz
    ├── 4d0146c6e8b8bd58eb98b335130d299131fbfc55.nq.gz
    ├── 4d6e1e4cbca09d0aa6e892fbe52b0f7aed3ba947.nq.gz
    ├── 4e2001101fe444c39c01a73b0168c5ed58351932.nq.gz
    ├── 4ed9071599511016698d0e45b4672bab63cd07a4.nq.gz
    ├── 4fc525076b7adf558f4306896083cf4e536c27e4.nq.gz
    ├── 50054addfc106d231ec426676ca624b3e9618752.nq.gz
    ├── 5083166bf3c71850cce9861a72657dd4117e5ed0.nq.gz
    ├── 5097ea0efb311d33d7c7b9ee3775db6c00142553.nq.gz
    ├── 5207549207e533479a7266b1b1a5bbdffe93a2ba.nq.gz
    ├── 53bca7ff2aa7e73b6353d977a14c0d3b167f7135.nq.gz
    ├── 53fa3113e4a9b7cfa73bccb0a1b036db22f5ff4a.nq.gz
    ├── 54a4825e38e3e00157a918d3d787d4e6d650f9dc.nq.gz
    ├── 55f7a75872bbb928704e5cad14e1d00b67ba4c78.nq.gz
    ├── 56279e761c84c2e73d76b6051ac32baa5c8ac632.nq.gz
    ├── 586329f630279bafbbe96de2025fb957e61b719d.nq.gz
    ├── 5bc444743181bf357656066f46c0508323a0031d.nq.gz
    ├── 5da7e20ab543eeebb89d6107ef62d0881d766685.nq.gz
    ├── 5deb42d644341e5033c27a2b2acc2d369b066311.nq.gz
    ├── 5e022bd5f6c3ce02bc92d0638b93e172d7d25326.nq.gz
    ├── 5e2c99fdbefc565576f8c5f37b0b0a66d60f2015.nq.gz
    ├── 5f686439cee2a6347d67b0c3f1c5d5c3f1be81c2.nq.gz
    ├── 60584214af7a92e0f32e3fa713c9199f52ad6f72.nq.gz
    ├── 6178b6e2467eb5b3ecc232f313663126fb02582b.nq.gz
    ├── 61b6cde5bb26395d993fb46c277c5d84b9c6b692.nq.gz
    ├── 630f85b04e635d81928b8f403761abc89c868325.nq.gz
    ├── 63dd30c113d07672c375dba489afbfd5f11ddb1b.nq.gz
    ├── 63ef8f52d7a5382a0a16fbaba79a5fb4c3e1af68.nq.gz
    ├── 667ec2d7af06d94ca031b1e53bfd1d1dfd4bbe5e.nq.gz
    ├── 67964b3823527caade9ec0eaa53ccdb69577bfb2.nq.gz
    ├── 6c3a98229ffb0cc4b18a5cbd9bbfa6afcafec81d.nq.gz
    ├── 6cdccc2f119d1f2faf3a5ada95841473cb608b19.nq.gz
    ├── 6def62a367721efe244812117833ade024e0868e.nq.gz
    ├── 6f3cc747eb64beb9ab136f5b04d755fd7055ca6f.nq.gz
    ├── 6fea0aab784e21f851dbc7c13c623c30ff2f464b.nq.gz
    ├── 70dc9d1a01e6b91be811cd02cd8f2eca593ad032.nq.gz
    ├── 717d11608285cf5a5728a411c095273bd296bad8.nq.gz
    ├── 72ae6c1dd8296ff83952bf3288533781df480324.nq.gz
    ├── 7301d103ad12cbb2dce29a0e5f6a41742692405c.nq.gz
    ├── 75812f6181a6da9409e5aa21329aafed7c44f73a.nq.gz
    ├── 76da9e08500ca5c6c31ed8b7f7a823164c5d139f.nq.gz
    ├── 776ebb7dd0571e0961305fee5e4b4bf0e3034d4f.nq.gz
    ├── 79212b5d9e19f234ad5af946831d23fd16b47061.nq.gz
    ├── 798077e18c0ac2887f40e82a2e3aa4a0a0be174e.nq.gz
    ├── 7c3b336ed728fd1a046c41629e2e594a3a4baa04.nq.gz
    ├── 7c4ba25bfce7e7b1e6d4ece0a3c4302d559eea5b.nq.gz
    ├── 7cb9d9e668c5a5efb1b12e72d115276298a70ec1.nq.gz
    ├── 7dd0cf7936654c44cc524237b9126b7e5218688f.nq.gz
    ├── 800780fae02610b1c39a09e573b1626c80540f9c.nq.gz
    ├── 8079e0ea2959224accd4b5dc7d449d5d33b6238e.nq.gz
    ├── 80a23068eda66262104fb514b011d4e87aa14781.nq.gz
    ├── 80a3deaab44a53202188349f049ccdd51c17a2f7.nq.gz
    ├── 826054e9248cc9c66c7743ac7483c0fa1da683c3.nq.gz
    ├── 8550546424e6ab1357be8af7967ce46fa2326f01.nq.gz
    ├── 85a5bc343a46324452a941f870e6efe88f622610.nq.gz
    ├── 86926bd848c23392283e6706a948d10d56b3c93a.nq.gz
    ├── 86f50cc6ff787f306e0d85d079ce5393903625bb.nq.gz
    ├── 879924d2c4337961a859373c315f7a0591a0099e.nq.gz
    ├── 89aa712ac4c923b6e3c4e72b8c8a764de282f585.nq.gz
    ├── 8a789770ffb1e0f016b90f7088a356c6bf92f753.nq.gz
    ├── 8ad9c725c5c4e5ed14a208f259444d2673ae59ce.nq.gz
    ├── 8c5ab26027e96a353edcae5b36e053dd183eb198.nq.gz
    ├── 8cb956825c6af1e906c89bfea8100ea098b49d31.nq.gz
    ├── 8f01b2cb8b9ac1d4d475f617f0227b7e29694832.nq.gz
    ├── 90a667dd101767ed5c4c36bb19d7acd90c4a6706.nq.gz
    ├── 910ea59502389c8295ad096dc8a3c19afd8c0261.nq.gz
    ├── 91bddfb473b5011e86af48f2fbe37f8bbbcf2c0d.nq.gz
    ├── 932625da65a3229487f68b1c180469ffb167d226.nq.gz
    ├── 95ab6d28aba0860e54f4846c9e72e989dd5f5579.nq.gz
    ├── 9680e456b17b9e6e6da58931a553d264f4922790.nq.gz
    ├── 980801818c9d302d9b051730a5ffc6fb241db581.nq.gz
    ├── 9b55bec502a99e43081176e465f31cc16356621f.nq.gz
    ├── 9c62c5d52e36d6807fe7e9fb951e8ac1c4ddffb1.nq.gz
    ├── 9cd4f7118c35806be8160d499e5d94bd97c504ed.nq.gz
    ├── 9dbb5cdb119ca290cb2850a8efc9f66694df18b4.nq.gz
    ├── a020904ee641c511d9fc898579c29d5ccde0b92a.nq.gz
    ├── a46ed492c12e5f7ee16d67884d32a184ebb10a32.nq.gz
    ├── a4f52afc31dc2ca80e65f2c1dfaa5a3bc61e306b.nq.gz
    ├── a50a4a494c3cd2fc86d68fa6e4692ffcb8175549.nq.gz
    ├── a6e6ad624d959a0a841a04d82b141599b3a59faa.nq.gz
    ├── aad18b58b93aa970c5c208bc058f2bd7e0585d14.nq.gz
    ├── abfedfd44682d405d1ac39622a049ae1b9da9cc8.nq.gz
    ├── ad17881f4e033a64f2c09f38f5c7815432135f13.nq.gz
    ├── aec2a7362ba46324b852d425030f3407b98c4479.nq.gz
    ├── af5626b4a114abcb82d63db7c8082c3c4756e51b.nq.gz
    ├── b24838db7e186e4b786e3e655a762434874e3c5f.nq.gz
    ├── b283b92bcf7d8efdde28626f43b571e566a6589a.nq.gz
    ├── b40fa65c0effe1162159eecaaecb34b36204bb0b.nq.gz
    ├── b5596a0008e7ddd5444f48b6d7e4048a08653e8a.nq.gz
    ├── b6b1ef79696bbc52b8f88a8f7f3f5f6df598ec14.nq.gz
    ├── b845b0f4c968eec68dcc4259e37bcd53dc9a8007.nq.gz
    ├── bbee625651d4b51e80d265099d8feb27f9a8c7f6.nq.gz
    ├── bd3c02fb50f7100c344488e57e72880e00abb510.nq.gz
    ├── be2e2974b66e51122da507a9768d3413eb201be1.nq.gz
    ├── be76e8198ab21be6300bdadf7f31fcaef6d2b4ea.nq.gz
    ├── bf85c0ed327e4899a1dc635e3d3a74f203df62a0.nq.gz
    ├── c0364ffa2d4cb375884e63439faaa1c8eaf7e78f.nq.gz
    ├── c213263b951bf5207eec32070e4d664b5d519c5b.nq.gz
    ├── c3b9e4f306c5c2368996442d6faab9a56ac6d280.nq.gz
    ├── c66e0476ad5720ff0340fc1ba67d3061d76901a3.nq.gz
    ├── c7a4d05dc5784dfb70b29a33df6337412bf8f90f.nq.gz
    ├── c86281578c8de764b6979410039c410f6579eeef.nq.gz
    ├── c8937905a439d8a9b9677c4c41aff123ee50f77b.nq.gz
    ├── c8a7b099f0051bbe0f43ef76acc7d94a7a64b660.nq.gz
    ├── c8deda2a0d9472dd6db31d7b981c424b3970fec6.nq.gz
    ├── ca13b80c111f6a6b1eecba4160cc54d9219433b8.nq.gz
    ├── cb824e0094a7eaeac06f5d39c8bfa461f5c53840.nq.gz
    ├── cb957e51e7de440d84ba6dd873a9696e45dc9d33.nq.gz
    ├── cd24b9f2e547e37dee9644bc099d130c26306881.nq.gz
    ├── ce09c2e91251dc7b9ed0dc189658207ca78e8531.nq.gz
    ├── cf1f1b1261e02b8ea950215dd4d550d3abdd6637.nq.gz
    ├── cf9f5f376a0f999d69f7b0f7e3fb84a0c37167eb.nq.gz
    ├── d0d3ad74b00c82e053841b677ae1d21faac291a6.nq.gz
    ├── d328532d277ba57cc9d270754d20b1631f73abd1.nq.gz
    ├── d333015610e7d94492c74d0143171ed10c4384be.nq.gz
    ├── d6c0dfdc697a5d7796aaf368b773ada08b8a56a1.nq.gz
    ├── d821691fd4871818d525d76439e2c33b55596a59.nq.gz
    ├── d8c73e937aeda0534b48d146e2816d5000f0680b.nq.gz
    ├── d90226ec0899bad72b5c8723c9dd8da075f4ac38.nq.gz
    ├── db63a6cd947ddf7608e232b2465afaba3134d1b9.nq.gz
    ├── dbd95dacfa896509d2033be932c16abafefc3cd2.nq.gz
    ├── df288f3fd779680c7daedfa097a9823ab9809bc8.nq.gz
    ├── e02243be982f0e9ff35a0d8483b08b6d3321a6b4.nq.gz
    ├── e0ed7bfd2bb5d6e897217068030418d46752774b.nq.gz
    ├── e2599bb450248911a32c4a72fdfeddc710fa9ec7.nq.gz
    ├── e324ad8665501a73e86eb548f6f21e1d21cf91ba.nq.gz
    ├── e37f76a912430155f8eb2fe022226641790dbb98.nq.gz
    ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
    ├── e6c72198fa68abc5b950f59126d9c5e692523b53.nq.gz
    └── e9856ecef509bada3979675a69a2c9b5fade33ed.nq.gz

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

[parallel-web/parallel-sdk-python](https://github.com/parallel-web/parallel-sdk-python)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
