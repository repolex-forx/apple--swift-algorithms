# Repolex Knowledge Graph of apple/swift-algorithms

RDF knowledge graph data for [apple/swift-algorithms](https://github.com/apple/swift-algorithms), parsed by [repolex](https://repolex.ai).

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
lexq download apple/swift-algorithms
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 87e50f483c54e6efd60e885f7f5aa946cee68023
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 87e50f483c54e6efd60e885f7f5aa946cee68023.nq.gz
│   └── repolex
│       └── 87e50f483c54e6efd60e885f7f5aa946cee68023
│           └── chunk-001.nq.gz
├── blob
│   ├── 00c2b2832a6850cffa3aa653abea1942bf6c6eea.nq.gz
│   ├── 0292a17a6e591c0499b97bdc699ec7c219247351.nq.gz
│   ├── 0398a3f62b072c215ada10b280597ddff4aa99d0.nq.gz
│   ├── 0446ef696be702eb7b922dd839986ba39b800e4c.nq.gz
│   ├── 074f8d05b468c665419d077906c7d3a8ddf5fd54.nq.gz
│   ├── 091985dda49d25f172d3522c53e464cce64f80bd.nq.gz
│   ├── 092447693eba141f1c788facef5ecddecac87746.nq.gz
│   ├── 09d647c0bf572cf7dc43cd46b6a03163943e5987.nq.gz
│   ├── 0bfcbff3847e7ccf1b97f366bf839451f4588691.nq.gz
│   ├── 126ed6e61b5b4be38a0892477d2f83afacde729e.nq.gz
│   ├── 13e52cc5e5a61b595684cf48785eba0a5a7467de.nq.gz
│   ├── 13f2f69b9f7ad0ed740ac4b8df6e7a2058adaae9.nq.gz
│   ├── 181547edace14415aa795f81e0cf11481bd2936a.nq.gz
│   ├── 18d981003d68d0546c4804ac2ff47dd97c6e7921.nq.gz
│   ├── 1e7ba489128ca95c81ae06bb82d2b38bcb0044c1.nq.gz
│   ├── 1e938429234e658849d84ee4b9ddf1aebd8ef4f6.nq.gz
│   ├── 23b8a87f6da104dce2f6b21fbf49da4b0075675d.nq.gz
│   ├── 23d141646b00e4b51f647340287fdefe5ec15be9.nq.gz
│   ├── 26ed376d70612c55365e1ddcc5cffac65dfdee57.nq.gz
│   ├── 282b2862a1cb557a78e5f9ec449d0de9daea7b66.nq.gz
│   ├── 2b0a6035582f1c83c23011c1190bb23846a824fe.nq.gz
│   ├── 2c567c2bcc6129296f50de271d131fc2c520d378.nq.gz
│   ├── 2f2b5b80a79c872dcfca6116596b551c29d7f6c8.nq.gz
│   ├── 33c5f08d2be50157402e098a1b3e87832aac16f1.nq.gz
│   ├── 34d284dabd4e2452d1cf75e56cd32f3a1faa4348.nq.gz
│   ├── 388422c1662c3b2974db35431a962c30123db55d.nq.gz
│   ├── 38a82a9c0e4c206383b1c63bd3655ef38bd184b8.nq.gz
│   ├── 39b785e396e6a1d214209b5d192089fc120526f0.nq.gz
│   ├── 3cfb26930a45a06a6fa99f417da1e88468928598.nq.gz
│   ├── 3df54438ad6c0538c7fa2dfc9efa0f0cdfe5d190.nq.gz
│   ├── 3f16882309d6fcd2e07090cf867c144657876c2c.nq.gz
│   ├── 45fe58743e51b1b3a6ec8775447d0a4ec1604f79.nq.gz
│   ├── 46d38ce9838019a6fe7926bf9d393603a62e2f8b.nq.gz
│   ├── 49c13762daeac70887c8de9cab51943320ea1687.nq.gz
│   ├── 4c9bbf2b28ef3784d75275882a2a8a35de318093.nq.gz
│   ├── 4d0fa0c0b6a1a486c44f13b37808808a6be7e6c6.nq.gz
│   ├── 4ec863d6b63447a7ba12a87efcefd35a1552c60b.nq.gz
│   ├── 50068218b0a59d4c8ec69d6e5c88d37318ad8b5d.nq.gz
│   ├── 50c76680b25aaab6f75d660b5a4067247edc9954.nq.gz
│   ├── 535958a35b32649de75be2d5d6c13e394fa58e97.nq.gz
│   ├── 54199fa4ae1b185e147a0775b4dcd4f07dbe48fb.nq.gz
│   ├── 54678aa3a2f6ed3102eced66466213d232818bab.nq.gz
│   ├── 572050ec894423afcdadc369e760d3bbcbe045fb.nq.gz
│   ├── 583f781c00bed493c7c98304c6aa0050ba4b07ba.nq.gz
│   ├── 5b985cbd41bf0e6cd7d719ce76c6cc1073526018.nq.gz
│   ├── 6080a0ce657c28f14967f20161627b6fd568d9b5.nq.gz
│   ├── 6183cf32ced39458919d4501cf9a58cbed0de61b.nq.gz
│   ├── 61b0c78195f2d00acaf658000eeca6ad406a3a29.nq.gz
│   ├── 62711077c726ad0f652cb43fe20ac9c9fd69b025.nq.gz
│   ├── 6298b6d6e34e49e8ef3ce517553df3f9320c87e2.nq.gz
│   ├── 63f70eb895387de4d61d385bef35d090b12b4415.nq.gz
│   ├── 66d39de0c47ed42515b91d50330d5aba41cb0300.nq.gz
│   ├── 677663ca2fb68b457c656e8145963420926d186e.nq.gz
│   ├── 67e43776f4507967f8b8ae16a76da5f66a2d8eb3.nq.gz
│   ├── 690659e53f0adc053a3a5febc898aaa5cfa96146.nq.gz
│   ├── 6badaff8fbd92c737f39448a97a4aa0a5eaa2714.nq.gz
│   ├── 6dd4a8fff2dc3e3392174d3148bcc00f6361ee70.nq.gz
│   ├── 6ff99e05c6c37a69ba5bf040ee003e59e6b98159.nq.gz
│   ├── 706c4ea23b58e3d098683a616a91ec6ffe13a499.nq.gz
│   ├── 74f774bae54d435e3d11bf7d119d8828e5386f21.nq.gz
│   ├── 753e02315057c943a6ffd2d2e98a2129420430dc.nq.gz
│   ├── 76322d303ce6daf7299aaee3ec756cb148bad23e.nq.gz
│   ├── 7eb9e7fc8c851788c0a3c9e99529f33fb9a1a494.nq.gz
│   ├── 81c8cb0e4da424b9e1f45d51b412c6f2b89eca1e.nq.gz
│   ├── 83b24916e10212818a3521f4cedba2e5334f8b0b.nq.gz
│   ├── 85073ab81aea02466b936d81058acafc54aea408.nq.gz
│   ├── 89527178da5aa918a163c30879de6bc78f04162a.nq.gz
│   ├── 8d369bbebb3d6fe01dfa18fd6f5fce82d3bfde89.nq.gz
│   ├── 8dcb18cca097d2714c496fd325dee302d6bd39ad.nq.gz
│   ├── 8fbe390b345e3508d5c94c2716e9aed0d1d447a2.nq.gz
│   ├── 919434a6254f0e9651f402737811be6634a03e9c.nq.gz
│   ├── 92db185bf8c91de99f3656475b7cb522c9536050.nq.gz
│   ├── 939378bc828a31f15be7d19dd087ac63377ac8c6.nq.gz
│   ├── 96372af60c16f441c36492cca85c2b186cc5ba53.nq.gz
│   ├── 97f98cd58b16344f5b0bfa955ded4c4ba184fd77.nq.gz
│   ├── 998f03f156aa4897d37bdc7e143fb03414a0b6dd.nq.gz
│   ├── 9b33126fea3ab0db26daf7ea6fea0ac90926cd59.nq.gz
│   ├── 9cb5a74d365eab4c277e54d7f106be970ea69942.nq.gz
│   ├── 9e895583756546930d9b580e04c1533e4c376b5e.nq.gz
│   ├── a23d01504984e72c4c061e97cf99e0d1a3e78df8.nq.gz
│   ├── aa296161165e1665493efba9943ec6c1e0193a67.nq.gz
│   ├── ae1243fb7f85ecfb51c2e7f2c91ce3122633c31c.nq.gz
│   ├── b04932ef0be8d0029f610d6ea03c0d31b350c165.nq.gz
│   ├── b8567ea9d44ef4b87b3a581872c9cb70817bc150.nq.gz
│   ├── b94f662d09437ccd588feb83abf47cbbe6b70d86.nq.gz
│   ├── bc07a39c81d928326299b26a068d252fd5a9fe22.nq.gz
│   ├── bee7b8642600db8c528bd242d10eeaf586ff4ead.nq.gz
│   ├── bf91612b51e9ec2dec841c5d5c7ac5113f83b25f.nq.gz
│   ├── c1939d8030c0d9d1497784e636f8f9161e19cacc.nq.gz
│   ├── c2b39e7650af1c35a8b83b7921c287d17df41910.nq.gz
│   ├── c3318c38c5eb5b933bcbc9379063892f91394983.nq.gz
│   ├── c567f2ce9db8505cb634adb9d547609b348322a9.nq.gz
│   ├── c5dee1d1538ebd7c10796fde770612c1daf41c8c.nq.gz
│   ├── c648234658f4464d2e58fa13bcf363292e8471d7.nq.gz
│   ├── c6f14485ee707a46fdd10c2402cf823d8999c67b.nq.gz
│   ├── c75c9abe45a61676647b5420f4cacb5122769da2.nq.gz
│   ├── c7c21dd94f0262dddd9a98bb532493028f272af9.nq.gz
│   ├── c942adf44e828168393e0a695073158e5b2b781e.nq.gz
│   ├── c947b63cd9a9f5e7155a6ca10d0af49e3fe872bf.nq.gz
│   ├── cdeeafa930258b78062bd4dc042ba4501e1ace59.nq.gz
│   ├── ce5671cfd38cc576b5676bba8834fb51426b98d7.nq.gz
│   ├── d28c4a10b8b90ffb60c270d1bebb94c29450f807.nq.gz
│   ├── d34581a6a9a78a54c58616bcb0d808a12de05dd8.nq.gz
│   ├── d45ca0e040f2fae100726d06f280e4b6f146b88e.nq.gz
│   ├── d4894882c1414cdeb3a7e4a52d599bb4bf612a21.nq.gz
│   ├── d5611e99de8a8fe9dbd9a2a4f7fb3f7ef71436a7.nq.gz
│   ├── db973061b1ba59d76fcbc81a8e0a7b67bba457f4.nq.gz
│   ├── dd8473dcdebaf500b3f2a609487faa28b9efe089.nq.gz
│   ├── e36bf969f0cb9a57caf42b70ec3d73de116a7023.nq.gz
│   ├── e5bed603583dbf358fae30178f7824cbf9caf245.nq.gz
│   ├── ea6b5a7ab977885582b8152f963405cfc35a3b87.nq.gz
│   ├── ec9d8536c0c6d80a51cf45026b7bebea8fbee979.nq.gz
│   ├── edfe8a3e564059de2f32fad81b2aa684fd727fac.nq.gz
│   ├── ef78c1de0433ef1259195956418daa25481750ed.nq.gz
│   ├── f07fe52a4048eac5e68640e2dfc20727f099b97a.nq.gz
│   ├── f0adad5e095d6f90f7da4264ae4a8ae2a04b1193.nq.gz
│   ├── f3d9bce70d043c25f6fcfee5f8098efbbccb1bc2.nq.gz
│   ├── f9719f380f81e738b4b8369c91812fa3bb47dae1.nq.gz
│   └── fb673393dad32def73992aea26e654f961514cf5.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 87e50f483c54e6efd60e885f7f5aa946cee68023.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

14 directories, 128 files
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

[apple/swift-algorithms](https://github.com/apple/swift-algorithms)

---
*Parsed on 2026-04-21 by [repolex](https://repolex.ai)*
