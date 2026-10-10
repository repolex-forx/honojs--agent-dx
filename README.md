# Repolex Knowledge Graph of honojs/agent-dx

RDF knowledge graph data for [honojs/agent-dx](https://github.com/honojs/agent-dx), parsed by [repolex](https://repolex.ai).

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
rlex download honojs/agent-dx
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 8e85e3c3e8a91b0de55882671e09aea0c4e4ec7c
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 8e85e3c3e8a91b0de55882671e09aea0c4e4ec7c
│           └── chunk-001.nq.gz
├── blob
│   ├── 01c29158cb187446494e7294a3881ed70c7d6798.nq.gz
│   ├── 04ef5860e58521d6f8751708a50c84746d0a9b4d.nq.gz
│   ├── 06557fd3f7441c218ae68e1a16a9d2e78e601175.nq.gz
│   ├── 07038bd6554cd23930cd2ff60c90ce088577cdb2.nq.gz
│   ├── 08724e8eed7ee56995846f23303b17ee2e432f38.nq.gz
│   ├── 0fec592e25e85ce59b9b13255a2fe1d96084602c.nq.gz
│   ├── 12481c7a0064e2161a33e2693242cf29535d7cd5.nq.gz
│   ├── 139ba74dfb113eebd10c2130ad2181892fc630ce.nq.gz
│   ├── 1407aecfc58830b097b4c509e2b2ca8b50abebf1.nq.gz
│   ├── 141661e24122466732ffb5c9606420035f3c27af.nq.gz
│   ├── 14d47e8ae5faff4740a53e3c8faa7c904fe09869.nq.gz
│   ├── 160d5148d61f6c24548203d6ba4a0697fb275398.nq.gz
│   ├── 1a877303de7d1885b1830c1aab8654f8c1452f77.nq.gz
│   ├── 1b673219103dfa8ea2ad84f0d3fcdb7c84507bd1.nq.gz
│   ├── 1cc8b2b0e4f43037cb5522b888606e0c4a5813e4.nq.gz
│   ├── 229e5617f0b497a026fa116837660529596ec6ad.nq.gz
│   ├── 2c9e1a9ca9f11fa3b26e589b60cb44c6c31659dc.nq.gz
│   ├── 3191383b3322ed7cbc44e659934efbfe4b403e95.nq.gz
│   ├── 339c159fcb3a20aca8b6560df8ca60dd8f6255c6.nq.gz
│   ├── 33a85351dd004b3e718c6887a87843b23d30c843.nq.gz
│   ├── 349f47782d04c87eecf6ed83c9174d80408eb0c0.nq.gz
│   ├── 36d81e26c745d281e3a32091f334195d4dbce0c7.nq.gz
│   ├── 3b73742f0980b5f6da64ba149a99f091006f653c.nq.gz
│   ├── 4087091d9df9df33934d2ba3db17a632341ce90d.nq.gz
│   ├── 41ea34636f4479cdb5e306945e63572caed5c787.nq.gz
│   ├── 43063f0dd4c671b308de41f415234d3974c8845d.nq.gz
│   ├── 43c994c2d3617f947bcb5adf1933e21dabe46bb5.nq.gz
│   ├── 473b34ed165bd89ab04efd324166a91246b08987.nq.gz
│   ├── 51beaed374766f929b4bb39e7fd0a0755e960330.nq.gz
│   ├── 5352c8b7f1587fd4ac701a846546df2e3dd015c0.nq.gz
│   ├── 543164354afc72a8b8de19830b6b9c06af58c0ae.nq.gz
│   ├── 54f72546d1a5f90843c9c8155800d1d1bdfed7b1.nq.gz
│   ├── 5937a75c8bfaff7ab4bb579a709be5788c68aa9f.nq.gz
│   ├── 5ad7132bb14fc8524fbbb4d3472e94f66ccec710.nq.gz
│   ├── 5c80252dc191fda8400cdea735ec0fac5e4b8e8b.nq.gz
│   ├── 5d3a243049081ff95cb4e3d084672eb7a4045056.nq.gz
│   ├── 5e1f025cc70dba03880f296d12c0dd77384036cd.nq.gz
│   ├── 5ea3d8fbdbdc45333cbe39c2f184dc75cec5d527.nq.gz
│   ├── 5fd4050fdd60dd843f6856741a75b246fa00983a.nq.gz
│   ├── 610b6cd3a88ae408049335aca6b3052f2a229f34.nq.gz
│   ├── 63d31ae3dd6e15e47be4fcf101480474410f48a0.nq.gz
│   ├── 6a4189b00753da5db56423128972e4021f8b182e.nq.gz
│   ├── 7981baa605ca275906336b8d0438fb231df6b01e.nq.gz
│   ├── 7aa277a1002e15aa801830609817168b9a8984a0.nq.gz
│   ├── 7f74d2d3fa319199a7b6f08fab9063e9b6d85606.nq.gz
│   ├── 7f7a2ccd04ea959d944c6fa100299a8aa8e5bf08.nq.gz
│   ├── 80e0b36148ab021a4a47243f9634bcdefab5dd49.nq.gz
│   ├── 8275c96f62e6e8f8fc21e6c9b619ccb8e4ea4734.nq.gz
│   ├── 8380461d21ebdfc813a42ea03ed68316fd7195ee.nq.gz
│   ├── 8635027968f942dcea3740a115208e1fae4c0aa2.nq.gz
│   ├── 88ae0c19937f69535bbb3dccb3f7ba439d093578.nq.gz
│   ├── 8cdf4a4ffbe94fce475cdfd5a30b854bb268ce97.nq.gz
│   ├── 8d8ea510b4fc542f0cfffe9f46f789df50551777.nq.gz
│   ├── 9199465d67a94ba905ea3dad879be30587f67931.nq.gz
│   ├── 942123d3465fa8bb8504643e22a4fcf5c37b4dc3.nq.gz
│   ├── 96b1283822837f4e1416f0e0ddabbafe052a3143.nq.gz
│   ├── 980077028966b19842f9ffa0807c2787bef1c958.nq.gz
│   ├── 980ef8e6b278a101063903557af67620374cf71c.nq.gz
│   ├── 99e2f7ddf76db13942fbbae28d209ce4bf94dead.nq.gz
│   ├── 9cb4d02f47857483f11bac2682cfc75ca2426314.nq.gz
│   ├── 9f1f131d6f672a331f8904e373e36c8102a65c42.nq.gz
│   ├── a1631827b16089da3d98400dbbc66c3502f95435.nq.gz
│   ├── a21b28d953cc9af4cb1e57e97ed06a6bbeec126e.nq.gz
│   ├── a3bf3a6ea87b700f9ba253a36dbf72008e787306.nq.gz
│   ├── a57056ee345bceef7242c727024495c7be1a7c3c.nq.gz
│   ├── ab1024680de0846fd17c3a76ffdbeadf34578191.nq.gz
│   ├── aba7f27965d011f453544ac9222d14a96b407d5f.nq.gz
│   ├── b15509dad6c1fe725935c2c791c2869d72f10d45.nq.gz
│   ├── b33453a2ac667e8d4796fe9e22a6ac564570142b.nq.gz
│   ├── c173fee752b332e3c09710f00be620c3d2c66fc5.nq.gz
│   ├── c5c2289502624ca5936a24209930751f2854c419.nq.gz
│   ├── c9e73137033c982ba3a18530f604c1ce22c190e2.nq.gz
│   ├── cc6688fc8d6d75add72d67fe2e45f169e9d94687.nq.gz
│   ├── d4650e1c4e94505840714f9bf349be1762fd7136.nq.gz
│   ├── d72a6889b7d4c69eb5bba2a83cabc18e9f006d75.nq.gz
│   ├── d800430c26168971bbad1157b6485d0c69238607.nq.gz
│   ├── da61783fb5d179150416c16c516697d8a19184b3.nq.gz
│   ├── db9fb15831fbd499c0a99941cbdac18c917180ab.nq.gz
│   ├── dddba12121d6cd95cf77372e5d53dcef20efaa08.nq.gz
│   ├── dddfc942605012fce2bb010d2f8544bd89d168e6.nq.gz
│   ├── de293e7abe3f7e98390b09353aed5ed054e17291.nq.gz
│   ├── de634a9ff3192f8df4da7a8af172ef0b324ec77b.nq.gz
│   ├── df9a99d1e65bca7be44d507376dad92c39d8a513.nq.gz
│   ├── e1dcd433cc6d3d177d646505e038f3ba7c183d0d.nq.gz
│   ├── e35530653ce8ac8e432ce86330d5f822c81231dc.nq.gz
│   ├── e8da1777bad953e807dc7c96ece38d3cd4613c04.nq.gz
│   ├── e9b0dad63bacd2aa6865fcb9b7e86ad630964730.nq.gz
│   ├── ece69098938cb7bd3cccc6d18f7d6901c6db68e5.nq.gz
│   ├── ed8b047641d0922000ab62cd471992e147581ea0.nq.gz
│   ├── efb0277d11186428f53e4ef835bcbac920ba97ce.nq.gz
│   ├── efea8254b63c8f89682548e0300c26d7dadb2ef8.nq.gz
│   ├── f4b7abd4ba415d67a26bfb912308057b86c73c54.nq.gz
│   ├── f8e574a792fdea011c2f82acd466734bcf66cd1c.nq.gz
│   ├── f997cb22220cfe9537159e31b5e4976d8c262a92.nq.gz
│   └── fb14a01c60e26ffbf7e94f5bb7915b72eb67b597.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 8e85e3c3e8a91b0de55882671e09aea0c4e4ec7c.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 102 files
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

[honojs/agent-dx](https://github.com/honojs/agent-dx)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
