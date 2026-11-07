# Repolex Knowledge Graph of allenai/sinonym

RDF knowledge graph data for [allenai/sinonym](https://github.com/allenai/sinonym), parsed by [repolex](https://repolex.ai).

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
rlex download allenai/sinonym
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 3fdad803ba0e13f58c84d1c1ac1bedbfcb2927e1
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 3fdad803ba0e13f58c84d1c1ac1bedbfcb2927e1
│           └── chunk-001.nq.gz
├── blob
│   ├── 013f5018e0b57d3e518d500bc720fdd877baba62.nq.gz
│   ├── 02d10368c152e332de72236710123525fba276d2.nq.gz
│   ├── 03f4ecc6e0e779c8acab8afbd1e88f2ffdaa79a0.nq.gz
│   ├── 04875e88576a9af06d481523e73910618e23038e.nq.gz
│   ├── 04a70c87a093694902526d479aabe3f1e4f24e58.nq.gz
│   ├── 0732187efca7f9358cdbd1647f6e2b00144e7655.nq.gz
│   ├── 0a6e4606070e505c895fb2f5d562800ce4a72e8b.nq.gz
│   ├── 0c45eebb81f679e0816ed6e9dd94c05c3b65ce8a.nq.gz
│   ├── 0ca064584c31c812bef17f95969559d1c6440e12.nq.gz
│   ├── 0dd6b847b404f96fe7643d73f199de79c34464ba.nq.gz
│   ├── 0e3769e74a36cde03e2ccc8a162f150ea35a95e9.nq.gz
│   ├── 0edc149298d5be9e81ebf7238228928cdfa8c08c.nq.gz
│   ├── 10f4433f9b117c23b274e0f0750fa8f4303b3ad7.nq.gz
│   ├── 111b3c8dc1ced0d3fbf9df7d986c6100d6edbe3d.nq.gz
│   ├── 1124b424fce6a552ec3d9fd96cd2802c1fddab11.nq.gz
│   ├── 11e1a3a7038e4a0a376b243ed8e3652f525ab977.nq.gz
│   ├── 17d70902f4d9854327d28b8cc7a3567f8a730758.nq.gz
│   ├── 17fa812e462533aa335cf1aa48d0d05bc0223bc8.nq.gz
│   ├── 1984d32e94f691e1f08afdde5028a3f42158d412.nq.gz
│   ├── 1ce20e09aea6aa38ebf7e47bcbc3f714b167f0b8.nq.gz
│   ├── 1f61a4288e299bf10cab2e5e4a9a37298bbc4d89.nq.gz
│   ├── 23e2dc1cd3dd44576f67bd70c4f8465798fa00d8.nq.gz
│   ├── 2479e835be22acf062dddaff331fd213ea4cc43b.nq.gz
│   ├── 25ed821c60671ec1f57a3948a81b75a328aa9f69.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 29824f5e8d3240d2e23bab8716735a4067e15b16.nq.gz
│   ├── 2bd29cad2000b4d70d924e080e853cc2908a1b5f.nq.gz
│   ├── 2e4b8f48c724aba91712e66a89b8cbf02522f36e.nq.gz
│   ├── 2f40be6ab376b3044974e766e5ed8f5400f79637.nq.gz
│   ├── 2f6747849a1cf747eb14c575e1135be8774eef26.nq.gz
│   ├── 3017a57f57b973a3d7aa203c0a0d33903e67cae5.nq.gz
│   ├── 359d76540b7835410d856f4d7ecaee012ae1c171.nq.gz
│   ├── 372005e760a8e8838734b01cf26ae39e35a10d51.nq.gz
│   ├── 3757cf62c25348bb7f46de6945769197f15b9e04.nq.gz
│   ├── 37a3af021a8add4e7780f3b4f9aa52449c41ccde.nq.gz
│   ├── 38f4f8fe867fbf76f063ffc33d0daab9e1d58f9f.nq.gz
│   ├── 392473b7198289628bc25fe33ab8abf931aa211c.nq.gz
│   ├── 3b18510758754611affd6b0d876c4148ef318881.nq.gz
│   ├── 3d78bf3629f7119c0a31c91849b7f1159cc77995.nq.gz
│   ├── 3e138540a2d4750c2011bfa5744f43d26912e5c4.nq.gz
│   ├── 3e54fcfc84bb1e7dec48b25b47b3eecfaab3cf85.nq.gz
│   ├── 40b06e9a696126851baea20dff76b56c997bae39.nq.gz
│   ├── 42f3d153cb9d7072e448b9f1b7375b44556eb329.nq.gz
│   ├── 43256f5d596c42a0d40306eca9d0ac824fb90f9f.nq.gz
│   ├── 4356ec1cb43ebb58a69c5e5f507fc8d0b0b733ba.nq.gz
│   ├── 43bac8bd03c734d1d4ee5bf51affb0fb8a031045.nq.gz
│   ├── 44132f92c4839127e9f4980d9dfde1c2a636f9c6.nq.gz
│   ├── 4862c62ac4d2523f40697b439e9ccac25bc49c23.nq.gz
│   ├── 4930b44ae8af063828931ff0c33b1a65692b718b.nq.gz
│   ├── 49728eb46490bed891faf74248e7945f27c0959d.nq.gz
│   ├── 4a82401b1357174ff52d202ad9839f90f907e9e1.nq.gz
│   ├── 4c96c6dddf399b22d3a1ac3ae7561fde8dca2b1f.nq.gz
│   ├── 4d994114455241bd4ef65d7f81c68b97b488fbcf.nq.gz
│   ├── 50484813b1801fc33389910142b601faf36bdb67.nq.gz
│   ├── 505f4a3e8bea3c6b489ce5a01d0cd7737be4287b.nq.gz
│   ├── 52013b8cdf923ba18775ce74a2c49e0b79e47d8d.nq.gz
│   ├── 532faaefa734e3c524b35bb0907c50028106603c.nq.gz
│   ├── 53882574df0c36c8019e301c5cda28872c084416.nq.gz
│   ├── 540efc7ee2ebe6245c8616551b9c4908e28893ba.nq.gz
│   ├── 564abbfb19a58b75d09272a277601f9375b2aef3.nq.gz
│   ├── 56e5115547300054954ac964a692da9740f4b1ca.nq.gz
│   ├── 5735a22406396c55d6b595396d6538b1cc573ce4.nq.gz
│   ├── 58cad2aa51cf528ff48973d196e7e02f596c24e9.nq.gz
│   ├── 59033f4a126924de6d38a0b80ff5bbd26d8a00c2.nq.gz
│   ├── 5a6ecd4c3d9de4bca459f052565b031b7fe3a334.nq.gz
│   ├── 5be6c7cf66688d7ef30c0f53ee8dbc4b9cc7c001.nq.gz
│   ├── 5cf25a2775557023a005330071ae752c8d48d3de.nq.gz
│   ├── 5d29d89d36200778741724102bc2e409cb650731.nq.gz
│   ├── 601b149cac56dfdffd33eaad2001854bf8de04d5.nq.gz
│   ├── 6313b56c57848efce05faa7aa7e901ccfc2886ea.nq.gz
│   ├── 6415696ae31126667b2320d6b646fc1de5dc56d9.nq.gz
│   ├── 658a23d028d87708b66c9746547290e98d3ef71e.nq.gz
│   ├── 6633119b8b078bcc8a5ec4101e26d323cd5549cc.nq.gz
│   ├── 687192b6dc0b714d793133efd2ca13075f322898.nq.gz
│   ├── 6c60b300387ce68d853c5f27b19bf7b4c874b400.nq.gz
│   ├── 6d7ee0c23ab7fd7dd139590eb72c86799361c324.nq.gz
│   ├── 6f2002584e9104d621e0c8b4aef70baef1820aac.nq.gz
│   ├── 70891904430a3fd5d7c81119aa6109bd8d979d87.nq.gz
│   ├── 709a87b430122e3a1a42333b574e68343c2acc9f.nq.gz
│   ├── 73cc7495f58042373d62533609085780d6ac7a27.nq.gz
│   ├── 74305d47618630a09bc654105bde81fd19b48070.nq.gz
│   ├── 7759eec4ed2fb8022d925ca153f9799314be2c47.nq.gz
│   ├── 80e75172c084dfbd0e378b0af73e00fbb30ec8e0.nq.gz
│   ├── 817088a6072f96e996e620f3c170d4bef4487dea.nq.gz
│   ├── 818e7456f375e43a8149a24e19e7113084b10a72.nq.gz
│   ├── 82a14ff6ad6b5587b25bf3b34a9fd16e1292934a.nq.gz
│   ├── 8b28c1e339a97c0a70797b11a9ec9546e2dd1e5d.nq.gz
│   ├── 94330ec241783e3cbb90dbc8c82060f45d45e3db.nq.gz
│   ├── 94541471e51edc9cb5902eec7bc8c73542e93a38.nq.gz
│   ├── 971c94f8ea521bd8167ccab509afb934709dbf55.nq.gz
│   ├── 982971229775adac1dfbb10236cf953198334f05.nq.gz
│   ├── 99a9270bbab2f47c7af2eb1012c2dea52ba98216.nq.gz
│   ├── 9aab59356758725d020d3a03e61ef5308c6e23d5.nq.gz
│   ├── 9c05033a4cc701b2f18546d0c43a779cb833f017.nq.gz
│   ├── 9d98df71881380d35f81e52000ca635e666dc9d1.nq.gz
│   ├── 9e0dded721512a66c370e23a2a57f89b10408fb1.nq.gz
│   ├── 9ea29a73a897754d7387f9b0c3ed1872c15bca92.nq.gz
│   ├── 9edae6477437bf8880330718afd6b80d2164dede.nq.gz
│   ├── a0a540db4a8d6cf533c02d7baebab84ade6fafa2.nq.gz
│   ├── a0ef1ea804628b536c97a48b8d08620cf12f7321.nq.gz
│   ├── a11a766fb9ed39bcab5f7498893d5452ba4f1f45.nq.gz
│   ├── a2259fd1df203f03f96f3f73663927b6e9d94834.nq.gz
│   ├── a46069154afc3f321b78ca0ecf5c096b6a91569e.nq.gz
│   ├── a51b8fbfa69058c61be99292b9c8315d13f91193.nq.gz
│   ├── a6e2f560ef1d8d272c2ae2be9dbaa68da7551e6c.nq.gz
│   ├── ab65976205f56f51a33c3669a420fb5daf0aa8c9.nq.gz
│   ├── aba24552b9675fe48c55df659c784e66564e249d.nq.gz
│   ├── acd3b15f27b0e136854bcdb1298956679b8b34f0.nq.gz
│   ├── adf96400deff96d4186814053c754ec79db1cea5.nq.gz
│   ├── b0ef32c0b58b569166d4efb0b6011f39d280c396.nq.gz
│   ├── b123af33628eeecae784416faa179b11183aae60.nq.gz
│   ├── b128d41ab84f6df83b85a1c8f761ceaa5bfb7e62.nq.gz
│   ├── b15a7d964f25851cc85c5bf0969732b748a4662e.nq.gz
│   ├── b44ab1a4b55f70ac94ab79672d58f89f1e588efc.nq.gz
│   ├── b4f0522adde6ee0ffccc74f7193bc9427757d6fc.nq.gz
│   ├── b6755541dde7009e94234a078f47e96cce93f647.nq.gz
│   ├── b6f3b50ea7b2e8d3e79dd65c0f4698c4af8e2cee.nq.gz
│   ├── b7168bb6949e0b609f63b47113405cfcef518135.nq.gz
│   ├── b819433d2304c58549d61f98862c10aa98e8ec08.nq.gz
│   ├── b8447e363075e0b3e54fc3611daea74c0339ff4d.nq.gz
│   ├── b90497d723db659229bb817f86e8249a87ec0e11.nq.gz
│   ├── ba3d3e351aca5bd3b7b96bb48a9a5c483acbf092.nq.gz
│   ├── bb3e52ba83d6aba2a9c6c281a02125e3ac5335b8.nq.gz
│   ├── be8d78cf833caa433d48bcb7b4adf69c9a2706b0.nq.gz
│   ├── bf3db7bfb3d776baeac362c0a56b8a366fc7b512.nq.gz
│   ├── c11cd8f6c1b378e18c0d6bb65db5a3dcaa7809d1.nq.gz
│   ├── c585a31338d87faba8a43c5636f681e1d1fd623e.nq.gz
│   ├── cb68f4be758a8bc3bf4da3a45d59c7383de78365.nq.gz
│   ├── cd3c5637f74a99801aff0c6339e65fb0f681c6fc.nq.gz
│   ├── d0c1942773a3610fb72d4ef71a44dd63297a573e.nq.gz
│   ├── d4b9539b8bb21a50219dc50c46d28511b08e1575.nq.gz
│   ├── d5a880ce1e2d30343d50affc2c8e468c1c1d8475.nq.gz
│   ├── d6a0c72f867c4e134fdf036ddcc8dd79a714a34e.nq.gz
│   ├── d8b700ebf22f11588b53d136cf1d86ea40e6559d.nq.gz
│   ├── dbfb94da1309b2ed762c02fad8bb027ae957cee4.nq.gz
│   ├── de1f3a0a9a3da6dfb45aab9c98c46d9e6384ea82.nq.gz
│   ├── df0fb272495e8efa224c32de0daa722530e5e175.nq.gz
│   ├── e0694b912991942436e30f695bdde85534626bbc.nq.gz
│   ├── e109a66c19bb4ad68b6c974c323e62ed884ac25e.nq.gz
│   ├── e290fb5ab582f6840ca1b974aabd5c69e0792e1c.nq.gz
│   ├── e4561a6c8e202940a9da3477738640dcb77acd83.nq.gz
│   ├── e4c1dcc04c1413b1947d296f9407312e56a3d600.nq.gz
│   ├── e4c6b9222827ec9168b06cbcfb1fe4f6259aef9a.nq.gz
│   ├── e57a60ad4ce6453ca93fe73aa3ee27455051b831.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7e0040e3f19a7c1953b5a882e2fe9f4e2b3764d.nq.gz
│   ├── e7fd21258f95e814d6e1ce9ae72e020905880bcc.nq.gz
│   ├── e81f5b52c8008c1f9f91bd0bc9df0e576e71f785.nq.gz
│   ├── eb000fef493993c50214c0a328bab62a543ed614.nq.gz
│   ├── eb35d88d490a01ccd8f28d0a3d1a31d9915b12d8.nq.gz
│   ├── ebb5ad253e50878b50446ae826bf5eb3aef10d64.nq.gz
│   ├── ec3110ef03b557c20536f890eea05a14e8d0f784.nq.gz
│   ├── eeb3f2bbb9df9c7d045c8d930ccaf3076604996f.nq.gz
│   ├── f008535e3def76ef3368173c704d19cebbe70ead.nq.gz
│   ├── f044821aa03dc6d866308404d32921ec33bc20f5.nq.gz
│   ├── f14bee3a3d1009774bf2b3ee3248de384d96bd93.nq.gz
│   ├── f1ed6f79e1eeade3daf99593ce3fc44257d6bddc.nq.gz
│   ├── f36a68942ef175ab440f2f62c39b4ed31dc2281e.nq.gz
│   ├── f81d42a2fe278666f1c79dead342968a157f6edb.nq.gz
│   ├── f9e50dd52ee2154e1cba09fcda5e0082cae87499.nq.gz
│   ├── fb388f9ef98caa8e84c199f7268e07339619805c.nq.gz
│   ├── fd3d1288ba1042a306212ff21c60e9ca6ab9592b.nq.gz
│   ├── fd9ae4af50103cd06dc98b9041ebd6cdc7ff2976.nq.gz
│   └── ff7b8e6ad2b84ce3b8eec9994c277c2894555664.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 3fdad803ba0e13f58c84d1c1ac1bedbfcb2927e1.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 172 files
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

[allenai/sinonym](https://github.com/allenai/sinonym)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
