# Repolex Knowledge Graph of agronholm/pyinstaller-hooks-contrib

RDF knowledge graph data for [agronholm/pyinstaller-hooks-contrib](https://github.com/agronholm/pyinstaller-hooks-contrib), parsed by [repolex](https://repolex.ai).

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
rlex download agronholm/pyinstaller-hooks-contrib
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c8339c6246a68349bf271f127f3734e3e8dd2b4d
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── c8339c6246a68349bf271f127f3734e3e8dd2b4d
│           └── chunk-001.nq.gz
└── blob
    ├── 0068549a5e18f924b5c614465024f9750375120b.nq.gz
    ├── 0111fb4ef9e956674ac324ef0f48a708b3bcbaec.nq.gz
    ├── 02c52a4d87a526e23999ab4e1660fd133d121203.nq.gz
    ├── 03253c4bb31f50af10c9715fba94d0ac605f4ad5.nq.gz
    ├── 03319351bbd18fe7419160eb85938afd86d28c68.nq.gz
    ├── 06f9b1c6f728c1ddd99b542ce83ecf1bb2950d83.nq.gz
    ├── 07d467f18ab1ec68195c03e9a07548d83a74bed2.nq.gz
    ├── 0841debcfd02ac1a629cde200a84792694d299df.nq.gz
    ├── 08f7296bbfd879b564ab1f04457366642311ad45.nq.gz
    ├── 08fdb8cdd4f42fdaa2a0fb3833946c8eb61d9373.nq.gz
    ├── 0aee42424ea62c02749f5d1edf5156e15a29be2b.nq.gz
    ├── 0c3f4da4925f408a3bc627dfd447995b5f7567b6.nq.gz
    ├── 0cff831ce9e4a5e7c1fa3418102d56cdecb007ee.nq.gz
    ├── 1175d9b2bfb29a1b66225333e04be0977146024b.nq.gz
    ├── 11c01ef615e906ac8dd0786f7272ef2e06985443.nq.gz
    ├── 11f2b5fc3bceea3d4e04d5389ebf9f06b065936d.nq.gz
    ├── 125426ff5d8918c31df47907aba1ecd413701f81.nq.gz
    ├── 13573da91d383edee9d1097941d850b135fac523.nq.gz
    ├── 1596521ae7f8a8addb23f0acffe6d234a1d011ae.nq.gz
    ├── 15b191c1180049bfeb86bae3d82f63eef1b784aa.nq.gz
    ├── 15b4295e6fa1d0d8cd6ec43ffe8055676d28c2bb.nq.gz
    ├── 19082f55eb2f8b0931afab1e40ca06239eccc6cc.nq.gz
    ├── 193cd5ecb1f46cdeeb493ff069b20f47a9d07bbf.nq.gz
    ├── 1ad290699a515fe7a16f36e92a62838804c97489.nq.gz
    ├── 1b22c286fe3f7300f269b0ec19044cd2c28cc11a.nq.gz
    ├── 1b2cb955242cef61ff1305be4c5a8192a6af7761.nq.gz
    ├── 1d0d7655d1f6a2e6060ed0f168dff504ff462154.nq.gz
    ├── 1d8b7a29363d9e3c9f2abdd31b54444450b8ce8c.nq.gz
    ├── 1eaf5aff72119a34442cebe1bcccc22c7ff10390.nq.gz
    ├── 1ef29499af98b492b37a7bc902fb9532e1abc901.nq.gz
    ├── 1f5ce238b7a2659cb5126d40f4307825cd909af6.nq.gz
    ├── 21018c7de75aa4f719131a6b215a0f051d82707c.nq.gz
    ├── 21dbf4f7fbad25a5e9654caff13d01ebeb0d0b68.nq.gz
    ├── 23582021ed0700282a9c7e506db94eba478ae5b4.nq.gz
    ├── 2416290f42e646117839be5dc7dc51d527abcc40.nq.gz
    ├── 2751248abdaabb2be905e8069b52e0a17333b6e8.nq.gz
    ├── 28769e2321a0a6b7daee0792b0f65a68d8618161.nq.gz
    ├── 28c335f5696855bf8aae2ce8cd6734f23708524d.nq.gz
    ├── 2aa5596de216815983f60922f7cfdb65ff57d791.nq.gz
    ├── 2bc9efb3fabc1816e073cbfc6f4047eb51c82724.nq.gz
    ├── 2c195f9e7c68526ea0224e2b6a7d45129b6d3e36.nq.gz
    ├── 2caba659db25b9b12d0f96e4f0a24ca467e79fa9.nq.gz
    ├── 2e49be06013de59d948a7adea3e29910ad0c71fe.nq.gz
    ├── 2f4da28c616b0491f77533a4468bff5af187e9a1.nq.gz
    ├── 2f591e415897697b0ff7d6b8815c4cab9dfc37e4.nq.gz
    ├── 30c3bcf9423f24f07c91bdf53be2e63adad4e24d.nq.gz
    ├── 317c335bf2ccfbc2dd5bc132653010e64c962e1d.nq.gz
    ├── 364b647aa852b52261fd73efdbd4115191e69530.nq.gz
    ├── 3833b230f42a8bdb833f3ad257f36520364e68ef.nq.gz
    ├── 38d78f2d8c1565d3ce4d49d9c5e83f855745bcc5.nq.gz
    ├── 392d972a62846dab3d44c93aa716eb60cf57dc26.nq.gz
    ├── 393552598bc201c65b823d1f338259f95e3484d2.nq.gz
    ├── 39f08b47ba1c162a832117438065eef608f5fe19.nq.gz
    ├── 3a3b86fe4c1ee5e9ad91c83bfe445c8dca56ddec.nq.gz
    ├── 3b779497287f7b956049eaf7ebdce7a75848b963.nq.gz
    ├── 3c25e3b4303ee221d3af25fa8408861dc7445d49.nq.gz
    ├── 3d4764b663bb79c962821e67f7d5e17470a77a51.nq.gz
    ├── 3d7dfbccb84a79a3572e7ff62ccdb54ec94ea83d.nq.gz
    ├── 3e0f8d23adb8fca9b5987c33513811e81562462c.nq.gz
    ├── 3e733211d171b2e98822097d3eb34a720199bb55.nq.gz
    ├── 3eb8973daa82ca52ecbd4e523ec10087c9853406.nq.gz
    ├── 3eeb974bdafd6923e19a7f44de8b9d24d7e5382a.nq.gz
    ├── 3ff941bf4106ac36fe8b90b006535628b73996fa.nq.gz
    ├── 404ea38bd259030797a694858efca3654cd3b708.nq.gz
    ├── 40b37273ad2c7b81a8c7a0fd337f9e60cfac2640.nq.gz
    ├── 427986fa91c5c7f42fa453f6eea1b89a6367adbe.nq.gz
    ├── 436d1d716bb419cef5345f314cd9ae08a6617c08.nq.gz
    ├── 44cc7af5a9d28261cbea19e6fb4c42d439cd2309.nq.gz
    ├── 463b50c9fe270c0045ce3f5c24c5679b6552ed14.nq.gz
    ├── 47a11f76549ec91b22f7f78dda1b2ce2b21e8896.nq.gz
    ├── 47b3196342b4ae0ac498a6a8007a8932279751d1.nq.gz
    ├── 48c3dd6a1e8a0cdb33b1b44a1f522f08122a357b.nq.gz
    ├── 4dac3387c3e758d00be1c99f41390c32800fa127.nq.gz
    ├── 4eaa7183421967e16489d63d19aca4a38a830873.nq.gz
    ├── 4fd1abe4d0c49761f71ea7f069b5c28bdb88c093.nq.gz
    ├── 51cf5f59257e3ab57f087bc21a3bda7549131b2f.nq.gz
    ├── 51d5bf238436b9f80d04b5e0b8d925337d4f6f2e.nq.gz
    ├── 51e9dbc98109255c7e97435a9e4aa4562d212176.nq.gz
    ├── 51fe0e72244c98be255d24f6ddd03e9222453fc6.nq.gz
    ├── 52c4a08d2fa27565dabe776849343da235b572ab.nq.gz
    ├── 55d8f18633c907eaf9e5584496e4fdd0750dc655.nq.gz
    ├── 56c21b593d6de91c22978ee05a33abd6f22ece58.nq.gz
    ├── 57e9e5caf78899b0ee30a8d920348dab161f3563.nq.gz
    ├── 586c0a403184eb8c7c327021231b7eed3d5f42fe.nq.gz
    ├── 59c0f16244369132bc15fe739dd4a9c6b7368c52.nq.gz
    ├── 5aa877f2a980143312bbee74f92338bb438b2b10.nq.gz
    ├── 5c7f814b95453cb025e3a210c5f0d7db1b9b7a30.nq.gz
    ├── 5ede6389a5bd3e4e3ad4627a59cba7ffe08c5504.nq.gz
    ├── 5f620c6e8f0e54008d0178309b6de8f57e1b8a19.nq.gz
    ├── 602d73b896f83ce4b9fd237bebb18f9b7dccfaa0.nq.gz
    ├── 6475963aa40f9c928057d49563facb6a590c84b3.nq.gz
    ├── 652ddf2f408eefd7f3c74200f9c530703936a602.nq.gz
    ├── 66a219a1b938566b68f0065e4ae0e83eddfe26bb.nq.gz
    ├── 670f3aac5dc472d7657737b239850808b98a17ea.nq.gz
    ├── 67ebfd4a9a30c3afd080d82e0f94059443d8cc9b.nq.gz
    ├── 685287ba9a7b23df4ae2dd644da19041b6a1347a.nq.gz
    ├── 69467819373b24b02c03a913d97bf806e7e1b35d.nq.gz
    ├── 6d40a9a5777701868beb5491d4fdbb60b854fd9b.nq.gz
    ├── 6d58345771f634916c97b9c5c89fc47c8e9fd358.nq.gz
    ├── 6effd80c55e6b3e89091a56685d983c185f5145a.nq.gz
    ├── 6f0b7eb8ebe2aebc552e83a00f270e9b161608c0.nq.gz
    ├── 6fca2275b9ba7d06046d16ffa8932272882a17dd.nq.gz
    ├── 6fef09bd61e18aabedb8d5cd5837ea9df4b77fa7.nq.gz
    ├── 72852ba8a77bef76d4fca4926d4962b796f13741.nq.gz
    ├── 73e808f5dd654d93776fc54d80669963a1dcaacb.nq.gz
    ├── 74ed1066f60140beb5d255cdd2f9ab4d47549eb8.nq.gz
    ├── 74f3ef1f36d7b02b8a4d54f3ff2374e1b86e9d83.nq.gz
    ├── 770ad5e6104f7ce1636bb355b624240fb73e9119.nq.gz
    ├── 79229be5a91fd34750bf0ac00537e80183a6bd44.nq.gz
    ├── 7a54b482f6d26ccf117760b07e108936c95d5f7a.nq.gz
    ├── 7abfa4d6b1617cde23ef9d51bca0ccd79432311c.nq.gz
    ├── 7ac0cd7e05b220442b5eedd25f8341509cce1f1b.nq.gz
    ├── 7b50c5e9c17a7e54cc9ea8292f00df2aff19d3fa.nq.gz
    ├── 7bb76854ad119441288b67cec438287a516f6cf8.nq.gz
    ├── 7bdd484d275bf93acc07f633ab970573f4a0a6ef.nq.gz
    ├── 7c936dcc7c89b90a79af108e09585e67518a76e8.nq.gz
    ├── 7e6924a900683bd963e71ec14fb348eecc4aa8eb.nq.gz
    ├── 7e97c9d2f0177de9a4de343472b5a357807f2fff.nq.gz
    ├── 7f61c58a73d890fc57296ed68d6f515134cff2b8.nq.gz
    ├── 8010feb1459f80abc3bf503f433ba5b193a930c8.nq.gz
    ├── 80157a0a8c2c5e99ccf9b55e02e1cb7c5daf5a31.nq.gz
    ├── 8077b046d07d00567ad152001edd6cd34d0068f0.nq.gz
    ├── 80f07f4f036e7cb3eea29aeaee340b356072e914.nq.gz
    ├── 824558bedf6ec082ee354d61bf603762a085ce7b.nq.gz
    ├── 825d9f04002ed75258eeacb787f343fbdefaab24.nq.gz
    ├── 82e916a81d6d61c220f279d872ace6b63946663a.nq.gz
    ├── 84d003e262a153bc22ac93d5621e6ac801e936a4.nq.gz
    ├── 853115c2a39bb2abd23c96491b107ed75dd552f4.nq.gz
    ├── 862dc166a589f3aff22f5f1f50c3c2f46c773e88.nq.gz
    ├── 8a7ee58aa62168d8fbbc5b10de48d41a4b78a26d.nq.gz
    ├── 8ae669c46478803dc4da379b450e491dee303b06.nq.gz
    ├── 8b46d42ca4de36f3223909c6bd33b88dcba42f09.nq.gz
    ├── 8b83226864fd56b6c4a6f75d0098066070d5ac54.nq.gz
    ├── 8cf966348c48803772daa7f1e48f1b668f65bdd4.nq.gz
    ├── 8e3080265d860e732c0ba767faf361f1fde9b939.nq.gz
    ├── 8e6ab68d7045219339edfcde808692d9b0ba3b8c.nq.gz
    ├── 8f2dd6bea8c64882cb3469f51c3d12c3673f9edd.nq.gz
    ├── 8f45e8f45b763218d99525db657f9f3241278600.nq.gz
    ├── 9114320b2cd0777c5ad4ef41a59233edb87379db.nq.gz
    ├── 93360f7db34b5ab0f125b720329440957e603a9c.nq.gz
    ├── 93888ab302de5aecab4fdfa4a90da2a2cee8cc36.nq.gz
    ├── 95191969e15b060f7d929762797a146774c718bc.nq.gz
    ├── 9563f5a0818f196d9d42d3acb4633c6e2d86ba6b.nq.gz
    ├── 9568d535c1300032ba75f8e2f58c072095e77996.nq.gz
    ├── 97883e11b0af6fca7c4e1d6d31f796b1b9ca980b.nq.gz
    ├── 984feb1919890136b56ec084adec894b9a3c4ffe.nq.gz
    ├── 98cbd27f96083fce8910864413dde6f863a7c2bf.nq.gz
    ├── 9994b72e5fd9da231cfc2ab6ebfd397f1bf98e7f.nq.gz
    ├── 9b82c1a0ac3e9f803a6f89ca343dd8f20dba4ecf.nq.gz
    ├── 9b8850d3181f0f8cfb13d7bc596ad3df2e151c62.nq.gz
    ├── 9b92d758a2db8079e3775caeb9c86a18d64d4e20.nq.gz
    ├── 9c79b4a8203ada3cfc836ffc5dbe3597e794c7fb.nq.gz
    ├── 9f40f4619383b45ba59c7eaac38bd2c615241ea3.nq.gz
    ├── a10365632b692abb8662f14860c686288160497f.nq.gz
    ├── a403eb6c96ffa8dbf7d26db16802442306b2377c.nq.gz
    ├── a45c0d5b24dab0371e69298df6fa1421c0a758fc.nq.gz
    ├── a4baf1b4645eaec670ad1914a41817544a8a2965.nq.gz
    ├── a4bfb195eaa6cfe0d779373b99c2d1c6f30e91fa.nq.gz
    ├── a72a9a61f233faa2ac96357cc76ee2de36bb817b.nq.gz
    ├── aa163ff255fcf8973e3180ad1c094da44383583b.nq.gz
    ├── aab9031d41e09eb64dd0f399214ffcfcd8772f81.nq.gz
    ├── ab30d9dac471ecf295f1b66c6626746b7c6d3d80.nq.gz
    ├── abb9d614f40d318e69e2a50c34fbc092bc1dee48.nq.gz
    ├── abc4ad24e5bc360e1f986ead1e29ffe697b70717.nq.gz
    ├── acc1c916b03b24729884360b12bf7584c701e63f.nq.gz
    ├── ae9112f809c281073f2b542a29f552e6424aeed2.nq.gz
    ├── af32410c24442497e202867b77d189db8f6743d5.nq.gz
    ├── afbfe9c65e08321e66ea801f787b3b3fc354ca47.nq.gz
    ├── aff57cc346ec152fcaa0bf4da53e1e7983cf9aad.nq.gz
    ├── b0db612d0909a7bb978679c02019c1723c17b052.nq.gz
    ├── b40a45c702b8476f9c0fb14b03b75a2bbddca459.nq.gz
    ├── b585dd98dbb2708ae0cea8f8c6686a6e1cdc7cba.nq.gz
    ├── b655a9944b37994277c477e622122092481c574f.nq.gz
    ├── b8effbbc3dbd3b3776e015a44c784dfbd008d121.nq.gz
    ├── badb541e842523576850321daa58ba8e4dfe996c.nq.gz
    ├── bb093611d103ba56d97b80150ea6ebf0c4a9fdf6.nq.gz
    ├── bb2feaa201bbc8374bfb19f99f42c8cfe20f4b0e.nq.gz
    ├── bc365e071eb0a214b3dfbedb5b6f6b28c989db2b.nq.gz
    ├── bcb337b57006a55bdcd25acece9df14e8895b36a.nq.gz
    ├── bcf4e7d1f92fd28701e1f97baea2a52c0551562e.nq.gz
    ├── bd8eff5b40bb3dbbf24c728a31dd71547a217d29.nq.gz
    ├── bda4c2ad8a9023ac22f1a71412f17f29e8063e53.nq.gz
    ├── be4b9faed54978fe94307c48c8de3eb03fbdebeb.nq.gz
    ├── be8a381863d6c56f7955de37e2088682ecb1b650.nq.gz
    ├── bee91c5cadff096a545abf96e4082eece654e173.nq.gz
    ├── bfd0161006698d2dd1dee2fda3e1906a322e02e3.nq.gz
    ├── c09631df8fa3d93e6cddc693a098f7cf006b64d8.nq.gz
    ├── c0f5268f1c9fbd80c682d0904d98bf0629e49320.nq.gz
    ├── c2466a03923a2f5c6375b00f6bd2baeb959a3670.nq.gz
    ├── c48be95588ce7d91b72ff36e3b2dd94d128f4ecc.nq.gz
    ├── c4e626a264ab50f7a6601a622b384add28e70604.nq.gz
    ├── c95acc458f6a6326e86a5e8d4e65cbfa7ee442b8.nq.gz
    ├── c963a98c0f2e69893b2073f01f286fe13eb8df43.nq.gz
    ├── c9aae0b12b2ca245005afeab6a03ffa7db658cd3.nq.gz
    ├── c9ce04a0747d8fc3fd36c29eb7b673796a224bb3.nq.gz
    ├── cb74911b946d64b1e208f93defc3b0d41635a3c6.nq.gz
    ├── cbaf4250d48302d4cb2d6095b5cbd3ca014bac4f.nq.gz
    └── cbefa6746d300625de8a70bbba6e41e357f3b469.nq.gz

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

[agronholm/pyinstaller-hooks-contrib](https://github.com/agronholm/pyinstaller-hooks-contrib)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
