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
│   │   ├── 2e4a904fa07cd57ca48dd29b57bafd3c999ce9a4
│   │   │   └── chunk-001.nq.gz
│   │   ├── 3b1c1d5cb8fca96a51d5622289d7784b5e9e56ce
│   │   │   └── chunk-001.nq.gz
│   │   ├── 3b77a26f5a27473ad3b08194d773f325d018a2d0
│   │   │   └── chunk-001.nq.gz
│   │   ├── 7a983f7f0068669ead9d4f7571be24d6c0d83eb9
│   │   │   └── chunk-001.nq.gz
│   │   ├── 85442b8032cb7bae72866dfd7782234a98dd2fb7
│   │   │   └── chunk-001.nq.gz
│   │   ├── b10b90a7d1c3afac6852462fa2548db231810adf
│   │   │   └── chunk-001.nq.gz
│   │   ├── b3a5d7d68991c040615d5345bb55f61de53ba176
│   │   │   └── chunk-001.nq.gz
│   │   ├── b6e9bbc189d7c1b46e875678dac179995d57c8cd
│   │   │   └── chunk-001.nq.gz
│   │   ├── d4eefdccf992e963c48011875301d93df6a7f2cc
│   │   │   └── chunk-001.nq.gz
│   │   ├── d563917280d65a6ce2e622bd3d07438e1ee259f3
│   │   │   └── chunk-001.nq.gz
│   │   ├── d7af197ec2f7d005d1d7a79544ad99832800797e
│   │   │   └── chunk-001.nq.gz
│   │   ├── d8e3b31b734926ebbcaff654279f6855a73e052f
│   │   │   └── chunk-001.nq.gz
│   │   ├── e3f218269c0f2fd2aff228b310d7f474a3ffd487
│   │   │   └── chunk-001.nq.gz
│   │   ├── f0c324ec2222dae2c4eea0fc6e7c659a762eb152
│   │   │   └── chunk-001.nq.gz
│   │   └── f58537628042c7f29780b9d33f31597e7fc9d664
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 2e4a904fa07cd57ca48dd29b57bafd3c999ce9a4.nq.gz
│   │   ├── 3b1c1d5cb8fca96a51d5622289d7784b5e9e56ce.nq.gz
│   │   ├── 3b77a26f5a27473ad3b08194d773f325d018a2d0.nq.gz
│   │   ├── 7a983f7f0068669ead9d4f7571be24d6c0d83eb9.nq.gz
│   │   ├── 85442b8032cb7bae72866dfd7782234a98dd2fb7.nq.gz
│   │   ├── b10b90a7d1c3afac6852462fa2548db231810adf.nq.gz
│   │   ├── b3a5d7d68991c040615d5345bb55f61de53ba176.nq.gz
│   │   ├── b6e9bbc189d7c1b46e875678dac179995d57c8cd.nq.gz
│   │   ├── d4eefdccf992e963c48011875301d93df6a7f2cc.nq.gz
│   │   ├── d563917280d65a6ce2e622bd3d07438e1ee259f3.nq.gz
│   │   ├── d7af197ec2f7d005d1d7a79544ad99832800797e.nq.gz
│   │   ├── d8e3b31b734926ebbcaff654279f6855a73e052f.nq.gz
│   │   ├── e3f218269c0f2fd2aff228b310d7f474a3ffd487.nq.gz
│   │   ├── f0c324ec2222dae2c4eea0fc6e7c659a762eb152.nq.gz
│   │   └── f58537628042c7f29780b9d33f31597e7fc9d664.nq.gz
│   └── repolex
│       ├── 2e4a904fa07cd57ca48dd29b57bafd3c999ce9a4
│       │   └── chunk-001.nq.gz
│       ├── 3b1c1d5cb8fca96a51d5622289d7784b5e9e56ce
│       │   └── chunk-001.nq.gz
│       ├── 3b77a26f5a27473ad3b08194d773f325d018a2d0
│       │   └── chunk-001.nq.gz
│       ├── 7a983f7f0068669ead9d4f7571be24d6c0d83eb9
│       │   └── chunk-001.nq.gz
│       ├── 85442b8032cb7bae72866dfd7782234a98dd2fb7
│       │   └── chunk-001.nq.gz
│       ├── b10b90a7d1c3afac6852462fa2548db231810adf
│       │   └── chunk-001.nq.gz
│       ├── b3a5d7d68991c040615d5345bb55f61de53ba176
│       │   └── chunk-001.nq.gz
│       ├── b6e9bbc189d7c1b46e875678dac179995d57c8cd
│       │   └── chunk-001.nq.gz
│       ├── d4eefdccf992e963c48011875301d93df6a7f2cc
│       │   └── chunk-001.nq.gz
│       ├── d563917280d65a6ce2e622bd3d07438e1ee259f3
│       │   └── chunk-001.nq.gz
│       ├── d7af197ec2f7d005d1d7a79544ad99832800797e
│       │   └── chunk-001.nq.gz
│       ├── d8e3b31b734926ebbcaff654279f6855a73e052f
│       │   └── chunk-001.nq.gz
│       ├── e3f218269c0f2fd2aff228b310d7f474a3ffd487
│       │   └── chunk-001.nq.gz
│       ├── f0c324ec2222dae2c4eea0fc6e7c659a762eb152
│       │   └── chunk-001.nq.gz
│       └── f58537628042c7f29780b9d33f31597e7fc9d664
│           └── chunk-001.nq.gz
└── blob
    ├── 0007c0aa64aeae24c7e0ca90790a25ba51dbf7d6.nq.gz
    ├── 012acb130f17971e20b103111d8dd14db029c109.nq.gz
    ├── 03192c1777420cc1ffda8ff5f57dcc9d1b4587e1.nq.gz
    ├── 03bb391c4dba670a17fefbd027ea160aa0ed2917.nq.gz
    ├── 04579c4f2742cb15638aa390be9b8e2f0d5ca82e.nq.gz
    ├── 05e554a64c244d96c21dd2d8ce06f0060b65cac9.nq.gz
    ├── 068b2e6999fb8e16ab69a5f3a0062766ac1a748f.nq.gz
    ├── 0888fb6967ef3c3055ccbc6d7f7609984d842cec.nq.gz
    ├── 08a2a46d8c0fe5f579ebd18ebcd0fc002f40c685.nq.gz
    ├── 08f651fbd8dae57028d57721f7e9983053771a1e.nq.gz
    ├── 0b8e742c156ba9b2c5bf2e46cadaf38288f05e0b.nq.gz
    ├── 0c00eba331b736fbd266ecfc5d2761f3efa700e0.nq.gz
    ├── 0cad38ae541f129496681f96c88e02312eae98e6.nq.gz
    ├── 0e218a6f9f75ea2060a8b08d1f1a043fdad68df8.nq.gz
    ├── 0e79e8a882be74fe76c80ccf49a9cd68fb636fd4.nq.gz
    ├── 104fac9b3feb52e6c4f97055251368faea307b1e.nq.gz
    ├── 10564101ef92a1b537a49d56b2084b73b8937a1d.nq.gz
    ├── 1064d7d06ddba6e28d10d89d1f1d7e171ec83457.nq.gz
    ├── 11a6750fe1f4fae6512e17c05fa2795b8e6fab34.nq.gz
    ├── 11bfa22b2f29cd6cfa27b01f5bf690ab3dbf15fe.nq.gz
    ├── 1206c462d4fcaa670a816e201bb88b27dfc9cf88.nq.gz
    ├── 12db2105c7b68d355c4ca3c5d5c617f83eebc829.nq.gz
    ├── 1391863f0cb8ff14c92feb36d15ff2572663df2b.nq.gz
    ├── 13cadc7f04d4c24afb829c9fc44367ac06a3c61d.nq.gz
    ├── 1480b2aa767c4f80fbbcc76b39a661a9bf4b62fc.nq.gz
    ├── 1636d7d07583781fb5f039ae0d602e9ae3db1def.nq.gz
    ├── 184a794c35d6d206289ab422b78528886a5a7818.nq.gz
    ├── 186199a5853b2cf877bb6ec2bf3378a26697ac05.nq.gz
    ├── 19ccbde3ea2d8307c6c55cb1415fe098424185ec.nq.gz
    ├── 1a6a9a262085e722edc724028f024b7d5adf4248.nq.gz
    ├── 1d6853739aaaada8868ef581f8768366a77a22a7.nq.gz
    ├── 1dfd23fa3c0eb944358b1eee0b7c241c79da3cd3.nq.gz
    ├── 1e3d9575f8b977b5f212dc85e864ca9bfad7e2c6.nq.gz
    ├── 1ee62711c6867feb6d20b6a9d82a80a802827055.nq.gz
    ├── 210ff0e486e3863421cead6dcd8713bbb247019a.nq.gz
    ├── 21695a74b5107c96ba4bb2cbca6b7f259dacd330.nq.gz
    ├── 225e2eee01238571c50595eb104e0b70d5f503c4.nq.gz
    ├── 22809cfd5dc25792d77070c269fc8d111a12eed0.nq.gz
    ├── 22fe76bac14e60cbbfd4dfc07d009a03c7ae4236.nq.gz
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
    ├── 2bc6a8f98b2ff89f1347f33cc6ea265da801dfc0.nq.gz
    ├── 2c1573877903e40f72535f497f145ec1da9a71c3.nq.gz
    ├── 2c71ec2b619937c44cdb6b9f5383c7333307721c.nq.gz
    ├── 2ca012ecabf9fa49c5b8dc04cd6aecc1a199857d.nq.gz
    ├── 2d015bab5958fd9767cf5c9e449f2fa33292c962.nq.gz
    ├── 2f0cc7439a00da8e418a314d587f215d757320a1.nq.gz
    ├── 2f269edc18a502c160409ac69cb41b8623f82360.nq.gz
    ├── 2fa75f7abb715eb7cfbd871919c56035b2bae35a.nq.gz
    ├── 3079be69bf880f47e64dbf62993f0e54754b7315.nq.gz
    ├── 31834a394d5577d6ecbf7dfb1783799148e7c6fa.nq.gz
    ├── 3186ed53ea9f4016d4b56263bafd2ca3f0fb0152.nq.gz
    ├── 335b275fa7575b0a7c525a713fbe0252ad2d956f.nq.gz
    ├── 33c613b749a49d6035c0e549389e92c3d68a83ad.nq.gz
    ├── 34a0f146e8ce62d7cb8f38d283e53a870cd012a1.nq.gz
    ├── 3551bc2d29846441299cf57b397b02fc164c99b9.nq.gz
    ├── 3561bb99f20fbf33a42d247de086d470078cf3f7.nq.gz
    ├── 36e0128465be01cf5722f83a05e504299fe56d74.nq.gz
    ├── 36ea474b02cb0cc251619301f085cd544946f45c.nq.gz
    ├── 3705d50db9193e445056ebc6270faab2319a04db.nq.gz
    ├── 378aef1ad6a5081e5814dd6b9a3f0efcabc41386.nq.gz
    ├── 37f33b1ef849ed9e22a6dd44395c61654a9b7d7a.nq.gz
    ├── 39279f9663ff1235b561905bed1c4332c084db96.nq.gz
    ├── 39515e8d1c3da16e549f181eca82ac6ef0d5112e.nq.gz
    ├── 3a2f63d59d7cd06ffe83f7e1e9e3472d33a9d964.nq.gz
    ├── 3ad0ace732dae2ea9ad688eb0f7f8da86f0ca196.nq.gz
    ├── 3b0d3170837a801844f29f62180b33da7c7ae83b.nq.gz
    ├── 3bd8602d36c53374f1f10a0716d28fdc64e2d3ac.nq.gz
    ├── 3c50c5dcfeeda2efed282200a5c5cc8c5f7542f7.nq.gz
    ├── 3d3102391183a7772abd3bdae254418773939bf8.nq.gz
    ├── 3d666e88b535a7fac7fe171400988b1229a41967.nq.gz
    ├── 3f2e0d35949a20b2105d25fd197e2851b483c91a.nq.gz
    ├── 4112fec0a5a3ab3a8cd07d92a1e58188b5bca14b.nq.gz
    ├── 41bda762ac7e4cd1c7f6bbf4542b5ebb3b679e3b.nq.gz
    ├── 42ce7b75c92fb01a3f6ed17eea363f756b7da582.nq.gz
    ├── 444eb7967a8c3e00e5fd3936b5758b4dedb1301b.nq.gz
    ├── 446dee4ef7e7c760bee4b31bef25a5959bd4543b.nq.gz
    ├── 4480901820077e4d7997d7558aa4118dee0aa41e.nq.gz
    ├── 449c655be65a948f7b2476302a46c35d9e7605ac.nq.gz
    ├── 450f6f9f8a0d43a33f48589194f6d7f7d0edf8e9.nq.gz
    ├── 45285b3899727f2a17b09d5992a5001146483c11.nq.gz
    ├── 454ba21c8f42038b78cd8518ac0e75237f0ab068.nq.gz
    ├── 4576981c2dd7552d8b37dedf92d0f7466857ac41.nq.gz
    ├── 45856601908f7622c96bef534b60aee46607e549.nq.gz
    ├── 45c05230e25554347ffdb8082c800d6596f4c54b.nq.gz
    ├── 46066ad2ded1af7c68a4f5d4d3ccc66933b89f43.nq.gz
    ├── 46bc2613086732e34b8863b7ea562ffb6918865b.nq.gz
    ├── 491b3e03625936f6a7168beb627e7ff96c18aef4.nq.gz
    ├── 497b0645217512ae2ba8ff61341fd2bbfa3648cd.nq.gz
    ├── 49ae0d4e78311340cfa5cf58782de0e76d573ccc.nq.gz
    ├── 4a5a5f0a1c22946f057556fee5054a75b487371d.nq.gz
    ├── 4b4813a17c31ed3329418f3481460336ff6a0cc9.nq.gz
    ├── 4c379aa6f69ff56c8f19612002c6e3e939ea6012.nq.gz
    ├── 4ccc4770a613ae1d1a529ec6651455764119d33d.nq.gz
    ├── 4dcf03d11c1068ece6b084df83bebcd316004b06.nq.gz
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
    ├── 53bca63ba092cea94d8b4a600c83617974cea181.nq.gz
    ├── 53f9a3aa42b885c60ece311a31f9f19820196804.nq.gz
    ├── 5412a08349ed53c868988ba2139660f26d15adc5.nq.gz
    ├── 554059fc8f6cf09b4593e3ec5bda2d77615cb5a3.nq.gz
    ├── 565b0521d0c2cdbfe493d19765b04d5c119fa7eb.nq.gz
    ├── 5677c0e89bd9c84b10b0239a0c26a799d3e646b8.nq.gz
    ├── 569156d6ca47719f49b753a4781a86a924de173b.nq.gz
    ├── 56e38f9220ee796061315821764dd4a7fe932f3c.nq.gz
    ├── 59996e28c27516a7342a0f0b8052e0205455b65a.nq.gz
    ├── 59db7412d509294f913ce0bd5886d14d853f0369.nq.gz
    ├── 5a18b758fe0065416a92b9047dc9c392a3de2c4f.nq.gz
    ├── 5a9ca9e65aaf0cfbca5ca694301f4be92e6bd789.nq.gz
    ├── 5d26b0d1ae2d21b77e24b692d5a7e1fd01296edc.nq.gz
    ├── 5d85084a96c13180508e4d904c5ab4d8c47a4cf0.nq.gz
    ├── 5e4db59a86129582279a2c5a32b946a51d68a456.nq.gz
    ├── 5e591c3ec5dde987c61ed21c0d7fa52582dc1b34.nq.gz
    ├── 5e9899fc07609f37f5251f0da5a5af97d4d79234.nq.gz
    ├── 5ec89b2440f06dc5cefc282d6170d9deb476a5be.nq.gz
    ├── 5ef27c897a4df35a2a6923b608a5e04a0a38b9ee.nq.gz
    ├── 5f2251e11ec7688f8b215d5938d39d4edc5d47db.nq.gz
    ├── 5faab9bd0dcf28847960162b2b4f13a8a556ef20.nq.gz
    ├── 60c4bec6ca251d481825ef1f99fbafdc8edac914.nq.gz
    ├── 61339a6fcc1b82803136f3bf980e0c8f574b2220.nq.gz
    ├── 635b806c12f759f5c4fdac108e386325e605254c.nq.gz
    ├── 645214ae7d5386f0d078e75b06f4600841de1c3a.nq.gz
    ├── 64573a90163160c41d9ce387cf66a65d792ff445.nq.gz
    ├── 652a2f927eab38192f3e9c10ddb7a7e746ffb658.nq.gz
    ├── 661f6730d23e93515d368482935cad58f7e2120f.nq.gz
    ├── 6667d2990858447607f9fe21057a6e230a0caa8d.nq.gz
    ├── 678f1adb973c2dda7f8e01a5006caacdf3fc4699.nq.gz
    ├── 68369c981b1e9e9a49640fc15e69d06633ed21ff.nq.gz
    ├── 684df75457cb82d3683dc99ff52c5bf911f3341b.nq.gz
    ├── 6850e9e8df3a12976bd72f357f7ff74bd1037eda.nq.gz
    ├── 68dfb8014c11482de9ee5e6caa9e5b533801265f.nq.gz
    ├── 6b46ddc66d0f2d85e4f55a133a46505d04f56441.nq.gz
    ├── 6c4805959de7375c57bd8b0d502a5fcbc1c09f9e.nq.gz
    ├── 6c552555a7a851ddddf9ad821ddd7bb6652fa3a9.nq.gz
    ├── 6cdbe1909b397b28f05a7e84ba8ea0f69ae5e77d.nq.gz
    ├── 6dacfd1b16db596433ad2855751c950777187c4f.nq.gz
    ├── 6f0011956b7e06628ad52b15e5e0dd9b3946eed0.nq.gz
    └── 6f62d44e4ef733c0e713afcd2371fed7f2b3de67.nq.gz

36 directories, 200 files
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
