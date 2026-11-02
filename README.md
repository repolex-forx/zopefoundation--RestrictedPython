# Repolex Knowledge Graph of zopefoundation/RestrictedPython

RDF knowledge graph data for [zopefoundation/RestrictedPython](https://github.com/zopefoundation/RestrictedPython), parsed by [repolex](https://repolex.ai).

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
rlex download zopefoundation/RestrictedPython
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c5066f7d5b2c7538c67c2f8c4635d681c2b325aa
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── c5066f7d5b2c7538c67c2f8c4635d681c2b325aa
│           └── chunk-001.nq.gz
├── blob
│   ├── 011248ba358c7ab37206922d8615c1c0bae461c9.nq.gz
│   ├── 0185a7a204b37c1b96fb8e864d85f3db0050d5f3.nq.gz
│   ├── 01b1446ac4465348b0ab4eda3f5c4f712b42dbd0.nq.gz
│   ├── 051788c29d27d7b9cfd619064c75ee0bc279eec7.nq.gz
│   ├── 0528e38ca455ba8e9a01404b15d5c4b369c79888.nq.gz
│   ├── 085432ed6ab8c7cb031ca49891d344fc06ae4238.nq.gz
│   ├── 0c33811fb5880520e2d2f34ed51bf203bf5e40be.nq.gz
│   ├── 0d5722bd5720b8621efe6e1aa25d31db6eba1ccb.nq.gz
│   ├── 104e5880aac14b34b3b97a75dec6b32fbb9573b8.nq.gz
│   ├── 1225928deb242f9b8fb74b0cbcba433df2cb5874.nq.gz
│   ├── 12f0e9cdfc063e75d1e05e1338cc4255cfb2c75b.nq.gz
│   ├── 1481946f102938222d9a89f8cdaf9054f018cb66.nq.gz
│   ├── 178479db72c11b8af4baa4eb29c05adf9d370a14.nq.gz
│   ├── 188120b692cc972bed5f7063baaa7ebd9dd5fcea.nq.gz
│   ├── 18fe99002b84e5d8e89b37117fb185cb38aede08.nq.gz
│   ├── 1a42732528800c4137584b89db9e1bad38da86d3.nq.gz
│   ├── 1a6d2397ef574ebc945f25eb0ec91c127c81ef9b.nq.gz
│   ├── 1d861a9fe7321de0c7b04b23a5698e4101db4708.nq.gz
│   ├── 1ece45ccf77e6cb817014b85ec9f87f68b214b6e.nq.gz
│   ├── 1fc393b1bc52c18d2777354bb3b7bf1b74304405.nq.gz
│   ├── 2690a88036f761683650cdd4f6def63c782c59a9.nq.gz
│   ├── 26a00c7a2744f553d5bcf8cb86570d0c0165314d.nq.gz
│   ├── 2978e06fcb72752bd075f539870f5b29cb63ad3d.nq.gz
│   ├── 2b0aee1948b71c768beda7c1174459ad958305b0.nq.gz
│   ├── 2b31c83376597b610f2e064863ec58d7dfa50893.nq.gz
│   ├── 2bf1f2e6fad7bd210590bf18b1c46bc718df6df2.nq.gz
│   ├── 2c1e0b7860c3730f519317ef40de35d177c5e605.nq.gz
│   ├── 2ef35ebd0401e197164d997eb73ce355106fcc96.nq.gz
│   ├── 31b70dcb50ffbb1277b06791caa5dafa30ed0a6c.nq.gz
│   ├── 359cd1fbefa19537fce7c6d9656589e18f81d53c.nq.gz
│   ├── 379e71ffd1ae150192dcf2d7e2f49fc8bfb1a913.nq.gz
│   ├── 3a2bf2d55fd2f703a7f7542532f73543a2352192.nq.gz
│   ├── 3af01b45a9878323385763f672147cf506abb90d.nq.gz
│   ├── 3b78498f9f1f6302fed87c5acac7ef8852ecc031.nq.gz
│   ├── 3c30bf5af51973019cf59370d87726bdd8be7b8e.nq.gz
│   ├── 3d7005ef92111003ea7a7dd8cbaafec2264ecdb9.nq.gz
│   ├── 412082a895dfe37685467a6b4e9bc3eb657df8e7.nq.gz
│   ├── 46efe2b83068b1cb4f2c1e4b3e1d4c9f93607908.nq.gz
│   ├── 471ae18da17a4b7510aac60d578146e4f7f16507.nq.gz
│   ├── 48bc9c04299deb282606e30e7d4185a78f9adebd.nq.gz
│   ├── 49ba715402db6a542b2a3bd7baa59db93291afca.nq.gz
│   ├── 4a002be6655988567d40851153d6001b3f6dda1b.nq.gz
│   ├── 538626268d8073160511f8070c9f72d8a549917f.nq.gz
│   ├── 541021c001754f8d44d4145ed0d9806e33cbbd48.nq.gz
│   ├── 5894ea5f88ba66c4a52998c690064b8af1489549.nq.gz
│   ├── 5895d49c55f49d729f7dd0a766dca1ef8f15f4d0.nq.gz
│   ├── 58c861b64a4596f7a1947c629e57a7cdaf2f6215.nq.gz
│   ├── 5ae4b8472f22b0b63bb23e81061f17ebda318f29.nq.gz
│   ├── 60c7eb4bacbbb2bfd7cf6a8da9f3bb1ceb2c07de.nq.gz
│   ├── 6a269591cf3ccb55343c7302cf8d6c885307b286.nq.gz
│   ├── 6c290a01529e4d357dbc477e9acd62ac4277c998.nq.gz
│   ├── 6e0b8d9896e2082f5a10cd964be68c187df29917.nq.gz
│   ├── 6f0c0f052bb6cbcc46b78d30c94c7152e2c8397a.nq.gz
│   ├── 6f222a47848d99438b6d116a7ec0d44a45188a9a.nq.gz
│   ├── 7157babafcaa4dc16fab92b4d2e28d1205d7c50d.nq.gz
│   ├── 71d54927755967fcf9fa5027a3d24ba86fd445aa.nq.gz
│   ├── 7aa3e9a5096c5ddc3c9ace004c03500d96bcecca.nq.gz
│   ├── 7ed62494d69dda61da119a7225454dddd205cb32.nq.gz
│   ├── 81ae9898df6c512ce0b42f077a6f70cc50643972.nq.gz
│   ├── 839c41fdda7a3fed236b625a1c3b27723361da38.nq.gz
│   ├── 83ba10b860d8a09b85b786a420acf9df4d7cbb48.nq.gz
│   ├── 8432faedea5a3a2af2d17be1b4f797aa0f65b9f8.nq.gz
│   ├── 87efc5a4abd8ca65dd9580cbcaba883df4ee1fb7.nq.gz
│   ├── 884fc3b98d450628b1280783ada3d232c60a9e90.nq.gz
│   ├── 8a6c79691d5e4261bcc30906d47e58220bb9e305.nq.gz
│   ├── 8b06e17c014cf32d98c2a65362f693503a778617.nq.gz
│   ├── 8b370ab73a212fcbafc4e2e1ea1071313316a0d4.nq.gz
│   ├── 8fcfa54a82fa9096e3346ca6026e99194813290b.nq.gz
│   ├── 9165d2a411c3ee13b99bfb3a20211c6a2244a1ff.nq.gz
│   ├── 9559ae767d23205f6061ae28dd55abea63c68ddd.nq.gz
│   ├── 961588e235c4fb9c54cacaacff8f3dcebb0ed3e3.nq.gz
│   ├── 966aaaf43acaf8a57dd3b1c2c18d329cbbde6c3e.nq.gz
│   ├── 971bff27005fdb953c53bf1037523b18f25ecd45.nq.gz
│   ├── 984cb898e2851daa433e2e4dd369d4cf167238af.nq.gz
│   ├── 9a7d5dcec16b2f9fa98bef5f5c9e0a85ca224454.nq.gz
│   ├── 9b58e68b0d207856fff3f4400bb31180b0564d17.nq.gz
│   ├── 9bb8625833ecabaca6cf76525e611093630c32f7.nq.gz
│   ├── 9bbab2586fe80aa5f790c29c00578c3098fb8624.nq.gz
│   ├── 9d71eec44b8317f39613e7a7fc4fd2f48cfe0223.nq.gz
│   ├── a44cf0bf50408935aacd93fcb5ac18eeb4f95b1a.nq.gz
│   ├── ab4e68c0d8e8ef51458a18bcb94f93032a9f0f3d.nq.gz
│   ├── b0b748fc90e1917a497d3ffd62fe7f349284d7ee.nq.gz
│   ├── b1a5e06651fa1c2bcab00f3f5847e784029d25b3.nq.gz
│   ├── b4c585fad7ba686648960d8e6d55f130c8df1863.nq.gz
│   ├── b66e5ee3665242d7f30fe154baaf6c1f7c9e2215.nq.gz
│   ├── b8581dd898cbb33e63961b4d181ff0ffbe5d03ee.nq.gz
│   ├── c076a464f7e23e21cb6caf27c1167fda70fe257b.nq.gz
│   ├── c573510442afe731a8f67bb18127a8f336a284ee.nq.gz
│   ├── c72fb376ca7337df0201cbd53d1884185b1ce1f6.nq.gz
│   ├── ca517f4eb0cec1c691c0c2b54cd5eb85e906f11b.nq.gz
│   ├── ca522842745c7e62ce00e0fbb73ae30166b26aff.nq.gz
│   ├── d6ed8fd774cbb063e37e4c94b6bc423145e2d6d0.nq.gz
│   ├── d9e113ec685b92b018297dd2f200341d1fba01f9.nq.gz
│   ├── ddc779aff47732dad79c3f36a54a380979ef5e56.nq.gz
│   ├── de8fca92b02c2882a67f443a888b2f10a9721798.nq.gz
│   ├── e129b6316ad88bb1fd5a7bc52ea236f4819c2855.nq.gz
│   ├── e1f9ad7b3b48377bfbfaa1b380c384ddea24060f.nq.gz
│   ├── e23ee03fc49a431c5747e8d13644edc4639f19bd.nq.gz
│   ├── e25aef4f5c2a37891b50fb50ab6cf563504e384c.nq.gz
│   ├── e37d2d783854e25414c32ca130119cd6dcd787be.nq.gz
│   ├── e4b867329e05886a4818f86b117fca2102bc84bf.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ea50e445540593b4ff017d5e520075e927d04cb3.nq.gz
│   ├── ee9e9ca17d6b8d4038433054877cd35419e25bd5.nq.gz
│   ├── f01f2639a06231f8c9ed86c98e850d153610e6df.nq.gz
│   ├── f0440537bd7940197754c0cc629ddf9895756fad.nq.gz
│   ├── f3bdfd764331f1a519c60dd58fc6583011136a73.nq.gz
│   ├── f774e1eb0452e2f14329e0a60161983239e1e40e.nq.gz
│   ├── f7f8bc71f8afc17d6f56a80cfe9e23559947d2d5.nq.gz
│   ├── f81cabf053fb4487bb3496afbc276556076bc3f2.nq.gz
│   ├── f8e9282e3c7daa57212b0dedb47de8ac3a5a4447.nq.gz
│   ├── f91ff5456b1931ad0c2b42ceda49ca3bcdbe0d91.nq.gz
│   └── fee691580ec6afe6c224b6e70452fe09c12d9937.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── c5066f7d5b2c7538c67c2f8c4635d681c2b325aa.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 121 files
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

[zopefoundation/RestrictedPython](https://github.com/zopefoundation/RestrictedPython)

---
*Parsed on 2026-11-02 by [repolex](https://repolex.ai)*
