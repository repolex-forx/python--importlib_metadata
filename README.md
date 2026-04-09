# Repolex Knowledge Graph of python/importlib_metadata

RDF knowledge graph data for [python/importlib_metadata](https://github.com/python/importlib_metadata), parsed by [repolex](https://repolex.ai).

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
lexq download python/importlib_metadata
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 76f03df2f4df25de8aa9424cf31e600cf27f7d59
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 76f03df2f4df25de8aa9424cf31e600cf27f7d59.nq.gz
│   └── repolex
│       └── 76f03df2f4df25de8aa9424cf31e600cf27f7d59
│           └── chunk-001.nq.gz
├── blob
│   ├── 011f4751fb9e322c4455d7296d7ec75182757cd7.nq.gz
│   ├── 01356d69b97c95a6d41818e5c2c50a299146bef4.nq.gz
│   ├── 031d14e5e4d80a75b22e2a4de6ff95ffcf1ef4b3.nq.gz
│   ├── 0416e4a4118c867a425c63bac90ed8d5c4468e16.nq.gz
│   ├── 0c20eff3da75223a5ca76a1743b7c5b8fa1dc1f6.nq.gz
│   ├── 165aa6dd3bc9427840f20992b30893de9833e5b9.nq.gz
│   ├── 2193ec31fe44e1ad6f7d485175829061d160350c.nq.gz
│   ├── 304196f81e11a168c9894f966e4a617ebf4ed53c.nq.gz
│   ├── 32b1d2b98ac987e8361f60362b8bdabcdc6fb1c8.nq.gz
│   ├── 3a5327436f9b1d9eae371e321c491a270634b3cf.nq.gz
│   ├── 3c700778eb50a368469caac3cabb6db4d4a5e0e3.nq.gz
│   ├── 3dbed6281982b0ed41d3e09e4ba0db91da7a2186.nq.gz
│   ├── 479488a034818633141d42aed87b0903ac233b35.nq.gz
│   ├── 533fe73d7a21595c5479b9ccec63361f8c2e0d10.nq.gz
│   ├── 54cc8303b22089e12053e552d4e6cb852a865b8a.nq.gz
│   ├── 54f99acbfac68c2be8283174ea64f1730a795e49.nq.gz
│   ├── 577e87a793a20e413f7321f4f17ec1eba2ea1962.nq.gz
│   ├── 5bdc232005af9be104a00437ae9bc64417a4c1cc.nq.gz
│   ├── 5ca93657f819601b83a57762db71d03dad12f78a.nq.gz
│   ├── 5cbfe040f6f9b5bf9a7d544cf0ee5f04e1ff9758.nq.gz
│   ├── 63c0825f6bd49615f4f386b95463111f7992f6bc.nq.gz
│   ├── 641ab07f7aadd5c3ffe199b1e397b84504444994.nq.gz
│   ├── 667552166e2d7fea3af1c7d5573c2f77e6f804f4.nq.gz
│   ├── 6d3402d674212b5c7af84df86fc658abc0b07c2e.nq.gz
│   ├── 724370638fc188317bbc7dc868f1a571995fd796.nq.gz
│   ├── 79d37198ce7aff317873f6e4e84cd904a46a69de.nq.gz
│   ├── 8a53eb55d1503bc4e902e841bdb1fff5e98ac451.nq.gz
│   ├── 8ab689dfbfdb2231a848985825cb684ddd5532dc.nq.gz
│   ├── 904446b1aafa1fb8054e15ff664f7d1b3088ae38.nq.gz
│   ├── 9a0f3bce1395ae3819030b822e5d9076c85068ea.nq.gz
│   ├── 9bb3e7935efe59c89715a90859279874ea30bb2d.nq.gz
│   ├── ab44bcad2e02655f4c5cbfc526205324444bcd4b.nq.gz
│   ├── ae864d61259798452c3ac395bcfa7ee2733549a0.nq.gz
│   ├── aed40cd24e4f488e0adb91f8d6e9d31d8dbbacbf.nq.gz
│   ├── b4f7800944ee14b07c217aa86b041ae2adfe650a.nq.gz
│   ├── ba73b743394169c330e45fce1b4e5ff6264f8b71.nq.gz
│   ├── c159b46e48959cdaeb8635c09cdd48302dbfb44f.nq.gz
│   ├── c88cfbb2349c6401336bc5ba6623f51afd1eb59d.nq.gz
│   ├── cdb298a19b09d360d18f72a91e9dd70d7d7f54ec.nq.gz
│   ├── cf6d9d18b0c24f8865f798da388ba150f13afcd3.nq.gz
│   ├── d22eecd52f0150b036cc39e6fa6b8353e8494908.nq.gz
│   ├── d40c74ac327565dfb08b3560a524385ba357eb8c.nq.gz
│   ├── de645c2e8bc75b98b052b4731a5025fb1d60c5c3.nq.gz
│   ├── dede395d79a38bab322d56a66d916703af84f77b.nq.gz
│   ├── e405471ac4d94371b1ee9b1622227ff76b337180.nq.gz
│   ├── e63d889f96bf13071cfd207dd2be392b9823cb84.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e825d63725a7b7dfd74b326a25906fd04a012639.nq.gz
│   ├── fc5045d36be57251000393b32baba7baa9cd8c4f.nq.gz
│   └── fff50eb9dca545fec97bacf7fc7fb20e83c4fd89.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 76f03df2f4df25de8aa9424cf31e600cf27f7d59.nq.gz
├── filetree
│   └── 76f03df2f4df25de8aa9424cf31e600cf27f7d59.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 60 files
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

[python/importlib_metadata](https://github.com/python/importlib_metadata)

---
*Parsed on 2026-04-09 by [repolex](https://repolex.ai)*
