# Repolex Knowledge Graph of jupyter/nbviewer

RDF knowledge graph data for [jupyter/nbviewer](https://github.com/jupyter/nbviewer), parsed by [repolex](https://repolex.ai).

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
rlex download jupyter/nbviewer
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 5fde5fecfbe2c1bdb19d451ca7e2ab698f985aa2
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 5fde5fecfbe2c1bdb19d451ca7e2ab698f985aa2
│           └── chunk-001.nq.gz
├── blob
│   ├── 0172346cb0c596e9b2d1670d421088362bef5afe.nq.gz
│   ├── 03d9541dcc5fee7c84ecdd37d5377df96efe3954.nq.gz
│   ├── 05398f9639dab3148ba05a267386abc5782abad8.nq.gz
│   ├── 09da44ef4a96965eacc18b5ed3a0ae687a638236.nq.gz
│   ├── 0aa86c4e14f6c227e56e1e6427ed99368c188c71.nq.gz
│   ├── 0cdaf75b8262d8063688ebdccce58943c9ae3d81.nq.gz
│   ├── 0e398eb5548fd0156603f47d076be719a1f8127a.nq.gz
│   ├── 10673ec1b068a7556a27e4933f6ccb22c397d1b3.nq.gz
│   ├── 12ddded7d7ae89b6fa513fc5c1bca5dd62a9e561.nq.gz
│   ├── 145afaf93337089cbebdfa4fb8125ed5461c2237.nq.gz
│   ├── 14bfb62eaec9b707d8984948b62803eb58cd454d.nq.gz
│   ├── 17cc1f515cfb1eb5bceba99c8a718f39f062913a.nq.gz
│   ├── 184b7de2a8cca1e2ffb85549bbb52de9014a25ca.nq.gz
│   ├── 185ee1b0fce8580adbc76089bcf60303a7cc295d.nq.gz
│   ├── 1881489fa6d1b5c1ececfcb35519e769b4d15069.nq.gz
│   ├── 1955550d5c4dcc983715b3942ce7e39f72bed05c.nq.gz
│   ├── 19dbbbccb49869e802610a0a3211ba09840084c2.nq.gz
│   ├── 1bc82b03ab97f8173d664744abf93e831fe92a07.nq.gz
│   ├── 1bcea9fefc4e802aed1ca511cf6d50f88b7685b1.nq.gz
│   ├── 1c7864ba72873a895f64230fc9de34368ca2a03e.nq.gz
│   ├── 1e8788313acfded4f571e27bfdf1a09973323af9.nq.gz
│   ├── 1f8cc8c6a7573411a0cc2788047c5a6ad874a0ce.nq.gz
│   ├── 1fcdd9090ca67b29068ed6dce28896f8f02a4594.nq.gz
│   ├── 201e3f6657a066dd05d924c920a7492e82a0860f.nq.gz
│   ├── 20a672bf90347dccae123a65ce039b2f8f238323.nq.gz
│   ├── 20b7c99b9d44a8c1e61ad0e26e263ff61dd4c1e8.nq.gz
│   ├── 23a7619ce885f776ae800b3e940eb3ad2694f4d1.nq.gz
│   ├── 24d54721a2cd95fd3ffc9c674641d64fe11fab1a.nq.gz
│   ├── 252487c206a356758810f39e32021c17bb7dde2a.nq.gz
│   ├── 257f105194032a39502076ad77eee8315b5eec10.nq.gz
│   ├── 25986898a6247edbc472a6161ed7eede878a25ad.nq.gz
│   ├── 28a7488a81588dca36823c9f33f2fa8eeb76269d.nq.gz
│   ├── 2a4ca19df518cc6c9ba6625b11ff00f6690e42e0.nq.gz
│   ├── 2cba46ad0bb198b9145a85535bd9d1e83e2864b8.nq.gz
│   ├── 3040b45123ab71871ec5d95850b1d4f94291854c.nq.gz
│   ├── 30446c456ada138d0c5520dcd3e3130de75c327f.nq.gz
│   ├── 3bf6484a29d8da269f9bc874b25493a45fae3bae.nq.gz
│   ├── 3d2a7816f2e45cd63a0d5f087cca0796e942690c.nq.gz
│   ├── 3f4a671a34121efeabdb64239e8e267bad19ebb3.nq.gz
│   ├── 3f978b6c0f94e45262489a92b31c260c9dfba9bb.nq.gz
│   ├── 40561b13e06a7530dfca63b9a1678aa6c1557f07.nq.gz
│   ├── 413ee912f5f5d6bf76654e8148edf3aefcda8cd7.nq.gz
│   ├── 44f6851a3f31627faef9a2e968107bc06aae1d42.nq.gz
│   ├── 465ccb7f1ea925220b8808c2a64666eb5f35a266.nq.gz
│   ├── 467c69c8ee01c9cbcfc71bc924af704c7a39f428.nq.gz
│   ├── 4dd6cbce03def095b3c41434a3d722390a8eec92.nq.gz
│   ├── 5137d224e2f2b531d1d8dba6e1431fb4245af6e8.nq.gz
│   ├── 528ae17f4a59418cfd89990997e995de32cff958.nq.gz
│   ├── 528dbdf7f58386388cf446c630c09943da0f00c9.nq.gz
│   ├── 54ceb8ab99ed93a2f93742c2673e2d1110d74eba.nq.gz
│   ├── 5756bfc63529ef1a76a1e9472e4cac1134c44cb2.nq.gz
│   ├── 5973363b4f16fe3a257d69c7ed4fea3977a98971.nq.gz
│   ├── 5cb8f2d2a4be63b3f82296c8dad297b5919c90c8.nq.gz
│   ├── 5d9891f7b394da22cde2b60272aa055cfd02f213.nq.gz
│   ├── 611f1c1ae34803bc7356197b171095c321a8b699.nq.gz
│   ├── 66af4fe2a44c433c084bbeaaa83c63f5fac3132f.nq.gz
│   ├── 68d6a885269b35ad3f90f239b229a93e1b232de4.nq.gz
│   ├── 6a0561675924b474838cb971b79e1fd0f2e4b1c8.nq.gz
│   ├── 6b0e01b9aeb865165c918af61167bdd2d9e341c2.nq.gz
│   ├── 6b9163aa77622beffcfa47d27e5a6de04324c9bb.nq.gz
│   ├── 6be79ac2e8c5864278acca50bf4ef77490691270.nq.gz
│   ├── 6c1be97e7b900324d7ea39962abb7a8823ddbf7a.nq.gz
│   ├── 6d00c30c03c7454aaa04a04a0fab93fe5572366b.nq.gz
│   ├── 6e0f2c3888908237173d67a5fe33e0ac811a2b83.nq.gz
│   ├── 6f7aab0763a437d00a6186154ffcf943403af124.nq.gz
│   ├── 6fc7309ad482771d1bf4d3ee225a70a7d95a5840.nq.gz
│   ├── 707d9e03e3148636d89aa67a346dd9963be91766.nq.gz
│   ├── 71d29f725d8b7f76a33effc45654af4da1e9de06.nq.gz
│   ├── 72b796b1c1b07e5b2a7b9c84cb7109503f78b6d4.nq.gz
│   ├── 740f052826cdb22cf3fb43cf5b5ebaf0105fa60e.nq.gz
│   ├── 751e3b7184e58edcd7c05beee1d0f227104f10bc.nq.gz
│   ├── 755d860ec072d383dbded84f54dfac5e3f72177f.nq.gz
│   ├── 769f7ea291844f1ad5b8121837ed22dedfd21107.nq.gz
│   ├── 7992bb302fe72dfb173daa43d8be71942b1314af.nq.gz
│   ├── 79ca00a8b69d24d09d99d5a603de0283efdc8ea5.nq.gz
│   ├── 7a9f596ddc4b1ed5be01b69a3807b90aae06aec0.nq.gz
│   ├── 7f00972c0b7696418cb78fe5d9d500460f82bab6.nq.gz
│   ├── 80099bbeea4061f3849edd6902ff3c637c90ba13.nq.gz
│   ├── 80cb2ffb2b7f2d821237121fd429d47cd755a5b3.nq.gz
│   ├── 814ea8dbaef5fc627d45a3cb9671c6e70b66f851.nq.gz
│   ├── 817915daacf982843eb949a178c4c81bb90e3592.nq.gz
│   ├── 82316cf5057776f61fbf7ea175d64518d92f35a5.nq.gz
│   ├── 852f8a82f9838bae1faa612c017e68ca2f102659.nq.gz
│   ├── 853405bb35e7bf0eff3f609938214c1ad51b7099.nq.gz
│   ├── 87000e745c7bf86b7e9253d9a0c7800c01688c84.nq.gz
│   ├── 8c9a066c2416cbca865a77fd03589c2d85107da1.nq.gz
│   ├── 8e7cbde6b2b29e16d2ce52b6e402ba0a1df404a2.nq.gz
│   ├── 8ed31beae19cb710574cb953054596a124adb673.nq.gz
│   ├── 900dbc858f5e54debf8356c7eb4764b68cbffb9a.nq.gz
│   ├── 926df7e5506172b27b22895137b5a1058005ffc4.nq.gz
│   ├── 93ea597cb707b6c3f0d9c331459388fa8bdd0848.nq.gz
│   ├── 94aca96c5a2bb41a0eacb6a9d63320a71469fce7.nq.gz
│   ├── 95cd708639bd0ba8000a03d0be36fc089fe3b024.nq.gz
│   ├── 9c010dba5c180f4a708f816218a4532b94fde02b.nq.gz
│   ├── 9fc92ba9864ef6ab76c0afab3599860e91c823ed.nq.gz
│   ├── a2a3392abc4234fc803f1c391c1b00b0b386cd66.nq.gz
│   ├── a31093d012ecf7c1ef9e4d6ea9ffe9971fb5d28a.nq.gz
│   ├── a363bdf8328349a991671139a3afe585b76c8937.nq.gz
│   ├── a4716545fa6ff394c3b56e52236870268cfb5bc1.nq.gz
│   ├── a80eaf379af195233e96a9536a5f7b7a2b98dcd1.nq.gz
│   ├── a9181c9f23dad8d9586e85961018298823a46c90.nq.gz
│   ├── aabda049f8cccde3c208dbdb7f3bf0283577617a.nq.gz
│   ├── ab04b4a1b3f47fc15d890af14d510fbd6f876395.nq.gz
│   ├── ab5686e89076393550df2769b2624047525dd407.nq.gz
│   ├── acc9883849268c6fb603d72395ac4bc59bbd3ee6.nq.gz
│   ├── ad075a9b6acd4f4e9bea9053d6fc3124ee59bb4f.nq.gz
│   ├── ade52bddc0ea784e0d19e618b575dd5a6dda0bf3.nq.gz
│   ├── b070a0216ad768071c84995e2046dbefb18be4ed.nq.gz
│   ├── b0dafc8177caa69e0d969d5f49837f65eed97350.nq.gz
│   ├── b19309bd8055b48131d2752d3f5618fd4e6cc169.nq.gz
│   ├── b55db81074a8c4df43931d7b2678d912b5e61435.nq.gz
│   ├── b57a54fb230636f98f010475a1471bf3e95af4a4.nq.gz
│   ├── b8bc8abf8e519707d4974ab18a90529c9a1766b3.nq.gz
│   ├── b9008c271801621a3d695331bdd1504a439199c8.nq.gz
│   ├── ba01bc052afa494c9a909d4b5bf380ff3539965f.nq.gz
│   ├── ba8d54481e7537d0a62508247c788ecf2f7bb314.nq.gz
│   ├── ba90dc793fee084232892e3753a6a6bbcea4e32c.nq.gz
│   ├── bae920b91d9fd0ac9d86aadf9b876ca1476137a4.nq.gz
│   ├── bc0a61528b08b619956d9f1917e44260f5ce6c40.nq.gz
│   ├── be5c6f94b560661d614e9f1f30b89bdca347bb40.nq.gz
│   ├── c4d2c5d452ac85c42c8f3501274ca06244b5ced5.nq.gz
│   ├── c54c7d46f975d31ff03e5f6211699009a2bc4d27.nq.gz
│   ├── c61915f109764bf1727c0808805abea122baad46.nq.gz
│   ├── c99ab237a7e77fd149fba63e15e3463b387c0689.nq.gz
│   ├── cb56637cbf644ede9beee81798343b7116a3480c.nq.gz
│   ├── cc1a9db8df366282089c9979aee289ebebd16bd3.nq.gz
│   ├── cc7d7c6d0f9938de00536d40c9b1b42dd7bcf615.nq.gz
│   ├── cd613709815e494fb317c31b00437162f5ec3280.nq.gz
│   ├── cde606f8b3263f0cc844e60054248ad9a7d86f39.nq.gz
│   ├── ce0e417659ed6cc1e22bb1739efeeb53c2be1be1.nq.gz
│   ├── cf34ebf33df78c1ef01e9ff85c20a65b508619c7.nq.gz
│   ├── cf60842fadf6e05fa4692c54743e0c5e4de01ac6.nq.gz
│   ├── d7a42484e83841acfe50a08ab32c59105f03781d.nq.gz
│   ├── d8efcd730f4763e4fa18b64f0c8b479eab63bd83.nq.gz
│   ├── da2f9b570c8a554b3d3c9493847fc225fcede87c.nq.gz
│   ├── db77b0ae17fdbdcc555c27216441e70e48bf73ad.nq.gz
│   ├── dcf232ca5d86915e1c9e4f9f0ef0fffc64711d8b.nq.gz
│   ├── de1a8c370a30c383996531fde0df98b34b6a2d9f.nq.gz
│   ├── e07cb084cfc6570fff32d3f6e113922e53702b94.nq.gz
│   ├── e23fcea0d9272e4833fdb06bdb37a76be5608ebb.nq.gz
│   ├── e28c5f1263f6a1a4d647bf7e42ca5c649a9ea757.nq.gz
│   ├── e3a6487a01f6a41b1edf9687b2db5e0c960add4a.nq.gz
│   ├── e5fb3c62af99bd9d003921d7b840260e862fd0c5.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e70c88c58455c860d2f7aa52604f068a3f61b86f.nq.gz
│   ├── e73a106bdf98a7c47a68e9d2fc439da135d92052.nq.gz
│   ├── e78547b5de926603773161c1ad47c45848f2bba3.nq.gz
│   ├── ea3ab28b98d98d6605490c0a5e72d38a87221c5a.nq.gz
│   ├── ee7b5cb123fd27f357236d9e365b3fc9e89363a4.nq.gz
│   ├── f1cfb3785f3b1a76a3bdb87d9a34345d27705950.nq.gz
│   ├── f2e06bfa59fc8f26e2c47a3420413bdc11d4f83f.nq.gz
│   ├── fa71ec3411a3d4fcd7093a1bfef17a68b192f568.nq.gz
│   ├── fb549861b5f7d0ebd537b07a051cf4e320a500e9.nq.gz
│   ├── fb6a291f70b1ccde20da40259ef83148a1b85a12.nq.gz
│   ├── fc4d2db331d34b75f6deb8c3365a8e384f8932d6.nq.gz
│   └── fe2f3638883e7491f506f4515e22c3c1bd3d3f87.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 5fde5fecfbe2c1bdb19d451ca7e2ab698f985aa2.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 164 files
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

[jupyter/nbviewer](https://github.com/jupyter/nbviewer)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
