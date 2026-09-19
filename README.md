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
│   │   ├── 0120272291722bb0590e968ad005e5a1ec06f7ba
│   │   │   └── chunk-001.nq.gz
│   │   ├── 02a425ae95fa43687c310f84a637a3bfac2de221
│   │   │   └── chunk-001.nq.gz
│   │   ├── 06ab8eee469c6143a8601a3fef5c4c168d0d7216
│   │   │   └── chunk-001.nq.gz
│   │   ├── 07b8ff471fc978a5b8b3c726717d1941ed083bb8
│   │   │   └── chunk-001.nq.gz
│   │   ├── 07f09547c435d08b77c7c80834955f9640d3d3e5
│   │   │   └── chunk-001.nq.gz
│   │   ├── 085ff41692b687ae5b0772a55615b69a5b677be9
│   │   │   └── chunk-001.nq.gz
│   │   ├── 0dfec396998e7237e12dc2e3a06385ffa1bd97b1
│   │   │   └── chunk-001.nq.gz
│   │   ├── 192473d5237e198bb388d44c4d13d0ccdffbdbd4
│   │   │   └── chunk-001.nq.gz
│   │   ├── 2216f94ecf333bdeac38bf16f1b312b27a63a3c3
│   │   │   └── chunk-001.nq.gz
│   │   ├── 2e4a904fa07cd57ca48dd29b57bafd3c999ce9a4
│   │   │   └── chunk-001.nq.gz
│   │   ├── 3b1c1d5cb8fca96a51d5622289d7784b5e9e56ce
│   │   │   └── chunk-001.nq.gz
│   │   ├── 3b77a26f5a27473ad3b08194d773f325d018a2d0
│   │   │   └── chunk-001.nq.gz
│   │   ├── 47d40f640fddb7c97b01315419b6a1421d2dedbb
│   │   │   └── chunk-001.nq.gz
│   │   ├── 53fd698b1620aca027324001bf53c8ffda0c17d1
│   │   │   └── chunk-001.nq.gz
│   │   ├── 71b46f5a4ad9275b67c4b4eae873930f2d604aa9
│   │   │   └── chunk-001.nq.gz
│   │   ├── 7890ca820eca8580d63fcadae727e95a70daec27
│   │   │   └── chunk-001.nq.gz
│   │   ├── 7a983f7f0068669ead9d4f7571be24d6c0d83eb9
│   │   │   └── chunk-001.nq.gz
│   │   ├── 7dabc1b669d27b52ffaa623d724105d7d16f85a0
│   │   │   └── chunk-001.nq.gz
│   │   ├── 7f8582b698c41408ffb42645986053acc21d83df
│   │   │   └── chunk-001.nq.gz
│   │   ├── 85442b8032cb7bae72866dfd7782234a98dd2fb7
│   │   │   └── chunk-001.nq.gz
│   │   ├── b10b90a7d1c3afac6852462fa2548db231810adf
│   │   │   └── chunk-001.nq.gz
│   │   ├── b3a5d7d68991c040615d5345bb55f61de53ba176
│   │   │   └── chunk-001.nq.gz
│   │   ├── b5f0efdf3986725c2a45437e03d0ee5939c21192
│   │   │   └── chunk-001.nq.gz
│   │   ├── b6e9bbc189d7c1b46e875678dac179995d57c8cd
│   │   │   └── chunk-001.nq.gz
│   │   ├── c048e344affac7649be67c7e06f37e7cf58ef548
│   │   │   └── chunk-001.nq.gz
│   │   ├── cae492dfba9ec1d9f720a788912d9d7050e78bef
│   │   │   └── chunk-001.nq.gz
│   │   ├── d4eefdccf992e963c48011875301d93df6a7f2cc
│   │   │   └── chunk-001.nq.gz
│   │   ├── d563917280d65a6ce2e622bd3d07438e1ee259f3
│   │   │   └── chunk-001.nq.gz
│   │   ├── d58a8f1c91af7249ad86e9a1880dbaf6ea57dbde
│   │   │   └── chunk-001.nq.gz
│   │   ├── d7af197ec2f7d005d1d7a79544ad99832800797e
│   │   │   └── chunk-001.nq.gz
│   │   ├── d8e3b31b734926ebbcaff654279f6855a73e052f
│   │   │   └── chunk-001.nq.gz
│   │   ├── d93c6eea7d2caa637176426d255895bdf7db4f64
│   │   │   └── chunk-001.nq.gz
│   │   ├── dd33aeb12f08178b3122e8d065c4a73ae8e1d679
│   │   │   └── chunk-001.nq.gz
│   │   ├── ded06cedf6e20680eea0363fac894cb4a09e7831
│   │   │   └── chunk-001.nq.gz
│   │   ├── e3f218269c0f2fd2aff228b310d7f474a3ffd487
│   │   │   └── chunk-001.nq.gz
│   │   ├── e6c5b770df9940426fc879ed8e5bd3b7b969f8cf
│   │   │   └── chunk-001.nq.gz
│   │   ├── f0c324ec2222dae2c4eea0fc6e7c659a762eb152
│   │   │   └── chunk-001.nq.gz
│   │   ├── f58537628042c7f29780b9d33f31597e7fc9d664
│   │   │   └── chunk-001.nq.gz
│   │   ├── f72628d9442ea24474e9e50c0f5c3ee2d8186b5e
│   │   │   └── chunk-001.nq.gz
│   │   └── fd6c1d301a5162d4c78620444c55bd56aa2670a0
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 0120272291722bb0590e968ad005e5a1ec06f7ba.nq.gz
│   │   ├── 02a425ae95fa43687c310f84a637a3bfac2de221.nq.gz
│   │   ├── 06ab8eee469c6143a8601a3fef5c4c168d0d7216.nq.gz
│   │   ├── 07b8ff471fc978a5b8b3c726717d1941ed083bb8.nq.gz
│   │   ├── 07f09547c435d08b77c7c80834955f9640d3d3e5.nq.gz
│   │   ├── 085ff41692b687ae5b0772a55615b69a5b677be9.nq.gz
│   │   ├── 0dfec396998e7237e12dc2e3a06385ffa1bd97b1.nq.gz
│   │   ├── 192473d5237e198bb388d44c4d13d0ccdffbdbd4.nq.gz
│   │   ├── 2216f94ecf333bdeac38bf16f1b312b27a63a3c3.nq.gz
│   │   ├── 2e4a904fa07cd57ca48dd29b57bafd3c999ce9a4.nq.gz
│   │   ├── 3b1c1d5cb8fca96a51d5622289d7784b5e9e56ce.nq.gz
│   │   ├── 3b77a26f5a27473ad3b08194d773f325d018a2d0.nq.gz
│   │   ├── 47d40f640fddb7c97b01315419b6a1421d2dedbb.nq.gz
│   │   ├── 53fd698b1620aca027324001bf53c8ffda0c17d1.nq.gz
│   │   ├── 71b46f5a4ad9275b67c4b4eae873930f2d604aa9.nq.gz
│   │   ├── 7890ca820eca8580d63fcadae727e95a70daec27.nq.gz
│   │   ├── 7a983f7f0068669ead9d4f7571be24d6c0d83eb9.nq.gz
│   │   ├── 7dabc1b669d27b52ffaa623d724105d7d16f85a0.nq.gz
│   │   ├── 7f8582b698c41408ffb42645986053acc21d83df.nq.gz
│   │   ├── 85442b8032cb7bae72866dfd7782234a98dd2fb7.nq.gz
│   │   ├── b10b90a7d1c3afac6852462fa2548db231810adf.nq.gz
│   │   ├── b3a5d7d68991c040615d5345bb55f61de53ba176.nq.gz
│   │   ├── b5f0efdf3986725c2a45437e03d0ee5939c21192.nq.gz
│   │   ├── b6e9bbc189d7c1b46e875678dac179995d57c8cd.nq.gz
│   │   ├── c048e344affac7649be67c7e06f37e7cf58ef548.nq.gz
│   │   ├── cae492dfba9ec1d9f720a788912d9d7050e78bef.nq.gz
│   │   ├── d4eefdccf992e963c48011875301d93df6a7f2cc.nq.gz
│   │   ├── d563917280d65a6ce2e622bd3d07438e1ee259f3.nq.gz
│   │   ├── d58a8f1c91af7249ad86e9a1880dbaf6ea57dbde.nq.gz
│   │   ├── d7af197ec2f7d005d1d7a79544ad99832800797e.nq.gz
│   │   ├── d8e3b31b734926ebbcaff654279f6855a73e052f.nq.gz
│   │   ├── d93c6eea7d2caa637176426d255895bdf7db4f64.nq.gz
│   │   ├── dd33aeb12f08178b3122e8d065c4a73ae8e1d679.nq.gz
│   │   ├── ded06cedf6e20680eea0363fac894cb4a09e7831.nq.gz
│   │   ├── e3f218269c0f2fd2aff228b310d7f474a3ffd487.nq.gz
│   │   ├── e6c5b770df9940426fc879ed8e5bd3b7b969f8cf.nq.gz
│   │   ├── f0c324ec2222dae2c4eea0fc6e7c659a762eb152.nq.gz
│   │   ├── f58537628042c7f29780b9d33f31597e7fc9d664.nq.gz
│   │   ├── f72628d9442ea24474e9e50c0f5c3ee2d8186b5e.nq.gz
│   │   └── fd6c1d301a5162d4c78620444c55bd56aa2670a0.nq.gz
│   └── repolex
│       ├── 0120272291722bb0590e968ad005e5a1ec06f7ba
│       │   └── chunk-001.nq.gz
│       ├── 02a425ae95fa43687c310f84a637a3bfac2de221
│       │   └── chunk-001.nq.gz
│       ├── 06ab8eee469c6143a8601a3fef5c4c168d0d7216
│       │   └── chunk-001.nq.gz
│       ├── 07b8ff471fc978a5b8b3c726717d1941ed083bb8
│       │   └── chunk-001.nq.gz
│       ├── 07f09547c435d08b77c7c80834955f9640d3d3e5
│       │   └── chunk-001.nq.gz
│       ├── 085ff41692b687ae5b0772a55615b69a5b677be9
│       │   └── chunk-001.nq.gz
│       ├── 0dfec396998e7237e12dc2e3a06385ffa1bd97b1
│       │   └── chunk-001.nq.gz
│       ├── 192473d5237e198bb388d44c4d13d0ccdffbdbd4
│       │   └── chunk-001.nq.gz
│       ├── 2216f94ecf333bdeac38bf16f1b312b27a63a3c3
│       │   └── chunk-001.nq.gz
│       ├── 2e4a904fa07cd57ca48dd29b57bafd3c999ce9a4
│       │   └── chunk-001.nq.gz
│       ├── 3b1c1d5cb8fca96a51d5622289d7784b5e9e56ce
│       │   └── chunk-001.nq.gz
│       ├── 3b77a26f5a27473ad3b08194d773f325d018a2d0
│       │   └── chunk-001.nq.gz
│       ├── 47d40f640fddb7c97b01315419b6a1421d2dedbb
│       │   └── chunk-001.nq.gz
│       ├── 53fd698b1620aca027324001bf53c8ffda0c17d1
│       │   └── chunk-001.nq.gz
│       ├── 71b46f5a4ad9275b67c4b4eae873930f2d604aa9
│       │   └── chunk-001.nq.gz
│       ├── 7890ca820eca8580d63fcadae727e95a70daec27
│       │   └── chunk-001.nq.gz
│       ├── 7a983f7f0068669ead9d4f7571be24d6c0d83eb9
│       │   └── chunk-001.nq.gz
│       ├── 7dabc1b669d27b52ffaa623d724105d7d16f85a0
│       │   └── chunk-001.nq.gz
│       ├── 7f8582b698c41408ffb42645986053acc21d83df
│       │   └── chunk-001.nq.gz
│       ├── 85442b8032cb7bae72866dfd7782234a98dd2fb7
│       │   └── chunk-001.nq.gz
│       ├── b10b90a7d1c3afac6852462fa2548db231810adf
│       │   └── chunk-001.nq.gz
│       ├── b3a5d7d68991c040615d5345bb55f61de53ba176
│       │   └── chunk-001.nq.gz
│       ├── b5f0efdf3986725c2a45437e03d0ee5939c21192
│       │   └── chunk-001.nq.gz
│       ├── b6e9bbc189d7c1b46e875678dac179995d57c8cd
│       │   └── chunk-001.nq.gz
│       ├── c048e344affac7649be67c7e06f37e7cf58ef548
│       │   └── chunk-001.nq.gz
│       ├── cae492dfba9ec1d9f720a788912d9d7050e78bef
│       │   └── chunk-001.nq.gz
│       ├── d4eefdccf992e963c48011875301d93df6a7f2cc
│       │   └── chunk-001.nq.gz
│       ├── d563917280d65a6ce2e622bd3d07438e1ee259f3
│       │   └── chunk-001.nq.gz
│       ├── d58a8f1c91af7249ad86e9a1880dbaf6ea57dbde
│       │   └── chunk-001.nq.gz
│       ├── d7af197ec2f7d005d1d7a79544ad99832800797e
│       │   └── chunk-001.nq.gz
│       ├── d8e3b31b734926ebbcaff654279f6855a73e052f
│       │   └── chunk-001.nq.gz
│       ├── d93c6eea7d2caa637176426d255895bdf7db4f64
│       │   └── chunk-001.nq.gz
│       ├── dd33aeb12f08178b3122e8d065c4a73ae8e1d679
│       │   └── chunk-001.nq.gz
│       ├── ded06cedf6e20680eea0363fac894cb4a09e7831
│       │   └── chunk-001.nq.gz
│       ├── e3f218269c0f2fd2aff228b310d7f474a3ffd487
│       │   └── chunk-001.nq.gz
│       ├── e6c5b770df9940426fc879ed8e5bd3b7b969f8cf
│       │   └── chunk-001.nq.gz
│       ├── f0c324ec2222dae2c4eea0fc6e7c659a762eb152
│       │   └── chunk-001.nq.gz
│       ├── f58537628042c7f29780b9d33f31597e7fc9d664
│       │   └── chunk-001.nq.gz
│       ├── f72628d9442ea24474e9e50c0f5c3ee2d8186b5e
│       │   └── chunk-001.nq.gz
│       └── fd6c1d301a5162d4c78620444c55bd56aa2670a0
│           └── chunk-001.nq.gz
└── blob
    ├── 0007c0aa64aeae24c7e0ca90790a25ba51dbf7d6.nq.gz
    ├── 00371e86a87edfc5f8d1d1352360bfae0cce8e65.nq.gz
    ├── 012acb130f17971e20b103111d8dd14db029c109.nq.gz
    ├── 01e4aa6b374bed45077ec9dfeaf7b176f0e74b8e.nq.gz
    ├── 0213d6deb351197da0c372d0644a0fdad1a13b1f.nq.gz
    ├── 03192c1777420cc1ffda8ff5f57dcc9d1b4587e1.nq.gz
    ├── 03bb391c4dba670a17fefbd027ea160aa0ed2917.nq.gz
    ├── 04579c4f2742cb15638aa390be9b8e2f0d5ca82e.nq.gz
    ├── 05e554a64c244d96c21dd2d8ce06f0060b65cac9.nq.gz
    ├── 068b2e6999fb8e16ab69a5f3a0062766ac1a748f.nq.gz
    ├── 06cbbf7bff647b7a6c2ffbf5a5e70d0d35ee00d6.nq.gz
    ├── 0851d7893442103bee66eec005a59a4e7f942ede.nq.gz
    ├── 0888fb6967ef3c3055ccbc6d7f7609984d842cec.nq.gz
    ├── 08a2a46d8c0fe5f579ebd18ebcd0fc002f40c685.nq.gz
    ├── 08d2c892b83963b0749cc34bac00083fb9a806df.nq.gz
    ├── 08f651fbd8dae57028d57721f7e9983053771a1e.nq.gz
    ├── 0b04428823f426766582d074a3d66955cb2907a8.nq.gz
    ├── 0b8e742c156ba9b2c5bf2e46cadaf38288f05e0b.nq.gz
    ├── 0bb4fd61613c78c1fa6ea4d63724132e1f2cd232.nq.gz
    ├── 0c00eba331b736fbd266ecfc5d2761f3efa700e0.nq.gz
    ├── 0cad38ae541f129496681f96c88e02312eae98e6.nq.gz
    ├── 0e11301413d5e3dbafa3112bd5460380e54f5253.nq.gz
    ├── 0e218a6f9f75ea2060a8b08d1f1a043fdad68df8.nq.gz
    ├── 0e2d96a93b05bb84ba2852642b2dc21cef7ec281.nq.gz
    ├── 0e56cd9d916a96162c35ab4c4f657c74faffe832.nq.gz
    ├── 0e79e8a882be74fe76c80ccf49a9cd68fb636fd4.nq.gz
    ├── 0fe202a5f52fa115d87d7cc04e02a169531fc1c2.nq.gz
    ├── 104fac9b3feb52e6c4f97055251368faea307b1e.nq.gz
    ├── 10564101ef92a1b537a49d56b2084b73b8937a1d.nq.gz
    ├── 1064d7d06ddba6e28d10d89d1f1d7e171ec83457.nq.gz
    ├── 11a6750fe1f4fae6512e17c05fa2795b8e6fab34.nq.gz
    ├── 11bfa22b2f29cd6cfa27b01f5bf690ab3dbf15fe.nq.gz
    ├── 11c61aabd3b5aa46bf9f24a2a6b4f46c66ea8e1c.nq.gz
    ├── 1206c462d4fcaa670a816e201bb88b27dfc9cf88.nq.gz
    ├── 126d348bfbb84a8c7f66bb6533fe270d2853bed5.nq.gz
    ├── 12c25b9bea7535ba4e1686373ba672cc1fbcffe6.nq.gz
    ├── 12db2105c7b68d355c4ca3c5d5c617f83eebc829.nq.gz
    ├── 134094aa30e0278370bdf37bc9220825aa0c0eb2.nq.gz
    ├── 13798e38bce4505ab64620c1e2ba715943d5020e.nq.gz
    ├── 1391863f0cb8ff14c92feb36d15ff2572663df2b.nq.gz
    ├── 13cadc7f04d4c24afb829c9fc44367ac06a3c61d.nq.gz
    ├── 13d49423bef7bc1bf3bf1e140ab267d490ca7794.nq.gz
    ├── 1480b2aa767c4f80fbbcc76b39a661a9bf4b62fc.nq.gz
    ├── 1636d7d07583781fb5f039ae0d602e9ae3db1def.nq.gz
    ├── 170b31d48f6557af7b000669a1443778f0d8276c.nq.gz
    ├── 180310716e66db31b5589b0f7824fd3249d31237.nq.gz
    ├── 184a794c35d6d206289ab422b78528886a5a7818.nq.gz
    ├── 186199a5853b2cf877bb6ec2bf3378a26697ac05.nq.gz
    ├── 18fecb867a89326898cc0cf28bc5826f6a1c8fdc.nq.gz
    ├── 19579c1a0fa38c088a7cbb80950d0c85f5514cca.nq.gz
    ├── 19afb627cab063eddf8254245bfb14f9088ad62d.nq.gz
    ├── 19ccbde3ea2d8307c6c55cb1415fe098424185ec.nq.gz
    ├── 1a6a9a262085e722edc724028f024b7d5adf4248.nq.gz
    ├── 1b547927df7cdabd33c49b2ce29e557d240e6272.nq.gz
    ├── 1c05969f7942c7d61b543b78fb03cfc2cc2b1e33.nq.gz
    ├── 1c96b31253032d6e7c08b96af9f8c3588cd0d238.nq.gz
    ├── 1d6853739aaaada8868ef581f8768366a77a22a7.nq.gz
    ├── 1d8ae108fd7ff431f07bae2d4b0d136db68b587c.nq.gz
    ├── 1dfd23fa3c0eb944358b1eee0b7c241c79da3cd3.nq.gz
    ├── 1e3d9575f8b977b5f212dc85e864ca9bfad7e2c6.nq.gz
    ├── 1eacf68640f6c02a87480df99406d2586e24d271.nq.gz
    ├── 1ee62711c6867feb6d20b6a9d82a80a802827055.nq.gz
    ├── 1fa2fcf384ea2818aacd7d6f95ef329d2dfcb7b0.nq.gz
    ├── 20512aaf9925e4e95cd50d509e401e09c5637147.nq.gz
    ├── 210bb80b7e7b64cb79f7e7cdf3e42819fe3471fe.nq.gz
    ├── 210ff0e486e3863421cead6dcd8713bbb247019a.nq.gz
    ├── 21695a74b5107c96ba4bb2cbca6b7f259dacd330.nq.gz
    ├── 21fc6ce3e741c57863e69e03af5053123957ff22.nq.gz
    ├── 2226e984e246711d449bc0c4c420ec5684a6ebb0.nq.gz
    ├── 225e2eee01238571c50595eb104e0b70d5f503c4.nq.gz
    ├── 22809cfd5dc25792d77070c269fc8d111a12eed0.nq.gz
    ├── 229fd51f928d545e04cab29b24714f754b86c5bb.nq.gz
    ├── 22fe76bac14e60cbbfd4dfc07d009a03c7ae4236.nq.gz
    ├── 23007c788ee1db926d5de05b9e84d3f3793954d1.nq.gz
    ├── 23450953df74eccd9c13cd2a955ce09d1f968565.nq.gz
    ├── 2390d8c809eea1d6587357cdad25ed4af134db32.nq.gz
    ├── 24a97655ee055739962e65a8c4a70ad37c25c279.nq.gz
    ├── 253f6b1b7ebd711fdc6bbbab3b56897061bab515.nq.gz
    ├── 25da473c196855ad59a6d2d785ef1ddef49795be.nq.gz
    └── 25f4282cc29cb03d7be881f03dee841d7dbc215a.nq.gz

86 directories, 200 files
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
