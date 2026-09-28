# Repolex Knowledge Graph of eemeli/yaml

RDF knowledge graph data for [eemeli/yaml](https://github.com/eemeli/yaml), parsed by [repolex](https://repolex.ai).

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
rlex download eemeli/yaml
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 7f536de04fc0993ee01af8145e64915ffec5f019
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 7f536de04fc0993ee01af8145e64915ffec5f019.nq.gz
│   └── repolex
│       └── 7f536de04fc0993ee01af8145e64915ffec5f019
│           └── chunk-001.nq.gz
├── blob
│   ├── 03a9cce99d564ad25c075a822824df8c2dbf90ec.nq.gz
│   ├── 042584df7c445f40ebd7a6fd5d607c6f847954c6.nq.gz
│   ├── 082d52ee677d8045b2c5876110d2b046e08f593d.nq.gz
│   ├── 09d1f9159438f0bdf90ed667e968832f8179335e.nq.gz
│   ├── 177e14ebd895e2c1d81bcd8d4ead2a8871987b5b.nq.gz
│   ├── 1a50bfb9320b3da5c701f54d2ebb3be7ba9dab7e.nq.gz
│   ├── 1a62b656ec4aa475fe1e3d21c8184ab5eb7baa72.nq.gz
│   ├── 1af04d9b04c18c215c6e71455c87af9aa4c29a68.nq.gz
│   ├── 1b4ea2b2a70280d67244616338c55c0df86699dd.nq.gz
│   ├── 1bc947f1d83e6c27a46d4a26cb33bf4fedc86a61.nq.gz
│   ├── 1d44f7b2df8404769b66eed34f9c195b7463efe2.nq.gz
│   ├── 1fb3036bd79b1f170785b2a6c37bf190b61c112d.nq.gz
│   ├── 214d549a70295caf56ffbd14262b56fee9190245.nq.gz
│   ├── 224d40fb9480ac28c810e81e4470d5edc68310d4.nq.gz
│   ├── 22a7cf163056e1e3f4ce23b6873f479d368482b8.nq.gz
│   ├── 2332e41cd0db0821a36aee103ca64fdbfbfa821f.nq.gz
│   ├── 2721022ff8adb96175801f91381144782103d6a4.nq.gz
│   ├── 2728a6533aec54b6931d9afe2a425aa66c215c2e.nq.gz
│   ├── 279dd92589e852f55ba0ca96d8a34c21e1b4416a.nq.gz
│   ├── 28c278785b5d3312283e15a6b9ab910b438711c9.nq.gz
│   ├── 28edc02f718fb140fc3b0a8c50a163ddff288173.nq.gz
│   ├── 2abcbedfcb3e217f30a04e195f57a9844450eb1f.nq.gz
│   ├── 2ebde3798e3bce06137eb5326179bec6f386ed61.nq.gz
│   ├── 321696e1a08c0b9b0064b3b8d527f606e72dcd2a.nq.gz
│   ├── 327b493d6e6f6ee45d944bbbd5fa702361024502.nq.gz
│   ├── 3666045e7475db9d8e224cc8e759146cafa18bfc.nq.gz
│   ├── 380ecef2f7f1131e8bf30c233ce4d67c93084342.nq.gz
│   ├── 3818d5ecefa3bbc9ac400f3c7088128b7a0ae4af.nq.gz
│   ├── 3b1a8403076aa7e7cf29013bfe10a7f9b2f2b593.nq.gz
│   ├── 3b474573c62ca63769c4184c261ced59fbfc0661.nq.gz
│   ├── 4162f81e6cb097f111a127077943513d48f31b3c.nq.gz
│   ├── 422bbffe33f4c31dd051f0f30daaaaeadc6718b5.nq.gz
│   ├── 43df932b8efd11779aaa32c904a5ca2463d43505.nq.gz
│   ├── 47b400fa48fb23b5d21499f22c3930cde6685456.nq.gz
│   ├── 4a33cf1079fe5cbe97f1e3dfef7c7cabd51d0a2d.nq.gz
│   ├── 4df980596c9376142132ed1cd26764debae2673a.nq.gz
│   ├── 4ee7b5e67d08ccee93cea75127a5f8b2a29a0a8b.nq.gz
│   ├── 521fec276605c69ee8c014809ae3a7beb873fe6a.nq.gz
│   ├── 551fadbdb2ae637588eadd914094aa24cf193f42.nq.gz
│   ├── 5568d63cd312b1fd3ee31c1e07e6adeb6eb7944e.nq.gz
│   ├── 56146a48ca610fbd51be7da5991a0ff44447cf5a.nq.gz
│   ├── 57be20ee0ad73e8205bb6ccb91382081641d750b.nq.gz
│   ├── 58a69abf8b92fdf4dc829f9f818e4eab925edf3f.nq.gz
│   ├── 5a01192fbdb4cddc8e1790e09d521964215c01b2.nq.gz
│   ├── 5a103a6b140e35755beb0f9e95cb7d6b3e7ffdc8.nq.gz
│   ├── 5b669627f76945cee8a560e8e6a26320e92f6bc5.nq.gz
│   ├── 5df947b7bd332c54dcc4c6eee818538f9e8583bb.nq.gz
│   ├── 60770462584b1eb20c80d87f329124eb51a64668.nq.gz
│   ├── 633eaa118fc75368de69309ad30b1049eec0ec4b.nq.gz
│   ├── 64049d8c91784156717d1f4953b956a2be020757.nq.gz
│   ├── 655c82d2397d0d19345c07cbb5c796ca83982a0b.nq.gz
│   ├── 65ed26667be4cf72bcda6ec0bf141543c9c4bb9e.nq.gz
│   ├── 6890e1be87ab28ae7a8a9a7d0739e09519727f19.nq.gz
│   ├── 68b6450a8d90b7edfa40489e4451f8da7715b299.nq.gz
│   ├── 68df39d3e9352085697039dea60ee0ed085cccd4.nq.gz
│   ├── 6ae0b4ecb61c7f51b10dd90febe5263ee0c27c03.nq.gz
│   ├── 6d7582f388a79d9f4aa864a2371e56e49dcb4897.nq.gz
│   ├── 6f328a6f9d46d1f5d6b89328137e93825fa91781.nq.gz
│   ├── 73c97d6c11cde8a5c4594beb240edd6a28ee06f8.nq.gz
│   ├── 7438aee5fc8ec923f56437c45c00c8ebfd9060a5.nq.gz
│   ├── 74820c385b8bdeaec8d2b7fe81a449e1243fcbff.nq.gz
│   ├── 7980cc23bcd944c428e5744f8f519e6a37408c2c.nq.gz
│   ├── 7a2ca54297f130cd09e0b85dffdc7f75b80a2860.nq.gz
│   ├── 7c97680e87269f3fc7bed8216a59d2b884f06bf1.nq.gz
│   ├── 7ccb55101bef13afdf560e695f548b6e31fdc8c6.nq.gz
│   ├── 7d2846bc62295ba1998bb3e7b3f15a71c3d02486.nq.gz
│   ├── 7e11d1a5b85b2355012a09bf27a702d868df9640.nq.gz
│   ├── 7fb3f11e57bdd70b3e1d52bcf442ccdd1a342bd1.nq.gz
│   ├── 7fe9d95e93bff976d4a87f4ed57ad937613dd262.nq.gz
│   ├── 8191d16e7be4c1d8c1d83250f8c5f8fceb2d14b1.nq.gz
│   ├── 8336b8f66cdac5e88b39f1ea6fbe31716d59516c.nq.gz
│   ├── 8782137e9869eda039b7866ed1226d5ad6833f9c.nq.gz
│   ├── 88ea3bafdd7a4164d66f15641a18ad148b6e045f.nq.gz
│   ├── 895b4c343968dc26c8a6afaea12ddd01de1c9961.nq.gz
│   ├── 8abc50023ef8627915c03b8e3f71b7fb0000360d.nq.gz
│   ├── 8b72ba9f9f168c6ca24bd07d9b8cf91cb1c3615f.nq.gz
│   ├── 8bbe69267ce4c1331fd9fc4b311200e2703b4df1.nq.gz
│   ├── 8c35ad4c865597d245d87d2af0a6a56e799a8325.nq.gz
│   ├── 8c7ef5418519d47521d7a3a1e674323e8bac1539.nq.gz
│   ├── 8cdb03ffc795783cc4743ecbb2f4512467d3c480.nq.gz
│   ├── 8d4e9b3ad33ff273c7412803f5e6f2207eac672e.nq.gz
│   ├── 8f81e9e0ec5d48504149821bfca2d634835e1f1a.nq.gz
│   ├── 93d4c875d5e8a268b67f90436aad2e9942184a97.nq.gz
│   ├── 94349ecf977a666c60c86f63fb9302806e3c048f.nq.gz
│   ├── 9635e11ee080213ea816db74e3d51266fa4162f9.nq.gz
│   ├── 990a4846e47c776814ada457382c534135ead89f.nq.gz
│   ├── 9950f9649a30a44cad19208c68c977151e726fbb.nq.gz
│   ├── 9bf75b7c9efee24ee1b5b1959f769b261d538b19.nq.gz
│   ├── 9ec5ad181b47d5186dc79d35a8c9e3e83b5ab707.nq.gz
│   ├── 9fdb9433eae31b8e0013b552d3fc13c26e592b66.nq.gz
│   ├── 9ff3327bc2d1880b1372ebd1a7b4d74e985a7478.nq.gz
│   ├── a425d50795d22f298365af9aa12ade96bb478ca6.nq.gz
│   ├── a518d50c0476c9e13d1b9baa44001800f9f92723.nq.gz
│   ├── a52f5faff6aeca132e86272347096d11009c0eae.nq.gz
│   ├── a5bcd2ce16b867beae7b72fc9c5193bcf04facd6.nq.gz
│   ├── a78a8edc67199540ee89c764118dbf4c0adac664.nq.gz
│   ├── a945ea03765dbf77cb5e05115f568854e25eeeb0.nq.gz
│   ├── a9617073f352ff80c9a981bbde33321dfe1d6572.nq.gz
│   ├── aee8e9c4af776043efa2a35571335164a9492667.nq.gz
│   ├── aef96d0613d4fdb7d17bd362c5d91597989de2c4.nq.gz
│   ├── afa3835f1a57909be30e3a84249630e066878340.nq.gz
│   ├── b17346451164c25d00990647b76ac781439288ef.nq.gz
│   ├── b34fdb511d3ff36a306bb91f005dd62e9cea98e8.nq.gz
│   ├── b47ce38b0745942c2cb3028e3b757418fa8c5a55.nq.gz
│   ├── b581361dd2f00b406ba8200bd45264ddbb407d95.nq.gz
│   ├── b6559e7b28d44fcca389ff3978522c2952c79a9b.nq.gz
│   ├── bbe2aa54c0a26052550f5618f718cdb18e39d41e.nq.gz
│   ├── bc445dc88703e930d1d946723bb71f457d489c6a.nq.gz
│   ├── c36fb72e6d460be8849f48f8c60e94c7a958c1bc.nq.gz
│   ├── c403f56f10f63dd562684b4c3797b8c37447a7e0.nq.gz
│   ├── c41e2634f60da0e405c4af9084d4b38436091dd9.nq.gz
│   ├── c44e0c470c21c399ce9981efacc464954cbe548a.nq.gz
│   ├── c5d178e3fc0d1638d5574a6ff82781767b9ee662.nq.gz
│   ├── c7334538f1b687fed0c09c2452991c9da7672872.nq.gz
│   ├── c7e2bb7fa2b91646a386854f2cb0c4fa8473fec3.nq.gz
│   ├── c95bb1c9c446d2a3554fd12ac947577c59d78c9c.nq.gz
│   ├── ca998af93c398944c31d7f9d04df820ae0b03015.nq.gz
│   ├── cecdc28003f008bde93250d7f22e1b3cc42ff308.nq.gz
│   ├── d2e6b21e6cfa8f137bcf1d964a441f591f513764.nq.gz
│   ├── d70731356637b07c5cf1caf2c2723a36548d59be.nq.gz
│   ├── d9c4ae9b5ed48037c21ae0c326d8433a10f34fe7.nq.gz
│   ├── db90a56cedd67bc8bb0370a57bb219ed0783b108.nq.gz
│   ├── dbbc023a2e584787fa54d513b1ebceb1fb536857.nq.gz
│   ├── dc5e916d919fab85b158c5af2cae7bdef053d2c1.nq.gz
│   ├── dd0b02381772c4b4105e43ef73d833db5cb97a3e.nq.gz
│   ├── de1d2e1cb8894d0866d7da452da81d43083c631a.nq.gz
│   ├── e060aaa1fe0f933e699c8feb3fdcc51c2999bf0c.nq.gz
│   ├── e291eaf71e57937c630eabc7dfcbbaecab19d8b8.nq.gz
│   ├── e363e3a8272fc1da4bc9e2faa0f9fde02a87f8cc.nq.gz
│   ├── e46eaf6032eee77aafdd8f28aaebf3df22f42dd5.nq.gz
│   ├── e56dd054b4f6cd26d45163a522aa97749ef5a836.nq.gz
│   ├── e66751e67c0ec106ffb804659105347bee0371f9.nq.gz
│   ├── e67c776fdb947e7e36c8fd907f3cb794c870c016.nq.gz
│   ├── e87fbc1f70c0aa28d8b194c44f28610eeb6ebc9a.nq.gz
│   ├── ebab07aaafc96adaa6b31d365b18c87e18dfe455.nq.gz
│   ├── ec5649a502a9d4aa6678492c96aa0330aa047ddd.nq.gz
│   ├── ecd1c65572a21b518eb9fc50d8af20ff73cfb175.nq.gz
│   ├── ed197f032dd904972a788cad501c93af131c2a9a.nq.gz
│   ├── edbf55e19488f03131746327e3475471a8c98295.nq.gz
│   ├── edf5243bc05e8c46886b0e59663da88c5e4d33bd.nq.gz
│   ├── ef8a0aaf79bf4f499c736bb09861895ea088531d.nq.gz
│   ├── f16338d9935c19f52e439680ea6a2bd647262c27.nq.gz
│   ├── f1f07e2d7e0c8e3c8ff8e953a2c0f744494d0c70.nq.gz
│   ├── f2cccedb6506f43ba98ab77b7ac99319fe2dd88d.nq.gz
│   ├── f42bb0710028ee94c9042fd0f7f863f40a763290.nq.gz
│   ├── f91e565df43d9f89604439bd949a75c8fda7291d.nq.gz
│   ├── faf0fd136b0c4bfa33309532dffb1a1f0a2951e2.nq.gz
│   ├── fc37259f84f0d707f94042797ce8d78585baa8c8.nq.gz
│   └── fcd0d6d196abec57c360d85097917c69d94b47bf.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 7f536de04fc0993ee01af8145e64915ffec5f019.nq.gz
├── filetree
│   └── 7f536de04fc0993ee01af8145e64915ffec5f019.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 159 files
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

[eemeli/yaml](https://github.com/eemeli/yaml)

---
*Parsed on 2026-09-28 by [repolex](https://repolex.ai)*
