# Repolex Knowledge Graph of scrapinghub/web-poet

RDF knowledge graph data for [scrapinghub/web-poet](https://github.com/scrapinghub/web-poet), parsed by [repolex](https://repolex.ai).

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
rlex download scrapinghub/web-poet
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b3cc347952b9bc6cf534e44543b789d2f5f2fafb
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── b3cc347952b9bc6cf534e44543b789d2f5f2fafb
│           └── chunk-001.nq.gz
├── blob
│   ├── 002ed75e36a1dc01851718af881c55ac4b26874b.nq.gz
│   ├── 007014ee8b00670df8768696b309da2036a1d529.nq.gz
│   ├── 0495affcea5b587a7f0bb050c60328bb8c7a9b37.nq.gz
│   ├── 0661b5feeccb159efdd0766edff727e0da51e1d6.nq.gz
│   ├── 06e6a37b35e8b2e39007dd9c216dc0600fe418cf.nq.gz
│   ├── 0b892d0286a96752093b49f10cfc95d697cd263c.nq.gz
│   ├── 0c6c45f768b1aacda280d99c1c5900d80136d23d.nq.gz
│   ├── 108ed515dcf77fa8b77fdcb92ba6b3b85dce22d5.nq.gz
│   ├── 11471aa2f4b9e3e288c78dcab8eff6a0feda92cb.nq.gz
│   ├── 114a4c5b6f4a30c3630055e4cef9e6a81cc49414.nq.gz
│   ├── 13cee0eb3bb4e7bcc1b1de171d8c723d83bb6fd9.nq.gz
│   ├── 19696213666b89e0bc305e62431dd62bc9c60a4f.nq.gz
│   ├── 19ae5bbecacf323629410322110dd2082f49e9d1.nq.gz
│   ├── 1b011f3940b0ae129a17c9f887aa70c0a3e6d340.nq.gz
│   ├── 1bac671299d559e84f7b7b83f9a38b665853c071.nq.gz
│   ├── 1e8800c1780c695710aa07c89bf17ca69e85bb65.nq.gz
│   ├── 21397b1effca86e7a62b78e052cb4ad7d24d0db2.nq.gz
│   ├── 219bd8df6f6ac4dfd76d5c3be295ed43cc002336.nq.gz
│   ├── 25e7089dbb80de6d87cede24a3486c5b42296f51.nq.gz
│   ├── 29759d8727593fd29184c010d797f2cf1ff0397f.nq.gz
│   ├── 2efaf89347da5454b9575b94594c7f23ee7580fe.nq.gz
│   ├── 309fce32d622c2680990456b85eb6215802c7736.nq.gz
│   ├── 30d1350afdf73aa77cf0021065877cac3f332dc3.nq.gz
│   ├── 31db54eed2ba5ef98621805b35fb940271119563.nq.gz
│   ├── 336e3fa6647f3b8d09186a3700789a6b3a9f1110.nq.gz
│   ├── 3861cabb6b4f618d5b373d363571b64c217266f2.nq.gz
│   ├── 3a8025db731120a4a605659fe1291a5435fafe59.nq.gz
│   ├── 3d31df8ccac0e5f030d4b5aec341e034bb3a18fd.nq.gz
│   ├── 3d9c8351744a124bf8204ec8db03303aafebaa89.nq.gz
│   ├── 3ee9a1be2c5757e6624398c03298b95e9bf425c2.nq.gz
│   ├── 42cbfc64c9e181d254644e93e2334d52dc297dde.nq.gz
│   ├── 4afc8c4a7e2061cb9e9676315ac87e7aed4f7f7b.nq.gz
│   ├── 4b4281046e265ec35f0dbb9f03b796864a302dc0.nq.gz
│   ├── 4cbcca3037852402062a9ffc5f9cd87ed0e4a4cb.nq.gz
│   ├── 50e57e249bb9a903e81de8e3fe5cff4bcdb9cfbf.nq.gz
│   ├── 51f1982a516d2b043227bcf4c87f06d09efe75a3.nq.gz
│   ├── 546763eb380a179c6b561703ea05529979f89b40.nq.gz
│   ├── 565b0521d0c2cdbfe493d19765b04d5c119fa7eb.nq.gz
│   ├── 56ac6feb8d67e192b1b7cb6cf48ec5903ecd5ad2.nq.gz
│   ├── 57b470a336f8b3629000e58cb26bdb2da45a2442.nq.gz
│   ├── 5b2d1b56af3ff3f46b3b827b34549898fda45124.nq.gz
│   ├── 5ea748dc33ba189a597c5a078daeaef7df949046.nq.gz
│   ├── 6020b702d35a72c7a096b8953e3dd75dea1ecc11.nq.gz
│   ├── 623d48cfa6b6f2ba551dde2435254ed5a1b63862.nq.gz
│   ├── 62c400982df5af2645aff6934d826c8c318d907b.nq.gz
│   ├── 6817eb37e4bb1dec3e79fab6a85092018d3acaa6.nq.gz
│   ├── 6831b34252376f9f2671ef596052ec634142a879.nq.gz
│   ├── 68f0cdb20d204f244dc945d60f2484d9c18c06d7.nq.gz
│   ├── 6932fd2cbf3604b9e2336a1d3724d11c4afadf64.nq.gz
│   ├── 6d1aeb5078edd823bfa584ef6776ec50a467ef79.nq.gz
│   ├── 6df6af033a7393468a03bf925376a8432ced594a.nq.gz
│   ├── 6e8a3ecc89ddd724eb2d2a65271f5ff268bbd0d4.nq.gz
│   ├── 71175665e37c215f0a59721a2e3d1cba515a24e2.nq.gz
│   ├── 71a4348fb95607e73121925098a706b9f16d6e63.nq.gz
│   ├── 73aa7ad24b991ddafd2d67825a52bb221e4ca7a4.nq.gz
│   ├── 758387697e372dca28bf6a80c6c162aff2a2f966.nq.gz
│   ├── 77cd29c2e25de8de3e0b4ff9b990278bb977569a.nq.gz
│   ├── 7ae523254be76f354506e9586e525b4afd84000a.nq.gz
│   ├── 7b62f21536bd10e02e2b6fd394cf80852a3e800e.nq.gz
│   ├── 7b8ca0658e0cf0279a040bfbb614afb98b195f1e.nq.gz
│   ├── 7bc831339ee2dd1ca94a8fdd2267971875ec1877.nq.gz
│   ├── 7cc94657b670e2d9e59f1f2d96d47d87f3b9f672.nq.gz
│   ├── 7dd10c28165a860a706e3d40212911a3bd52bab3.nq.gz
│   ├── 7eaf392827f8513605d9976e7e921d714522e912.nq.gz
│   ├── 7f10496d5409cc92b8f005b7f1861290c14a305e.nq.gz
│   ├── 80801c7d7d74cfeed3986ae30619ad85d2de465f.nq.gz
│   ├── 8313601c29219e60c15991f6ce9cf64aee5eff16.nq.gz
│   ├── 8382f7d573105f584edc620488a65d7c9c4998e3.nq.gz
│   ├── 854659eb1786b91257db5bf6402fc8840d7617fa.nq.gz
│   ├── 87e26de242aa27599b5f20eadefe4c923caafd04.nq.gz
│   ├── 8a9cdc0eebcdd1c87ded628a3516b3d1d7657d7a.nq.gz
│   ├── 92e4ca4da7cff82b92272625fda184367f941154.nq.gz
│   ├── 942d350c5be7ee336a24c1f8e15b7a6ae022f41e.nq.gz
│   ├── 958fd9ba1ec8c7fcd796bd825f8872824cb4f74c.nq.gz
│   ├── 9674940fac5adca40e7c00b67387238219af2902.nq.gz
│   ├── 98906eea2a31f74b58a1c33e033c19e6c4e67417.nq.gz
│   ├── 98f213e0a5605f98a8bc923cb243ab7905407a21.nq.gz
│   ├── 98fcfe7fc0fcfd9bcf48f93dbbda7b5056d72d8c.nq.gz
│   ├── 9b47e2c9ff5b791d1cdfa7009e58b679a44d8391.nq.gz
│   ├── 9d8b3fbc76abf590bd67a572f90bc1e1408e2898.nq.gz
│   ├── 9dd93d83a7b339703ad0f0c4e242190c2e2018a0.nq.gz
│   ├── a1440a4f36fd90782fe77b9837c72ac62e8ee0cf.nq.gz
│   ├── a1f98d0293501f0746246419d59f3b2c6365897d.nq.gz
│   ├── a3c52d5215fe47dba2b5a21a5997e20d84c7c3e8.nq.gz
│   ├── a4bf04269ab3e32611915b6067d672cae0334197.nq.gz
│   ├── a712570eb0f84722e7e4fa5339187e331bf421f9.nq.gz
│   ├── a7ba6fe81e20e763dea87818caff693468bdaf1f.nq.gz
│   ├── ac27967dc71dba9cc393a1b932dd01d51c8be154.nq.gz
│   ├── acde066f0509755f25466d2e164f292d0460924b.nq.gz
│   ├── ae228110abfa478e2b9460fa51e0d852baea1da8.nq.gz
│   ├── ae2f68f2c7918f54367076d3245e4b7153c64e40.nq.gz
│   ├── b12e20a2276f41bbf838fa2a54b91d48f800c295.nq.gz
│   ├── b1d831deec13c1052af2d12b106104ed01a01bc1.nq.gz
│   ├── b31f22f9fe79680cb8f51a8f90bc0d045b27a4f5.nq.gz
│   ├── b4301f17def2426077185339efd4b993d3ac823c.nq.gz
│   ├── b4d6f578326baf13600002560424a822af39f7c0.nq.gz
│   ├── b574fecb44e1ef68e306b87f6abd2bd0de9b0444.nq.gz
│   ├── b596a819d94838152560e3c839827f2624208a90.nq.gz
│   ├── b63567500d9d1289c02500df6852b3139fbd175a.nq.gz
│   ├── b66376eb33d07834e7ad165666b1e6978dcc93d9.nq.gz
│   ├── b671af8471d64476a1930606e211cd47528296cc.nq.gz
│   ├── b9ec9e55f2e520fd43e39dab4dcb981a66104e58.nq.gz
│   ├── b9fdaa1162c039b25dc143b4a95d7799ba54db17.nq.gz
│   ├── bb889fe6aede2950a767bf1a508df51989754983.nq.gz
│   ├── be425fdcf20294301c2734f11885796cd648fac2.nq.gz
│   ├── befc220b6655d911a188a1e1e4791912a4188a95.nq.gz
│   ├── c099b2bbb6640553a237dbadaee4311d4bf1176f.nq.gz
│   ├── c257924d13172b31a3f8d004bc9ac401d035b196.nq.gz
│   ├── c30236f011ec0afa9778e41756522b89aa4ea2f7.nq.gz
│   ├── c307a8f7c830bad41677d75ca3d75760f32fa1b7.nq.gz
│   ├── c4d617cdf96f057a6a73a6e05da6d56cdf1dc7ed.nq.gz
│   ├── c4e3db437e6a6b7aa21b6a68fc89482faeebce5e.nq.gz
│   ├── c61305698eddbfce877e3254e37af3d305a4ed8f.nq.gz
│   ├── c9a80bd04db7dca31f0a8a473feea919143a27ef.nq.gz
│   ├── cdddbb101fc5e93f142637806b7c4b935339b660.nq.gz
│   ├── d05ecd06473de775afb378f1e69116f54cd088b3.nq.gz
│   ├── d093da6d145e93620b62381ba18e2b39d2c96070.nq.gz
│   ├── d185e6b3277f84ae9baa3ca87f9675253407c427.nq.gz
│   ├── d316625144dbd3a363b41360a5930f9b95c429d0.nq.gz
│   ├── d356683c91a990055c682e798f19b0be9864aad6.nq.gz
│   ├── d4291d3823b2f2ca54a8846ff91fd86ccfe0be1f.nq.gz
│   ├── d4530a15fb26cf682bcd83eedab7a6564aee9d27.nq.gz
│   ├── d78ef279d9f8d033f010b0cbc905ce251f7ea374.nq.gz
│   ├── d7a9c895502946741e0a2b5dd1a24a0a1510e76c.nq.gz
│   ├── ded5290121c9abb954f27d183c1b74c72b298515.nq.gz
│   ├── e647e18078dab05f75dc79df0f716a6d2f8d5e8b.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e98078b082c38aa16f2654c620d325cad96bcc96.nq.gz
│   ├── eb2f9878b86b1ffe2a06035a1ee22c2a9e67c699.nq.gz
│   ├── ecebc00f4b8bd8008ddf82f8f5bc258ef29fd83b.nq.gz
│   ├── efe7d1d1a6c644533a29a80b4130be3e38eefa70.nq.gz
│   ├── f378536301841212de9c34d5db273c03af29d15a.nq.gz
│   ├── fcfb134b5b906020c1ea4fe0590ef34aa5cdea09.nq.gz
│   └── ff1549d6b7deb3d43b948039448c296b8f6b571c.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── b3cc347952b9bc6cf534e44543b789d2f5f2fafb.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 142 files
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

[scrapinghub/web-poet](https://github.com/scrapinghub/web-poet)

---
*Parsed on 2026-10-19 by [repolex](https://repolex.ai)*
