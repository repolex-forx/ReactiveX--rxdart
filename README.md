# Repolex Knowledge Graph of ReactiveX/rxdart

RDF knowledge graph data for [ReactiveX/rxdart](https://github.com/ReactiveX/rxdart), parsed by [repolex](https://repolex.ai).

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
rlex download ReactiveX/rxdart
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d1f3ba64f71669a137489341009345f59ec84614
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── d1f3ba64f71669a137489341009345f59ec84614
│           └── chunk-001.nq.gz
└── blob
    ├── 002c25954274a25b440198c9efe235749f845d76.nq.gz
    ├── 006257625b4e8816221649d1a04d936df5897af3.nq.gz
    ├── 008d2b52d49890c2c33a401c11a1b2efb1819558.nq.gz
    ├── 00e4bd03c36e79f30758b1faf067d6ad362b1e6d.nq.gz
    ├── 00ea1f84cacd012cf4b1ae55b8e28d6ce56aef03.nq.gz
    ├── 041a3855474575f3224e068641f65d9623220a8a.nq.gz
    ├── 0468afbee3f7b988b39b9e84c2dcf77eab9c05f9.nq.gz
    ├── 04a021ce14190390a42ccf594394bc68bf4c5382.nq.gz
    ├── 04a776672591aaec706eeb08072d02a6b99cb0ec.nq.gz
    ├── 050e4568931e92974c03ecd29f8ae7343973cca1.nq.gz
    ├── 053cb99f9df166c58b0cd5d4417718df6f723574.nq.gz
    ├── 0564402d660c722695b1503761db2547afdb26db.nq.gz
    ├── 05e6073b5b836438d093dcdba1f16461370c6d4b.nq.gz
    ├── 06952be745f9fa6fa75196e830d9578eb2ee631d.nq.gz
    ├── 0775b7f3fa864afecbe638794415abfea3b70acb.nq.gz
    ├── 0827f11f6f7d721cc8bb42f3c0b236741a810df3.nq.gz
    ├── 086af6a739be72524af4711cc8c534938a71dbf1.nq.gz
    ├── 08c3ab17cc263a50bd1d67b108c0689c69e7aba8.nq.gz
    ├── 09d4391482be68e9e4a07fab769b5de337d16eb1.nq.gz
    ├── 0a3f5fa40fb3d1e0710331a48de5d256da3f275d.nq.gz
    ├── 0a741cb43d66c6790a2a913fa24c8878fb1ab7b5.nq.gz
    ├── 0b0a37dd2e30d24cefed99004b775c8267190d1a.nq.gz
    ├── 0cb55243972e0768423867b8796f6cfe5eda0f49.nq.gz
    ├── 0eb921a7ee9f004d7a7e59e0ed5d48f302f68056.nq.gz
    ├── 0f3282c4fa1e49db11d30c261c44ca98146b5579.nq.gz
    ├── 0f3813162e9cd829bac51350e5d28086abb182ef.nq.gz
    ├── 0ffce3d393c57986652eb388222f3c565e609248.nq.gz
    ├── 1050eca4caff18d491af5898f25adf0e647161eb.nq.gz
    ├── 114d08420710964feccbf0658d930bd3d8a8e137.nq.gz
    ├── 12535fa71c688ac8efc3bd55afdf5e00a8cb706a.nq.gz
    ├── 137bfc08a56698b81ed4da965c10b13e68753649.nq.gz
    ├── 13b35eba55c6dabc3aac36f33d859266c18fa0d0.nq.gz
    ├── 143a18e964fd8d31bb0069cbb7e8718fe93710b7.nq.gz
    ├── 152a8da55c6741cc90b0c202a9eaa58ba3673b56.nq.gz
    ├── 168657af5194f79eecdce8f8d76c318997e267d5.nq.gz
    ├── 169436abd9f225abcd5e8438f7379c366f5558c8.nq.gz
    ├── 16bb2480805c7a770fa30706dbbcb4e41fe6ba8e.nq.gz
    ├── 17831e50fb8f6649f92005b705261348e0d94164.nq.gz
    ├── 17987b79bb8a35cc66c3c1fd44f5a5526c1b78be.nq.gz
    ├── 17d71145be30e26dbe9883388afa334f64644e84.nq.gz
    ├── 18c2439a781367aceb05fc20f2dcafcda5e1e02e.nq.gz
    ├── 18d981003d68d0546c4804ac2ff47dd97c6e7921.nq.gz
    ├── 18ec60c2e40907726f07a1eec2de21413a8a6385.nq.gz
    ├── 1a0541f992fc5c20ff3ec17798125ed6f0cd9c08.nq.gz
    ├── 1b6c8d83524a8ddbd16aee15232f30fac09479c2.nq.gz
    ├── 1ba0f821e5f05f48a09b5989fec38d80eee05aaa.nq.gz
    ├── 1bcaebb3441c3e938eae2472f505eb3da699c078.nq.gz
    ├── 1c19f4b86e14805d1ac6fbc3603929b7a65ab1bf.nq.gz
    ├── 1cbed852a99aca985f097af1d956061919f44f70.nq.gz
    ├── 1d526a16ed0f1cd0c2409d848bf489b93fefa3b2.nq.gz
    ├── 1f7a845d56d02038028ab4a25c9967bef5df3a23.nq.gz
    ├── 1f83a33fd4f2c45c5ffa5b6c1b729c431fd445fc.nq.gz
    ├── 2003c7aa915dd8e2a449b56efabf4cc562e80312.nq.gz
    ├── 200afa99a98df915b720380dffda820958b29da0.nq.gz
    ├── 20657f644e4d11e63beb901a21dfb991c1f41e81.nq.gz
    ├── 20eb09cceb970aad1610a9e68f568822bfa8fa93.nq.gz
    ├── 2213f06920070842b231884e757684c542a6049d.nq.gz
    ├── 2241739815f47f56ca85761be92f39d6d74bd5a8.nq.gz
    ├── 22a76a62234f2d439c8209e38590f81b0b0a64bb.nq.gz
    ├── 233a8eefc488dfb8bb28c18932c32176b9b1bc86.nq.gz
    ├── 233fe946bc9938898388fec91ae3dc837d7daa84.nq.gz
    ├── 2346d765e49c1c67655bc4097d24fd54a236c19c.nq.gz
    ├── 23d2a68975c1d3020778daa143dd4263478f7500.nq.gz
    ├── 25a8a12705436f6da959cc8f9976919e99e50b50.nq.gz
    ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
    ├── 28c6bf03016f6c994b70f38d1b7346e5831b531f.nq.gz
    ├── 2953880e40688c434ee23b183ee5eb0124d3a346.nq.gz
    ├── 29c5cbb4cbf9d49ae87bbffcd9f1553ccdde9d5e.nq.gz
    ├── 2a8f4fda9ef98765743d1022dec5fc69257e2d9c.nq.gz
    ├── 2ccbfd967d9697cd4b83225558af2911e9571c9b.nq.gz
    ├── 2ccf3ec966aeafb362f5bd7b9bb8c80b885b2fd1.nq.gz
    ├── 2e1de87a7eb61e17463f7406106f6c413533cecf.nq.gz
    ├── 2e2833951d078c61e85e718a3a7bb4f37e740339.nq.gz
    ├── 2f1632cfddf3d9dade342351e627a0a75609fb46.nq.gz
    ├── 2f3c918767b807d1354c5d59084e022b97996bc6.nq.gz
    ├── 30133e784e46070b5320a4fd4c6e79b8efac69e5.nq.gz
    ├── 304732f8842013497e14bd02f67a55f2614fb8f7.nq.gz
    ├── 306a7dc138bb142e4ecb2010aa13073f78f72e57.nq.gz
    ├── 307b08115da0bed3a556fe441c2582a3a3d4adda.nq.gz
    ├── 308a2a560b42f17aaf3c36e4e9c8cd07182fbb7e.nq.gz
    ├── 30cff7403da04711c46979a06f6bf8eb10ee088a.nq.gz
    ├── 326c0e72c9d820600887813b3b98d0dd69c5d4e8.nq.gz
    ├── 335833059c9aaafe06d6053f3cc014f42b10573b.nq.gz
    ├── 33a68c9dd78b7c884b6e2e4117e9168dbeea91ca.nq.gz
    ├── 3466d12003549965070e93ae1d36f5d864e02019.nq.gz
    ├── 36b0fd9464f45b33f482e64bea579787e142affa.nq.gz
    ├── 36e21bbf9cf407bfa7968f28d35675da72c6c6c0.nq.gz
    ├── 3731def805355999e27bfa840f4e8a6e11fe8eda.nq.gz
    ├── 37a2c4905939f4b243fee706195977f93501e1b6.nq.gz
    ├── 3879d54755798567f0f318d63340508d5668eb96.nq.gz
    ├── 38e0747b5e8bdf2afa8850b1f17ece3cc43ec977.nq.gz
    ├── 38e7abb6188c005b2eb4e9678854bdd603e5e89d.nq.gz
    ├── 394917c053a04daa76d8b94f0a02db0bd99e1034.nq.gz
    ├── 3aac27dea1f22b905269a0a81ea80d60d8c8a629.nq.gz
    ├── 3ac65458734bf5861475e17eb03bdab5a4763a5a.nq.gz
    ├── 3c57fcdfd4fdd0d38d4f6eb7eac01d07c28aea2f.nq.gz
    ├── 3cc05eb23491684aae1c51ce94668a142bad5125.nq.gz
    ├── 3cc869c4addea3fd500f93ad84ff47b68a9d93e3.nq.gz
    ├── 3d43d11e66f4de3da27ed045ca4fe38ad8b48094.nq.gz
    ├── 3dcf0c18dddaefefe3844feb093569f6a2f00801.nq.gz
    ├── 3e0a36472daf65616db5cb2b0727ee54e4bd9d67.nq.gz
    ├── 3e89a0ee4da763905fa7fe070aa15a5646e460aa.nq.gz
    ├── 3f202d853571986fecfeac6b50c13fa16d5e1dec.nq.gz
    ├── 40f2a39b464f8a7fce9283e16822dc7fbe2b9ac1.nq.gz
    ├── 42bcbf4780b187e80025b7917058bcb882012aa1.nq.gz
    ├── 43667602b11b08e989dc3ba124bebdc4c14a2b80.nq.gz
    ├── 44580fbf3cf67346956babdb7ff701e50718fa58.nq.gz
    ├── 454fea264774bcdcffa025fae4c52c8dd3bf6162.nq.gz
    ├── 4567c02c038ee383380f51b12dad451174a61161.nq.gz
    ├── 4651d2ffa082ba2ef1ed7ab10b8556e2cb721234.nq.gz
    ├── 468bb1b95e45085e702f5c7594e4eb79cb89fbdb.nq.gz
    ├── 46ba5ea6591710db9adbee61624bad374c2a3527.nq.gz
    ├── 46d64ed1ab3ba51d644dac675fb77ac2f926c7cc.nq.gz
    ├── 4789daa6a443eefa7f3f729164a18351e06e9800.nq.gz
    ├── 48674e02b4c391d9195103b04c8646b1db32e31d.nq.gz
    ├── 49154fc9ff87c59eec45ac0bf8ae76b6da5a23a9.nq.gz
    ├── 49dfbb326aac5e702293d22f24fffc50f75c0147.nq.gz
    ├── 4bad4571d4790486bac11c769ec5a08bacdb39f4.nq.gz
    ├── 4c2d4b0ae9dae8076e0338bc41e00d12dec7add7.nq.gz
    ├── 4cde12118dda48d71e01fcb589a74d069c5d7cb5.nq.gz
    ├── 4d6372eebdb28e45604e46eeda8dd24651419bc0.nq.gz
    ├── 4e7591eff795059b946a737514887f28401d19da.nq.gz
    ├── 4fa92703aea2a4d53cf5e9e14201bd5cce675e62.nq.gz
    ├── 5181428bc70ff40626ae4fd53e9834cedd43b893.nq.gz
    ├── 51c8ca3f53e47fe1506cb01bd9d77a5c2a8dbac8.nq.gz
    ├── 536f483322f2bd610df234f802bb1d8f3c0ea914.nq.gz
    ├── 5407620deaf05ee5450f9bc94a99e04f393f05cb.nq.gz
    ├── 5460b1dfec62ba9bf31e775183fc2888991bc24a.nq.gz
    ├── 549a20b3af84fce3c80abba0da0a30a6913d7de0.nq.gz
    ├── 5644b666b5b41861c4047bf86546c28df86a7b15.nq.gz
    ├── 589251671b49f609349dd33f740b686151bf458f.nq.gz
    ├── 58ba111d8457bba7aef00d578d98e0960f5a442b.nq.gz
    ├── 5921bbd015a9d4255340d87cfe68d5c09f116c8c.nq.gz
    ├── 592ceee85b89bd111b779db6116b130509ab6d4b.nq.gz
    ├── 59a72e90be12e0aef464a1c3173b632db6237fd8.nq.gz
    ├── 5b1bfbea5440838b4fe0e848cb02b124cb02da29.nq.gz
    ├── 5b3389ca9d2b4393e4b59f817ea4301b83612dc2.nq.gz
    ├── 5bb5a414b8c9731308a2bd479203a4c1ff202168.nq.gz
    ├── 5d027b29c7fbab0179d2caa5e772446cf268b4f3.nq.gz
    ├── 5e521951b5b93892baebced19b7678fa5188fce5.nq.gz
    ├── 5ec0d264513983a1d4fafda5c7fd16bcef68529f.nq.gz
    ├── 5fdcb4e6dd371f16c20e776bac6bb1e91af1424a.nq.gz
    ├── 5fdd3759f52c540fdd9782031e318f336563bdbc.nq.gz
    ├── 60099b19452b3f285263aaeb44df879ab74bdf45.nq.gz
    ├── 602e5f2843ca05c387ed41b613082395ee800291.nq.gz
    ├── 61f3bd1fc504c3b78271416d8cfd14faa1dae2b4.nq.gz
    ├── 634a5ae74b3121d4eeec7f6b981c64d3c0a7e1cd.nq.gz
    ├── 649c771dfdd9d2c0c7cd4c3eb6d8c36a2085619e.nq.gz
    ├── 658042ab9da9793c24bfccbb1bf353ef01f0970f.nq.gz
    ├── 65b0f2f1c6c26fceb3fd5b4659a099024fec951b.nq.gz
    ├── 66a65d1e4a79f230031ec0e0959a721039e7282f.nq.gz
    ├── 6709c7b68921f00c5da191c53d469f616f61622d.nq.gz
    ├── 67e6847dcd09e36e7323b6f2c3e493227678a072.nq.gz
    ├── 696ad560c92a12b6e878f85189390b41cc22ed36.nq.gz
    ├── 6973372e289398018123e531546bd3bb7a19cfef.nq.gz
    ├── 69a9ebc4aed31bdb28cef46ac841d2ba4c831a80.nq.gz
    ├── 6a84f41e14e27f4b11f16f9ee39279ac98f8d5ac.nq.gz
    ├── 6da0652f05f28fc6950cec20ebdfbae89b665479.nq.gz
    ├── 6dd809659a8ccace7ccee108d024d33cd4f936da.nq.gz
    ├── 6ee9bedc448981589b29600e1612cf12a10bbb2d.nq.gz
    ├── 70693e4a8c128fc4350b157416374ca599ac8c7b.nq.gz
    ├── 7071d731a73fa20257c1e0a1da997299fec2831c.nq.gz
    ├── 72271d5e41701cfbffad74d38640bf9cc7c1f7be.nq.gz
    ├── 724d6ba10b9d608220f38d74bdcdfc57b06922dc.nq.gz
    ├── 729d44cd8f85c8e0edefb27804f4b8fa5ff3eb33.nq.gz
    ├── 746188de66ad8d5b4464c8204b9affdd0061ca82.nq.gz
    ├── 746adbb6b9e14b7e685c91e280a4d37a672afbd8.nq.gz
    ├── 753378cc891c25a1694b314de051d8451fd25368.nq.gz
    ├── 75aaeb337844fa22052c909aa90d1ab249a17fda.nq.gz
    ├── 75ac99d23fe5e54709ea99e0a0d61ce94830135d.nq.gz
    ├── 75b2d164a5a98e212cca15ea7bf2ab5de5108680.nq.gz
    ├── 75db638741b2e26a2330794c71200082f0529017.nq.gz
    ├── 762e1af1921a8923a475581aa325739733ac49ed.nq.gz
    ├── 77bc47250855ad2e0ad4ba3a7762ffa5c630419e.nq.gz
    ├── 77e241f8f242df6f822f9ba7447e2d4713b67337.nq.gz
    ├── 783a5275aee2bf1d89a69579ef701c5db31ff559.nq.gz
    ├── 78d90635315fe421f771a102193882ea8f909b8b.nq.gz
    ├── 79790fdd3923228e8964bee2c62c9e6e0bf3f54a.nq.gz
    ├── 797cacbd71e6a8ea156e9c9a462b26e0a9e9b8f3.nq.gz
    ├── 79f57b3d79cd83d51f6d1e9f25b2f4219831c44d.nq.gz
    ├── 7b615994fca2da322fe64ebdf3b33c458ee830ed.nq.gz
    ├── 7c245f0a6bff16c5dcf96ed688b97276bffd933c.nq.gz
    ├── 7dd74242500ba79006eb8771a27df563f7ed23e8.nq.gz
    ├── 7de0f3444681b0986faa0c3579fb64f8eac8886f.nq.gz
    ├── 7e2605a9bc6ea0d5e615241c70ae650d79419e91.nq.gz
    ├── 7f711a2b486f44fb869f060ffc7498bcb5ea6eff.nq.gz
    ├── 7ffd379d93cce775ffa469cf051284792941900a.nq.gz
    ├── 80114e6674f729b26801a0b354e8ec7dedaf59b7.nq.gz
    ├── 80e867a4e06b4dc26d0a2b327cbd54041addc50a.nq.gz
    ├── 81cc95634fb2e41b6a51f91612442fc1805fd3af.nq.gz
    ├── 81edb00db4cd5fc7c56f1cef409fee6233f3728a.nq.gz
    ├── 82b6f9d9a33e198f5747104729e1fcef999772a5.nq.gz
    ├── 8321971dcb25de87656209496eb1b1c879b59155.nq.gz
    ├── 8327aa5d853c538c55b93f3b6f8ae85c2261695d.nq.gz
    ├── 838846eea7c6a8ddacb2a76b116d5355e834ce9c.nq.gz
    ├── 83b4c1eda3bb644cce8f6cf029aaedbe30c3c178.nq.gz
    ├── 8471db13fe72c44000a7cfcd2db89db29564ef4a.nq.gz
    └── 85c29b19df59cdaa9aeec3a2efe15aeeee66d07e.nq.gz

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

[ReactiveX/rxdart](https://github.com/ReactiveX/rxdart)

---
*Parsed on 2026-11-09 by [repolex](https://repolex.ai)*
