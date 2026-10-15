# Repolex Knowledge Graph of pypa/linehaul

RDF knowledge graph data for [pypa/linehaul](https://github.com/pypa/linehaul), parsed by [repolex](https://repolex.ai).

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
rlex download pypa/linehaul
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── cc9908824b018d555e9eb54f14eb743fa6274b09
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── cc9908824b018d555e9eb54f14eb743fa6274b09
│           └── chunk-001.nq.gz
├── blob
│   ├── 04941660cf44ef22633e69f6cc87f9dac43ee4e3.nq.gz
│   ├── 0810ff1d571a762f8bddc8e505f84b941597955f.nq.gz
│   ├── 1275b99ed5c42c73de2c8e9a804385715d27ed71.nq.gz
│   ├── 16428e58dfe432746ca23a4d121c4d09541519cd.nq.gz
│   ├── 164f68b09175be144dc9a28f7d3d3daf00bb9b9a.nq.gz
│   ├── 2af8c323e0ea31c62f5b1cbfa7689b80fed88423.nq.gz
│   ├── 2f24367425700ff9b601aba964e8373805c304f9.nq.gz
│   ├── 313b26e33082755a1d2944567b94d44ed711c88e.nq.gz
│   ├── 32036bd07ba8e82b8710579a5e472aec78e50a79.nq.gz
│   ├── 377a5ed9762418dff5e2f9b0d4172fb96ec355b8.nq.gz
│   ├── 3bd70ede8b99b72f6b476e7fb59d672289ff54e0.nq.gz
│   ├── 3ccf0ae9aba270e7431d0483bcb130bdb0ce4b89.nq.gz
│   ├── 416fdf2f903162da19e235832e15cf5f44b96762.nq.gz
│   ├── 438cad5c6c4eb127dcef5961733d7f586c282c35.nq.gz
│   ├── 44716c1e70bf1daa9681b295fffa3e9f8b7d196f.nq.gz
│   ├── 483c0d80c144fc87f61710673faf0b8bbf2508cb.nq.gz
│   ├── 4b707d3498d8aa59d3f24d2cfb91cacf0ed161f9.nq.gz
│   ├── 4e5f295b4a0c275d1e50c75bad78c207edd98162.nq.gz
│   ├── 5071c550543809a66d81586c80982e39febe97fe.nq.gz
│   ├── 53fb0db5a7d458458691dc4459d63d6b442d1e28.nq.gz
│   ├── 585272b6e16161a354e332eee5e3182635c14b08.nq.gz
│   ├── 5d94c7a18a0bac89bf56ba0dccceb579122a17a6.nq.gz
│   ├── 60c5719f30c5e704ffd5e9601091c4331cefe588.nq.gz
│   ├── 622249aa41d9359ad8b39f4cb7cfd4f1a920482a.nq.gz
│   ├── 63144288b05e91dce0adae0a792841313d8a1787.nq.gz
│   ├── 65d0d6e0d050d783693ad1eb2a7d53b12101df7f.nq.gz
│   ├── 690aa563cf5b79cc0c4683c1d91d0d774d71a4f0.nq.gz
│   ├── 694d23b59f5d94f9cc27f0b1938628eab6ce95eb.nq.gz
│   ├── 6a3ec566c87ba09dc5e51e2e0828ec9456664d7d.nq.gz
│   ├── 6d2c40100f53190cccc724f033d4d74be3775019.nq.gz
│   ├── 6e83509fc912bcb781e2d65141e5b1352eb32e27.nq.gz
│   ├── 71da2b104f522c005994158733648762ac6aee98.nq.gz
│   ├── 78eb12976ae610ec9d5ce97fae30be76673d2f7b.nq.gz
│   ├── 7beff5029ef6607e72e98d5d7ac253f8fc34ade8.nq.gz
│   ├── 7c118b8d796ea50e9b866feecd9a92ea829a29e2.nq.gz
│   ├── 7e0c52185f6c6685e1e7887847ed6aa4e0a61c7a.nq.gz
│   ├── 80f54d30325d0f6396577a47cbacd3576470d7a8.nq.gz
│   ├── 8437c98d42c913e95baf948478033269aadd5c6c.nq.gz
│   ├── 9003490a4e60a3d9482f274f0bea3c50ce1edb76.nq.gz
│   ├── 937c15052da44c0402d6760b566815657cc4fa4f.nq.gz
│   ├── 9ec586fdc5a12527001e803df2ac739a67877df4.nq.gz
│   ├── 9fddaee1e95639f0a9dd157f96940893d9c10d21.nq.gz
│   ├── a0505ef58afa21f5ca444dc27a92f678864f5ed6.nq.gz
│   ├── a2409d4ed411cefd6b004100d0c0e640c5468998.nq.gz
│   ├── a70a4f330b0e2dadb87f59a31066e28c7a196df5.nq.gz
│   ├── abe68130c3a7cd6e1daf5b09732194150c9c8851.nq.gz
│   ├── b0d72655d407108701e14d317e95ad46ba2a7dca.nq.gz
│   ├── b770835829dcaf2159d3fc0bd1b3cfaa2aaf6309.nq.gz
│   ├── bab2413f791c82f3568e484a7662735ea3bdb9d7.nq.gz
│   ├── c585f52ac22d8bf38caa741c659de1653518811b.nq.gz
│   ├── cf1905fc77a793bdb1cd061fcef5819fc6c1ef4e.nq.gz
│   ├── d118d402d9c7dc432de507a7a5f77e2c4aae502b.nq.gz
│   ├── d29d4f6298aba1eaa1a88f38ed33598e57eead9f.nq.gz
│   ├── d2bdcacf198f36e79e0f31f62c65d2349c03751a.nq.gz
│   ├── d4521067bf0c315bb23cfcc802c7042c65dd5e23.nq.gz
│   ├── d4e089aa80fb669db920e3975ba5c1caa1047be7.nq.gz
│   ├── dafb9f65f0fe34685255573fd3cc163fe0eeba55.nq.gz
│   ├── e0445c4adcb2a35465ee4b775feabb937958028b.nq.gz
│   ├── e256f9e2b8ca23653067c1ea4a03f5a0d86708cf.nq.gz
│   ├── e4eb57efbfc69c2861ab3818454a2f256ddcd1f4.nq.gz
│   ├── ed21c3ef14f32d774ae0d3c108989f13ef7f4f27.nq.gz
│   ├── f220614a6f97b9fde6d43aa6f1987db584305e17.nq.gz
│   ├── f5bc7b2010edddd299b7b3ffe62afbab7e4d3ee7.nq.gz
│   ├── fc1a9568243f80df4a5183a7930dac68fb614f15.nq.gz
│   └── fdbe3a24b41f7db62f8625467a88b6457a570641.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── cc9908824b018d555e9eb54f14eb743fa6274b09.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 73 files
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

[pypa/linehaul](https://github.com/pypa/linehaul)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
