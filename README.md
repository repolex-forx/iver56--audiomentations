# Repolex Knowledge Graph of iver56/audiomentations

RDF knowledge graph data for [iver56/audiomentations](https://github.com/iver56/audiomentations), parsed by [repolex](https://repolex.ai).

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
rlex download iver56/audiomentations
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f5e45049dfa8b33e8ee79a900b2b796a9dcae45f
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── f5e45049dfa8b33e8ee79a900b2b796a9dcae45f
│           └── chunk-001.nq.gz
└── blob
    ├── 00480a712dfb956c46c3612dcb094128eaa08951.nq.gz
    ├── 0125a54187c735c5f752381b60efc5dacc0f5dba.nq.gz
    ├── 0390a38248e8a41de2e404cd212c7495f1e1fba0.nq.gz
    ├── 04df219b616ce9ae9a9798e7e67c513ba5cd7619.nq.gz
    ├── 060dff3d456f43516945a71bdfce77f12e9acab2.nq.gz
    ├── 06dd4b76c4e9e9c45c97910fc8d87d4756ddfd38.nq.gz
    ├── 06f0ce0f79a66d29d75da5cf317d8a1182c7396c.nq.gz
    ├── 0750a39d8f96dc212001f02d7b0aaf7435446dfb.nq.gz
    ├── 08352aaa566e9c7d35b1ee2f4fd0c0a2bed9cac0.nq.gz
    ├── 08afc4364a9ce1222a7f13181b2b2ab29ec84b8b.nq.gz
    ├── 090957a1f06904177f6217a4a8a480cf6293a4d4.nq.gz
    ├── 0a9303ba3ae8731d1f1878605802530c9e7b39eb.nq.gz
    ├── 0aefeaeacd17e8266236d3ab10568d3efdb477be.nq.gz
    ├── 0cada54c22947a1441b7fe40dd18bd236134ff59.nq.gz
    ├── 0dc5b9b02f0373b3edebcd307117130575772ba5.nq.gz
    ├── 0deb09f50f066962d98c3ace61ec6e76a1b3b208.nq.gz
    ├── 0f834ba359ffa21b62c20a56292ec89a01053c77.nq.gz
    ├── 103a784445f131f828cd042169c171dcbf37ac62.nq.gz
    ├── 10eee4f4417020bbc0a0cfb82287ad40fd796293.nq.gz
    ├── 12a9db8245e64c780e265870e79303b5891a9ea0.nq.gz
    ├── 14a9473d2854420b5f44597bf68b8fcd87a3c2ba.nq.gz
    ├── 1cfb6d1b8ab443d3ad4b4544332a3917a2a765de.nq.gz
    ├── 1d628a4fcc7d7faf6b13314ebe4bf8f9ebb2a062.nq.gz
    ├── 1d6826c5911814d6907593707c2407ed018a83ac.nq.gz
    ├── 1f1dd76d05c4917fb6610aaf327bd15861d49e7e.nq.gz
    ├── 1f33352ee20f9a5581bbd08821e855c052a09e43.nq.gz
    ├── 1f33c0e6e18db92cff769f5deacc7f280637942a.nq.gz
    ├── 1f8b801bb25e5123718750fd40d1555ca5dcbba2.nq.gz
    ├── 21d59b4e5fe74521ff797cf6d2c1ef2c6370d1bc.nq.gz
    ├── 223e6ab3210d3a6ce1972de1df7bd4246cad9203.nq.gz
    ├── 23e321e4bb6ad49cad2453bce801fb39bf744b1d.nq.gz
    ├── 2587b475b887d51f6d123f5bc2c574a77fe03243.nq.gz
    ├── 25881ac90ce70ebda45130500f6d4a9f7727d8df.nq.gz
    ├── 2691c04d366b5eeac17defff6ad18e653e9b7b25.nq.gz
    ├── 2a4924ec3d3dda675d3255922c5f5c933a702220.nq.gz
    ├── 2ad59aa53cff3e33a3a67597176384b767934b08.nq.gz
    ├── 2f5df076506b7cfe872c1b8fa01793a79a1ab605.nq.gz
    ├── 30e80842c7a50e592d54670964a8fdbb62fef48e.nq.gz
    ├── 31d8eba2cc625a47d230d177c4a4a0848b6dea4e.nq.gz
    ├── 3267d9d356f0ce9f7e6bfcb2338349005f0824a2.nq.gz
    ├── 327b9f38c676061b8dbd4e34df3ee72d1087fbf2.nq.gz
    ├── 32de3df734612be0d452cd1370475b5eb16499de.nq.gz
    ├── 34b5c13d1beb1991e5f435e9de638fc86394aee4.nq.gz
    ├── 3557cb576ae7a3b08fea4a275aa9eed8506bfc7d.nq.gz
    ├── 3579f7d61bf88c63c2d81ed82ba57a5e124582f9.nq.gz
    ├── 37c3bb46f503407c2ff5afc56dd6580848f4eb8a.nq.gz
    ├── 39092af57a52804ad29e3996e40f590cb3a1cf2f.nq.gz
    ├── 3967f3da78ee68491d6d0bc1e8089ac25feb1ae6.nq.gz
    ├── 39b96b22c326b60828b150c0075a096cbe0ec79a.nq.gz
    ├── 3a758d5d5965ad0bfcd445a1cbe920dcb6d72005.nq.gz
    ├── 3b8cc619e80f38dff9135696178cc446ece27a14.nq.gz
    ├── 3c05cad3999462ad4acb787d503f8d1477a0d52d.nq.gz
    ├── 3c24d957ec8268ca8422958f4876cdeb0c9b1364.nq.gz
    ├── 3d0541fba337bd901b2b1eb209bebd53a2209428.nq.gz
    ├── 3f6d1e292ac707d9d5b0f9a4f603daff18165075.nq.gz
    ├── 4073748f276f2712ddc4eb7a3ccdea530d315035.nq.gz
    ├── 414f28c22bc8bffe140f943fcd43a055598b033c.nq.gz
    ├── 42bbb8f25c13e095eb9ece86024ce004b0c8a892.nq.gz
    ├── 42e8a682d15810f388a1a7c574216cb5338f1691.nq.gz
    ├── 42e8ef24c4206e20821c7942cc848bc4f6238e75.nq.gz
    ├── 43e7011008d7e24c0d3325eaa6261932adf5cf23.nq.gz
    ├── 44201c954befb222dafd5d78fde4dc69c215ccf8.nq.gz
    ├── 4473a57a34893d48271c7b99be48bbe62754ae92.nq.gz
    ├── 44a87c9f7f1cb30d81e61dd8278055bf1e2949e9.nq.gz
    ├── 455137a485173d4168b1b9a0267dd649bc756a9f.nq.gz
    ├── 45560f1176713eaa8e8d98eb74689f166dcf822b.nq.gz
    ├── 4566ec9aab682ab69e18865f7467ca1a66bf3271.nq.gz
    ├── 463c4fb8bac156e4c547451a0da92af5eee336c0.nq.gz
    ├── 4695ba344849282b7a8a1baeaff1c7e3c620f329.nq.gz
    ├── 47d6a5703c1928b99c84bc6d5df1f5f58f4bd4b8.nq.gz
    ├── 485448358bd84a451b1d9340c1035334311f19df.nq.gz
    ├── 48cc792e59227c38780642e1528b265464b3cd87.nq.gz
    ├── 49c96594ed09594fa93bd815dbf3433dca50e698.nq.gz
    ├── 4b158e0a43214877628c03de67a50edb1e0a9528.nq.gz
    ├── 4d9f4ca7841dea80ed84e5a78a22c204a97732b2.nq.gz
    ├── 4f19c1dc991f395643a1f3bc15bf00315213d70a.nq.gz
    ├── 510e4ef1dec7943bc28de57cad1819181bbe9795.nq.gz
    ├── 515640ae967ee478c89c71bc4b72d5b7809c7420.nq.gz
    ├── 52ead000848c906b643ddddb89be80d5b2eacc60.nq.gz
    ├── 52fb02d321dd7cc5b82c1e7e3cbc8035214c8191.nq.gz
    ├── 548ede02e1bb3cf945d2de7e0df21ca19a6b1ae0.nq.gz
    ├── 55830941503c7140fc90683540cf30c124083fb1.nq.gz
    ├── 55afcd91d5872066ce22f8b28aa9b3dec7d2270c.nq.gz
    ├── 55c8e02edd58e2970ecf86b3bc67f565934c2357.nq.gz
    ├── 5615ed389895a32aa8b6cc1c6200c351388f2619.nq.gz
    ├── 57288f6756f5ab4bc24e93067004f8bf71a2e2ee.nq.gz
    ├── 5767c8642f399cfe9b640871dd3eaf4c4f0dd6b9.nq.gz
    ├── 5926c91da8a98acff799cf45240ef77bd1b347c0.nq.gz
    ├── 594457f037561efc72a3db0481449a3ec3d3dcbc.nq.gz
    ├── 5a1d9487695ce9ff878d755f32e145b431701183.nq.gz
    ├── 5a7a274caad6ecd33105d97ad0f644ec1bc2c704.nq.gz
    ├── 5b19b7b19fa29068590d9efb5426a082dfee4fac.nq.gz
    ├── 5bdf272168a35156b55c148a8f1159c2de3833c9.nq.gz
    ├── 5c87a6ef85e75a1c8538f4078f8f91a802004e61.nq.gz
    ├── 5d6154341c8f0e13db204b821ea7a3a1ed5a18e7.nq.gz
    ├── 5ffab521acfc0df388568070fb426eb185044625.nq.gz
    ├── 608769c48a8651819f22230405bcf7340db5d80f.nq.gz
    ├── 61186f143c13da5a27f4fe2e130d5dda28004bd8.nq.gz
    ├── 615e6a1239240c811a938251ad4e6b4cf6353f1a.nq.gz
    ├── 618f767a6411141ab49f12e89d3011284d17546b.nq.gz
    ├── 62290730edafac6bc269c4049c14a261f310a72b.nq.gz
    ├── 62cdbb4cfcd2b609f667569ee04f11186a7dde0f.nq.gz
    ├── 63f68bdb7e4cceff66e9110cbfd8985cb4930c74.nq.gz
    ├── 6457b075fc61988504e47cafbfa4685acba775ef.nq.gz
    ├── 646d94aa728c355f73df8d3443a896ddb7650685.nq.gz
    ├── 653c97493da648c64da895e98a105c12847d1644.nq.gz
    ├── 65b2e955ab2c412c51b8c75bec7da97059bf0c82.nq.gz
    ├── 67f525611cf75f301bc042177c52afd5389ba3ef.nq.gz
    ├── 681be7295ce52ddfce3ff4e9af007cfb3c814613.nq.gz
    ├── 696133fbd95911a9090ee04706f76f64e7c61af7.nq.gz
    ├── 69704e97cbc534d21bc6fd8fa0d7f45ff82cac0a.nq.gz
    ├── 698a1099b740bfe159a3c6b6ab951f857547abe9.nq.gz
    ├── 6e2126db850a9769a8cf985748a5050efecfb448.nq.gz
    ├── 6f18e2eb0ae41e8467a2d8ab49611258c531c458.nq.gz
    ├── 7098d45955eefbd06d8b69fdfdec805fca1fc5f1.nq.gz
    ├── 71b10fe297c83d2d48d676a1f89e5076e634f22e.nq.gz
    ├── 7347d0af53454946f5857796f1ee941c6e4afdbd.nq.gz
    ├── 73a2a448fed9a2e1a09ef4e4d2855730734dad6c.nq.gz
    ├── 7628d743f0b7026896516bc8834628c79c30dc16.nq.gz
    ├── 77ad5f297ae6cb0a51b18b23e83227eefdb27472.nq.gz
    ├── 77c79a93da5bcda404ffdc703715fc84430db26e.nq.gz
    ├── 7beddeb774dd93d653b11568b9dde7656f8f2543.nq.gz
    ├── 7d229f317842c656996ccab2f490dc852b091e29.nq.gz
    ├── 7d889bee34ebd5813cbceff15f3fb36204fba883.nq.gz
    ├── 7e122677b15bc8a89aeb170a2eed349c89f457e3.nq.gz
    ├── 7eba52876a3bfa4c429f9a4ac2676ff1f89c5c00.nq.gz
    ├── 7f76383a98f7c3a83921bc006c984a6effb4b1c7.nq.gz
    ├── 803956cd9c5bb34739f4dc2232cec6012aa28a83.nq.gz
    ├── 84baaa3948d2d621b0773c44e82403d707e01dc4.nq.gz
    ├── 860e60560c508cb0b97c0648e64510288ec6c452.nq.gz
    ├── 863e88fd030241cbf2b46aefed1cabc8df153c40.nq.gz
    ├── 86c8268eb2e432c8c4f1dbf34119ee61e09e64b8.nq.gz
    ├── 88b6504caff7b50134dae1d9613fd56977d1138b.nq.gz
    ├── 89b6734f29c3f655a4985c57b9b70067e5df6008.nq.gz
    ├── 8b4b4bef76081221a897d9abc8f6ac5c56f2f838.nq.gz
    ├── 8ba1b49532e4a4b8d7dc5591c39a106bb30da12f.nq.gz
    ├── 8c6f26564e7f7cb31bcfc5cfa0090ffd8ae33b0e.nq.gz
    ├── 8d721ca46f99195fbb48476ab29f5bc3fd41a431.nq.gz
    ├── 8ec1434f76f4d9f4db7aeb3800ac556f82ea7dd2.nq.gz
    ├── 907cdb81c230d0607ce808cbbf151a9e1e48c977.nq.gz
    ├── 910126dab675a2f148d781e3a3d2ee36e05b5d16.nq.gz
    ├── 942148d701f8adbe4d27bb5ab09b68b94a4f68e1.nq.gz
    ├── 9468a88fce17f04aae3da16bbf9889d1590aca10.nq.gz
    ├── 96b51bebc0671b0b7f62ad19f41235e6edc53d5e.nq.gz
    ├── 9888660170cf594781dec984433feec717c51eb4.nq.gz
    ├── 9a274e0017664fdfab3d75ab6e6941ad23bc67bc.nq.gz
    ├── 9a47b2a99ac2117781956045ca8b5e4a894a98ed.nq.gz
    ├── 9c4f8646617fa729d47a68869a3ea1ccd80ab70b.nq.gz
    ├── 9ddd32e8682e1eed9e4f7ae73c4daf9a99062e78.nq.gz
    ├── 9eb47caa6cde5d470ed6949ec927ff1838be9de4.nq.gz
    ├── 9f6b3582e97ee98cf8557d4a85f8360877040a27.nq.gz
    ├── a04afb97a0340c86ca43f167750c03de534b3444.nq.gz
    ├── a25443b66c52c93af637287e00d9037e12e80dcd.nq.gz
    ├── a2bea424d342f69bf5cdad05c2c10e1de1dad5a2.nq.gz
    ├── a3d52a9dcbc55585641aae058c00036a874b23a7.nq.gz
    ├── a498ded9d85b9fc0f3101ba99184448490880454.nq.gz
    ├── a49a489b74a85277d6dc0fca2a14abe0a6ed5c84.nq.gz
    ├── a50475291490c19710dcb427ca8de3dc62a6ccdf.nq.gz
    ├── a5fb4ad5141c5562d0d49b82246b2bd452f917bf.nq.gz
    ├── a833680a0bed5a32555b89665ea03337fff528aa.nq.gz
    ├── a867f86c8325d40c381be2c6d293151662908437.nq.gz
    ├── ab386782f58e0a994522106733006212fd2ffe97.nq.gz
    ├── aece4c1846be3c06da0273422b77e85ca7b1b1d3.nq.gz
    ├── af26a1d0860a0c30fc063a7b2a4d084d8446e8b0.nq.gz
    ├── b05960dbd524f3f230f3c33db38d3d90113c61d7.nq.gz
    ├── b099a96118fa2293e98dc2282bc9bd81060d1046.nq.gz
    ├── b13d9799e1dd0eb5ab2a8565a1feaaf5c3c8890d.nq.gz
    ├── b1a96ff10742462916aab712c2bd9df5cf40364f.nq.gz
    ├── b4e83b4a228265c3a14b3cd8eb6bc02941709fe4.nq.gz
    ├── b54e8cfa71174d6f9af5094aaa4e0fa2d5356977.nq.gz
    ├── b54fd0f90998ab741636f5eaa216eaf4dd28c81b.nq.gz
    ├── b58dce8bfb2e69eaa0dd16e88e786a7c36b045a2.nq.gz
    ├── b763a4d15d76d75c076913976dda5a5b727a443f.nq.gz
    ├── b8f8f31931a1d20808888af85e6d8bb398c36d8b.nq.gz
    ├── b97a2febbe599e283582df74b7b54e109796027b.nq.gz
    ├── b97b3a9b62bab75b7c3e9a9cbb0142eee54a84e2.nq.gz
    ├── bc475bb30328943ce7dab75e3e5bf71ffdc571ee.nq.gz
    ├── bd7268864920d243e9afbd0e50ea872cca928df2.nq.gz
    ├── bf081ccc7b34658edc0dc939381dff88f208bb71.nq.gz
    ├── bf1923bbf8f7f9df54331b3241cba6f8c48241b0.nq.gz
    ├── bfe4da72c0f5a26d48444059d0098488a667483b.nq.gz
    ├── c1c3dcdf01d2ecabda8240f07aeed13f3a56dacf.nq.gz
    ├── c209300fb616c98534410341317597b3bd988948.nq.gz
    ├── c2ebcaf24346ba80dfe6fb08fca7849337cb3930.nq.gz
    ├── c6d6db1cbe8e7409ad8b05aac6baaed1b7004b08.nq.gz
    ├── c736b7679c090ce332552c1ece7ff18ef4929c70.nq.gz
    ├── c757f116b36e1b4405b6d41a221345417b5289b9.nq.gz
    ├── c763cf24d141570bdd7c6b212ef442b4ae3f5863.nq.gz
    ├── c9ac9fc0b3438d1d6bb8d7e93bad9cb9425fec44.nq.gz
    ├── cc43eac97981cdf021f9e85e0ef76598b4a3f107.nq.gz
    ├── cc69216bdd2f7a067921ff251543680476162394.nq.gz
    ├── ccd3ae37f73f1605923d0c2e4250d9b699b79b9d.nq.gz
    ├── cd43395528e46d492a913bface1d98329808c716.nq.gz
    ├── ce83d5f2850d67a985afb1d63f9ae540f36932e2.nq.gz
    ├── ce86c0303328d375921d1730d4c080eff6d510fd.nq.gz
    ├── ce8871325bef4268e4290b59f46222df573a72e3.nq.gz
    ├── d252e4d032dee0b8688fa73d2d4b1f426258a0f9.nq.gz
    └── d37152fa824b621c0a5f89682634fb6de97e1ce7.nq.gz

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

[iver56/audiomentations](https://github.com/iver56/audiomentations)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
