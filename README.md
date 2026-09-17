# Repolex Knowledge Graph of testing-library/react-testing-library

RDF knowledge graph data for [testing-library/react-testing-library](https://github.com/testing-library/react-testing-library), parsed by [repolex](https://repolex.ai).

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
lexq download testing-library/react-testing-library
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f32bd1b033d5e3989ae1cb490d515ce389c54e53
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── f32bd1b033d5e3989ae1cb490d515ce389c54e53.nq.gz
│   └── repolex
│       └── f32bd1b033d5e3989ae1cb490d515ce389c54e53
│           └── chunk-001.nq.gz
├── blob
│   ├── 002bafb40e71b327c603ff2385078cb0e2d46c76.nq.gz
│   ├── 03b31d3fee61c091d585238015527898fd9b8d72.nq.gz
│   ├── 0464ad24af8ee0f014530368756805a8ab1befe8.nq.gz
│   ├── 083a8188856016993094dbc8e5b43501ff557196.nq.gz
│   ├── 0f9c487d18422f0e25a15588ed7937a995b3deb3.nq.gz
│   ├── 1a4401dedea30ee994f92b3da51ad87a419289a4.nq.gz
│   ├── 1c722ba1a9032bd5849d9a082c8d47a2d6a05df4.nq.gz
│   ├── 1df2a6d8579b70495787fe6685f698941e2acb49.nq.gz
│   ├── 2a6752990103f99ba7cbc2653dad53eccf0fd6a3.nq.gz
│   ├── 3005125ee04774662dc908a93fc27f9551ff5a09.nq.gz
│   ├── 309703858d7a372dbd447a118934c8e105a88487.nq.gz
│   ├── 345cd9379546d501afa8d935f59488ae61b0822e.nq.gz
│   ├── 357d1df761c08cb0db744643b297e238dcce0218.nq.gz
│   ├── 3bceb32ea6a9ad6ea5d9a09327269520f7ea3633.nq.gz
│   ├── 439dddbfc47895e4c8dda2fb49348cdec50b5d63.nq.gz
│   ├── 450a6136afb5fb5834c49c625556368c94113985.nq.gz
│   ├── 4679d9bf6be92cd766e6d59d40d7da8bdf42335f.nq.gz
│   ├── 472fcd83dd4a07540ca50285a176f3129809ee5b.nq.gz
│   ├── 47681ae0d4f1ba33314a7fb920584919041129bf.nq.gz
│   ├── 496c8563193c7f9f03c859ba1d45832c692d8180.nq.gz
│   ├── 4bc12816cf989f4001b6dc3919b6d60e673a285d.nq.gz
│   ├── 5430f28b2f07f12ca912c6e110c147bf1891db7b.nq.gz
│   ├── 5696d4e3449f48811f0710b011009d1f30eefd72.nq.gz
│   ├── 587bfdae380e201ea839b6d5fa23602a23d8e312.nq.gz
│   ├── 5e45c45dba483c9d907b4e6e7dc7cba401f93710.nq.gz
│   ├── 60db1410c9761f2016150c07da317fd8df8b0850.nq.gz
│   ├── 6313b56c57848efce05faa7aa7e901ccfc2886ea.nq.gz
│   ├── 669fe7e461712ec87cd2de8c95d9e079e9fedee4.nq.gz
│   ├── 6eaec0fb7dc9f49df9a009277cbf69c078cec77f.nq.gz
│   ├── 6f5b5b39f78f0296d5d52b410875fc41a51d6cb1.nq.gz
│   ├── 75dc04521afb50a259b6c1702bbea16246019913.nq.gz
│   ├── 7b5271956748f47212403973d06232971eaba6ca.nq.gz
│   ├── 7b9cf3b4475b0c31e75693a59053be3e65493d76.nq.gz
│   ├── 7e18d5dd6977ea1b8c120d298ff3f4b95c7e4232.nq.gz
│   ├── 7fdb1e0076922bef0fc9277775ed5b648d279450.nq.gz
│   ├── 83e0c64189ecb491d31e916a05fe224045201800.nq.gz
│   ├── 8c6b417e330fe53e8891975390e8ce98ebc0942a.nq.gz
│   ├── 8e0c70cb093496f582f9e12365e74d2e657ced6a.nq.gz
│   ├── 9c628283b98527a803e7edaef15fb592ab4b562f.nq.gz
│   ├── 9f17c7222e7f3f603e2ef72303c5f88640c6ef84.nq.gz
│   ├── ac8b1325cdec8278ac01b3fb0bb2d062aeed7237.nq.gz
│   ├── ad10155656a3096dfc2ed17e9a353a0b1992d5c7.nq.gz
│   ├── b22c94149d68722d52f5caf4706c8e3757890418.nq.gz
│   ├── b768729fe1c2ecf07998a667cc1fe5ccfa49a7b3.nq.gz
│   ├── b8f19236db8501e03d2f4a5a503b597f34294df6.nq.gz
│   ├── bad26af75ce3d4ccdb4ae2cbe03196cb302f8106.nq.gz
│   ├── bb0d02709933a6c22a0a9371cb5be6856927d9c8.nq.gz
│   ├── bc3f482324a651908b188f4c083b452a6fb9a01c.nq.gz
│   ├── bd0b0329cb30b517a7f3a19ecbb963227be5eeaa.nq.gz
│   ├── c04bef38fc89208ba76448fceb1cc7b663a4eb67.nq.gz
│   ├── c3cc4e696f7dc52b479fd8f481142ba3bf734e89.nq.gz
│   ├── c6a1d1fe918430febeb3354508a404680443fd4b.nq.gz
│   ├── ca399d5706c30a9ff7b8ba8277423d9c34ac228c.nq.gz
│   ├── cb790c7f7450fd83337c9ef0d038075d3f321009.nq.gz
│   ├── d8288e0316d570ce25261e7f1fb019239a543dfa.nq.gz
│   ├── da09ba7cc0d87b710096bb02bf0737ad520bbc3c.nq.gz
│   ├── dc8a5035a4d29aabce394acc5a09241ebaad2d7c.nq.gz
│   ├── e16e9d6126246a07d54c63af2788a6e2f52161f0.nq.gz
│   ├── e3eaebbe32193b5287c516d4d331d51c8ce06a5b.nq.gz
│   ├── e59e5ed9dd8036c2e2f5828ebe8ad1f3d52ce4a2.nq.gz
│   ├── e625486bb56f207dfc2c58f62546b54f952662ec.nq.gz
│   ├── ef5a7e11c865e574a343e94c8f50a55fc9dce867.nq.gz
│   ├── f331e90ea80d3b64f2a1d2087aed3e8021a117fc.nq.gz
│   ├── f5000e218625480187930b4995925679a8f869ae.nq.gz
│   ├── f93c23be0cca43601582a81eff40c7572c7abb05.nq.gz
│   ├── fe29faaab2a2b9c89c6e4a12af915b07f5b2d451.nq.gz
│   └── fed4df2e4dc758defef27ffb6104aa136f4cda48.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── f32bd1b033d5e3989ae1cb490d515ce389c54e53.nq.gz
├── filetree
│   └── f32bd1b033d5e3989ae1cb490d515ce389c54e53.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 77 files
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

[testing-library/react-testing-library](https://github.com/testing-library/react-testing-library)

---
*Parsed on 2026-09-17 by [repolex](https://repolex.ai)*
