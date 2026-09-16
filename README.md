# Repolex Knowledge Graph of quic-go/quic-go

RDF knowledge graph data for [quic-go/quic-go](https://github.com/quic-go/quic-go), parsed by [repolex](https://repolex.ai).

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
lexq download quic-go/quic-go
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 7659dd8e0fa06b41290ad29af323d93d673c6b36
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 7659dd8e0fa06b41290ad29af323d93d673c6b36.nq.gz
│   └── repolex
│       └── 7659dd8e0fa06b41290ad29af323d93d673c6b36
│           └── chunk-001.nq.gz
└── blob
    ├── 00361308e70a5e30e86d2f46101f04765ee860c2.nq.gz
    ├── 003e2d0dc1c23dd06b26c221341c91491c0c0278.nq.gz
    ├── 00890eef76688f7b969f22a6b89ef34f86b7c8a0.nq.gz
    ├── 008d9561f1220aace486878ab6b10f00f0cbb37d.nq.gz
    ├── 01107b905388e5dc34fa98e332414786334d311a.nq.gz
    ├── 0159ba07e8cb7fbef03c9f8757f2471caafad9d0.nq.gz
    ├── 01983ac77b8c79eb430d13f89ea40bba3b29a89c.nq.gz
    ├── 01f04760739dd63724fd67c5b4be117323178ea7.nq.gz
    ├── 03a1235ee0d01f3c409ddec118cdac3c98e86169.nq.gz
    ├── 03fe0dad8e19bdda890b9d944130487e1a09e2b1.nq.gz
    ├── 04a9f98eec2a88d7caf46af06e1f710fb3ac4bfc.nq.gz
    ├── 04c5bcc857aae66b9660c032510082371f163664.nq.gz
    ├── 053f235e093080a871aa086fa5de74ef051fd540.nq.gz
    ├── 058319266f5a12d86bdf8e743466b57c44ecbad8.nq.gz
    ├── 06fc6db4943114f860504607b4e344ffb645003e.nq.gz
    ├── 0729636e2a3283825bb7525c2dd785eee29ee375.nq.gz
    ├── 0735d70ba4347e8d844e433ab35388f8f3c4b080.nq.gz
    ├── 07a3354f6c816a49b567270be9a14b5506aee033.nq.gz
    ├── 0861d57fc43f3bfb0a999188d3fe41d549a615f4.nq.gz
    ├── 0966ea46954e275c01cedaacfa5f404bfd85daf0.nq.gz
    ├── 09671241863c6c8cae79bf053dfd421bc5aa7e1f.nq.gz
    ├── 09ea92f754180a2e453c19cdae78406a6603edde.nq.gz
    ├── 0a35c45495f5e4b5758f37d7dca2c5943dd18df2.nq.gz
    ├── 0aa69cda4326a27d937bdb490bbd40f54abeb3f6.nq.gz
    ├── 0bf3b8c47ec1b93f836038504af6e5bf5cbe4c8e.nq.gz
    ├── 0c74dcc90ab0897364a77bfda10134f2f81e831b.nq.gz
    ├── 0cab9109c300e28224fd029ec0bb795075c328e0.nq.gz
    ├── 0d6c18342371af678fcb249f31b82a88f3ed0b1b.nq.gz
    ├── 0d6d302a6f8e31678621a4cd2bea60e8bc2e0f14.nq.gz
    ├── 0db61509db7d09403f841118ca96397fb6afee14.nq.gz
    ├── 0dd12a3f3b0ac59f46d90b6992317dd8487ed7cf.nq.gz
    ├── 0e2ed4c5fdbc83c0937757298b99d92426ec98fb.nq.gz
    ├── 0e3c57248d97ece609effda2e4cb8b5e1000a7e2.nq.gz
    ├── 0fbffe5ba3123a5b33d07005fc354fbd21359326.nq.gz
    ├── 10088154fbffd5b98bc0b5dfd75fb723020825d7.nq.gz
    ├── 10a8777f45d125fff3c268e2f6728c42bfa2646a.nq.gz
    ├── 111c5aeaa274a84a67a6c98f156d21b36d5537cc.nq.gz
    ├── 1138fba98da7abd2996710221d749023c7790318.nq.gz
    ├── 119a38c42035af2dc4f5df9a4f4c83ca26438ce5.nq.gz
    ├── 119e320560f0992a195a2ba22cf43a0c38986519.nq.gz
    ├── 11c72ea32d23339ed1924db27de8f66d56667f0c.nq.gz
    ├── 121b478cd1ec2863236a118bf40123611a100ab4.nq.gz
    ├── 123d3a341d3001cdd8ef41a6f4a2784dfa911e9d.nq.gz
    ├── 133932a6a5ab9b00436ed7a2eec0dd17b311b4e8.nq.gz
    ├── 13f4e693a1dfbed92368311c7f8ebe383b21bc7b.nq.gz
    ├── 13fac8460d4a6deabebce862b79dfc80ce02f15e.nq.gz
    ├── 149ebcb6a939a8cc62314e203b29323e6df5c62c.nq.gz
    ├── 1500e1cdf73d1f5287b9a83ec262542248692872.nq.gz
    ├── 15551ba7ebf05e8068bbdf23ca01d0700eb2bb80.nq.gz
    ├── 1577918953c9bf8a680e9f49cbfb2d6ade22e757.nq.gz
    ├── 16146e757a4801289974fcbc19b199eeebef4676.nq.gz
    ├── 175d3c86dccdba955b5250890e69b9d2a825f1fb.nq.gz
    ├── 17d15ba42e45e6a8033987d88afdf795f3cae890.nq.gz
    ├── 181c4d657a1906ec0b65de50720af278620f174d.nq.gz
    ├── 1829ff88e70abfbebb2b0b0e792c2c652137ffc1.nq.gz
    ├── 191e15307cb706144996c434f4d6e9afb9210963.nq.gz
    ├── 1927f9dc07b4818683540ccc135e07ce9ff62f0d.nq.gz
    ├── 19d883126972a7bc26375e6f0540c2a6346e505a.nq.gz
    ├── 1bb8e40449ee378749a79f75f70d9c1ee3ed079f.nq.gz
    ├── 1cb396fcc24ff43c6bc5100bafe9fc36883bbaae.nq.gz
    ├── 1e1f967e9dea9dfea994745045f62a0e04d3f7c0.nq.gz
    ├── 1e7dbf7472e119a28e0f38a126ff34ae3c05e8ff.nq.gz
    ├── 206a3149028c4dcc1d2dac14fb0a0d179ca731a5.nq.gz
    ├── 20a61fce85ff630617ddaf39b049ba396c1d973c.nq.gz
    ├── 20c6d9cc0820b11bf6f57550c8931a530ce1cb3b.nq.gz
    ├── 224ff2300ca62f58f1d91d4c3d4c6a096a7c5406.nq.gz
    ├── 22e390e7eb72ac67b2c5a68648bd0b733c762574.nq.gz
    ├── 23735421f5fd710f1e5d11fd0743aa56a9ebd524.nq.gz
    ├── 23f91a65e52388210e47854484d3560b915cb827.nq.gz
    ├── 249c331cce90a29d73bd27c98b8b3bb0f3aed39d.nq.gz
    ├── 252a288390ac8be4a678fb64abdcb18d381cc327.nq.gz
    ├── 2545d582db5c11cdfb64fa76ac70487d30a2b703.nq.gz
    ├── 256683234c42138a7b022b50e52140f24dfaa4c1.nq.gz
    ├── 260cc3d6a0410e772dd85c847871f7c412856c1f.nq.gz
    ├── 2702af37954d1c64c1340ff7158c1ffd214dab9d.nq.gz
    ├── 275313073211459114944bd519ffa625984f9882.nq.gz
    ├── 27a09e22fa988ff672166fd9f14caf201233c649.nq.gz
    ├── 28e01d619b6694db92619c711879e199dce998b2.nq.gz
    ├── 2a1f807efd4bf963acca3f40cae89cba18cce58d.nq.gz
    ├── 2aee475a997d4701ac78f10966a53b041be53a4c.nq.gz
    ├── 2b15c7109f6a2977853b73013dfc8b76b7af021f.nq.gz
    ├── 2bc70017a5cd17755b482593b4ed24f1ce8075a0.nq.gz
    ├── 2c200257ac02655dcc21ab89f9401fb6a861ee8b.nq.gz
    ├── 2d6410364cef78868234124915187da3822a46bd.nq.gz
    ├── 2e69bfa1de1ffb0dd40f0061539fb865e2058afb.nq.gz
    ├── 2eff1fef284972d607aeb311d7b184fda067898a.nq.gz
    ├── 2fe61ffd9058172a97627d99fbef5b75506c0be8.nq.gz
    ├── 30069144a2072116c2093b61f3a3a8bd03507c54.nq.gz
    ├── 30612e23bc49f634feaa99eb71cff289436e6551.nq.gz
    ├── 30c604211fc869f247c0b2e8f9e01dc9e224c742.nq.gz
    ├── 323af5b0c43c0acf9ebcce184eaff9106335ec32.nq.gz
    ├── 325cb58fd7f8763d7eb226daca9aa13d7cbb1c74.nq.gz
    ├── 3292e0f3c91efa54f73590115c7777773368715b.nq.gz
    ├── 32a921cd5567df0eadd3ef5a2f9d5c851dbb69de.nq.gz
    ├── 335003ef35fecd1be10e8f38bf387d66f483e1d9.nq.gz
    ├── 3394048fdccd51deb678add72ff5f17cea18ccf5.nq.gz
    ├── 3474e1552c007f86af7e7176c2fa533b7e5c8015.nq.gz
    ├── 34aedb58a6ce8d4241d05be21abc9541e33e8c04.nq.gz
    ├── 34b335159094d42b2658c02b11e53b6e5418b06a.nq.gz
    ├── 36e5ad451cde55108ea6b1ab43c070918d924f81.nq.gz
    ├── 3751e5c8c565f23cf0bd1c23ca59cd201a8cbb5d.nq.gz
    ├── 3762ec76acd3f11739cc76ef11243daf2db751cd.nq.gz
    ├── 387d7275f5bfdf067fd299453e507600b779184e.nq.gz
    ├── 3884a10f798366cc2fc91fed190b805fbafbcc24.nq.gz
    ├── 38a6f02142b6048002e9e2cd9c6d648c556270ce.nq.gz
    ├── 39a3be118e8dafd00426eab046126e58e499d40a.nq.gz
    ├── 39c5f2f3e33168da5949ba67ca36d1a7d2e9a07e.nq.gz
    ├── 3ad827d2b2b7cec0424de5db106386f25ffceb91.nq.gz
    ├── 3add80d1f317f16ae06789e99e0c0a042c9ac55a.nq.gz
    ├── 3b5ab38edb6cbfd9d2177b435347ca3c8f170792.nq.gz
    ├── 3c658100135372c66bec6906421940cc98f5a057.nq.gz
    ├── 3da97cd86de3ac34852027f9b359b5def00c6bac.nq.gz
    ├── 3de37d5d2c7f7e00c0daaf80d074b2220375110a.nq.gz
    ├── 402520c6871fe7da4b995f6d6310ba1580fbea99.nq.gz
    ├── 405ed99086caacd48ea6a259214ccc91fd177231.nq.gz
    ├── 40655de61ecf1de6ed97f09606b319305530e058.nq.gz
    ├── 40665734d9fa0f927fdc06b3c0ded1aae14124db.nq.gz
    ├── 407cb629cc18fc320861008ac3238aaa20da3808.nq.gz
    ├── 40aa331aaa60b044876f92a0a90bc7d1acedaaf2.nq.gz
    ├── 4101b76b26fb3442575b84c654f0eeddd8b931a0.nq.gz
    ├── 416f6b0dd38424bd5769886a7de079deeb1391e2.nq.gz
    ├── 41787668e52e92ab6b2f5c7c9bb58cee164fef36.nq.gz
    ├── 41c3d15ff8667fdb083dc37891b6bd99650a6161.nq.gz
    ├── 43d30f8a7886655813ced32449de884419bed59a.nq.gz
    ├── 43f0d10fa8751da6d00f2a0a2fed52116fd0df9f.nq.gz
    ├── 44a4897487bde0e01e3059edafd77da351bb09ba.nq.gz
    ├── 477753e0b3cc322fda0ff65a5a3aa4067f106de3.nq.gz
    ├── 48434239b62643ef1c6af913690677905cee20f0.nq.gz
    ├── 484bd89cf2b16d8a8af2759dc99bc6a212583dea.nq.gz
    ├── 48589e12365f9d331185d9e264a660580bb1ae4b.nq.gz
    ├── 48b8bf9072d8716346ec810e5a1808305c97d50f.nq.gz
    ├── 48c7fa51c8665566e4293ff692befa063290c571.nq.gz
    ├── 48e023d6480d87eb82ec7065d30cfe690ef99295.nq.gz
    ├── 497b4547cc6d38036aa38e4528caee24f5272c35.nq.gz
    ├── 49862c7914b16b867e12ac7b6cc26c75dc5eb3fe.nq.gz
    ├── 4a0a9e65a63958163ddfd85d8211bb5fa237cdb3.nq.gz
    ├── 4a9db86356b3ff4bdffb688c297bd2011cd34fde.nq.gz
    ├── 4abc9d9e2cd4201c5e04cc62ba5eb9924c6b5205.nq.gz
    ├── 4b133e36a44245101c1f8fa46f498013d5b34ab2.nq.gz
    ├── 4c140f00167f803e92774cc23522a0b0e456b1a7.nq.gz
    ├── 4c4650a70f39202cd2f671b1465f9b12c6813d2c.nq.gz
    ├── 4dec11533760cab67a11e3cf1769423544280970.nq.gz
    ├── 4e03bd22aeddb1ebbee7297630225c5182689c4c.nq.gz
    ├── 4ebe1bda430539de1aa202655fe811f119354a71.nq.gz
    ├── 4f048ca11114d63fabe04f7c62de89e126f7b928.nq.gz
    ├── 4f1df32609f6f6a404818e38d0246dc243604560.nq.gz
    ├── 4f2ee4d9733890ec7e7fc5348fe33ac145cfd332.nq.gz
    ├── 4f679b3f8937f67d2923fbe6346750e9275c5db1.nq.gz
    ├── 4f715bbdebb63e95011578723eaa2bd75852fd3f.nq.gz
    ├── 4fc234f1318aaf056069a94cb99323521f2780eb.nq.gz
    ├── 5018097ec97d8ad06dc824fd904c0d6e350425fe.nq.gz
    ├── 503a6ea9efd582b7546789a5fb3b865d68ed721f.nq.gz
    ├── 507ee6db7a904a676641132603b37020e08bb07c.nq.gz
    ├── 51355d11f82a8abd1741c39280b8493f4f1cc5c8.nq.gz
    ├── 51378befb8e0917eef4221ececde573dffd1b2a0.nq.gz
    ├── 521f80d46b9734fa2fcfdce87fd376ee387024a6.nq.gz
    ├── 52c752ff640a0ca7b572bedac6a3ba4c236c1e4f.nq.gz
    ├── 52e47f21f9f57436066f8a164d81a059bbc551c3.nq.gz
    ├── 52fb153c7a05d9650e5811697a697a5b9d58281c.nq.gz
    ├── 535a60b2e6c65c0ff5da564de300c60307104fe0.nq.gz
    ├── 53b08c833dac5ea2ec269df8b9a3a2bffa70134b.nq.gz
    ├── 547d320bde21615bd51963bb25ccea4a3eb11e2d.nq.gz
    ├── 54a2d2eb2fc3b75d7d8c1be14f6f62b8762cb7e6.nq.gz
    ├── 54af823ba22c595db92f9af38d0b2a24c105a5a1.nq.gz
    ├── 54e12016aa58cea42e86d7373668bc3688e218d7.nq.gz
    ├── 54ed4d3de77b72eed003ed3ffbd2cdf73eec6797.nq.gz
    ├── 5513b645d9c5d0cb2b100809a2997589000f7ac5.nq.gz
    ├── 558803ef26afb87b94e4e6011b5bd667ec5e89ad.nq.gz
    ├── 56b8d894dc12c146ff16e176a942b7dc44aa4562.nq.gz
    ├── 579ad9dc1f0f8bfa80bd03b41d721a37f8e25111.nq.gz
    ├── 588693800a21f190e6ebd65a51db2dddc63aa165.nq.gz
    ├── 58c94e9bdd234b7478d428be2a1a82bf5821104e.nq.gz
    ├── 58fea6445312bd5a0c626881b6096a58a8fbf03c.nq.gz
    ├── 59617cddeb67470714758220d3e837ff945f75e6.nq.gz
    ├── 599d37b5619955fb9c532767ce14af19d48e1022.nq.gz
    ├── 5a29d3ce291595fda6b2d2bcb130ec3565b23140.nq.gz
    ├── 5ace4600a1f26e6892982f3e2f069ebfab108d87.nq.gz
    ├── 5b566c4f836680a0e34fc49b44abf128ab128106.nq.gz
    ├── 5bde8b1e9addd5526027c92060ca712964f54c50.nq.gz
    ├── 5d344d447f8c6b330d9cbd38ab09054ddc0b47f5.nq.gz
    ├── 5d49e29a920440aa20272ac03788277d6decdd07.nq.gz
    ├── 5dbfba8963b9a880e9ddf2939a1a56822c5997a7.nq.gz
    ├── 5e5b7278ac8b52a7fb443731637679e1c9c3fae4.nq.gz
    ├── 60586ad8670933a2a1831182711cd006cbd151e0.nq.gz
    ├── 60a713f7413cc587db67f341611d5edb3893219a.nq.gz
    ├── 620a5e11f0eac3e31642255f7607091a1d118141.nq.gz
    ├── 63132f2deb1d5e56ce3deb0c62f9478f644196ee.nq.gz
    ├── 64092cccf8314c3bba454fc76959d81693747a54.nq.gz
    ├── 6474a8e38beebc8d3ed7cd6b994851980afe2dd1.nq.gz
    ├── 6486ea65e8d9fc389deb35064f192fc06efdd081.nq.gz
    ├── 648c97d0eca2aeb92e5343b5a20e6a6c98985667.nq.gz
    ├── 65160d0d29324825989d81a465306913352d2180.nq.gz
    ├── 659eb58d591b109fd93b6fd73c3326fca6eebb0e.nq.gz
    ├── 661258fc27e4751c281d4db76eac97eae114f0e2.nq.gz
    ├── 66482f4fb1b5396708510ee4851708ea36e9a29b.nq.gz
    ├── 665547a9c5c37e40b7084867cf6364c1234f0048.nq.gz
    └── 672a20f5baac709b257ad813725d41b0bb07922f.nq.gz

8 directories, 200 files
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

[quic-go/quic-go](https://github.com/quic-go/quic-go)

---
*Parsed on 2026-09-16 by [repolex](https://repolex.ai)*
