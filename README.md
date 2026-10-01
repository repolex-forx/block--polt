# Repolex Knowledge Graph of block/polt

RDF knowledge graph data for [block/polt](https://github.com/block/polt), parsed by [repolex](https://repolex.ai).

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
rlex download block/polt
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 8864cb43c971485e0433347ae73eec678335566d
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 8864cb43c971485e0433347ae73eec678335566d.nq.gz
│   └── repolex
│       └── 8864cb43c971485e0433347ae73eec678335566d
│           └── chunk-001.nq.gz
├── blob
│   ├── 074f3c00dfd0ab94304946d3f77a86da5ecc4e07.nq.gz
│   ├── 09c70bc29a8976e652901414e2e0b850ae0017c5.nq.gz
│   ├── 0c68eb1f43aa4832e75980e4668f2232a4a49b32.nq.gz
│   ├── 10831a2efd2c4a888fd78f3455657879f5e34052.nq.gz
│   ├── 1a821f9ce24160936b4a1530fd5fe9d44e09d22b.nq.gz
│   ├── 1bc469e68eb776aa52185c6cbfc5cdcaee837ce3.nq.gz
│   ├── 1d90a1da29f73c75ae7534bcf56d321df87d387d.nq.gz
│   ├── 1dfc17b1b99c597ae2c0172e4c91df154190ce54.nq.gz
│   ├── 23d7c3fa887a84a7227e98992787cd52344e55e2.nq.gz
│   ├── 25611169d1345bb95877b816bbd49c0c83c72930.nq.gz
│   ├── 27435ee4c755aab59493cb33a9f589e5061d9bdf.nq.gz
│   ├── 2a0014a66b23e38822f0a05b2684110bae9f4d16.nq.gz
│   ├── 2c72a113f92679f32ba325171ed6cd709b7fdb92.nq.gz
│   ├── 304be6e2d3764c24e6eb144f4ec8bc6dea0d8f3b.nq.gz
│   ├── 3065c4873029fa5049dda5607097879a334dd417.nq.gz
│   ├── 31126d356c5d0e19948fdc96c7a458ee3225b379.nq.gz
│   ├── 31a9927edc30d1ed95e4b492bb2affb9e810d428.nq.gz
│   ├── 383f4511d444516caed0fd113ee8a2b640cd2290.nq.gz
│   ├── 418354cac78ec2e30c0b64eb9b952ab6dd0b0855.nq.gz
│   ├── 41985d023702de059b1d0119c3e4dfb154e75eb9.nq.gz
│   ├── 4b3a542df8be5f930e531416e26c1b62040da9e5.nq.gz
│   ├── 4bb57ea8ffe7b8a45a616a627140b9813f5f5b17.nq.gz
│   ├── 4cacefc161ec34e47af9662e646b4c64ebcf949a.nq.gz
│   ├── 4f483863db3f5af7f17a86279072c10c74cb7e63.nq.gz
│   ├── 594d3c6694aaf1d441cf3e45c5e228757822c448.nq.gz
│   ├── 5b4df2f9efd999a87720614c7ded9d7201b64a12.nq.gz
│   ├── 5b848a14a35deba9f30cd04fbe1b7e0d63b638b1.nq.gz
│   ├── 5cd6ae2febb4673293c96b1df7248470ae713249.nq.gz
│   ├── 5cec36d3562d789962d1aabe8a32913d2c9fc8ba.nq.gz
│   ├── 5e7ad07a9e59fdcfb4ae7ca328bb0a688543e6bd.nq.gz
│   ├── 607d97654fec37457a1752d48fbda38ce910ff8d.nq.gz
│   ├── 61ea505a8a6a5d76696b072a78d77811a7796021.nq.gz
│   ├── 6680282143722f56bcfd4aa5ef1feb95e302ca73.nq.gz
│   ├── 6addf113654b87131528665d7974bc0ffcfb6d77.nq.gz
│   ├── 6f33c9f6885c06370e632ed23f43e4841be74717.nq.gz
│   ├── 7163ac1a303108cc6aa65982ee203c4b8e523634.nq.gz
│   ├── 75498f0305f843ed3fb6a416c2ef5135ffd89476.nq.gz
│   ├── 77f5e1a18b62a863ea5c0f62819b93ff80fb63cc.nq.gz
│   ├── 780af1ca50a63f8c08ba729ac88ad07bdb267f9c.nq.gz
│   ├── 7fef769248e85eab6c828b9f2f7b802296cddadc.nq.gz
│   ├── 817ca1ec943abeb197e6fd8c80f472793648cbdd.nq.gz
│   ├── 8db6005e9863c946e0a63a3e12a2031a78d693b8.nq.gz
│   ├── 8de3cbe0cc664efb3c10fc6b7903be7050960a56.nq.gz
│   ├── 91bd212c6efd3cb0669ffe0b26f42930dca30ae2.nq.gz
│   ├── 96d560ffee1ab6668680d609937c85007a13d179.nq.gz
│   ├── 97630f74d3fd3a6b510cd7e1c27b0b6eb0b0f739.nq.gz
│   ├── 99fe633a1d103709f417a4b2436f2d034a3fa679.nq.gz
│   ├── 9b514038d87c41b22261b55d781e9f3cdb1c081b.nq.gz
│   ├── a09bbff936c1dd823a292ebf046dd9099750171e.nq.gz
│   ├── ab24dc71f881d1560507960f66e81d44b2c034b2.nq.gz
│   ├── ab945e9794eca68ad5a4ed76983fa648eb65f916.nq.gz
│   ├── adcce923d9659aa1b20cdaa67348bee1e873ed11.nq.gz
│   ├── b2fa5eea2e277bdecfc5e43c9844f240fb3ce9fa.nq.gz
│   ├── b34f2c950efb0c7aa0779c2cb135dd1cae776338.nq.gz
│   ├── b4346a6a3a8966b8300275d169958f74ab52c4d0.nq.gz
│   ├── b77ece031bc4a08dfd00ccc2ed45f013def7e2cf.nq.gz
│   ├── b787f8ea86ca2bba5707bf148786f41a018e2eca.nq.gz
│   ├── bbabee85a19dbf4a938f571030dc80110db33c15.nq.gz
│   ├── c335bbb92ba67a6085499ea59e6f6560d8fbbded.nq.gz
│   ├── c4391f2803534c3f25e3e6c1e2c1195cb2b0bb58.nq.gz
│   ├── c47209e23f549e5eb67f778a28731cc05de09c5e.nq.gz
│   ├── c65eb1bd60079dff51bfb22a88a23c796bdef000.nq.gz
│   ├── cc31ff2ecc837d58cfe4ab95a8bc902f4fbaa30f.nq.gz
│   ├── cf234f1673d3affdbb6d78867fcc01bd491b1ca9.nq.gz
│   ├── d12324f2a268fd9bab033c7124c0dc5d0cef4ac5.nq.gz
│   ├── d1f75a0f83f58066986ff56218506239992431e1.nq.gz
│   ├── d22076cd9646fd104328776da28f8f45890ae738.nq.gz
│   ├── d340dbdf920348bc141ef12d0dffa4098ae9edc4.nq.gz
│   ├── d7609b2de98844259fd02be6605507c97a8604e6.nq.gz
│   ├── de13eea49efe1401efda95ddb7e9fc6cf7045aa8.nq.gz
│   ├── dfd58a9962249532dd8442ee0c7e850785dce893.nq.gz
│   ├── e0b835da477826058d6edc2f5dec1f34539fffc5.nq.gz
│   ├── e470aebe9b4ebcc06854329d8347a4ce65a31474.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e889550ba4cbc92a720527042e5f6e7a303bfcbc.nq.gz
│   ├── e9224975667c953745ae33aa440d6d3bc01c6a62.nq.gz
│   ├── ea4d720642f6316be9b737cc10eee8943943de49.nq.gz
│   ├── ebd26e50565d839e33951b58ba8631090965c9d9.nq.gz
│   ├── f0c3915625fc2c622f7627395d9edca777d7d70b.nq.gz
│   ├── f108f4bc821b2108e512469fc7fd69ea8b124699.nq.gz
│   ├── f1637c8f76c638f618c82a66278b88e28247a909.nq.gz
│   ├── f4856569b12c50c6fe69f7c810bb883459c61ea3.nq.gz
│   ├── f739293aedbecf68afba283f0f1103f070287696.nq.gz
│   ├── fc06dfb0240dba3a35fbca57a58de5898477f5a8.nq.gz
│   └── fe28214d3352b0ed40820a4999317694c8b1ef57.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 8864cb43c971485e0433347ae73eec678335566d.nq.gz
├── filetree
│   └── 8864cb43c971485e0433347ae73eec678335566d.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 95 files
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

[block/polt](https://github.com/block/polt)

---
*Parsed on 2026-10-01 by [repolex](https://repolex.ai)*
