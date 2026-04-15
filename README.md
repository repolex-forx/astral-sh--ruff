# Repolex Knowledge Graph of astral-sh/ruff

RDF knowledge graph data for [astral-sh/ruff](https://github.com/astral-sh/ruff), parsed by [repolex](https://repolex.ai).

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
lexq download astral-sh/ruff
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b54922fd7394c36cdc390fd21aaee99206ebc361
│   │       ├── chunk-001.nq.gz
│   │       └── chunk-002.nq.gz
│   ├── lsp
│   │   └── b54922fd7394c36cdc390fd21aaee99206ebc361.nq.gz
│   └── repolex
│       └── b54922fd7394c36cdc390fd21aaee99206ebc361
│           └── chunk-001.nq.gz
└── blob
    ├── 001589c1debf1ad0085c47f3d0b69842218f0e45.nq.gz
    ├── 0017fe8889720267f6d414c97e70886bf3500e1b.nq.gz
    ├── 001931f9e8baef4cb4c24d6bbef14d8bef84dff0.nq.gz
    ├── 001a554163b3269d29c19d8d801ef0ffb8090ae4.nq.gz
    ├── 001a6098cddffb09ad1d5a06aa4b618b1ea556ac.nq.gz
    ├── 0029b89e9b77824541bea6260f871311295f8807.nq.gz
    ├── 002ceea3306865a4d45c0b7d526577f0b0d32ccb.nq.gz
    ├── 002fac596cb4c82b1a04e31a4c22416064be93c0.nq.gz
    ├── 0030d7bdc97d81e68ed883ccb714e896af976556.nq.gz
    ├── 0038f8b1518ff003854a3013f56d60c1579506d5.nq.gz
    ├── 004b7a2de2f575f7ef9c6e8d0dfd1d6e2a34048d.nq.gz
    ├── 0053e9e9dfac96ec7652c5699d82f781d0bb9cbf.nq.gz
    ├── 00544aa856f22321e59530ef6ca827e57ed5b420.nq.gz
    ├── 007097427b016f3fb9e907e4435a827415d92393.nq.gz
    ├── 0070d0d200fe234d308f7fb92b509e66f52c5ab1.nq.gz
    ├── 007a4ef75d67dc9ae632a4bdca61f62cef9ec3ec.nq.gz
    ├── 008343d91449e0fa9ce2e5bd6885f107e34957ba.nq.gz
    ├── 0085558579ae415e409097e33ac4fc226cf3462b.nq.gz
    ├── 008e68502946c5c8ef0c21b9974756e780e11994.nq.gz
    ├── 009aebe0d4c4be00aeaf5685b9130729497d07ad.nq.gz
    ├── 009ba794b77b6b1f0b1bfbd71733ae5aa6164039.nq.gz
    ├── 00a0e4a677dcf2d8d622cf5764a8dbf32f5531fc.nq.gz
    ├── 00aa3d1cdf43951a0caa3883180c32b5f759de11.nq.gz
    ├── 00ab19b271bc6c69ab95e71ffef5bd665625db57.nq.gz
    ├── 00ad084ed6c2ac30ea542bbc5d95d80c545eba24.nq.gz
    ├── 00b7245742c64af7511c224658419e8533e02ffd.nq.gz
    ├── 00c8f3023909441fc8c6acebf9a5390d4268a507.nq.gz
    ├── 00d55f68467416915eb5d4fbec392c86364e8bbd.nq.gz
    ├── 00eae242e889d9ebd0363856d42772b73a4b1dad.nq.gz
    ├── 00eee0db9234427c4992306cc5f9cc9cf2afaa97.nq.gz
    ├── 00f2cae754ceea6d296c338e7a1756f166cebd69.nq.gz
    ├── 0100397db388f64b58c84ff5135931708c1611af.nq.gz
    ├── 01043e77d4505c4d26cf7d5d1ccd756a7658fe3a.nq.gz
    ├── 01089b0c964cbfd31dd088043c45e16c6ef35553.nq.gz
    ├── 012db5016c98dea4ed85233a01060ee08937d58e.nq.gz
    ├── 01358120c2a9798fdae93355ca9ad5bc6dc69022.nq.gz
    ├── 014682e8e9217b79bc99aef77724c4a9aecf2fd8.nq.gz
    ├── 014b96b8e30a0d548a01cf906302586ac28276e0.nq.gz
    ├── 016feffd38472e751457f6042725cef9630974a1.nq.gz
    ├── 017b3947a8b22394c0b0f9a3553bfb5cde3a6d9e.nq.gz
    ├── 017e243da93f1ee8ad5fd3b5e3b7965c126336ea.nq.gz
    ├── 017e2b2b8b5396146c2fa985727e24a38951b3bf.nq.gz
    ├── 017f679115a064ab84a49492409d6f624215f269.nq.gz
    ├── 018367b341a24b6809f793e3385eef861cb144bc.nq.gz
    ├── 01873749f857f5786039a9231ca17911ad94358b.nq.gz
    ├── 01896580232bb913cdf37a205517ee6b3e61234f.nq.gz
    ├── 0193312898a7fdd8902f3bc763d48245ba5ee33a.nq.gz
    ├── 0194ab5c10d339a1e2e9f4c4bb9b4d212e4d7225.nq.gz
    ├── 01a3d6f58a5fc24b09662d7ca3d154fb4df7338a.nq.gz
    ├── 01b1ae356800e40bfeead67b707de24343b83f97.nq.gz
    ├── 01b5c9e6b66b2036f7b5cedd4cfb9aa9f5b87f2c.nq.gz
    ├── 01b82cd542f1f1d7cd58012cf3f67b400b84433d.nq.gz
    ├── 01bbf87c0012d98a873ba70deacd857badbf9c97.nq.gz
    ├── 01c9c002e32645335fdd450f71758474fe8f8a00.nq.gz
    ├── 01cf7e107dcfb3d7423858db5fb5cdb0cf4b89fd.nq.gz
    ├── 01d5a439dbaab706e4bec781650c4955da078b5b.nq.gz
    ├── 01e2dd6beabf89ee2210fd982d949e76b397111e.nq.gz
    ├── 01e9be2c0d597589691433f19388c2c9bdd716f2.nq.gz
    ├── 01f401e99a11adc423b21113050eb42b293a3b3a.nq.gz
    ├── 01f98587634c94b2292fc3a7eccbf7c4fc58dd6d.nq.gz
    ├── 01ff10a9ab42ee81cd830c2843a7438745cd5c85.nq.gz
    ├── 0202a8cb8fc8c4ef01c492f07c56334780d2479e.nq.gz
    ├── 0207b9329dab0cfdac265910cd301304d1cd4d67.nq.gz
    ├── 0221ec269ab88637bf04ee974da2ad9f33cfba43.nq.gz
    ├── 0229737c4b536128f15b468661bec08725b75252.nq.gz
    ├── 022e334a7a19d50d8721e205d9c8d6444e8ab06a.nq.gz
    ├── 0253bc44cd427b36300aed7d5ed393015e8778b1.nq.gz
    ├── 0256ba88ba81a839f86718de26d10e52ec25bf3c.nq.gz
    ├── 025add5fdd0bc2bef67df7c18ff4246c441cb213.nq.gz
    ├── 025eda7263b077718964babb9cb51c7d4d8af8e5.nq.gz
    ├── 026360e756ff128b6b5149ae56dafc1839a00efa.nq.gz
    ├── 026bbd7fe75efc97147b7f0435bbab7d3b77d302.nq.gz
    ├── 027482127777110f8e6b5fe56932d7bf423dbafc.nq.gz
    ├── 02813d0ac4b20af576cc2ab65ce089eb4e746628.nq.gz
    ├── 028a5e5a413304d9593ac7eb1c67d8295d24c698.nq.gz
    ├── 02a19f057d2c5c2064a5a86968305928ca704bae.nq.gz
    ├── 02b55a48846cf90eeb7a51dfb5ce9b46cdfa887a.nq.gz
    ├── 02c39544ca7a1220457e1e9e6fe868efe054c409.nq.gz
    ├── 02d35ab0c0f9932471ddd026ca46c68db836235b.nq.gz
    ├── 02da7e23d15bab5b51b10f3e7f0ddcd32ec0beb7.nq.gz
    ├── 02e102a7ba6fb5d26ee8ad73cc45f2bfef72b98b.nq.gz
    ├── 02ecf816e4371a5dd0f855768a8d8b335ee90dfd.nq.gz
    ├── 03016aa5ca0d1a3fc6a2bcaeee5c332e9ac0c622.nq.gz
    ├── 030bdd99cf00cb211d8f9cc16626ab28acb71088.nq.gz
    ├── 031164bad78ba8531ebe3a410284258a444bde63.nq.gz
    ├── 0311b233837ccbe32a35092b799980d33e76200e.nq.gz
    ├── 031773b92edf32686bf0821b05971109d0e14b94.nq.gz
    ├── 031e08412fb02d093856c9e70df744f8c2df2d06.nq.gz
    ├── 03281db7aca58ce74e423a0e5abe68688104c598.nq.gz
    ├── 032ad0e13259d1b78500ee8f1cfbf73e87fc8c98.nq.gz
    ├── 0332e48bc8401bfe60d0904db95b1687ae4b3ba2.nq.gz
    ├── 0339d4a010f97d736fe0a318d1568886f7254157.nq.gz
    ├── 033a2d511e07c9cbd307602443ef32865f697efc.nq.gz
    ├── 0342d4203495f80986639ff9c7a0243cadddd1f4.nq.gz
    ├── 0344ce16df878c0d89240688dedf475fd1dce5eb.nq.gz
    ├── 03551b0a0a93f528371c7aad365a7b9348fa0409.nq.gz
    ├── 03611f84d4c6d00e859b85e94336ae01ee98cbeb.nq.gz
    ├── 03698da5d6afce227fb8f5e13550b94767ecaed0.nq.gz
    ├── 038e5fcf64a24d3fc8c4e22445bf6930f65b7abd.nq.gz
    ├── 0393d76865383652376cb2bd5672e9ace7f96b4f.nq.gz
    ├── 03966e90ea777e906a217f743e122287510e11b3.nq.gz
    ├── 03a9caacb89216c54e4ce2894776ef8411ef9f26.nq.gz
    ├── 03aa2598fefbcc40e8f0f7880274c33a31ffcf1e.nq.gz
    ├── 03c7ea34d3bb6f05ab6b82c49ecd71dccb2cbb16.nq.gz
    ├── 03cb3c36feabde1da92a806cfb4834c581553b20.nq.gz
    ├── 03cd50db754c850e3b0f9f68e1d2895fd39dfa1d.nq.gz
    ├── 03cdf780c3a83572bf1bbf616a3e084112cda31c.nq.gz
    ├── 03dcc2980c52d2cc67ae04a8d1b1c2b4c47951d3.nq.gz
    ├── 03f74e7b11b543bbe07bae1120f9054625555b36.nq.gz
    ├── 03f9ef95f2589ce94596bebca6fbbfcff20b18c9.nq.gz
    ├── 03fc7b09f494ff79d95a3917d71528585eb3fd5c.nq.gz
    ├── 03fd0e76b98d6d9efd3947e05fb315de07133d9c.nq.gz
    ├── 03fe8c28cf619c227877ff016f875a83bb63a48e.nq.gz
    ├── 04086f5524d9513721a8c112ac3aaddd87ae82ac.nq.gz
    ├── 0425268563b408978a10563e2936f67cf09e5b95.nq.gz
    ├── 042fe887ec36d72a4f612b304c5b4fb9422c9d76.nq.gz
    ├── 04340e219c219ed9941fc3537a59191fc85e296f.nq.gz
    ├── 04355270d9c6865adfe27ae9d66236d996a5e69c.nq.gz
    ├── 0435e3a9fc6ba770e1dbc7437102669741da0a4a.nq.gz
    ├── 04391303d2caa4ec1f503cf0d001ab0b4d254e52.nq.gz
    ├── 044165e39b0e2c7abf24c982bc2a8dea7f79dde5.nq.gz
    ├── 0445c1746193bfa11efe38b87b815d268ae7329c.nq.gz
    ├── 045e8c733ec8c54400feb0233bc29b1716b36605.nq.gz
    ├── 0461eeea1b703a8a3d521e90d3226dc23d9c3b79.nq.gz
    ├── 047d90f30dc0626842b1774da4e76189cacaf85c.nq.gz
    ├── 0487770133434d0651d50184c37bd1523087614d.nq.gz
    ├── 048b2e59296cc1935e20522f7cfdf7ace068484f.nq.gz
    ├── 0494356fb0a582a75607533a537fb99b5a7c9bf3.nq.gz
    ├── 04969281fa87cb95ab2b80c5d57eedfbf6b1b75f.nq.gz
    ├── 049f396f639f28eb924659a655d4b9bd09db1a34.nq.gz
    ├── 04aaa8d8c498aa9bbe8cb67eb5f113d40d24cf71.nq.gz
    ├── 04ab35d22e774bb7c113aa804f906864b0e6cd77.nq.gz
    ├── 04b1d09e647759b026139ab363626c245e07a352.nq.gz
    ├── 04b837951cfbd4298d9632ee554dd06ff2e166c3.nq.gz
    ├── 04b9109982959346e4e7caeb04118f5875737be1.nq.gz
    ├── 04c5276bedb3b49aa6894d5803607f68b953de22.nq.gz
    ├── 04d9f9b1fa42ecf14a6ff3556e6d1bc687ddac0a.nq.gz
    ├── 04e9a2dd487de7fdffc46f7e6e920cfad789e2f1.nq.gz
    ├── 04ed9285de85ad82b013e69a292a0085b14a39a0.nq.gz
    ├── 04f6d6b44f880bc9b1b89bbe7cc2427b7fc15c90.nq.gz
    ├── 0519ecba6ea913e21689ec692e81e9e4973fbf73.nq.gz
    ├── 051cc542ca6c9fae499c82aa692a17703ee8b3eb.nq.gz
    ├── 051e7026062474d0be4ce51bed1449d37ff8f08d.nq.gz
    ├── 051eb28362a8832445ee03376e2e7707b855b474.nq.gz
    ├── 0528b96f48c7813c2ee503ec008401c7a7a10654.nq.gz
    ├── 0529ba2c8c2cf26fbf8eb4fa0d7dea262c77004c.nq.gz
    ├── 052baafcab781af966f6a74a471ab1b3ade83f82.nq.gz
    ├── 0537931402fce09dd0c565af1433ee4d2849655f.nq.gz
    ├── 054b9a0d2008d34fe26e8f3ea44e9b4d9ece413b.nq.gz
    ├── 0554b3e9569e21fe48d60b247555914de4f6867e.nq.gz
    ├── 055cd0548b3997bfeed8dd160d2d87e88af6a021.nq.gz
    ├── 056479e9184d9170407c76018767d1918c13a59e.nq.gz
    ├── 05761fe9967df5a1843b72c7740ab4d96e3ce186.nq.gz
    ├── 058c60b92440b9dedee2c6cc404955f39437f21c.nq.gz
    ├── 05925a02f18a82151f82a59030e5d12363c7f137.nq.gz
    ├── 059f9b80df572951f39c361fcf617c69c00caa12.nq.gz
    ├── 05b2395e072bf297c0a73b45f6375ce073dd4165.nq.gz
    ├── 05ba4616d513a7a9b208ac354bdf57525f3dc972.nq.gz
    ├── 05c361381644adf9a98553b2b1a3f965f855d255.nq.gz
    ├── 05cc97963f21e95dc7b37755a373a3384a30ed5c.nq.gz
    ├── 05d8b758c76a831a7d1ada01d3e1c55a5f4180cc.nq.gz
    ├── 05e3ebcd8c5866ec522dea785891bc87631c72d2.nq.gz
    ├── 05eb2c2a8b4ba1898e772070d7319b4bbaa0e3be.nq.gz
    ├── 05f3edbfce5403fe1afdbf2e1af1016da8d65b08.nq.gz
    ├── 05fbaf22c9c400e732a826031ea344bd95dda0f5.nq.gz
    ├── 05fdbd20f189d2666d782e0608a69cf811552802.nq.gz
    ├── 060a6879aad9daebad039a028d55bc4109cd1965.nq.gz
    ├── 062a61bebf50d1c4c13251611ee37eb464f15d56.nq.gz
    ├── 063199131ecd67628dcaa941cd920c0f2ce32f9f.nq.gz
    ├── 063adbb02b16f3239a37b886bd4bcc26fc41d305.nq.gz
    ├── 063ef5fd9605d51e64731fa46383c93a7a4f0b49.nq.gz
    ├── 06422b37187544414955a5e82d5a8f20f791e1e2.nq.gz
    ├── 06486f98179590609ba9a684623752a3d1986b26.nq.gz
    ├── 0660b0b97f85a5b23b6b8c86753aa1ca6cdef53e.nq.gz
    ├── 0669b9b51e4f2c1e2b7832651ab76e31d05b4571.nq.gz
    ├── 066ddb7c846cecc16825937ddb534af04f69e983.nq.gz
    ├── 067cbe927f6df208cc20467d463fc58a098a5773.nq.gz
    ├── 068f245637b5c8b52981d7d28f0fd5d2173fe678.nq.gz
    ├── 069024753f74b84a16d60324ce5cc969f8775f98.nq.gz
    ├── 069d635ce46e12131a647fdf027f6a78b42d1d18.nq.gz
    ├── 069e3c36ebfd68d3acf26db3467a1f345d512715.nq.gz
    ├── 06a08ddfe1dd1afef7b5c9b416568e5bffa971b5.nq.gz
    ├── 06a7ca1300184e0a9a7ae1da83d3b2b6dd108acf.nq.gz
    ├── 06aa7504f71402a5554a95809351492cd4fbed26.nq.gz
    ├── 06b513485a3d08285f8fd6a42d3b33430e583e4b.nq.gz
    ├── 06bbc8cdd8237ba62739102050767ed40b798b8a.nq.gz
    ├── 06bccc084a803362971a7bc02a203679d85e153d.nq.gz
    ├── 06c726dff4cbe9809161f069d308a2c618dc9c6f.nq.gz
    ├── 06ca9d1d25f043d692e0d753bd4ecdb8a26c075c.nq.gz
    ├── 06d0956121ba76d73b296311408b5d3497e9c975.nq.gz
    ├── 07043dd802d2730b8ca7e849566dda563989a3c1.nq.gz
    ├── 0704457cf8efaaa4378f13215e25b65d1b837b6c.nq.gz
    ├── 07127b5f052d5bc8c84c2f06f5b3144687824afb.nq.gz
    ├── 0714f923aafe4d756b652f66941d947ea72c6938.nq.gz
    ├── 0715c3e5d83d91d5cf417788ffd55f8ba293ad3c.nq.gz
    └── 071736ac3cbaef42010e98860fb8bb506e38454a.nq.gz

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

[astral-sh/ruff](https://github.com/astral-sh/ruff)

---
*Parsed on 2026-04-15 by [repolex](https://repolex.ai)*
