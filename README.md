# Repolex Knowledge Graph of pypa/packaging

RDF knowledge graph data for [pypa/packaging](https://github.com/pypa/packaging), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download pypa/packaging
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 3b1c1d5cb8fca96a51d5622289d7784b5e9e56ce
│   │   │   └── chunk-001.nq.gz
│   │   ├── 3b77a26f5a27473ad3b08194d773f325d018a2d0
│   │   │   └── chunk-001.nq.gz
│   │   ├── 7a983f7f0068669ead9d4f7571be24d6c0d83eb9
│   │   │   └── chunk-001.nq.gz
│   │   ├── 85442b8032cb7bae72866dfd7782234a98dd2fb7
│   │   │   └── chunk-001.nq.gz
│   │   ├── d4eefdccf992e963c48011875301d93df6a7f2cc
│   │   │   └── chunk-001.nq.gz
│   │   ├── d8e3b31b734926ebbcaff654279f6855a73e052f
│   │   │   └── chunk-001.nq.gz
│   │   ├── f0c324ec2222dae2c4eea0fc6e7c659a762eb152
│   │   │   └── chunk-001.nq.gz
│   │   └── f58537628042c7f29780b9d33f31597e7fc9d664
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 3b1c1d5cb8fca96a51d5622289d7784b5e9e56ce.nq.gz
│   │   ├── 3b77a26f5a27473ad3b08194d773f325d018a2d0.nq.gz
│   │   ├── 7a983f7f0068669ead9d4f7571be24d6c0d83eb9.nq.gz
│   │   ├── 85442b8032cb7bae72866dfd7782234a98dd2fb7.nq.gz
│   │   ├── d4eefdccf992e963c48011875301d93df6a7f2cc.nq.gz
│   │   ├── d8e3b31b734926ebbcaff654279f6855a73e052f.nq.gz
│   │   ├── f0c324ec2222dae2c4eea0fc6e7c659a762eb152.nq.gz
│   │   └── f58537628042c7f29780b9d33f31597e7fc9d664.nq.gz
│   └── repolex
│       ├── 3b1c1d5cb8fca96a51d5622289d7784b5e9e56ce
│       │   └── chunk-001.nq.gz
│       ├── 3b77a26f5a27473ad3b08194d773f325d018a2d0
│       │   └── chunk-001.nq.gz
│       ├── 7a983f7f0068669ead9d4f7571be24d6c0d83eb9
│       │   └── chunk-001.nq.gz
│       ├── 85442b8032cb7bae72866dfd7782234a98dd2fb7
│       │   └── chunk-001.nq.gz
│       ├── d4eefdccf992e963c48011875301d93df6a7f2cc
│       │   └── chunk-001.nq.gz
│       ├── d8e3b31b734926ebbcaff654279f6855a73e052f
│       │   └── chunk-001.nq.gz
│       ├── f0c324ec2222dae2c4eea0fc6e7c659a762eb152
│       │   └── chunk-001.nq.gz
│       └── f58537628042c7f29780b9d33f31597e7fc9d664
│           └── chunk-001.nq.gz
└── blob
    ├── 0007c0aa64aeae24c7e0ca90790a25ba51dbf7d6.nq.gz
    ├── 012acb130f17971e20b103111d8dd14db029c109.nq.gz
    ├── 03192c1777420cc1ffda8ff5f57dcc9d1b4587e1.nq.gz
    ├── 04579c4f2742cb15638aa390be9b8e2f0d5ca82e.nq.gz
    ├── 05e554a64c244d96c21dd2d8ce06f0060b65cac9.nq.gz
    ├── 068b2e6999fb8e16ab69a5f3a0062766ac1a748f.nq.gz
    ├── 0888fb6967ef3c3055ccbc6d7f7609984d842cec.nq.gz
    ├── 08a2a46d8c0fe5f579ebd18ebcd0fc002f40c685.nq.gz
    ├── 08f651fbd8dae57028d57721f7e9983053771a1e.nq.gz
    ├── 0cad38ae541f129496681f96c88e02312eae98e6.nq.gz
    ├── 0e79e8a882be74fe76c80ccf49a9cd68fb636fd4.nq.gz
    ├── 11a6750fe1f4fae6512e17c05fa2795b8e6fab34.nq.gz
    ├── 11bfa22b2f29cd6cfa27b01f5bf690ab3dbf15fe.nq.gz
    ├── 1206c462d4fcaa670a816e201bb88b27dfc9cf88.nq.gz
    ├── 12db2105c7b68d355c4ca3c5d5c617f83eebc829.nq.gz
    ├── 1480b2aa767c4f80fbbcc76b39a661a9bf4b62fc.nq.gz
    ├── 184a794c35d6d206289ab422b78528886a5a7818.nq.gz
    ├── 186199a5853b2cf877bb6ec2bf3378a26697ac05.nq.gz
    ├── 1a6a9a262085e722edc724028f024b7d5adf4248.nq.gz
    ├── 1d6853739aaaada8868ef581f8768366a77a22a7.nq.gz
    ├── 1dfd23fa3c0eb944358b1eee0b7c241c79da3cd3.nq.gz
    ├── 1e3d9575f8b977b5f212dc85e864ca9bfad7e2c6.nq.gz
    ├── 210ff0e486e3863421cead6dcd8713bbb247019a.nq.gz
    ├── 21695a74b5107c96ba4bb2cbca6b7f259dacd330.nq.gz
    ├── 225e2eee01238571c50595eb104e0b70d5f503c4.nq.gz
    ├── 23450953df74eccd9c13cd2a955ce09d1f968565.nq.gz
    ├── 2390d8c809eea1d6587357cdad25ed4af134db32.nq.gz
    ├── 253f6b1b7ebd711fdc6bbbab3b56897061bab515.nq.gz
    ├── 25f4282cc29cb03d7be881f03dee841d7dbc215a.nq.gz
    ├── 2659b8ee25768ba38932177ae91d4f44a482917a.nq.gz
    ├── 26afe92faee70e4b4b09305039fb4a1530ba7ea2.nq.gz
    ├── 274c0971985e9c507840d2e8e799fb5a6777984b.nq.gz
    ├── 299a951cf11fd09eede8df0e3e95a77dfeea4a64.nq.gz
    ├── 2adf336e5a09e67d7146d3b0c48d88f63d1d8da8.nq.gz
    ├── 2bbe495f4694e665ea39d9d14dfec048df1e0729.nq.gz
    ├── 2d015bab5958fd9767cf5c9e449f2fa33292c962.nq.gz
    ├── 2f269edc18a502c160409ac69cb41b8623f82360.nq.gz
    ├── 2fa75f7abb715eb7cfbd871919c56035b2bae35a.nq.gz
    ├── 3079be69bf880f47e64dbf62993f0e54754b7315.nq.gz
    ├── 31834a394d5577d6ecbf7dfb1783799148e7c6fa.nq.gz
    ├── 3186ed53ea9f4016d4b56263bafd2ca3f0fb0152.nq.gz
    ├── 335b275fa7575b0a7c525a713fbe0252ad2d956f.nq.gz
    ├── 36e0128465be01cf5722f83a05e504299fe56d74.nq.gz
    ├── 378aef1ad6a5081e5814dd6b9a3f0efcabc41386.nq.gz
    ├── 39279f9663ff1235b561905bed1c4332c084db96.nq.gz
    ├── 3a2f63d59d7cd06ffe83f7e1e9e3472d33a9d964.nq.gz
    ├── 3ad0ace732dae2ea9ad688eb0f7f8da86f0ca196.nq.gz
    ├── 3bd8602d36c53374f1f10a0716d28fdc64e2d3ac.nq.gz
    ├── 3d3102391183a7772abd3bdae254418773939bf8.nq.gz
    ├── 3d666e88b535a7fac7fe171400988b1229a41967.nq.gz
    ├── 3f2e0d35949a20b2105d25fd197e2851b483c91a.nq.gz
    ├── 42ce7b75c92fb01a3f6ed17eea363f756b7da582.nq.gz
    ├── 444eb7967a8c3e00e5fd3936b5758b4dedb1301b.nq.gz
    ├── 4480901820077e4d7997d7558aa4118dee0aa41e.nq.gz
    ├── 450f6f9f8a0d43a33f48589194f6d7f7d0edf8e9.nq.gz
    ├── 45285b3899727f2a17b09d5992a5001146483c11.nq.gz
    ├── 454ba21c8f42038b78cd8518ac0e75237f0ab068.nq.gz
    ├── 46066ad2ded1af7c68a4f5d4d3ccc66933b89f43.nq.gz
    ├── 46bc2613086732e34b8863b7ea562ffb6918865b.nq.gz
    ├── 491b3e03625936f6a7168beb627e7ff96c18aef4.nq.gz
    ├── 497b0645217512ae2ba8ff61341fd2bbfa3648cd.nq.gz
    ├── 4a5a5f0a1c22946f057556fee5054a75b487371d.nq.gz
    ├── 4e01206a1446804e6722e74c163d63e6606c873d.nq.gz
    ├── 4e068c9567def3564f238a76fe7ab46b569f33e5.nq.gz
    ├── 4e5c0396b94d8f3c6b5ef6fcd1cc67317edd3e85.nq.gz
    ├── 4e8116a79ca80d60657542a23b4bbcbc3c518eaf.nq.gz
    ├── 4f6aca04341fb524fafe006abddaa61d3c65d28c.nq.gz
    ├── 4f97e8e5e3687f5d600e0bc5fe72fc3ad918042c.nq.gz
    ├── 5071561560ca52c6a1b000ca59a44558b2f2d907.nq.gz
    ├── 50cfb9566f509cbc94639950d3d8146c52fcf99f.nq.gz
    ├── 5106427db980884105fcefc7800c485c6b8a581f.nq.gz
    ├── 52964aec70def27c8a75f7164dec43111aafc012.nq.gz
    ├── 52de3485edf9ce8e337b20e01f6fba7bba1298cc.nq.gz
    ├── 5412a08349ed53c868988ba2139660f26d15adc5.nq.gz
    ├── 554059fc8f6cf09b4593e3ec5bda2d77615cb5a3.nq.gz
    ├── 565b0521d0c2cdbfe493d19765b04d5c119fa7eb.nq.gz
    ├── 5677c0e89bd9c84b10b0239a0c26a799d3e646b8.nq.gz
    ├── 569156d6ca47719f49b753a4781a86a924de173b.nq.gz
    ├── 56e38f9220ee796061315821764dd4a7fe932f3c.nq.gz
    ├── 59996e28c27516a7342a0f0b8052e0205455b65a.nq.gz
    ├── 59db7412d509294f913ce0bd5886d14d853f0369.nq.gz
    ├── 5a9ca9e65aaf0cfbca5ca694301f4be92e6bd789.nq.gz
    ├── 5d26b0d1ae2d21b77e24b692d5a7e1fd01296edc.nq.gz
    ├── 5d85084a96c13180508e4d904c5ab4d8c47a4cf0.nq.gz
    ├── 5e4db59a86129582279a2c5a32b946a51d68a456.nq.gz
    ├── 5e591c3ec5dde987c61ed21c0d7fa52582dc1b34.nq.gz
    ├── 5e9899fc07609f37f5251f0da5a5af97d4d79234.nq.gz
    ├── 5ec89b2440f06dc5cefc282d6170d9deb476a5be.nq.gz
    ├── 5ef27c897a4df35a2a6923b608a5e04a0a38b9ee.nq.gz
    ├── 5faab9bd0dcf28847960162b2b4f13a8a556ef20.nq.gz
    ├── 60c4bec6ca251d481825ef1f99fbafdc8edac914.nq.gz
    ├── 61339a6fcc1b82803136f3bf980e0c8f574b2220.nq.gz
    ├── 635b806c12f759f5c4fdac108e386325e605254c.nq.gz
    ├── 652a2f927eab38192f3e9c10ddb7a7e746ffb658.nq.gz
    ├── 661f6730d23e93515d368482935cad58f7e2120f.nq.gz
    ├── 6667d2990858447607f9fe21057a6e230a0caa8d.nq.gz
    ├── 678f1adb973c2dda7f8e01a5006caacdf3fc4699.nq.gz
    ├── 684df75457cb82d3683dc99ff52c5bf911f3341b.nq.gz
    ├── 68dfb8014c11482de9ee5e6caa9e5b533801265f.nq.gz
    ├── 6b46ddc66d0f2d85e4f55a133a46505d04f56441.nq.gz
    ├── 6cdbe1909b397b28f05a7e84ba8ea0f69ae5e77d.nq.gz
    ├── 6dacfd1b16db596433ad2855751c950777187c4f.nq.gz
    ├── 6f62d44e4ef733c0e713afcd2371fed7f2b3de67.nq.gz
    ├── 6f7f9e6289dabe5bbc45cc8f01ac2449da890d02.nq.gz
    ├── 6fb19b30bb53c18f38a9ef02dd7c4478670fb962.nq.gz
    ├── 721f411cfc44f6d24c13112e4246b5ad776a5e0b.nq.gz
    ├── 732c592460db4f39319b9f7409bc34d361165948.nq.gz
    ├── 735fb8cdec219d287b18ab54af3999a48635c656.nq.gz
    ├── 7362d62fab7b4a88eeb7c5a793d9c90c2109d64b.nq.gz
    ├── 767f0885fd2f4915bcbb9568f1060be401c59467.nq.gz
    ├── 775b51fd7ea90df396a538ee491c693a8fb62da3.nq.gz
    ├── 795364586420d27213fe45d7500f5986657dc27f.nq.gz
    ├── 7a5afc33b0a2401cf509bb6a8d1143d5230324d9.nq.gz
    ├── 7ac7bb69a5325a6d9866885f2266539e8413a3c9.nq.gz
    ├── 7f1bee9cb3284cf6c093ac7b6b68f5055662b82d.nq.gz
    ├── 8053e06ac02e74d721f9706f55a5393dedba29d5.nq.gz
    ├── 80d3f14ee9119da8960869fdfaed0ee2f2b7f8eb.nq.gz
    ├── 83e8aa6693fdff33e41c77d0ad4c8320cc7fba74.nq.gz
    ├── 84e5bec868a123b2535e2a35ef16d2a0c5c26e35.nq.gz
    ├── 8522f59c4f2d0039c1a02ea9aef66fe017dbdb20.nq.gz
    ├── 855fe9128a9c359fad75abc561b22d0b91b1a016.nq.gz
    ├── 86419df9d7087f3f8b6d0096f32a52c24b05e7c1.nq.gz
    ├── 8648dbc8783b075a32cfcb957f08b17c058ec65a.nq.gz
    ├── 87c86eefdadc9918168528ae023370e31171198c.nq.gz
    ├── 883da23c96d1ef8cf28a0dc02a4e6c1c7d6d013a.nq.gz
    ├── 89d041605c006e326a67f399a58a1fec8eb24acf.nq.gz
    ├── 89f1926137dd2d2a6bd63616bf5b9f722fc8d584.nq.gz
    ├── 8a1b1ae1326aa7466d7b885ec7ef33ea315b844a.nq.gz
    ├── 8b98fca7233be6dd9324cd2b6d71b6a8ac91a6cb.nq.gz
    ├── 8c7b09949f2b07beeeda1e201ef5e26bfa525ef9.nq.gz
    ├── 8dc94e9f0a32ad07aac91dc76f918d856fbea68b.nq.gz
    ├── 8ec8c559b5c188c4fa09c4d7915c382df14c411e.nq.gz
    ├── 8f81945e861203bbf6a1626c69586c5070761e00.nq.gz
    ├── 90a6465f9682c886363eea5327dac64bf623a6ff.nq.gz
    ├── 9107ecfa4cd3fe78d704bce1a6e056c24aa7e210.nq.gz
    ├── 9208558f4258c405b9d6a26d3191f86c0144d8c3.nq.gz
    ├── 931ca206825700e7c195bea88f7410737fbbf455.nq.gz
    ├── 934d9f6f8496111775a490baf5c38d7965caf3fb.nq.gz
    ├── 95f55762e86f08af76aaa95f5cd147d4517c6d66.nq.gz
    ├── 96179e40911fd40f1159ab85fa656459937283cc.nq.gz
    ├── 965ab3003af97dc37d31878feeff574b59dae17b.nq.gz
    ├── 96da8465d76463b27e86f41c40bdc29226eb1617.nq.gz
    ├── 9768fd06d0da25abe514ff21702454b3e48ac822.nq.gz
    ├── 9821fc254bf5b47d3ba801294299706376ac1f43.nq.gz
    ├── 985fd1809529412390ab414494c2e6b4bb13f34f.nq.gz
    ├── 98bcad28e5fc3d9af6a9f42096fd99f7bd99e62b.nq.gz
    ├── 9907b9c94ef7ea0eedbc4d11121887983449ad6f.nq.gz
    ├── 9ba41d835795ff4f86f6530f20f9bca976e8c6f1.nq.gz
    ├── 9c94ae315dcb83c43219175d8519f68bedb79b2f.nq.gz
    ├── 9d683b40247cd7bd8d91519ae41c1bacdea61a28.nq.gz
    ├── 9fa0fb17a3b94da69af67088d2948e3238ea3c72.nq.gz
    ├── a277af28220b6dbe4599471104d1c7a2bd1e1288.nq.gz
    ├── a2f92b303b0e98a28a9be666b1cbc7acac429380.nq.gz
    ├── a564f15246ad65038029f8fefb48621fa64a3abd.nq.gz
    ├── a5f0ba47f2e691048557a6da01d9a5d804fd5149.nq.gz
    ├── a713eac823e12a6b1dd9f089acb82f5223f59eb9.nq.gz
    ├── a779538ebd712eaa23677f39b290634da979c53d.nq.gz
    ├── a79b860e5e89008f67d80034ab2c459162d0656d.nq.gz
    ├── a8cc8d71e2d69f6904c26f4cc45774187bd393eb.nq.gz
    ├── a95ae18b4f9d331091bc5ac036985c7fb1f96cd3.nq.gz
    ├── acd2b94c7f46c2ba174c16865636d9433c4a70a0.nq.gz
    ├── ad62505f3ff66c3d4da07ce1f2a50d9f10bc1bdd.nq.gz
    ├── ad88b146d2a2754659b8f77bf10eec721586bc86.nq.gz
    ├── afc671bbcacd852e0a9614f57377858855f420e7.nq.gz
    ├── b0896e1f764bb6dd4bdaed053e9c60b4eebbb477.nq.gz
    ├── b20b071ec7d995dd8e6d1a4fbe9fbf3624d22f51.nq.gz
    ├── b30054603fa5e61fde81180b399ca7362ea561f1.nq.gz
    ├── b30926af8bf4f47efe98eea44d5ded4cb6f7e07d.nq.gz
    ├── b35ec45cf0b201c4086b32217951cd0a517c29ca.nq.gz
    ├── b4da79ee09a873846eb9278dc7affd1b319b8c72.nq.gz
    ├── b509336233c2fafe4185a49da5909c8bbb38dfd7.nq.gz
    ├── b5a35be92af25523637c1402e42a59d97b02a35a.nq.gz
    ├── b811bb4f208d4055cc40fa9972ba9aa17141c3b5.nq.gz
    ├── ba3fa462bf16f25165b5165966b4fdf3dfa05279.nq.gz
    ├── bdc43a7e98d87dba0c2069bfb4554f71d228cad4.nq.gz
    └── bf57ee1d9e1282ddd4ae914375d593eac402ff26.nq.gz

22 directories, 200 files
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

## Source repository

[pypa/packaging](https://github.com/pypa/packaging)

---
*Parsed on 2026-09-19 by [repolex](https://repolex.ai)*
