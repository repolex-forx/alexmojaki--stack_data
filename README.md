# Repolex Knowledge Graph of alexmojaki/stack_data

RDF knowledge graph data for [alexmojaki/stack_data](https://github.com/alexmojaki/stack_data), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download alexmojaki/stack_data
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 53501eb8b7c7963aa85335716d1de9f0b9f7aefc
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 53501eb8b7c7963aa85335716d1de9f0b9f7aefc.nq.gz
│   └── repolex
│       └── 53501eb8b7c7963aa85335716d1de9f0b9f7aefc
│           └── chunk-001.nq.gz
├── blob
│   ├── 00144a73aa01bd9c818f34971b08a543886852eb.nq.gz
│   ├── 0415e1d35e3066592514d0866719686e4adeab7c.nq.gz
│   ├── 05d50a73db58b02b9cf6717437de20a3923cc887.nq.gz
│   ├── 0b8bcd4aed4e1b9aee0411a0a30d0e952bc5d5cb.nq.gz
│   ├── 0d813f69c4f49168c921c8405819c85fe963aebe.nq.gz
│   ├── 0ecf750d7c645423fc831b271e24b34279fa30f8.nq.gz
│   ├── 11cbe80eb01096ad35f660be42e5685b138a4af8.nq.gz
│   ├── 12f1f408fd3e75c358317abfbfd776d6e48d87ba.nq.gz
│   ├── 15000868c73f52bd648c217557309ab9b2ff45be.nq.gz
│   ├── 17bcba2990d37b6016e50db7aff60aa62a45fdab.nq.gz
│   ├── 18eceb9d8b74ec2ec8de82d53f6bd10868f18280.nq.gz
│   ├── 23da718f93011dbea662752dc04c714485d551de.nq.gz
│   ├── 2ef9ecffff253f104a3f0f7c041f5e05187ea6e9.nq.gz
│   ├── 3971566b26fcadfd5909f14e2e3f0c7a0368db57.nq.gz
│   ├── 42fe6ae2b8244345221086e62ce63b949b0e9507.nq.gz
│   ├── 4402a14d48faf6be4c7f82990277198e07df1c8f.nq.gz
│   ├── 473e36e246edd5800325e9fa1eaa7697c95be1ef.nq.gz
│   ├── 4f197daef1650f2a5a8a7a349216b95a132b5a27.nq.gz
│   ├── 50109b8bfd96252fee0fc53c5a61c3ffb35b6108.nq.gz
│   ├── 5949510b0556ed3ff123de968a9d50a15c8f741f.nq.gz
│   ├── 5ed46e359cc5630b4430712ab9c39a3cf83d3546.nq.gz
│   ├── 5efe64405dada111be41823bdfbd97ddce475cdf.nq.gz
│   ├── 659e4d13b6a7627d41922aee6009f17e8acd3fba.nq.gz
│   ├── 681e2ea63daa3fd9adb9ced4f0159a4fb9a52c0d.nq.gz
│   ├── 6afc8f212f84ab9ede1306108df8447138b43b22.nq.gz
│   ├── 7f1a1763ca9cebc7bc16576d353d3284ee5d3c7d.nq.gz
│   ├── 812ddd07d10249111f7983db40feab81c1c174c6.nq.gz
│   ├── 828121483c01cfb4a67782f74359c2606f9dba89.nq.gz
│   ├── 8288d7832ff3a454a6b0bb9568c3c6d858e87f64.nq.gz
│   ├── 86ede069b09a3ca4196755255af02aef86d2dd4e.nq.gz
│   ├── 88e060392adc5d713b5593302cbfb01023a37613.nq.gz
│   ├── 89a2331ac83762b67807909bf507c9bf45dd1b8f.nq.gz
│   ├── 89c057e6b7e1254e52552328ea8fd9b2de1e8b03.nq.gz
│   ├── 9f3deaf43045f99afb791261cc6ae16f461681b3.nq.gz
│   ├── ad8cd38dc46b41155cabf4ff264d6d4f4beef8ea.nq.gz
│   ├── b0cbe1f4ed38782b350c42103ae79a72c5c534ef.nq.gz
│   ├── b0ecdc2f21a1b19d09f7cf31863d74f46667cc94.nq.gz
│   ├── bc8acca3f79371e5f8f02e28f4b7a86cdb1cf766.nq.gz
│   ├── c1c21c796eb777a4fabae0be3499b71850197910.nq.gz
│   ├── c44b8679f9f0091304605da266f8d7b6879cb6a4.nq.gz
│   ├── c77712700f6bd76fbb6c1cb78494a59cb6ee595a.nq.gz
│   ├── c82f142cb629689da9f95b7a01cfa7d602adc583.nq.gz
│   ├── cc34a36a41cc91a569f42cef0fcb942a7f3e4e1e.nq.gz
│   ├── cf050c5a3a1a085472b4cd788d7fde04ca8f0305.nq.gz
│   ├── e4c6f07fc8f1a002260e10c3ec63706a9694db92.nq.gz
│   ├── e5c0a6661ccc46434b2e1b6447592cc65a494b17.nq.gz
│   ├── e61d09f772b20e4fed930d68a2c0d93c55c2497e.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e9d447a74d284a0f07b62d1ab1ff7e214d7e8d7a.nq.gz
│   ├── eb03860716dac31a73aec402871dc30ab09b250a.nq.gz
│   ├── eef556ee4edb42ee6f13759532b83f12faf00512.nq.gz
│   ├── f084d185a15ce07acfd67b008f655961bf471ebd.nq.gz
│   └── f930184ad3cc193a9dc0e817b9dc10514803e1c4.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 53501eb8b7c7963aa85335716d1de9f0b9f7aefc.nq.gz
├── filetree
│   └── 53501eb8b7c7963aa85335716d1de9f0b9f7aefc.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 63 files
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

## Source repository

[alexmojaki/stack_data](https://github.com/alexmojaki/stack_data)

---
*Parsed on 2026-09-16 by [repolex](https://repolex.ai)*
