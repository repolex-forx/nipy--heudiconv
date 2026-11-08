# Repolex Knowledge Graph of nipy/heudiconv

RDF knowledge graph data for [nipy/heudiconv](https://github.com/nipy/heudiconv), parsed by [repolex](https://repolex.ai).

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
rlex download nipy/heudiconv
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── fb8161b6128fa350cf6273f6d4b136fee98bb116
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── fb8161b6128fa350cf6273f6d4b136fee98bb116
│           └── chunk-001.nq.gz
├── blob
│   ├── 00f1131df792593c5cac6c15f386acf7d1cee3a7.nq.gz
│   ├── 09b83f93d8ccb74fa983e5823b26278797bc67e9.nq.gz
│   ├── 0a109e3dd6fcc710b825a7c2e4de93b0a644fe37.nq.gz
│   ├── 0f143563bfbc712fedfd64934aef534c51598059.nq.gz
│   ├── 15d21b9d7ec5ef28fe45da00ef8619b849cb769d.nq.gz
│   ├── 16b57c03046362b8c1b3b97843510089342a8e97.nq.gz
│   ├── 184a7e06e1d1881153c6a2df6bbf772f5b877aa7.nq.gz
│   ├── 1ba920b88a75e66b6877120f1315b98f4d56830c.nq.gz
│   ├── 1dd9f5be9439c77a3ae3c8c252723cf987c8d9fe.nq.gz
│   ├── 22d2b272294257da1c8bac7f5716dddfdbb54d8c.nq.gz
│   ├── 251c704d3f9d93a880d520f06ae9f857dd1eb9d7.nq.gz
│   ├── 262f7e456cd1c48d3b8348289c04d59596c030f5.nq.gz
│   ├── 271d217d08dce2c1ade2c1782736749a80ac09ee.nq.gz
│   ├── 28ae6c7d2136e013424b1a349773fe5ddd3e006a.nq.gz
│   ├── 2b687cfcc1a4701d87aa1e55754dc1001fc53a5a.nq.gz
│   ├── 2bd4ddf62c3cd1359b2855384a64bbbcbd555465.nq.gz
│   ├── 2f63f52435e485f32f29d3e664786fe98f438664.nq.gz
│   ├── 2f8b1f2f7cf019c6b5d64ef7b245e3dbdf560741.nq.gz
│   ├── 346480459717120f8a3fd80c724b75f2badbb199.nq.gz
│   ├── 347de849d78afacb39201e3984418cbb53523e01.nq.gz
│   ├── 37aa8bb03b57d282825d7239c471cfa7a328e822.nq.gz
│   ├── 3df288f37b537342cdf378fb56ab26f81e2855e0.nq.gz
│   ├── 3e75078d5ae65a4f8a729a2d3a0a58997bab5ccd.nq.gz
│   ├── 403812a0f8056644f227eb31f8343f63d34cf472.nq.gz
│   ├── 427d7a3a5097ef01b7b1d461fc8b8745e4ba3fd0.nq.gz
│   ├── 432af808b4d447139356f79854fca219383bf600.nq.gz
│   ├── 4810ca9038c839306cdd563dec24dde3d3117d1c.nq.gz
│   ├── 48b29fb1ba8b6a191502027e0836b24dad2b7109.nq.gz
│   ├── 49dbd84a3e8f517b57bd585534357910a8a06dbc.nq.gz
│   ├── 4b33f767a574e6e1cf612e5583ca18d64df12b01.nq.gz
│   ├── 4bb564271a51e4fe75efefb7632686542c3ef4d8.nq.gz
│   ├── 4f28b30e5f0abaec668d3781ee9e947db5300334.nq.gz
│   ├── 51285967a7d9722c5bdee4f6a81c154a56aa0846.nq.gz
│   ├── 516d7d9a2ac524fc8501219a7cd0626c11519e64.nq.gz
│   ├── 53b90ba324dd481a6f0f9245c14795ee9805865d.nq.gz
│   ├── 53cede06826e98657f42380cdfd86570db5ac1e6.nq.gz
│   ├── 54299bbbe2f5ab0f5476038bc2c1ee64d0fa69dc.nq.gz
│   ├── 5581dd05799d5128e8c8dbaf7888c28ea24479d5.nq.gz
│   ├── 55dc94277b5913e2e2ecc480788df812b161423f.nq.gz
│   ├── 5952b41c17b92214cb234ce68a79af7c5764144d.nq.gz
│   ├── 59e1262afbedee4b672e7f9a1d8d877fe8c4a7d1.nq.gz
│   ├── 5cb250dd352b756601fec3289a40f253eaed97a1.nq.gz
│   ├── 5e8b9cf92a45cd33399e49a752d89b822a7e04e7.nq.gz
│   ├── 62535f2a47409076b03a82d2c542bf0b2d24afaa.nq.gz
│   ├── 62c468c8638ac094093517fc3f4ec47aa3e13c4d.nq.gz
│   ├── 64a82b5d29be11b754f6edaa2c1d07b826c9b88c.nq.gz
│   ├── 65030dd230001d5bdb16231daa96b9624f4b8495.nq.gz
│   ├── 66852758039cc5b81e1d8fb802735d12d6d90be4.nq.gz
│   ├── 66a3b041505953b301630e5bd82aa7d34531b7e9.nq.gz
│   ├── 6abb05a6c8d37bf9b661973beecaa701f342a5f6.nq.gz
│   ├── 7515087d64cc98063ce0662e00779e51847ba17c.nq.gz
│   ├── 77ce2bac5d34b1974aebe42a248a5fac895f78a7.nq.gz
│   ├── 781c585259d604db8e0983e883bad02830720f17.nq.gz
│   ├── 7962d1c4f36299068fe797239536735cf3cf89b4.nq.gz
│   ├── 7b68925fb1eba153589a8f46860ab53a762feac6.nq.gz
│   ├── 7ca8b4088de8badc261517fc8a3272a392580b17.nq.gz
│   ├── 7da05c45be94b7ddc6368527d3e884132e551830.nq.gz
│   ├── 7f944f281a22ce79c65a9faf97b1a6bad5588086.nq.gz
│   ├── 81964c3a5078491f27bb9ccf7493de8b4dfc2249.nq.gz
│   ├── 83b704959fb3ff5faeac614ae0fb3a7a7ce83673.nq.gz
│   ├── 844e7446c523e2812089b446dd5bd5d2edb9b2a7.nq.gz
│   ├── 88bbe3da8c5b0e2c5520e2becc3fd2f632c3c41a.nq.gz
│   ├── 89398df916d3005b17d3fe984dc3960e92e7930c.nq.gz
│   ├── 8b4aa07124968aa784f73875c894d5141aae1d16.nq.gz
│   ├── 8eda1d771dd374f97548e390fc9492387a720ee4.nq.gz
│   ├── 904c67f8699d9ef2c2a0e71b9a6ddd90ee858e2a.nq.gz
│   ├── 912288b42b69a4f173845857575c939f89439bd3.nq.gz
│   ├── 9240bcd52f284f9601e4b89a0720c123c439b3ef.nq.gz
│   ├── 94cb11098999ada252678c63a750633726ee4739.nq.gz
│   ├── 950d3555248f62f229cc94913e8920b14369c649.nq.gz
│   ├── 989f6c68630b45775bf56f3769d83e8b9c07d4c4.nq.gz
│   ├── 99f4fdbe6b76c29100ef4a9b80ae785e6304c6ff.nq.gz
│   ├── 9beff3bcd06fb203f8ef8c530d5cea38cb37d271.nq.gz
│   ├── 9c5b040d8f91255312c5b8c607d07ef1cab249f2.nq.gz
│   ├── a0ed9133595baefca060026a1865deeba32e3689.nq.gz
│   ├── a4019706870907f41d93a891ef3e44ab1d7305c1.nq.gz
│   ├── a4971e768f1865201e5d29628a3e75d7a3c0904f.nq.gz
│   ├── a6ffc1ea74a3482c4cc6596cef4eb1c3f01c2ac4.nq.gz
│   ├── a7e52f2a5100582c147172f31972160693a28f09.nq.gz
│   ├── aa807cd2759375223d1e64a795eb79729ec00c5a.nq.gz
│   ├── ad3f39ae13befc9c6cb3f5ba0b42ac045a30c900.nq.gz
│   ├── adc7f46cd23758921f7d24f3280f9a48c021735b.nq.gz
│   ├── ae3e92105c4866b862495326d48457eb8ee65e2d.nq.gz
│   ├── af7a3bac1bf2ad802ab052177d3756607f516ad8.nq.gz
│   ├── b2a8afc5b19700bd22798d828221686a11ca0932.nq.gz
│   ├── b334fbafb54ab6eee4da30733fbeb10dcda97347.nq.gz
│   ├── b598c5a5b8217dd6b88de2f04e84b9f2a80e00ea.nq.gz
│   ├── b6a4f3ae8eb8907c13875c10b8e5bc118c6e7ec3.nq.gz
│   ├── b897c5e522a61e1c3ba65895dd88aa9da1aebf2b.nq.gz
│   ├── b8fe72b38e88603a0e875e0f4b667a5bd3b43231.nq.gz
│   ├── bafdaa512ee74b9c4379f60d66c10a6ce81de89c.nq.gz
│   ├── bb4404192c9702e78702db89b818ee947c89b167.nq.gz
│   ├── bc9b89346d6fd17fe6e676539b8f655d2bc1c2a5.nq.gz
│   ├── bd390593e607e6e6d8b7dd130ef97c2a06992fb0.nq.gz
│   ├── c44ff7b93d9e449e218638052cdae206c7fac7cb.nq.gz
│   ├── c655a3e2c8ab3374a961d8c14aee6a96b265704c.nq.gz
│   ├── c80b9e3862221471a02a138089216cb3cbd51c19.nq.gz
│   ├── c9151d9a1a13c810d38f115dca20efc76c9dbd03.nq.gz
│   ├── c94eec579abffed0d8894f71d187d4447c25b2f8.nq.gz
│   ├── c9878951398b602458494bc1dc152f8638f42d3f.nq.gz
│   ├── cc6ae1f3a7e98d28045f1a135064518f1c688b0c.nq.gz
│   ├── d0b84ad1d69d7a4751c91d61703d88fa1a08b1b9.nq.gz
│   ├── d13dff49656f73a3d6c00d1713e07e6a09d16b76.nq.gz
│   ├── d21605b9c7e2a56e84132e19906627b9cae3a451.nq.gz
│   ├── d2f47807989a34b9df1b52ac444e4cfbfd39bcc4.nq.gz
│   ├── d440220dc21d0a12a72d6712184d4fab7da4d657.nq.gz
│   ├── d567d8802fdb6d600e266a6ff8c2e2fbb7d37e0b.nq.gz
│   ├── dc5ef073da1a52e623327f0dfa66e21cd5aeb09b.nq.gz
│   ├── dc67cc46e9922e708f945739c10f1a746b5dff64.nq.gz
│   ├── df8dbd034ca1f5f98778ca96f1a81ee698e77dc6.nq.gz
│   ├── e24ce491bb91161e9f719ca0d1b4e03c8bdcb9f2.nq.gz
│   ├── e2945d4bd42344c4ecc8c7c613f16445e1243937.nq.gz
│   ├── e341306dbc127a2d754b51384fdcb6610d29729b.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ee2c3a51a4a3a3a05ebe11cfe3387989effc67e0.nq.gz
│   ├── ef47de3f90ada64ae4a54853d6bbaa0f992698a5.nq.gz
│   ├── f124147c46e8a4f51cc0269a39e0740e629804dd.nq.gz
│   ├── f52b905f153da21cd99f49cd27268e4c284ae44a.nq.gz
│   ├── fa7cc8dac6b5b075ecbfe939b625dcfe5e8bd487.nq.gz
│   ├── fd0b8de12da3081684afc3f31c1e7f17b3c4331b.nq.gz
│   └── fde9605bfddf06bc43d419fdb648bb3d41cfa9c3.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── fb8161b6128fa350cf6273f6d4b136fee98bb116.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 129 files
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

[nipy/heudiconv](https://github.com/nipy/heudiconv)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
