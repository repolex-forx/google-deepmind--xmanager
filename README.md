# Repolex Knowledge Graph of google-deepmind/xmanager

RDF knowledge graph data for [google-deepmind/xmanager](https://github.com/google-deepmind/xmanager), parsed by [repolex](https://repolex.ai).

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
rlex download google-deepmind/xmanager
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 25ea8d54a9677997165c5aa9bf5832275dd53c8c
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 25ea8d54a9677997165c5aa9bf5832275dd53c8c
│           └── chunk-001.nq.gz
├── blob
│   ├── 0035c683e6d3529aaec41b4b28d6fbf2639d0612.nq.gz
│   ├── 00462b5a0f867e32d3c0bcadd3b834ee198431c7.nq.gz
│   ├── 01260cf7ef0806b5722cc12532f6903a3660e77d.nq.gz
│   ├── 01caaf9a3919a7640543a8a19e796ed49375c0b7.nq.gz
│   ├── 02cae846d150bab7501580e11ad2fe2be32a55ca.nq.gz
│   ├── 03969aac63dbb5a3079f5aec52d851dce24c6388.nq.gz
│   ├── 039f6c09dc8b2809dd5ea68cdc5e948aa5ae1108.nq.gz
│   ├── 0835d9f37db3d761149b90b00ed6eb3d094af1a9.nq.gz
│   ├── 08c91b572fcafa270f8cdd29a0316b68983d2b7a.nq.gz
│   ├── 09a8c6683a6ae0839698afb42915ff04c9fd6186.nq.gz
│   ├── 0c222554d913ab71ab276b172af142bdaee5ec88.nq.gz
│   ├── 0ca5619a893f2e5c450e387ddeed9593090e2799.nq.gz
│   ├── 0e1e510a60eb203fa52c088bc1fd19448ce2b5e0.nq.gz
│   ├── 0e9f907e286b75ab2398780fa2a80c5211ae9f77.nq.gz
│   ├── 0f45f4eab49a90f05ce407c1b95b046c5c1cf032.nq.gz
│   ├── 0f8af3f1272fd014614f82aad7e6016a4388aae5.nq.gz
│   ├── 1150c7ea079b532b8788aa59345b123730afa332.nq.gz
│   ├── 125f8e07890b74269877b8833fcafab09a66a471.nq.gz
│   ├── 1284aea2b6f5f6aff9fea50190eb05a9d6096571.nq.gz
│   ├── 1462e1e83c47a9049785b166b3429dce83fc1276.nq.gz
│   ├── 15f64936074aa40d5ff1d65d577f2bc9bfd89b29.nq.gz
│   ├── 16130ab366a340acd73ffdcb0dc57e4a2b057e69.nq.gz
│   ├── 180e58c725d5b6b5be6b886e6ea541387439b080.nq.gz
│   ├── 183376fa8eddeb4ac59b142384ff6bf9659f2a7e.nq.gz
│   ├── 1a6010f7561fe443fe6939e22098cf0900cdaa70.nq.gz
│   ├── 1c05a013dee0ab9e909997f0f3de3e3a15b42ba4.nq.gz
│   ├── 1e7010ee5c5566ec196b0ba32a1601db2d790673.nq.gz
│   ├── 1ea27469fcb990a31dcee02de74c5b5ceda66f5b.nq.gz
│   ├── 1f92d70bed8bc5c8001cf037e83a4dd3c591285b.nq.gz
│   ├── 2283b9de981dc5181a63de88bd1b6672ffb5a783.nq.gz
│   ├── 23f159dea1a6e9edb11cbe8a2b05eeda8ad1b832.nq.gz
│   ├── 26c5102625944e411d760f5521aed899cfd2fb39.nq.gz
│   ├── 2836a1d0f18d1caced0ee9beed60b8ccf86e8326.nq.gz
│   ├── 28e69750eeaeff4543690644a4d1f656f78b8a14.nq.gz
│   ├── 2bcc1c11e09b6b6ec777ad6b08096af586a95e8e.nq.gz
│   ├── 2da9f2a33f81c3770e7c5188ed86247f058020cb.nq.gz
│   ├── 2e251e940f4298d531dd136e14153e9a05a65b3a.nq.gz
│   ├── 32634cc26037ff4baa541596920be27302eb32b0.nq.gz
│   ├── 33c49df10ca293a067332bad72e210ad61ee5dc9.nq.gz
│   ├── 34429ad2cbd77c5a29ba41a48d660a612ee78884.nq.gz
│   ├── 360abbb91e0da07381899b4f0cee521e6ba7b650.nq.gz
│   ├── 36debe4a0bf6dfe9a12a12930973292be6304cff.nq.gz
│   ├── 3711455060a910df4b05b9d6088fe1b0b7368a90.nq.gz
│   ├── 38a3ec4db5c096f4c834b87c3a95c15fcae488a6.nq.gz
│   ├── 39d3dc8a5d4525ee54360d93ab53cae5fb957746.nq.gz
│   ├── 3a2a090a2cd6bfaba9813483f087f383ac2c77ae.nq.gz
│   ├── 3a92dfa83d721a4f9b1f4e3a0adc60bcd0b066ba.nq.gz
│   ├── 3c76f8218f70d92f5b59970662e38989d6f523c9.nq.gz
│   ├── 3c8d236f0b251ddd09b1c900fe05f1d08ce23615.nq.gz
│   ├── 3ca4b6332dee3372ae463952a8325480e28d7668.nq.gz
│   ├── 3d70a9c0fb8ac9491bed1697c275a4d34a1b2b9c.nq.gz
│   ├── 4044a8b4854c208a7bfc192d218f8483d2ec412b.nq.gz
│   ├── 4125ed1944fbd44cb0347221eea245908226663e.nq.gz
│   ├── 4196af4a7ebd7f88ffb801d3796533f721865139.nq.gz
│   ├── 431a8b03f3b1676a363cdd7cebf639b7cb8cd057.nq.gz
│   ├── 4414cd6aafbe9f300af78f1e49a0f1dcb3fb0527.nq.gz
│   ├── 44f2a121d535e64931f02abda954e8ad0fd04570.nq.gz
│   ├── 451354345cbd04a288f0c165a5e942294ea2901b.nq.gz
│   ├── 4863b6d18c17f02dc39d58c70f5f1c8a9edf7aab.nq.gz
│   ├── 49ccfe1905ba75540dd43acb8bf4f013f870e1ec.nq.gz
│   ├── 4b306f0134ddc3cc7dae14f577349023b576625d.nq.gz
│   ├── 4cac713dfe25516684cd6c11fde514a9d059233e.nq.gz
│   ├── 4d087effccaa0c4141c7817b9eaf6998dfe67818.nq.gz
│   ├── 4dfc44e25a8eaed7b8b7661cc0ad43be40889993.nq.gz
│   ├── 4e9f42a2b075e10c131557bbeb1a714b2beec07d.nq.gz
│   ├── 505eb1a2685164199bd3d1c06ceb221230be7db7.nq.gz
│   ├── 526de0b9b65e08198184807b75ef8c79b72f095e.nq.gz
│   ├── 539f4847e26917a00c0bc09dda03ad6a0299cbbf.nq.gz
│   ├── 5521cf351e4ebad1063909d9e0857dcf8fe1a612.nq.gz
│   ├── 5584cc5278357c768a417f42c0ac56cb9b0239e4.nq.gz
│   ├── 5636e19685931fa05cd86a298a10b11bd7525d34.nq.gz
│   ├── 56ef6c1d58bc815b44612057633eb8161dd0db36.nq.gz
│   ├── 5895443c3bcc9f9d220ff01497dbcfda34c83f51.nq.gz
│   ├── 59b77f1e963c576075f74a21e609d1c6f09d710e.nq.gz
│   ├── 5a3dfc6587ef9829d77ff6f0a3feaed912e8f6be.nq.gz
│   ├── 5d3ab39b1c3b988c89eb4ee878e210dc8716a154.nq.gz
│   ├── 5f824d36e91ead098e9864fe441b500ba14a4819.nq.gz
│   ├── 5fe92f8d9d337d7722c9e3bd9075d0897df550d3.nq.gz
│   ├── 616bc5587d04dcba445c129cf8301e8292089b59.nq.gz
│   ├── 64843d86b79d833bf1a4e147711272058765b1ff.nq.gz
│   ├── 66e99fa87e328e1d6a54f7b028c78f46bcc7e7c0.nq.gz
│   ├── 6c87e881adfe56111a4fd05b3ba16ae4e0448fa8.nq.gz
│   ├── 6eaf24e1afbba30a48e4b7d0f5579e3f4290e227.nq.gz
│   ├── 719df1db0fbe9376311e94fc47ae2a02f4483f64.nq.gz
│   ├── 71c317e936bce594a95a2259d83656e12e35b4f1.nq.gz
│   ├── 727ce0088d034215251b6eb08ffc39a6987f7f48.nq.gz
│   ├── 72b33051a853894610c8758cd4d52e317f56739e.nq.gz
│   ├── 74d1a7b6410da461909d1e4b7a3e1c4d82ba1bf9.nq.gz
│   ├── 76343b7927029b900cf9ed971be2598d356bae35.nq.gz
│   ├── 791a4fcc72d74daa1df99a15d46818a85bbbbf93.nq.gz
│   ├── 7b8fede27512fa90286419c8623b73d895768688.nq.gz
│   ├── 7c1da5cb7d5d1e84c75ae92d4fdf399141321cde.nq.gz
│   ├── 7ccdc98a4cda2fd3d327d09737b5618e9406d900.nq.gz
│   ├── 7e05a1592ee11323adb302d060452c59bf88f67a.nq.gz
│   ├── 7f3c2864b4f6c5f1a666c3f7bafe33a81dffcdfb.nq.gz
│   ├── 7ff3fa40925a49adec00fa4921ad2bcceb54bea3.nq.gz
│   ├── 80a165135b56b602fee8af76e696b21de954e29c.nq.gz
│   ├── 818acde07b3bdaa8a5bde05fff55d54f5249ce66.nq.gz
│   ├── 839c1530db236cf443f904191ea5e4824cba30e5.nq.gz
│   ├── 84f1a653965a750a8a06a8055a8997556a8942f1.nq.gz
│   ├── 8555ba07b4a8bf155238e8940d02c72ff4ed6370.nq.gz
│   ├── 85aa6c31b356e1148f8faf6f0a8737d9a84500fa.nq.gz
│   ├── 85ccad7944fb3ac81427aebb298cd0e0c7f4fcda.nq.gz
│   ├── 883f67dc9e8f9d52970b078c07f5a8cb563142a5.nq.gz
│   ├── 89e71156ffcbdccf89345dd79b4f60858359eb1c.nq.gz
│   ├── 8be37ae3fa68a78c626473e172c9c39faa88da2e.nq.gz
│   ├── 8d5338e28621ebbda4d3f24d29c453ab8e49f14d.nq.gz
│   ├── 910b1703f4979edda787f905d1edff9e90aaeb31.nq.gz
│   ├── 911fb510d3767baea7ebe4c6807523c1b4f5e534.nq.gz
│   ├── 9576cda7cdeaf5910a563f9c07faba8ecbcecb45.nq.gz
│   ├── 97441da27b17ed4f1edb7aecefc0ab807287340a.nq.gz
│   ├── 97e9822e6128374bfe34244e323f0f0bcff41991.nq.gz
│   ├── 98078188833a7c5b7dd64d5d03cf16a2d0508937.nq.gz
│   ├── 9b61f69413c80143d7bcfa22d1ae35d307c7a45c.nq.gz
│   ├── 9e3be86d402796ac41bb294423a8ee69ea445b0b.nq.gz
│   ├── 9e455ee406de8f755872bffa541ac0533a1bb037.nq.gz
│   ├── 9f2fbb09129170316a82b5ae5fbbe0db4884dd47.nq.gz
│   ├── a40778d95bcabdbc23e2438d4e3b76f0d2385654.nq.gz
│   ├── a4240748c7614ea93cbafe720a924e92859da42f.nq.gz
│   ├── a57435174c1e22c3cd2537d55aab59b86b76c42f.nq.gz
│   ├── a613d0e7f6e37c1b1184e6eed4cf434c27617bcc.nq.gz
│   ├── a72384bede23fb753f015ac7bfe7a4398c87d41c.nq.gz
│   ├── a74ff06f0458535b37a7c66625c61184c637ed5a.nq.gz
│   ├── a78a0a44ddad1669b528e0c01ac56184e899bff7.nq.gz
│   ├── a7c6c916950c3eec8779434ca68d5e48bbd63ece.nq.gz
│   ├── a874e3803b80b74d90ce2fc1dee47ef2a3c5ba02.nq.gz
│   ├── aba90d8c1b51cb5bcb13de11afd9a10783fa5bf9.nq.gz
│   ├── ac6c89c7b99689afec129340223338acd8c7eba7.nq.gz
│   ├── ae5cfb786eb6ed61119377fc7c93f16a4148c190.nq.gz
│   ├── aeabebb928fe397cb51ea2f74caf2daeaf3aff93.nq.gz
│   ├── aebf6cd3928bc6a166528c6c2d3b002ffc6f742f.nq.gz
│   ├── b02a0624bfb1d9b02b0638d56335052283faac2f.nq.gz
│   ├── b1b05aff8d05cc7d2ddfd82e95cf794f7d08db1f.nq.gz
│   ├── b1bba96243cd878ef35d625867bac8388f5fa5c0.nq.gz
│   ├── b2db2fb8e5fe2876b3fbf03ff5627f13df9ce039.nq.gz
│   ├── b2f79fda90e903cd180155b1fc4a9b308fc1c918.nq.gz
│   ├── b49bae8db41364370be0298111bc48cc50217d84.nq.gz
│   ├── b9c5a934debe9a0c281e48d48bdd6c675b26d6da.nq.gz
│   ├── ba7a67a21e4593ac262407c1a9fe1e836854e43c.nq.gz
│   ├── bb0789db9d8d17d357e3dd95906e04b7758eefe2.nq.gz
│   ├── bbb010e8b92fa703ea31a6ebf01efde85f35c987.nq.gz
│   ├── bbcd168bcff696447c59f6d9debfd8c97c864aae.nq.gz
│   ├── bc3021f321073f4d63e676a49aa94c8d279e67d4.nq.gz
│   ├── bdafad82576d7016fad55e2591fa75c5e5957deb.nq.gz
│   ├── bffbbfabd2eeaacc9fb7ba602e09337e8f5227b4.nq.gz
│   ├── c248d3b9b03f2796986e8409bc2d1cfcc3c5e315.nq.gz
│   ├── c4d07ecee3c6f8308ed82ac812026416e0ebb02b.nq.gz
│   ├── c6697e8da738f0e4d3a3be32fbcac787927a3fd6.nq.gz
│   ├── c79e7b803c090c90722053e6e2662baf8dbdfe25.nq.gz
│   ├── cbb897e3d1041e11c24321ba294337ef44deeb2a.nq.gz
│   ├── ce5edb09fadf40625d63facec62dd8616a1bd7bb.nq.gz
│   ├── cf89b74c0f7dde129afdf9335e87ab70e4dd1bab.nq.gz
│   ├── d0a703dc24b24d0cd96adf2063eeb45974cbb520.nq.gz
│   ├── d0fdb7b1e962e033de12db9ff9f9ba50245acf24.nq.gz
│   ├── d1b17f1317ac166cc299178f2cffe3ade410e843.nq.gz
│   ├── d36f55dd5f4407a404ca510945df30cbac9f222e.nq.gz
│   ├── d3ad236a06aab59b5c20ab8e27c9c16e7949ad86.nq.gz
│   ├── d4a88f6423c1dde051ac8901f0d003cb8277f575.nq.gz
│   ├── d645695673349e3947e8e5ae42332d0ac3164cd7.nq.gz
│   ├── d7bcab4f590edf40ce0c44788b2fb6a9322e5a33.nq.gz
│   ├── d9c1235348cd32f34869c368a668b0dad493486c.nq.gz
│   ├── db6b2b085e9fe256cd5538e8f08b4bd84ac9d442.nq.gz
│   ├── dc98987377387ca45b1105fd2140dccff1054eda.nq.gz
│   ├── e197cb2c71ff33132aa841d4b1809f58de2442f8.nq.gz
│   ├── e2969fb2b2d0bacfaaccdab4d1b3c9831bae1d1e.nq.gz
│   ├── e6a3f97bf005b2d9b586952dde7a64cb129df370.nq.gz
│   ├── e6aa753b81b017014c41525ce4aefff6e7d469f5.nq.gz
│   ├── e777dd50fbd2e6abce07dc0be5a8239c0a863378.nq.gz
│   ├── eb837b7ad03b03238db806f86eca22d097e333b7.nq.gz
│   ├── ebfbd98a776373fb015deacdf1210d1ff29762dd.nq.gz
│   ├── ecc832de8fbc31ec04086cf494a4ebfc5d4132aa.nq.gz
│   ├── ee504a8e7b832c6303006a1eb57b210ec54d4048.nq.gz
│   ├── eecad1b0abc13d4d05e9e68b04f311fc5ad6aa5c.nq.gz
│   ├── ef57a4b9d618a116599debd174064829b624913a.nq.gz
│   ├── f0173254d9b20bb8d219d95d26ac431f181dc974.nq.gz
│   ├── f057e97bc7f26d023a384033f74cb97b2fee4f88.nq.gz
│   ├── f0af8867ee1d675b307161a968782eed65f60d4c.nq.gz
│   ├── f0c2f2e012a2e32ef5695376f3c8a7ef620d2938.nq.gz
│   ├── f1885afc80870f89c944a75e062f109adde38165.nq.gz
│   ├── f40be129bef02620fd69e531b7823b8af7c8c77d.nq.gz
│   ├── f4b0caf9faee8a9c382680ad14162a9cdfe8392a.nq.gz
│   ├── f6a5b4e979b9bebe32e388aae2ba7513a4ddbd94.nq.gz
│   ├── f6e4e83f4bc66061a6b4fa5aef6f7a30afb8d784.nq.gz
│   ├── f6e724906f112ddaada4e96ceeebbc344935b2a9.nq.gz
│   ├── f8cb557790a709554a16f41577693492af26d295.nq.gz
│   ├── fad7870ee4c4ba2ec97507d1ac6ba3679cbe91bf.nq.gz
│   ├── fd350a4fdf78e9c823659e873e1b621e031bc0d0.nq.gz
│   ├── fd4763eca420fe1a8f53312af6ef8cd75391c5ae.nq.gz
│   ├── fe1250f859ada8ea48127ebc050ce8864843d577.nq.gz
│   ├── ffafd31d00f72972a14f93774652928b9ebc12d6.nq.gz
│   └── ffcd8b84fd06460a31359df5966ee95b24ecc455.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 25ea8d54a9677997165c5aa9bf5832275dd53c8c.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 199 files
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

[google-deepmind/xmanager](https://github.com/google-deepmind/xmanager)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
